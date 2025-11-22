Título: Agência Criativa Web (empresa fictícia)

Descrição: Página web de uma agência de design digital fictícia chamada "Agência Criativa Web", que utiliza conceitos de Design Responsivo, Unidades Relativas, Flexbox e CSS Grid. O site é totalmente adaptável a diferentes tamanhos de tela.

Tecnologias utilizadas: HTML5, SASS/SCSS

Pré-requisitos: Navegador atualizado (projeto foi testado e funciona no Google Chrome Versão 142.0.7444.163 64 bits - Caso utilize este navegador, recomenda-se tal versão ou superior). Node.js instalado (necessário para rodar o compilador SASS). Gerenciador de pacotes (npm ou yarn).

Instalação:

Passos para clonar e rodar: git clone https://github.com/tayanibritto/agCriativaWeb.git / cd agCriativaWeb / npm install / npm run sass (ou npm run build, dependendo do script configurado) / abrir index.html no navegador
Como usar: Para testar a responsividade da página, você pode utilizar o DevTools do Navegador e escolher os vários tipos de dispositivos.
Estrutura do Projeto: 
  - css/
    - estilos.css
    - estilos.css.map
  - img/
    - social/
      - icon-facebook.png
      - icon-insta.png
      - icon-tiktok.png
      - icon-x.png
    - fundo_block_depoimentos.png
    - fundo_contato.png
    - fundo_home.png
    - fundo_servicos.png
    - logo.png
  - scss/
    - _base.scss
    - _componentes.scss
    - _layout.scss
    - _mixins.scss
    - _variaveis.scss
    - estilos.scss
  - index.html

Observações: A estrutura do layout responsivo funciona 100%, porém a configuração JavaScript (ou a linguagem que preferir) do formulário de contato precisarão da configuração do desenvolvedor. As informações personalizadas (como imagens, depoimentos e dados da empresa) também precisarão de alteração.

