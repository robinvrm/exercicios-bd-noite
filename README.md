# exercicios-bd-noite 
Exercícios para o módulo de Banco de Dados

01 - Crie uma base de dados com o nome curso_programacao com as tabelas a seguir:

Obs. levar em consideração para o campo sexo 0 = masc, 1 = fem

-tb_alunos (id, fk_cidade, nome, endereco, numero_casa, nascimento, telefone, sexo)

-tb_cidades (id, nome, estado, abv_estado)


1.1 - adicionar as informações na tb_alunos

('4', 'maria', 'marte', '37', '1988-04-01', '99999-9991', '1'),

('1', 'calos', 'aleixo', '244', '2004-02-02', '99999-9992', '0'),

('1', 'cleuza', 'abraao glasser', '1567', '1969-04-29', '99999-9993', '1'),

('2', 'beatriz', 'vicente machado', '03', '1995-08-02', '99999-9994', '1'),

('1', 'marlon', 'balduino taques', '29', '2000-12-02', '99999-9995', '0');


1.2 - adicionar as informações na tb_cidades

('ponta grossa', 'parana', 'pr'),

('curitiba', 'parana', 'pr'),

('camboriu', 'santa catarina', 'sc'),

('caixias do sul', 'rio grande do sul', 'rs');

Obs. se atentar para os atributos de integridade referencial.


02- Abram um arquivo de texto e insiram os registros encontrados, identifique a questão e coloque a resposta abaixo.
Para subir no reposiório.

A- Selecione todos os registros da tabela tb_alunos.

B- Selecione todos os registros da tabela tb_cidades.

C- Selecione da tabela tb_alunos os alunos residentes em ponta grossa, apresentando apenas o sua primary key e nome.

D- Selecione todos os alunos com todas as suas informações.

E- Selecione todos os alunos do sexo feminino, apresentando os seus nomes e data de nascimento.

F- Selecione o(s) aluno(s) residente no Rio Grande do Sul, informse sua primary key, nome e sexo.

03 - Crie uma tabela chamada tb_cursos com os seguintes campos
(id_curso, materia, carga_horaria)

03.1- Adicione as seguintes informações na tb_cursos.

('html', '36'),

('css', '40'),

('js', '44'),

('php', '44');

04- Adicione uma coluna chamada fk_curso do tipo foreign key na tabela tb_alunos.

05- Adicione as informações a seguir na tabela tb_alunos no campo fk_curso.

('2'),

('1'),

('3'),

('4'),

('4');

05- Adicione as informações a seguir na tabela tb_alunos.

('4', 'bianca', 'azaleia', '58', '1990-04-03', '99999-9996', '1', '2'),

('2', 'jocelene', 'colibri', '256', '1095-07-09', '99999-9997', '1', '1'),

('4', 'lucas', 'germano', '356', '1993-03-29', '99999-9998', '0', '3'),

('2', 'marcos', 'siqueira', '21', '2001-08-02', '99999-9999', '0', '4'),

('1', 'ricardo', 'santos', '25', '2003-12-04', '99999-9910', '0', '4');

06 - Gere as sqls e o resultado adicione no txt já existente para suir no git.

a- Selecione todas as informações dos tb_alunos e todas as informações da tb_cidades utilizando as chaves de referência.

07 - criar uma tabela tb_turno com os campos:

(id_turno, turno)

criar os registros:

('manha'),
('tarde'),
('noite');

08 - criar uma chave estrangeiro na tb_alunos com referencia ao id turno

09 - selecionar todos os alunos que fazem o curso de html, no turno da tarde.

10 - selecionar todos os alunos que fazem o curso de js, no turno da noite

11 - selecionar apenas os alunos do sexo do tipo 1, que estão matrículados no turno da tarde, independente do curso.

12 - selecionar o nome de todos os alunos que fazem o curso de html e js.

13 - selecionar todos os alunos do paraná, que estão matrículados no turno da manhã.

14 - crie 2 sqls uma para o sexo masculino e outra para o sexo feminino cada uma delas com todos os alunos cadastrados e informe o seu id, nome, data de nascimento, o nome da cidade de onde ele é e o abv do estado e em qual turno eles estão cadastrado.

15 - Selecione todos os alunos cadastrados no curso de php e informe o seu id, nome, data de nascimento, o nome da cidade de onde ele é e em qual turno o mesmo está cadastrado.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1 - Em um arquivo a parte marque qual o número do exercício e insira a sql compatível com a solicitação.

a- Selecione os alunos que não moram em Ponta Grossa.

b- Selecione os alunos matriculados no curso de CSS no turno da tarde ou da noite.

c- Selecione os alunos em que o nome começa com 'mar'.

d- Selecione os alunos em que o nome começa com 'mar' e que sejam do sexo masculino.

e- Gere uma lista de todos os alunos, onde contenha seus ids, nomes, cidade, estado, curso matriculado, turno e ordene ppelo sexo e o nome em ordem alfabética.


_________________________________________________________________________________________________________________________________________________________________________

1 - faça uma nova tabela (tb_notas), nessa tabela deve-se ter os itens obrigatórios abordados nas aulas anteriores. Além disso, crie um campo fk_aluno, fk_curso, nota, ano, semestre.

2 - faça insert de mais 20 alunos na tabela de alunos (pela linha de comando).

3 - crie registros na tabela tb_notas, relacionando as fk's necessárias, das outras tabelas já criadas.

4 - crie uma SQL para buscar todos os alunos que tiverem notas maiores que 7.

5 - crie uma SQL que busque a quantidade de alunos que obtiveram nota maior que 7, separado por matéria.

