# Confere na Bomba

Primeira versão funcional de um site mobile/PWA gratuito.

## Arquivos
- `index.html`: site e calculadora.
- `manifest.webmanifest`: configuração para instalação como aplicativo.
- `sw.js`: cache básico para uso offline após a primeira visita.
- `icon.svg`: ícone.

## Publicar gratuitamente no Cloudflare Pages
1. Extraia o ZIP.
2. Crie um repositório GitHub e envie os quatro arquivos para a raiz.
3. No Cloudflare, abra Workers & Pages > Create > Pages > Connect to Git.
4. Selecione o repositório.
5. Framework preset: None. Build command: deixe vazio. Build output directory: `/`.
6. Publique. O Cloudflare fornecerá um endereço `*.pages.dev`.

Também pode publicar por upload direto dos arquivos, se a opção estiver disponível na sua conta.

## Observações sobre os cálculos
- Por litros / tanque cheio: total esperado = litros informados x preço anunciado.
- Por valor: compara o total cobrado com o valor solicitado e calcula o preço efetivo por litro com base nos litros informados.
- A ferramenta é educativa e não determina, sozinha, a ocorrência de fraude. É importante conferir o preço válido para a forma de pagamento, o visor da bomba e o comprovante.
