# Nome do Sistema: PS-ES-Faculdade

### Introdução
Os requisitos abaixo listados são para uma faculdade que precisa de uma aplicação para controlar alguns processos acadêmicos, como inscrições em disciplinas, lançamento de notas, alocação de recursos para turmas, etc. 

### Requisitos Funcionais
**RF1** – O sistema deve permitir que os alunos visualizem as notas obtidas por semestre letivo.

**RF2** – O Sistema efetuar o lançamento das notas das disciplinas lecionadas em um semestre letivo e controlar os prazos e atrasos neste lançamento.

**RF3** – O Sistema deve manter informações cadastrais sobre disciplinas no currículo escolar.

**RF4** – O Sistema deve permitir a abertura de turmas para uma disciplina, assim como a definição de salas e laboratórios a serem utilizados e dos horários e dias da semana em que haverá aulas de tal turma.

**RF5** – O Sistema deve permitir que os alunos realizem a inscrição em disciplinas de um semestre letivo.

**RF6** – O Sistema deve permitir o controle do andamento das inscrições em disciplinas feitas por alunos.

**RF7** – O Sistema deve-se comunicar com o Sistema de Recursos Humanos para obter dados cadastrais sobre os professores.

**RF8** – O Sistema deve-se comunicar com o Sistema de Faturamento para informar as inscrições realizadas pelos alunos.

**RF9** – O sistema deve manter informações cadastrais sobre os alunos e seus históricos escolares, bem como das disciplinas no currículo escolar.

**RF10** - O sistema deve estar disponível para os usuários, alunos, professores, etc. o acessarem, via internet, na rede local da faculdade.

**RF11** – Professores possuem permissão para atualizar os dados (notas, frequências) das turmas atribuídas a ele por semestre.

### Rregras de Negócio

**RN01 – Quantidade máxima de inscrições por semestre letivo**

*Descrição:*
Em um semestre letivo, um aluno não pode se inscrever em uma quantidade de disciplinas cuja soma de créditos ultrapasse 20.

**RN02 – Quantidade de alunos possíveis**

*Descrição:*
Uma oferta de disciplina não pode ter mais de 40 alunos inscritos.

**RN03 - Pré-requisitos para uma disciplina**

*Descrição:*
Um aluno não pode se inscrever em uma disciplina para a qual não possua os pré-requisitos necessários.

**RN04 – Habilitação para lecionar disciplina**

*Descrição:*
Um professor não pode lecionar disciplinas para as quais não esteja habilitado.

**RN05 – Cancelamento de matrícula**

*Descrição:*
Um aluno deve ter a matrícula cancelada se for reprovado mais de duas vezes na mesma disciplina

**RN06 – Política de Avaliação de Alunos**

*Descrição:*
    **1.** A nota de um aluno em uma disciplina (um valor de 0 a 10) é obtida pela média de duas avaliações durante o semestre, A1 e A2, ou pela frequência nas aulas. <br>
        *1.1.* Se o aluno obtém nota maior ou igual a 7.0 (sete) está aprovado; <br>
        *1.2.* Se o aluno obtém nota maior ou igual a 5.0 (cinco) e menor do que 7.0 (sete), deve fazer a avaliação final;<br>
        *1.3.* Se o aluno obtém nota menor do que 5.0 (cinco) está reprovado; <br>
        *1.4.* Se o aluno tiver frequência menor que 75% em uma turma, está automaticamente reprovado. <br>

**RN07 – Consulta de Notas**

*Descrição:*
Um aluno não poderá visualizar os dados acadêmicos de outros alunos

**RN08 – Perfis**

*Descrição:*
Aos usuários do sistema serão atribuídos perfis de acordo com suas permissões no sistema.

**RN09 – Controle de Acesso**

*Descrição:*
O acesso é por meio de autenticação com senhas individuais.
