Projeto M19 – Boas Práticas de CSS

Este projeto foi desenvolvido como parte do curso da EBAC, com foco em aplicar boas práticas de organização de código utilizando a metodologia BEM (Block, Element, Modifier) e pré-processador SASS.

✔ Objetivos do exercício

Refatorar o HTML fornecido, aplicando a metodologia BEM.

Reestruturar os estilos utilizando SASS.

Garantir que o projeto final mantenha o mesmo layout e comportamento do original.

Subir o projeto para o GitHub na branch boas_praticas_css.

🛠 Tecnologias utilizadas

HTML5

SASS (SCSS)

Metodologia BEM

📂 Estrutura do projeto
Projeto M19/
│── index.html
│── main.css        # Arquivo CSS compilado
│── src/            # Código-fonte SASS
│   ├── main.scss
│   ├── product.scss
│   └── reset.scss
│── package.json
│── package-lock.json

🚀 Como executar

Clone o repositório:

git clone https://github.com/kaio-oliveira5/projeto-M19.git


Entre na pasta do projeto:

cd projeto-M19


Instale as dependências:

npm install


Compile o SASS para CSS:

npm run sass
