Desenvolvimento de um Diagrama Entidade-Relacionamento (DER), que represente uma base de dados possível de ser implementado em um sistema de gerenciamento de banco de dados utilizando o software Workbench MySQL.
Uma biblioteca de uma universidade realiza empréstimo de suas obras para os alunos da instituição. Neste contexto temos:
- Aluno: pessoas que possuem registro na faculdade e são autorizadas a fazer empréstimo de livros na biblioteca;
- Livro: publicações físicas com registros passiveis de serem emprestados;
- Colaborador: funcionário da instituição autorizado a fazer empréstimos de livros aos alunos;
- Empréstimo: ação que o colaborador registra no sistema, e permite que livro fique relacionado ao aluno, por determinado período estabelecido pela biblioteca.
Cada entidade acima possuem os seguintes atributos:
Aluno (ra, nome, email, telefone)
Livro (isbn, nome, autor, paginas)
Colaborador (cpf, nome, email, cargo)
Empréstimo (id, dataEmprestimo, dataDevolucao, livroIsbn, colaboradorCpf)
Defina as chaves primárias e secundárias, defina também os tipos de dados dos atributos e elabore o DER utilizando o Workbench MySQL.
