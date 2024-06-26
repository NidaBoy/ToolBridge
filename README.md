# ToolBridge
Este repositório contém o código-fonte do ToolBridge, uma aplicação inovadora projetada para facilitar o aluguel de ferramentas entre lojistas e usuários. ToolBridge atende a necessidade de um mercado em rápida expansão para aluguel de ferramentas, oferecendo uma plataforma fácil de usar tanto para quem busca alugar ferramentas quanto para lojistas que desejam disponibilizá-las.

## Visão Geral
O ToolBridge é desenvolvido com o objetivo de ser uma ponte entre usuários e lojistas, permitindo que ferramentas sejam alugadas de forma eficiente e sem complicações. O sistema oferece um meio de aumentar a utilidade de ferramentas que, de outra forma, permaneceriam inativas, maximizando assim seu potencial e disponibilidade.
## Membros
- Espezzialy Souza
- Joao Brito
- Daniel Barreto

## Funcionalidades
- Cadastro de Usuários e Lojistas: Permite que usuários criem suas próprias contas, enquanto lojistas são adicionados pela equipe do ToolBridge, garantindo confiabilidade e segurança.
- Listagem de Ferramentas: Lojistas podem listar ferramentas disponíveis para aluguel, incluindo detalhes como nome, tipo, categoria, valor do aluguel por dia, ID único e quantidade em estoque.
- Busca e Aluguel de Ferramentas: Usuários podem buscar ferramentas disponíveis e alugá-las por um período determinado. O sistema simula a transação de aluguel, ajustando automaticamente o estoque do lojista.
- Gestão de Alugueis: Tanto usuários quanto lojistas têm acesso a uma interface para acompanhamento de alugueis ativos e histórico.
## Tecnologias Utilizadas
- Node.js: Ambiente de execução para JavaScript no lado do servidor, escolhido pela sua eficiência e ampla adoção para o desenvolvimento de aplicações web.
- React: Biblioteca JavaScript para a construção de interfaces de usuário, proporcionando uma experiência dinâmica e responsiva no frontend.
- MongoDB: Banco de dados orientado a documentos, utilizado por sua flexibilidade e facilidade de integração com aplicações Node.js.
- Express.js: Framework para Node.js que facilita a criação de APIs web de maneira rápida e fácil.
- JWT (JSON Web Tokens): Tecnologia utilizada para a autenticação de usuários, garantindo segurança e integridade das sessões.
- Bcrypt: Biblioteca para a criptografia de senhas, assegurando a proteção de dados sensíveis dos usuários.

## Backlog do Produto

- Como cliente eu quero criar uma conta de cliente para acessar funcionalidades exclusivas
- Como lojista eu quero criar uma conta de lojista para acessar funcionalidades exclusivas
- Como cliente eu quero logar na minha conta de cliente para acessar funcionalidades exclusivas
- Como lojista eu quero logar na minha conta de lojista para acessar funcionalidades exclusivas
- Como cliente eu quero visualizar as ferramentas disponíveis oferecidas por cada loja
- Como cliente eu quero filtrar por categoria as ferramentas disponíveis
- Como cliente eu quero adicionar uma ferramenta para aluguel ao meu  carrinho
- Como cliente eu quero visualizar o meu carrinho
- Como cliente eu quero solicitar o aluguel de produtos que estão no meu carrinho
- Como lojista eu quero aceitar a solicitação de aluguel enviada por um cliente
- Como cliente eu quero ver meus aluguéis ativos
- Como cliente eu quero devolver uma ferramenta alugada
- Como cliente eu quero visualizar meu histórico de aluguéis
- Como cliente eu quero alterar minhas informações de conta
- Como lojista eu quero adicionar uma ferramenta à minha loja
- Como lojista eu quero visualizar minhas ferramentas alugadas
- Como lojista eu quero visualizar meu histórico de aluguéis
- Como lojista eu quero modificar informações de uma ferramenta oferecida
- Como Lojista eu quero excluir uma ferramenta
- Como lojista eu quero modificar as informações da minha loja
- Como cliente eu quero avaliar uma loja a qual aluguei um produto
- Como lojista eu quero avaliar um cliente que alugou minhas peças

## Backlog da Sprint
- Como cliente eu quero criar uma conta de cliente para acessar funcionalidades exclusivas
  - Definir a estrutura básica do projeto, incluindo a organização de pastas, arquivos e componentes.
  - Criar aplicação node
  - Configurar o banco de dados e criar as primeiras tabelas
  - Configurar o Express e o Rest e testar uma rota
  - Criar a tela de cadastro de conta
  - Criar a lógica de cadastro
- Como cliente eu quero logar na minha conta de cliente para acessar funcionalidades exclusivas
  - Criar a tela de login
  - Criar a lógica de login
- Como cliente eu quero visualizar as ferramentas disponíveis oferecidas por cada loja
  - Criar a tela principal de ferramentas oferecidas pelas lojas
  - Criar a lógica de recuperação de ferramentas oferecidas pelas lojas
- Como cliente eu quero adicionar uma ferramenta para aluguél ao meu  carrinho
  - Criar a lógica do carrinho
- Como cliente eu quero visualizar o meu carrinho
  - Criar a tela do carrinho
- Como cliente eu quero alugar um produto que está no meu carrinho
  - Criar a lógica do aluguel

## Desenvolvedores
- Espezzialy Souza - FullStack
- Joao Brito - Fullstack
- Daniel - FullStack
