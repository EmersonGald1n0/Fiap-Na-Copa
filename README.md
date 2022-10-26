# Fiap-Na-Copa

1. Crie uma API JAVA, utilizando uma lista estática para simular e manipular o banco de dados que valide o usuário e senha do cliente.
- O usuário deve possuir os seguintes dados: login,senha,rm,nome
- A api deve possuir toda a estrutura já informada em projetos anteriores: TO/DAO/BO/RESOURCES, e não se esqueça da classe de testes.
2. Crie um projeto react utilizando o create-react-app chamado fiap-na-copa, limpe as pastas public e src, deixando apenas os arquivos que serão necessários para a sua aplicação.
3. Cabeçalho e Rodapé (1 ponto) - O projeto deverá ter um cabeçalho com um título “FIAP na COPA” e um menu contendo os links para navegação das páginas e um botão que:
a. Se o usuário ainda não estiver logado vá para página de login
b. Se ele estiver logado para o usuário deslogar da aplicação e retornar para página Home.
c. O rodapé deverá ter o nome e RM dos integrantes.
4. Login (3 pontos) – A página Login deverá ser chamada por um botão no menu do site. Deverá conter um título, um texto de explicação e um formulário onde o usuário deverá validar sua conta na API e ser direcionado para página home.
Obs. Use uma sessão no navegador para guardar os dados do usuário, que deverá aparecer no início de cada página enquanto estiver logado.
Obs. Você pode usar o login ou o nome do usuário para essa apresentação.
5. Home (1 ponto) – A página Home deverá ter um texto falando da febre de colecionar as figuras e o álbum da Copa e uma explicação com imagens das páginas de apresentação das figurinhas.
6. Figurinhas Nacionais (1.5 pontos) – A página deve mostrar ao menos 10 figurinhas de jogadores da seleção brasileira. E só poderá ser visitada se o usuário estiver logado.
7. Figurinhas Internacionais (1.5 pontos) – A página deve mostras ao menos 10 figurinhas de jogadores de 3 seleções Internacionais. E só poderá ser visitada se o usuário estiver logado.
8. Navegação (1 ponto) – O cabeçalho e o Rodapé deverão ficar fixos e apenas as páginas deverão ser montadas e desmontadas na tela, faça isso utilizando o React-router-dom.
9. Estilização (1 pontos) – Utilize o Styled-components para fazer a estilização da página dos componentes, onde o cabeçalho e rodapé deverão ter uma estilização interna e os demais componentes estilização externa. A qualidade da estilização será avaliada.
