Questão 1:
CREATE TABLE ` soy-transducer-365822.turma880.alunos_Railane` (
 ID int64 not null,
 Matricula string,
 Nome string,
 Estado string,
 Formacao string
)

Questão 2:
alter table `soy-transducer-365822.turma880.alunos_Railane` 
rename column Estado to UF

Questão 3:
alter table `soy-transducer-365822.turma880.alunos_Railane` 
add column Email string

alter table `soy-transducer-365822.turma880.alunos_Railane` 
add column Telefone int64

Questão 4:
alter table `soy-transducer-365822.turma880.alunos_Railane` 
drop column ID

Questão 5:
drop table `turma880.alunos_Railane`

Questão 6:
CREATE TABLE `soy-transducer-365822.turma880.Doterra_Railane` (
Nome string,
Filha int64 not null,
Mae string,
Pai string,
Cidade string
)



