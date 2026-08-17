# Portfólio — Wellington Mendes

Portfólio de UX/UI Design em HTML estático. Não precisa de build.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos deste zip para a raiz.
2. No repositório: **Settings → Pages**.
3. Em *Source*, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Salve. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

O `index.html` da raiz já encaminha para a home, então o link abre direto no portfólio.

## Estrutura

- `index.html` — entrada (redireciona para a home)
- `Home.dc.html` — página inicial
- `CaseP7S.dc.html` — case Comparador P7S
- `CaseOmnichannel.dc.html` — case Chamados Omnichannel
- `CasePsiPlanner.dc.html` — case PsiPlanner
- `prototipo-*.html` — protótipos navegáveis
- `_ds/` — design system (Broadsheet)
- `assets/` — imagens dos cases
- `support.js` — runtime das páginas

## Observações

- Todos os arquivos são estáticos: abrir localmente também funciona.
- Os arquivos `* v1.dc.html` são versões anteriores, mantidas como histórico. Podem ser removidos sem afetar o site.
