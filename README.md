Atividade 1 - App Web com Express

Desenvolvimento Web I - Prof. Arley

Tema: Desenvolvimento de uma Aplicação Web utilizando Node.js e Express para servir páginas HTML estáticas.

Descrição:
Atividade desenvolvida como parte dos requisitos da disciplina Desenvolvimento Web I, ministrada pelo professor Arley, no curso de Desenvolvimento de Software Multiplataforma, da Fatec de Jacareí/SP.

Objetivos:
- organização de um projeto em pastas;
- criação de rotas no backend;
- conexões entre HTML e CSS;
- exibição de uma página 404 quanto uma rota é inexistente.

Ferramentas utilizadas:
- VS Code;
- node.js;
- dotenv;
- HTML5;
- CSS3

Estrutura do projeto:
app/
|- server.js
|- package.json
|- package-lock.json
|- .env
|- public/
|  |- assets/
|  |  |- css/main.css
|  |  |- img/
|  |- pages/
|  |  |- index.html
|  |  |- login.html
|  |  |- cadastro.html
|  |  |- 404.html

Função dos arquivos:
- server.js: inicializa o servidor Express, definindo rotas e configurando pastas e arquivos da aplicação;
- assets: arquivos de apoio da interface (CSS e imagens);
- pages: páginas HTML da aplicação;
- .env: permite a definição da porta do servidor (PORT).

Rotas da aplicação:
- / -> página inicial;
- /login -> página de login;
- /cadastro -> página de cadastro;
- /404 -> página inexistente.

Execução do projeto:
1) Instale as dependências:
npm install
2) Inicie o servidor:
npm start
3) Abra no navegador:
http://localhost:3001
Pode ser utilizado outra porta, editando o arquivo .env, alterando PORT.

Modo de desenvolvimento:
Para visualização em tempo real das alterações na aplicação:
npm run dev

Observações:
- As páginas de login e cadastro são exemplos de interface e não há validação de dados no backend.
- Os formulários estão visualmente concluídos, porém não há salvamento de dados em banco.
- O objetivo desta atividade foi estudar estruturas, rotas e organização de arquivos.