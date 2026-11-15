# Voz Ativa — CAALL

Site responsivo de apresentação do Voz Ativa, aplicativo de Comunicação Alternativa e Aumentativa para Todos. Feito em HTML, CSS e JavaScript puros, sem instalação de dependências.

## Como abrir

Abra index.html em um navegador. A página apresenta o Voz Ativa e direciona ao site pelo QR code.

## Estrutura da página

- Início com chamada principal e espaço para QR code
- Explicação breve sobre Comunicação Aumentativa e Alternativa
- Cards com as funções do Voz Ativa
- Imagem estática da interface do Voz Ativa
- QR code de acesso ao site
- Área de equipe e contato omitida até que os dados estejam disponíveis

## QR code

Adicione a imagem real do QR code em assets/qrcode.png. Ela deve apontar para https://caall.stockmei.win. O HTML já contém o elemento img e seu texto alternativo.

## Equipe, contato e evento

Os campos para preenchimento estão em um comentário no final de index.html, marcados com PREENCHER. Quando tiver os dados, remova o comentário e crie a seção de rodapé com os nomes e papéis da equipe, o contato e o nome do evento. Enquanto os dados estiverem ausentes, a seção permanece omitida e nenhum rascunho aparece na página.

## Arquivos

- index.html: conteúdo e estrutura
- styles.css: identidade visual, responsividade e estados de foco
- script.js: navegação mobile
- assets/voz-ativa-prototipo.jpg: imagem estática da interface
- assets/qrcode.png: imagem a adicionar manualmente

O site usa Comic Neue para manter a tipografia arredondada da identidade atual, com DM Sans e fontes do sistema como alternativas. A conexão à internet é necessária para carregar as fontes do Google; o restante funciona localmente.
