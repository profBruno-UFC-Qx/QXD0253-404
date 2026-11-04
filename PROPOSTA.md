# :checkered_flag: BiblioHub

Nosso projeto é um sistema bibliotecário que gerencia livros e empréstimos. Cada livro do catálogo é emprestado a um aluno durante um período e posteriormente devolvido ao catálogo.

## :technologist: Membros da equipe
Antonio David Barreto da Silva - Engenharia de Software - 580169
Vinicius Menezes da Silva - Engenharia de Software - 579975

## :bulb: Objetivo Geral
Tornar possível gerenciar o catálogo de livros por meio de um sistema, já que atualmente tudo é feito de maneira analógica.

## :eyes: Público-Alvo
Pessoas que precisam de um sistema simples e fácil de usar para gerenciar um catálogo de livros.

## :star2: Impacto Esperado
Tornar o dia a dia mais fácil, evitar a perda de livros e a redundância nos arquivos.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Bibliotecária (Área Restrita): Acesso principal com permissão total para cadastros e empréstimos;
Professor (Área Restrita): Acesso apenas para consultar quais alunos da turma estão com livros;
Visitante (Área Pública): Acesso apenas para ver se o livro está disponível no catálogo.

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

Área Pública (sem login):

Listar livros: Mostra todos os livros cadastrados no sistema.

Área Restrita (com login):

Cadastrar livro: Adiciona um livro ao catálogo com seus dados específicos;
Cadastrar aluno: Adiciona um aluno ao sistema;
Listar alunos: Mostra todos os alunos cadastrados no sistema;
Realizar empréstimos: Registra um livro a um aluno por um tempo determinado;
Listar empréstimos não finalizados: Mostra todos os livros emprestados a um aluno e não devolvidos ainda;
Listar empréstimos finalizados: Mostra todos os livros emprestados a um aluno e devolvidos.


## :spiral_calendar: Entidades ou tabelas do sistema

Livro, Aluno, Empréstimo.
