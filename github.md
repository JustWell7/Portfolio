repo: JustWell7/Portfolio
branch: main

## Last sync

date: 2026-08-17T18:42:33Z

### Updated in this project

- Páginas agora independem da pasta `_ds/` — todos os tokens do design system foram convertidos em valores literais e as classes (`.tag`, `.card`, `.table`, `.elev-*`) ganharam fallback inline.
- Foto do perfil otimizada para `assets/well.jpg` (900×1125, 120 KB).
- Títulos e hover de links restaurados em gradiente, com cor sólida de fallback.
- Fundo das páginas de case igualado ao da Home (`#F6F9FD`).

## Pendências no repositório

- Falta a pasta `assets/` (imagens dos cases e a foto) — sem ela as imagens dão 404.
- O deploy do Pages estava falhando: criar um arquivo vazio `.nojekyll` na raiz (o Jekyll ignora pastas com `_`).

## Screen map

| Tela | Arquivos no repo |
| --- | --- |
| Entrada / redirect | `index.html` |
| Home | `Home.dc.html`, `support.js`, `assets/well.jpg` |
| Case Comparador P7S | `CaseP7S.dc.html`, `prototipo-comparador-p7s.html`, `assets/p7s-*.png` |
| Case Chamados Omnichannel | `CaseOmnichannel.dc.html`, `prototipo-omnichannel.html` |
| Case PsiPlanner | `CasePsiPlanner.dc.html`, `assets/psi-*.png` |
| Design system (referência) | `tokens.md` |
