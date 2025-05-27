*Prerequisite:* {{#if (isEqual _slPrereq 'Special')}}{{log '[log]isEqual true'}}{{#each prerequisite}}{{#each this}}{{this}}{{#unless @last}}, {{/unless}}{{/each}}{{/each}}{{else}}{{log '[log]isEqual false'}}{{_slPrereq}}{{/if}}

---

{{#if _fullEntries}}{{#each _fullEntries}}{{#unless (isObject this)}}{{this}}

{{else}}{{#if this.items}}{{#each this.items}}{{#unless (isObject this)}}- {{this}}
{{else}}{{#if this.entry}}- **{{this.name}}**
	- {{this.entry}}
{{/if}}{{#if this.entries}}- **{{this.name}}**
{{#each this.entries}}{{#unless (isObject this)}}	- {{this}}
{{else}}{{#if this.rows}}=={{this.caption}}==

|{{#each this.colLabels}}{{#if @first}}`dice: {{this}}`{{else}}{{this}}{{/if}}|{{/each}}
|{{#each this.colLabels}}---|{{/each}}
{{#each this.rows}}|{{#each this}}{{this}}|{{/each}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}
{{/if}}{{#if this.name}}>**{{this.name}}**
{{#each entries}}>  {{this}}
{{/each}}
{{/if}}{{#if this.rows}}=={{this.caption}}==

|{{#each this.colLabels}}{{#if @first}}`dice: {{this}}`{{else}}{{this}}{{/if}}|{{/each}}
|{{#each this.colLabels}}---|{{/each}}
{{#each this.rows}}|{{#each this}}{{this}}|{{/each}}
{{/each}}
{{/if}}{{#if this.entries.entries.entries}}## {{this.entries.entries.name}}
{{#each this.entries.entries.entries}}{{this}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}{{else}}{{#each entries}}{{#unless (isObject this)}}{{this}}

{{else}}{{#if this.items}}{{#each this.items}}{{#unless (isObject this)}}- {{this}}
{{else}}{{#if this.entry}}- **{{this.name}}**
	- {{this.entry}}
{{/if}}{{#if this.entries}}- **{{this.name}}**
{{#each this.entries}}{{#unless (isObject this)}}	- {{this}}
{{else}}{{#if this.rows}}=={{this.caption}}==

|{{#each this.colLabels}}{{#if @first}}`dice: {{this}}`{{else}}{{this}}{{/if}}|{{/each}}
|{{#each this.colLabels}}---|{{/each}}
{{#each this.rows}}|{{#each this}}{{this}}|{{/each}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}
{{/if}}{{#if this.name}}>**{{this.name}}**
{{#each entries}}>  {{this}}
{{/each}}
{{/if}}{{#if this.rows}}=={{this.caption}}==

|{{#each this.colLabels}}{{#if @first}}`dice: {{this}}`{{else}}{{this}}{{/if}}|{{/each}}
|{{#each this.colLabels}}---|{{/each}}
{{#each this.rows}}|{{#each this}}{{this}}|{{/each}}
{{/each}}
{{/if}}{{#if this.entries.entries.entries}}## {{this.entries.entries.name}}
{{#each this.entries.entries.entries}}{{this}}
{{/each}}
{{/if}}
{{/unless}}
{{/each}}
{{/if}}