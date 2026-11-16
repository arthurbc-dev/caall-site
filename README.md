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
- Seção da equipe com áreas de contribuição; nomes individuais podem ser preenchidos quando disponíveis

## QR code

Adicione a imagem real do QR code em assets/qrcode.png. Ela deve apontar para https://caall.stockmei.win. O HTML já contém o elemento img e seu texto alternativo.

## Equipe, contato e evento

Os nomes individuais da equipe podem ser adicionados no comentário marcado PREENCHER na seção Equipe. Inclua contato e nome do evento quando esses dados estiverem disponíveis.

## Arquivos

- index.html: conteúdo e estrutura
- styles.css: identidade visual, responsividade e estados de foco
- script.js: navegação mobile
- assets/voz-ativa-prototipo.jpg: imagem estática da interface
- assets/qrcode.png: imagem a adicionar manualmente

O site usa Comic Neue para manter a tipografia arredondada da identidade atual, com DM Sans e fontes do sistema como alternativas. A conexão à internet é necessária para carregar as fontes do Google; o restante funciona localmente.
