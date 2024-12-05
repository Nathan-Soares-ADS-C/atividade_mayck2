PKG_ALUNO
Excluir Aluno (excluir_aluno):

Remove registros de um aluno com base no id_aluno.
Deleta primeiro em matricula e depois em aluno.
Listar Alunos Maiores de 18 Anos:

Cursor que retorna o nome e a data de nascimento de alunos maiores de 18 anos.
Listar Alunos por Curso:

Cursor que exibe os alunos matriculados em um curso específico (identificado por id_curso).
PKG_DISCIPLINA
Cadastrar Disciplina (cadastrar_disciplina):

Insere uma nova disciplina no banco com nome, descrição e carga horária.
Média de Idade dos Alunos Matriculados:

Calcula e exibe a média de idade dos alunos matriculados em uma disciplina específica.
Listar Alunos de uma Disciplina (listar_alunos_disciplina):

Mostra os alunos ativos matriculados em uma disciplina específica (id_disciplina).
PKG_PROFESSOR
Professores com Múltiplas Turmas:

Cursor que lista professores com mais de uma turma atribuída.
Total de Turmas de um Professor (total_turmas_professor):

Função que retorna o número de turmas que um professor leciona.
Obter Professor de uma Disciplina (obter_professor_disciplina):

Função que retorna o nome do professor associado a uma disciplina específica.

No final do arquivo tem as execuções para chamar o que foi criado anteriormente.
