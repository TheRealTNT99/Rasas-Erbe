#{{spellLevel level}} #{{spellSchool school}}{{#if meta}}{{#each meta}} #{{@key}}{{/each}}{{/if}}
**Casting Time:** #{{time.[0].number}}-{{time.[0].unit}}
**Range:** {{#if (spellRangeType range)}}{{#if range.distance.amount}}{{range.distance.amount}} {{/if}}{{range.distance.type}}{{else}}Self ({{range.distance.amount}}-{{range.distance.type}} {{range.type}}){{/if}}
**Components:** {{#if components.v}}V{{#if components.s}}, {{/if}}{{#if components.m}}, {{/if}}{{/if}}{{#if components.s}}S{{#if components.m}}, {{/if}}{{/if}}{{#if components.m}}M ({{#if components.m.text}}{{components.m.text}}{{else}}{{components.m}}{{/if}}){{/if}}
**Duration:** {{#if (spellDurationType duration.[0])}}Instantaneous{{else}}{{#if duration.[0].concentration}}Concentration, up to {{/if}}{{duration.[0].duration.amount}} {{duration.[0].duration.type}}{{/if}}

---

{{#each entries}}
{{#if (isObject this)}}{{#if this.items}}{{#if (isObject this.items)}}{{#each this.items}}{{#with this}}- **{{name}}**
	- {{#each this.entries}}{{this}}{{/each}}
{{/with}}{{/each}}{{else}}{{#each this.items}}- {{this}}
{{/each}}{{/if}}{{/if}}{{else}}{{this}}
{{/if}}

{{/each}}{{#if entriesHigherLevel}}{{#each entriesHigherLevel}}{{#with this}}**{{name}}**{{#each entries}}
{{this}}
{{/each}}{{/with}}{{/each}}{{/if}}{{#if classes.fromClassList}}
**Classes:** {{#each classes.fromClassList}}#{{this.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}{{#if classes.fromSubclass}}
**Subclasses:** {{#each classes.fromSubclass}}*{{this.subclass.name}}* {{this.class.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}{{#if classes.fromClassListVariant}}
**Optional/Variant Classes:** {{#each classes.fromClassListVariant}}#{{this.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}{{#if races}}
**Races:** {{#each races}}{{this.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}{{#if feats}}
**Feats:** {{#each feats}}{{this.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}{{#if optionalfeatures}}
**Other Options/Features:** {{#each optionalfeatures}}{{this.name}}{{#unless @last}}, {{/unless}}{{/each}}{{/if}}

{{#each entries}}{{#if (isObject this)}}{{#if this.items}}{{#if (isObject this.items)}}{{#each this.items}}{{#with this}}{{#each this.entries}}{{#each (getCreature this)}}
```statblock
creature: {{this}}
```
{{/each}}{{/each}}{{/with}}{{/each}}{{else}}{{#each this.items}}{{#each (getCreature this)}}
```statblock
creature: {{this}}
```
{{/each}}{{/each}}{{/if}}{{/if}}{{else}}{{#each (getCreature this)}}
```statblock
creature: {{this}}
```
{{/each}}{{/if}}{{/each}}
