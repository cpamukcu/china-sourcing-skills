# china-sourcing-skills

Claude Code plugin from CP Export Marketing (cpexportmarketing.com).

## Skills

- **china-product-sourcing**: takes a Türkiye customer's product request (name, photo, link or spec sheet) and finds and checks Chinese factories and wholesalers. It also looks up the HS code, the Turkish GTİP code and the Turkish import taxes on Chinese-origin goods, then writes a branded English PDF supplier shortlist, an inquiry draft and a supplier database. It never contacts suppliers.

## Layout

```
.claude-plugin/plugin.json
skills/china-product-sourcing/SKILL.md
```

## Use

In Claude Code: `/plugin install` from this repo, then `/china-product-sourcing:china-product-sourcing <request>`.
