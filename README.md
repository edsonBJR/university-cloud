# University Cloud
Arquitetura para um sistema em nuvem para uma universidade, que tem várias unidades espalhadas no país.

Precisamos propor uma arquitetura para um sistema em nuvem para uma universidade, que tem várias unidades espalhadas no país. O principal requisito do sistema é que ele funcione pela Internet ou Intranet. O objetivo do sistema é acompanhar os históricos escolares dos alunos e o pagamento de mensalidades:
a)A universidade acompanha o nome, número de matrícula, número da identidade, endereço atual e telefone, endereço permanente e telefone, data de nascimento, sexo,
classe (primeiro ano, segundo ano, ...,graduado) departamento da especialização, departamento menos importante (se existe algum) e programa da graduação (Graduação, Mestrado, Ph.D.) de cada aluno. Algumas aplicações do usuário precisam se referir à cidade, estado e código de endereçamento postal do endereço permanente do aluno e ao sobrenome do aluno. Tanto o número da identidade quanto o número da matrícula possuem valores exclusivos para cada aluno.

b)Cada departamento é descrito por um nome, um código de departamento, o número do escritório, o telefone do escritório e a faculdade. Tanto o nome quanto o código
possuem valores exclusivos para cada departamento. 

c)Cada disciplina oferecida possui um nome, descrição, código da disciplina, número de horas do semestre, nível e o departamento que oferece a disciplina. O valor do código de identificação do curso é exclusivo para cada departamento.

d)Cada disciplina oferecida possui um instrutor, semestre, ano, disciplina e código da disciplina. O número de identificação da disciplina oferecida distingue as disciplinas oferecidas do mesmo curso que são ministradas durante o mesmo semestre/ano, seus valores são 1, 2, 3, até o número de disciplinas oferecidas ministradas durante cada semestre.

e)Cada alunos só poderá se matricular em uma disciplina ofertada.

f)Um relatório de grau possui um aluno, uma matéria, uma letra como grau, e um grau numérico (0, 1, 2, 3 ou 4).

g)O relatório financeiro possui o valor de cada mensalidade que o aluno deve pagar de acordo com as disciplinas matriculadas.

h)O relatório de aprovação possui as notas lançadas para o aluno, por um professor em um dado período em uma certa disciplina.
