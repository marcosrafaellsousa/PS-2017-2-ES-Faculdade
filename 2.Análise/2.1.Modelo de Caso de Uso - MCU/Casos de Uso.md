# Descrição de Casos de Uso

### Razão do documento
Esse documento tem como objetivo apresentar o diagrama de casos de uso do projeto e também descrevê-los a fim de
esclarecer melhor como funcionará a interação entre o usuário e o sistema.

Os casos de uso foram feitos baseados nos requisitos que podem ser encontrados aqui: [Requisitos].

### Personagens Envolvidos
> - Aluno
> - Professor
> - Coordenador
> - Sistema de Faculdade
> - Sistema de Faturamento
> - Sistema de Recrusos Humanos

### Modelo de Caso de Uso
![imgCasoDeUso]

### Legenda de Casos de Uso
| **ID** | **Nome** | **Usuário** |
|---|---|---| 
| UC01 | Visualizar Nota | Aluno |
| UC02 | Se inscrever em disciplina | Aluno |
| UC03 | Lançar Notas | Professor |
| UC04 | Atualizar Dados da turma | Professor |
| UC05 | Abrir Turma | Coordenador |
| UC06 | Alocar turma em sala ou laboratório em horário específico | Coordenador |
| UC07 | Obter dados cadastrais sobre os professores | Sistema de RH |
| UC08 | Informar as inscrições realizadas por alunos | Sistema de Faturamento |

### Descrição dos Casos de Uso
| **Casos de Uso** | **Autores** |**Pré-condição** | **Descrição** | **Pós-condição** |
|---|---|---|---|---|
| *UC01* | Alunos | Professor precisa ter lançado as notas de antemão | Aluno entra no sistema, seleciona a disciplina desejada e clica em ver notas. | Banco de Dados Inalterado |
| *UC02* | Alunos | As turmas tem que ser previamente cadastradas pelo Coordenador | Aluno entra no sistema e clica em matricular | Aluno estar matriculado na disciplina |
| *UC03* | Professor | Professor tem que estar vinculado à turma | O professor deve entrar no sistema, visualizar as turmas das quais ele cuida e clicar em lançar notas | Notas lançadas estarem associadas aos respectivos alunos da disciplina |
| *UC07* | Sistema de RH | Ter dados de professores cadastrados no sistema da faculdade | O sistema de RH deve solicitar ao Sistema da Faculdade a recuperação de uma busca na base de dados segundo uma consulta oferecida contendo o(s) identificador(es) do(s) professor(es). | Banco de dados inalterado. |
|  |  |  | | |
|  |  |  | | | 
|  |  |  | | |

| **UC01** | **Visualizar Notas**  |
|---|---|
| *Ator Principal* | Aluno |
| *Pré-Condições* | O aluno estar logado no sistema e estar matriculado na disciplina a qual deseja ver sua nota. |
| *Pós-Condições* | O sistema deve buscar no banco de dados as notas do aluno referente a disciplina marcada, sem, contudo, fazer qualquer alteração |
| *Fluxo* | 1 - Aluno loga no sistema com sua identificação única <br> 2 - Selecionar a disciplina deejada <br> 3 - Clicar em Visualizar Nota.|

[imgCasoDeUso]: <https://github.com/artiumdominus/PS-2017-2-ES-Faculdade/blob/master/2.An%C3%A1lise/2.1.Modelo%20de%20Caso%20de%20Uso%20-%20MCU/casosDeUso.jpg?raw=true>
[Requisitos]: <https://github.com/artiumdominus/PS-2017-2-ES-Faculdade/blob/master/1.Gest%C3%A3o/Tema%2001%20-%20Faculdade.docx>