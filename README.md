📘 Portal Escolar
Um projeto simples de front-end que exibe alunos e professores cadastrados em um portal escolar.
A aplicação está estruturada em HTML, CSS e JavaScript, com integração a uma API que fornece os dados dinamicamente.

🚀 Funcionalidades
Exibição de alunos com nome e email.

Exibição de professores com nome e disciplina.

Layout responsivo e organizado em duas colunas.

Estilização com CSS customizado para manter consistência visual.

Fonte personalizada via Google Fonts (Iosevka Charon).

Dados carregados dinamicamente através de uma API conectada ao script.js.

📂 Estrutura do Projeto
Código
/
├── index.html        # Estrutura principal da página
├── style.css         # Estilos visuais (cores, fontes, espaçamento)
├── script.js         # Lógica para consumir API e renderizar dados
└── README.md         # Documentação do projeto
🖼️ Layout
Header: Barra superior azul escura com título e descrição.

Container: Duas seções lado a lado (Alunos e Professores).

Cards/Listagem: Cada aluno/professor aparece em blocos separados, com espaçamento e linha divisória.

🎨 Estilo (CSS)
Principais regras aplicadas:

Reset de margens com * { margin: 0 }.

Fonte Iosevka Charon aplicada ao corpo.

Header com fundo darkblue e texto branco.

Containers com bordas arredondadas, espaçamento interno e fundo branco.

Separadores (hr) uniformizados com width: 100%.

Estilo aplicado aos blocos de alunos/professores:

Espaçamento entre linhas (margin: 5px 0).

Separação entre registros com border-bottom: 1px solid #ddd.

⚙️ Como Executar
Clone ou baixe este repositório.

Certifique-se de que os arquivos index.html, style.css e script.js estão na mesma pasta.

Abra o arquivo index.html em qualquer navegador moderno.

O script.js irá consumir a API e preencher automaticamente os containers de alunos e professores.

🔧 Personalização
Para alterar cores e fontes, edite o arquivo style.css.

Para mudar os dados exibidos, ajuste a integração no script.js (ou configure a API).

Para adicionar novos campos (ex.: telefone, matéria extra), basta incluir no JSON da API e ajustar o renderizador no JS.

📌 Tecnologias Utilizadas
HTML5 para estrutura.

CSS3 para estilização.

JavaScript (ES6+) para integração com API e manipulação do DOM.

Google Fonts para tipografia.

📖 Próximos Passos
Melhorar responsividade para telas menores (mobile).

Adicionar paginação ou busca de alunos/professores.

Criar cards estilizados em vez de listas simples.

Implementar feedback visual de carregamento (loading spinner).
