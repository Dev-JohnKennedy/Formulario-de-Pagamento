💳 Formulário de Pagamento Interativo
Este é um projeto de front-end desenvolvido com HTML, CSS e JavaScript, com foco em acessibilidade, validação de dados do usuário e aplicação de cupons de desconto. Ideal para treinar manipulação de DOM, validações, uso de localStorage e responsividade básica.

🖼️ Visão Geral
O projeto simula um formulário de pagamento, onde o usuário deve preencher seus dados pessoais e endereço. Ele também pode aplicar cupons de desconto válidos e ver o valor total atualizado dinamicamente.

📁 Estrutura do Projeto
css
Copiar
Editar
├── index.html
├── style/
│ └── style.css
├── js/
│ ├── formulario.js
│ └── desconto.js
└── img/
└── safe.jpg
✨ Funcionalidades
📝 Formulário
Campos: Nome, CPF, Telefone, Endereço completo.

Validações:

Nome com apenas letras e espaços.

CPF e telefone com 11 dígitos.

CEP com 8 dígitos.

Estado com 2 letras maiúsculas.

Feedback com alertas e limpeza do formulário após envio.

💰 Cupom de Desconto
Códigos disponíveis:

DESCONTO10 → 10%

DESCONTO20 → 20%

DESCONTO50 → 50%

Aplica o desconto ao preço total.

Armazena o cupom temporariamente com localStorage.

💾 Armazenamento Local
Dados do formulário e cupons são salvos no localStorage.

📱 Responsividade
Layout adaptável para diferentes larguras de tela (uso de flexbox).

🛠️ Tecnologias Utilizadas
HTML5: Estrutura da página.

CSS3 (Custom Properties): Estilização com variáveis e responsividade.

JavaScript (Vanilla):

Validação de campos.

Manipulação de DOM.

Armazenamento com localStorage.

🐞 Possíveis Melhorias Futuras
Máscaras nos campos (ex: CPF, telefone, CEP).

Validação em tempo real.

Integração com APIs para buscar endereço via CEP.

Layout responsivo com media queries.

Sistema de pagamento real (com gateway).

📄 Licença
Este projeto é livre para fins educacionais. Você pode usá-lo, modificá-lo e distribuí-lo como quiser.
