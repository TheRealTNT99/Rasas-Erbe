#{{replaceSpace _typeHtml}}
{{#if _subTypeHtml}}{{#each _typeListText}}#{{replaceSpace this}} {{/each}}{{#if (isNotNone rarity)}}, {{/if}}{{/if}}{{#if (isNotNone rarity)}}#{{replaceSpace rarity}}{{/if}}{{#if _attunement}} {{_attunement}}{{/if}}
{{#if value}}{{currency value}}{{#if weight}}, {{/if}}{{/if}}{{#if weight}}{{weight}} lb.{{/if}}{{#if weapon}}
{{#if dmg1}}{{dmg1}}{{#if dmg2}}(*{{dmg2}}*){{/if}} {{dmgTypeString dmgType}}{{#if range}} ({{range}}){{/if}}{{#if _fProperties}} - {{/if}}{{/if}}{{#if _fProperties}}{{#each _fProperties}}{{this}}, {{/each}}{{/if}}{{/if}}{{#if armor}}
{{ac}} {{armorType type}}{{/if}}{{#if _fullEntries}}

---

{{#each _fullEntries}}{{#if this.entries}}***{{this.name}}*** {{this.entries}}{{else}}{{#if this.wrapped}}{{#if this.wrapped.entries}}***{{this.wrapped.name}}*** {{this.wrapped.entries}}{{else}}{{this.wrapped}}{{/if}}{{else}}{{this}}{{/if}}{{/if}}
{{/each}}
{{else}}
{{#if entries}}

---

{{entries}}
{{/if}}
{{/if}}