# NhongaAPP — Landing Pages

Site público da NhongaAPP, alojado em GitHub Pages.

## URLs (após GitHub Pages estar ligado)

- **Landing principal:** https://minacio14.github.io/nhongaapp-landing/
- **Política de Privacidade:** https://minacio14.github.io/nhongaapp-landing/privacy.html
- **Inscrição testadores:** https://minacio14.github.io/nhongaapp-landing/tester-signup.html

## Configurar o Google Form no `tester-signup.html`

1. Cria um Google Form com os campos:
   - Email Gmail (obrigatório)
   - Número WhatsApp (obrigatório)
   - Nome completo
   - Como conheceste a NhongaAPP?
   - Sugestões de funcionalidades (texto livre)
2. No Form, clica **Send → ícone `<>`** (Embed HTML)
3. Copia o atributo `src` do iframe
4. Edita `tester-signup.html` e substitui `REPLACE_WITH_YOUR_FORM_ID` pelo teu

## Fluxo de partilha (smart link)

Em vez de partilhar diretamente o link da Play Store, a app partilha:
`https://minacio14.github.io/nhongaapp-landing/?from=share`

A landing detecta `?from=share` e mostra mensagem específica para receptores de partilhas.
