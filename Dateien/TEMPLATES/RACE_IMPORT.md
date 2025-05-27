**Ability Scores:** {{#each ability.[0]}}{{@key}} +{{this}}{{#unless @last}}, {{/unless}}{{/each}}
**Size:** {{#each size}}{{fullSize this}}{{#unless @last}} or {{/unless}}{{/each}}
**Speed:** {{#each speed}}{{@key}} {{this}}ft.{{#unless @last}}, {{/unless}}{{/each}}

---

{{#each entries}}**{{this.name}}**
{{#each this.entries}}{{#unless (isObject this)}}{{this}}{{else if this.items}}{{#each this.items}}- **{{this.name}}**
	- {{this.entry}}
{{/unless}}{{/each}}
{{/each}}
