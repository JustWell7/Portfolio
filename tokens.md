# Tokens · Broadsheet (design system do portfólio)

Fonte: `_ds/broadsheet-98e66aba-19cf-4391-97dc-cc67491d02cf/styles.css`
(neste projeto, a fonte foi sobrescrita para Inter — ver nota no fim)

## Cor

```
--color-bg: #f3f2f2
--color-surface: #eae9e9
--color-text: #201e1d
--color-accent: #0088b0      (cyan)
--color-accent-2: #d6006c    (magenta)
--color-divider: color-mix(in srgb, #201e1d 16%, transparent)
--color-process-yellow: #edbb00   (só em tratamentos de impressão)
```

Rampas tonais (100 claro → 900 escuro), geradas em OKLCH:

```
neutral   100 #f8f4f4  200 #eae7e7  300 #d7d3d3  400 #bab6b6  500 #9b9797
          600 #7d7979  700 #605d5d  800 #444141  900 #2d2b2b

accent    100 #e9f8ff  200 #cbeeff  300 #99e0ff  400 #62c5ee  500 #38a6cf
          600 #1186ac  700 #006786  800 #004961  900 #0a303e

accent-2  100 #fff1f4  200 #ffdee6  300 #ffc0d0  400 #ff90b1  500 #ff458e
          600 #d82071  700 #aa0b56  800 #790e3d  900 #4b1528
```

Uso: 100–300 para fundos tintados, 500 é a cor base, 700–900 para texto sobre fundo tintado e estados pressionados.

## Tipografia

```
--font-heading: "Source Serif 4", system-ui, sans-serif   → sobrescrito para "Inter" neste projeto
--font-heading-weight: 600                                  → sobrescrito para 700
--font-body: "Source Serif 4", system-ui, sans-serif       → sobrescrito para "Inter"
```

Escala (de `styles.css`, base 15px/1.55):
h1 42px · h2 32px · h3 25px · h4 20px · h5 16px · h6 13px (uppercase, tracked)

## Espaçamento

```
--space-1: 5px   --space-2: 10px   --space-3: 15px
--space-4: 20px  --space-6: 30px   --space-8: 40px
```

## Raio

```
--radius-sm: 1px   --radius-md: 2px   --radius-lg: 4px
```
No portfólio, `.btn` foi sobrescrito para `border-radius: 999px` (pill).

## Sombra

```
--shadow-sm: 0 1px 2px rgba(45,43,43,.14)
--shadow-md: 0 3px 10px rgba(45,43,43,.16)
--shadow-lg: 0 12px 32px rgba(45,43,43,.22)
```

## Onde isso é aplicado

Home.dc.html, CaseP7S.dc.html e CaseOmnichannel.dc.html carregam `styles.css` + `_ds_bundle.js` e usam as classes prontas (`.btn`, `.tag`, `.card`, `.nav`, `.table`) em cima dessas variáveis. A troca de fonte para Inter e o botão pill são overrides locais, feitos num `<style>` no `<helmet>` de cada página — o token-source original (Broadsheet/serifa) continua documentado acima caso queira voltar.
