# _**READMORE**_ 📖

# Informações

- 👨‍🏫 | **Professor:** [Marco André Mendes](github.com/marcoandre)

- 👥 | **Equipe** 
- [Bianca Lunelli Marques](github.com/bialunelli)
- [Erick Chaves Fiamoncini](github.com/erickChavesFiamoncini)
- [Mateus Lima de Macedo](github.com/mateusLimadeMacedo)
- [Renan de Lima Pereira](github.com/renan1811)

- 🔗 | **Links do projeto**
-   [Documentação (esse documento)](github.com/ReadMore-Org/ReadMore_doc)
-   Backend: [Repositório](github.com/ReadMore-Org/BackEnd) e [Publicação](Pendente)
-   Frontend: [Repositório](github.com/ReadMore-Org/FrontEnd) e [Publicação](Pendente)

# Proposta 📃

- 📑 | **_Descrição do projeto_**

   ReadMore é uma aplicação web progressiva (PWA) desenvolvida para transformar a forma como leitores organizam e compartilham suas leituras. A plataforma funciona como uma estante virtual, permitindo que usuários adicionem, gerenciem e acompanhem seus livros de maneira prática e intuitiva.
   Além da organização pessoal, o ReadMore promove a interação entre leitores ao possibilitar o empréstimo de livros entre usuários, criando uma rede colaborativa de leitura. Com uma interface moderna e acessível, o aplicativo oferece uma experiência fluida tanto em dispositivos móveis quanto desktop, incentivando o hábito da leitura e a conexão entre pessoas através dos livros.
   O projeto tem como foco a usabilidade, acessibilidade e eficiência, utilizando tecnologias web modernas para garantir desempenho e experiência de usuário de alta qualidade.

- 📌 | **_Problema - Projeto Capas Duras_**

   O governo municipal lançou um projeto nas bibliotecas da cidade chamado Capas Duras, com a finalidade de ampliar o acesso à leitura para toda a população, independentemente de sua condição financeira. Para isso, as bibliotecas municipais receberam doações que totalizam mais de 10 mil livros, os quais serão disponibilizados para empréstimo aos leitores da comunidade.
   Apesar de a nova biblioteca já contar com computadores e estantes adequadas para organizar o acervo, não há recursos financeiros suficientes para investir em equipamentos como leitores de impressão digital ou para produzir carteirinhas para todos os usuários. Dessa forma, surge a necessidade de um sistema simples e de baixo custo que permita administrar o acervo, controlar os empréstimos, verificar a disponibilidade dos livros e registrar as movimentações de forma prática.
   Além da gestão interna da biblioteca, também é importante que o sistema facilite a conexão entre leitores da comunidade que possuam livros e estejam dispostos a emprestá-los. Assim, o projeto não ficaria restrito apenas às bibliotecas municipais, mas poderia se expandir para a participação da própria população, ampliando ainda mais o acesso aos livros.
   Por fim, o sistema deverá permitir a geração de relatórios, possibilitando o acompanhamento dos empréstimos realizados e do número de livros disponíveis no acervo, contribuindo para uma gestão mais eficiente e organizada.

- 🧑‍💻 | **_Descrição da proposta_**

   O foco de ação do software é a organização e o empréstimos de livros. Existem dois tipos de usuários: o usuário administrador e o usuário comum, já que todos serão capazes de cadastrar livros para emprestar, receber empréstimos e organizar seus próprios acervos digitais. Para que essa estrutura seja completa, pensamos em uma divisão entre duas partes: em primeiro plano, o acervo digital pessoal, e, em seguida, a parte onde serão efetuados as relações de empréstimos. Toda essa lógica deve funcionar com a possibilidade de chats de conversas entre usuários, além da visualização de endereços de livros disponíveis para empréstimos cadastrados perto de cada usuário.

# Modelagem de Dados 🎲

<img width="908" height="506" alt="modelagem_ReadMore" src="https://github.com/user-attachments/assets/3e806e06-edf4-4ff4-8133-dbbb9257ef23" />

# Requisitos 🎖️

- ⭐ | **_Requisitos funcionais_**

- _RF001 - Cadastro de usuários_
   - O sistema deve manter usuários.
   - O sistema deve manter imagens.
   - O sistema deve manter e-mails.
- **RF002 - Cadastro de livros**
   - O sistema deve manter livros.
   - O sistema deve manter categorias.
   - O sistema deve manter itens.
   - O sistema deve manter status.
   - O sistema deve manter autores.
   - O sistema deve manter progresso.
   - O sistema deve manter avaliações.
- **RF003 - Empréstimo de livros**
   - O sistema deve permitir que usuários emprestem livros disponíveis por um período determinado.
   - O sistema deve manter histórico de livros emprestados.
- **RF004 - Controle**
   - O sistema deve controlar o tempo de devolução de cada livro emprestado.
- **RF005 - Alerta**
   - O sistema deve enviar um alerta ao usuário caso o tempo seja excedido.
- **RF006 - Barra de pesquisa**
   - O sistema deve fornecer uma barra de pesquisa para buscar produtos.
- **RF007 - Perfis de usuários**
   - O sistema deve manter avaliação.
   - O sistema deve manter perfil de usuários públicos.
- **RF008 - Controle de livros**
   - O sistema deve controlar a quantidade de produtos emprestados e produtos cadastrados por cada usuário.
- **RF009 - Avaliação de usuários**
   - O sistema deve permitir que usuários avaliem mutuamente.
- **RF010 - Sistema de contato entre usuários**
   - O sistema deve permitir que usuários entrem em contato.
- **RF011 - O sistema deve manter localização dos livros**
- **RF012 - O sistema deve permitir a opção de entrega de produtos alugados**
- **RF013 - O sistema deve manter editoras**

- 🌟 | **_Requisitos não funcionais_**

- **RNF001 - Login/Logout**
   - O sistema deve permitir que os usuários façam login e logout.
- **RNF002 - Arquitetura Cliente-Servidor**
   - O sistema será dividido em frontend (Vue.js) e backend (Django).
- **RNF004 - Segurança**
   - O sistema deve criptografar senhas e usar autenticação segura (ex: JWT, isAuthenticated…).
- **RNF005 - Usabilidade**
   - O sistema deve fornecer uma interface amigável, intuitiva e responsiva (adaptada para desktop e mobile).
- **RNF006 - Performance**
   - O sistema deve realizar buscas e carregar páginas em até 2 segundos, em média.
- **RNF007 - Compatibilidade**
   - O sistema deve funcionar corretamente nos principais navegadores (Chrome, Firefox, Edge) nas versões mais recentes.
- **RNF008 - Manutenibilidade**
   - O sistema deve fornecer um código modular e bem documentado para facilitar a manutenção e atualizações.
- **RNF009 - Backup e Recuperação**
   - O sistema deve conter mecanismos para backup automático dos dados e recuperação em caso de falha.
