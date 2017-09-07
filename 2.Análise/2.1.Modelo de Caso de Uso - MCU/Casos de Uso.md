# Casos de Uso

### Personagens Envolvidos
> - Aluno
> - Professor
> - Coordenador
> - Sistema de Faculdade
> - Sistema de Faturamento
> - Sistema de Recrusos Humanos

### Modelo de Caso de Uso
![imgCasoDeUso]

### Descrição dos Casos de Uso
| **Casos de Uso** | **Autores** |**Pré-condição** | **Descrição** | **Pós-condição** |
|---|---|---|---|---|
| *Visualizar Notas* | Alunos | Professor precisa ter lançado as notas de antemão | Aluno entra no sistema, seleciona a disciplina desejada e clica em ver notas. | Banco de Dados Inalterado |
| *Se inscrever em Disciplina* | Alunos | As turmas tem que ser previamente cadastradas pelo Coordenador | Aluno entra no sistema e clica em matricular | Aluno estar matriculado na disciplina |
| *Lançar Notas* | Professor | Professor tem que estar vinculado à turma | O professor deve entrar no sistema, visualizar as turmas das quais ele cuida e clicar em lançar notas | Notas lançadas estarem associadas aos respectivos alunos da disciplina |
| *Obter dados cadastrais sobre os professores* | Sistema de RH | Ter dados de professores cadastrados no sistema da faculdade | O sistema de RH deve solicitar ao Sistema da Faculdade a recuperação de uma busca na base de dados segundo uma consulta oferecida contendo o(s) identificador(es) do(s) professor(es). | Banco de dados inalterado. |
|  |  |  | | |
|  |  |  | | | 
|  |  |  | | |

[imgCasoDeUso]: <https://github.com/artiumdominus/PS-2017-2-ES-Faculdade/blob/master/2.An%C3%A1lise/2.1.Modelo%20de%20Caso%20de%20Uso%20-%20MCU/casosDeUso.jpg?raw=true>