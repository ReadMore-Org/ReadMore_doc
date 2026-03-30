# _**READMORE**_ 📖

# Informações 📋

- 👨‍🏫 | **Professor**
- [Marco André Mendes](github.com/marcoandre)

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
- _RF002 - Cadastro de livros_
   - O sistema deve manter livros.
   - O sistema deve manter categorias.
   - O sistema deve manter itens.
   - O sistema deve manter status.
   - O sistema deve manter autores.
   - O sistema deve manter progresso.
   - O sistema deve manter avaliações.
- _RF003 - Empréstimo de livros_
   - O sistema deve permitir que usuários emprestem livros disponíveis por um período determinado.
   - O sistema deve manter histórico de livros emprestados.
- _RF004 - Controle_
   - O sistema deve controlar o tempo de devolução de cada livro emprestado.
- _RF005 - Alerta_
   - O sistema deve enviar um alerta ao usuário caso o tempo seja excedido.
- _RF006 - Barra de pesquisa_
   - O sistema deve fornecer uma barra de pesquisa para buscar produtos.
- _RF007 - Perfis de usuários_
   - O sistema deve manter avaliação.
   - O sistema deve manter perfil de usuários públicos.
- _RF008 - Controle de livros_
   - O sistema deve controlar a quantidade de produtos emprestados e produtos cadastrados por cada usuário.
- _RF009 - Avaliação de usuários_
   - O sistema deve permitir que usuários avaliem mutuamente.
- _RF010 - Sistema de contato entre usuários_
   - O sistema deve permitir que usuários entrem em contato.
- _RF011 - O sistema deve manter localização dos livros_
- _RF012 - O sistema deve permitir a opção de entrega de produtos alugados_
- _RF013 - O sistema deve manter editoras_

- 🌟 | **_Requisitos não funcionais_**

- _RNF001 - Login/Logout_
   - O sistema deve permitir que os usuários façam login e logout.
- _RNF002 - Arquitetura Cliente-Servidor_
   - O sistema será dividido em frontend (Vue.js) e backend (Django).
- _RNF004 - Segurança_
   - O sistema deve criptografar senhas e usar autenticação segura (ex: JWT, isAuthenticated…).
- _RNF005 - Usabilidade_
   - O sistema deve fornecer uma interface amigável, intuitiva e responsiva (adaptada para desktop e mobile).
- _RNF006 - Performance_
   - O sistema deve realizar buscas e carregar páginas em até 2 segundos, em média.
- _RNF007 - Compatibilidade_
   - O sistema deve funcionar corretamente nos principais navegadores (Chrome, Firefox, Edge) nas versões mais recentes.
- _RNF008 - Manutenibilidade_
   - O sistema deve fornecer um código modular e bem documentado para facilitar a manutenção e atualizações.
- **RNF009 - Backup e Recuperação**
   - O sistema deve conter mecanismos para backup automático dos dados e recuperação em caso de falha.

- 🪐 | **_Regras de negócios_**

- RN001.01 - Dados dos usuários: nome, e-mail, senha, avatar e endereço.
- RN001.02 - A imagem deve ser associada ao usuário como “avatar”.
- RN002.01 - Os itens devem ser cadastrados por usuários.
- RN002.02 - Dados dos livros: nome, descrição, imagens, categoria, data de publicação, páginas, tipo da capa e tempo máximo de empréstimo.
- RN005.01 - O alerta deverá ser enviado como forma de notificação para o usuário.
- RN006.01 - Os produtos devem ser filtrados por: nome, categoria e/ou localização. 
- RN007.01 - A avaliação deverá ser em formato de estrelas e/ou descrição. 
- RN007.02 - Dados do perfil do usuário: nome, foto, região, avaliação e descrição.
- RN008.01 - Os produtos emprestados e cadastrados por cada usuário devem ser listados.
- RN009.01- As avaliações devem acontecer após a finalização de um empréstimo. 
- RN010.01 - O contato deve acontecer via chat/mensagem interna com os donos dos livros. 
- RN011.01 - Exibir localização com base na proximidade geográfica do usuário.
- RN012.01 - Dados da entrega: taxa e rastreio.
