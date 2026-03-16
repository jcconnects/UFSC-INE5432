# Plano de Ensino — INE5432 Banco de Dados II

## 1. Identificação

- **Disciplina:** INE5432 - Banco de Dados II
- **Turma(s):** 07208
- **Carga horária:** 72 horas-aula (Teóricas: 72 | Práticas: 0)
- **Período:** 1º semestre de 2026

## 2. Curso(s)

- Ciências da Computação (208)

## 3. Requisito(s)

- Ciências da Computação (208)
  - INE5423 - Banco de Dados I

## 4. Professor(es)

- Renato Fileto (r.fileto@ufsc.br)

## 5. Ementa

SQL embutida: instruções estáticas e dinâmicas, cursores. Processamento de consultas: otimização algébrica; plano de execução de uma consulta considerando estimativas sobre os dados, índices, buffers e pipelines. Transações: definição, propriedades, estados. Recuperação de falhas: categorias de falhas, gerência de buffer, técnicas de recuperação. Controle de concorrência: teoria da serializabilidade, escalonadores otimistas e pessimistas, tratamento de deadlock. Noções básicas de bancos de dados distribuídos: arquiteturas, projeto, processamento de consultas, gerência de transações.

## 6. Objetivos

### Geral

Fornecer ao aluno uma visão geral das técnicas de gerenciamento interno de um Sistema de Gerência de Banco de Dados (SGBD), bem como uma introdução a BDs Distribuídos (BDD) e à SQL embutida. Ao final da disciplina, o aluno deverá ser capaz de entender, avaliar e empregar adequadamente os recursos de SGBDs em geral, conhecer os fundamentos de BDDs e alguns BDs não-convencionais.

### Específicos

1. Revisar e reforçar conhecimentos sobre organização e indexação de dados para suportar métodos de acesso eficientes;
2. Familiarizar o aluno a sistemática de processamento de consultas em SGBDs, compreendendo os principais algoritmos envolvidos e as etapas de otimização algébrica e definição de plano de execução;
3. Compreender o conceito de transação: seus estados e suas propriedades;
4. Conhecer os tipos de falhas que podem ocorrer em um SGBD e as técnicas de recuperação das transações do BD na ocorrência de falhas;
5. Conhecer as técnicas para a correta execução concorrente de transações em um SGBD e a recuperação dos estado do BD em caso de falhas;
6. Familiarizar-se com os conceitos e noções de projeto de BDDs e entender, de maneira geral, as suas técnicas de gerenciamento de transações e de processamento de consultas;
7. Ser capaz de aplicar as instruções da SQL embutida no código de uma aplicação que acessa um SGBD;
8. Ter uma visão das tendências em BDs e noções de tecnologias de BDs não-convencionais, tais como orientados a objetos, NO-SQL, geográficos, temporais, multimídia e semi-estruturados, através de seminários e aulas sobre tópicos avançados.

## 7. Conteúdo Programático

- **Introdução ao processamento de consultas** [4 horas-aula]
  - Organização e indexação de dados para acesso eficiente
- **Otimização algébrica de consultas** [6 horas-aula]
  - Regras de equivalência algébrica
  - Algoritmo de otimização
- **Plano de execução de uma consulta** [4 horas-aula]
  - Catálogo do BD e estimativas sobre os dados
  - Técnicas para processamento de operações algébricas, considerando índices e pipelines
- **Introdução a transações** [6 horas-aula]
  - Definição, propriedades e estados de uma transação
  - Escalonamento de operações
- **Recuperação de falhas** [10 horas-aula]
  - Tipos de falhas
  - Gerência de buffer
  - Técnicas de recuperação
- **Controle de concorrência** [14 horas-aula]
  - Teoria da serializabilidade
  - Técnicas otimistas e pessimistas
  - Tratamento de deadlock
- **Introdução a Bancos de Dados Distribuídos** [16 horas-aula]
  - Arquiteturas de BDD
  - Noções de projeto de BDD
  - Processamento de consultas em BDD
  - Gerência de transações em BDD
- **SQL embutida** [4 horas-aula]
  - Instruções estáticas e dinâmicas
  - Cursores
- **Tópicos em bancos de dados** [8 horas-aula]

## 8. Metodologia

### Atividades

Os tópicos do conteúdo programático da disciplina serão apresentados através de aulas expositivas e trabalhados em exercícios teóricos e práticos, usando diversos materiais disponíveis no Moodle.

Serão realizadas as seguintes atividades:

- **Aulas expositivas** com apresentação de conteúdos teóricos e práticos, resolução de problemas relacionados com os temas tratados e de exercícios. Serão usados projetor acoplado a computador e quadro negro.

- **Demonstrações de software e soluções de problemas**, sendo ao menos uma demonstração de interação com otimizador de consultas em banco de dados relacional. Serão utilizados um Sistema de Gerenciamento de Bancos de Dados (SGBD) e materiais disponibilizados no Moodle. Máquina virtual do SETIC está disponível para os alunos da disciplina que quiserem usarem para fazerem experimentos de interação com o otimizador de consultas do SGBD.

- **Leituras** de textos pertinentes à disciplina, cuja realização será contabilizada no Moodle para acompanhar a evolução dos alunos. Em alguns casos será solicitado que o aluno poste no Moodle resultados de suas leituras, tais como resumos e/ou respostas a questões sobre o material lido, que podem valer nota na média da disciplina.

- **Exercícios** referentes aos tópicos tratados em aulas, alguns deles valendo nota na média da disciplina.

- **Duas provas (P1 e P2)** individuais.

- **Trabalho (T)** de pesquisa e/ou implementação desenvolvido individualmente ou em grupos, com apresentação dos resultados (ao vivo e/ou video com apresentação de slides) em data e horários a serem acordados entre professor e alunos envolvidos (de acordo com os grupos formados). Os grupos que preferirem podem postar documento ao invés de apresentação. O trabalho deve versar sobre um dos seguintes temas:
  - organização e recuperação de informação em bancos de dados;
  - processamento e otimização de consultas;
  - controle de concorrência de transações;
  - backup, log e recuperação em bancos de dados;
  - bancos de dados distribuídos;
  - outros temas de interesse, tais como bancos de dados não-convencionais e avançados, desde que relacionados à disciplina, negociados e aprovados previamente pelo professor.

### Informações e recomendações

- Diversos materiais (incluindo slides de aulas, alguns videos, demonstrações, exercícios, artigos e livros) estão disponibilizados no ambiente virtual de ensino aprendizagem Moodle. Eles são exclusivamente para fins didáticos, sendo vedada a sua utilização para qualquer outra finalidade, sob pena de responder administrativa e judicialmente.

- Os alunos devem estar cientes de que esta disciplina exige tempo de dedicação extraclasse.

- O Fórum de Notícias da disciplina no Moodle será usado para o professor divulgar informações sobre a disciplina. Outro fórum aberto para postagens dos alunos permite discussões referentes aos tópicos e atividades da disciplina entre os discentes.

- A melhor forma de tirar dúvidas sobre conteúdos e atividades da disciplina é nas aulas, pois a interatividade oral e visual permite melhor comunicação e contribui para o rendimento de todos. Se necessário também poderão ser usados video conferências adicionais em horários acordados. Mensagens assíncronas e e-mail devem ser reservados para a resolução de problemas pontuais que não requeiram interatividade.

- Recomenda-se fortemente a cada aluno tentar resolver os exercícios por si mesmo, antes de acessar resolução provida pelo professor ou outrem, por exemplo em aula, video, slides, documento ou demonstração.

- Parte dos exercícios desta disciplina não tem gabarito, devido ao grande número de soluções corretas ou simplemente mais ou menos adequadas segundo diferentes critérios. Faz parte do processo de aprendizagem entender inclusive tais nuances, que frequentemente acontecem em situações práticas.

- Colegas especialistas na área e um estagiário docente poderão auxiliar em algumas aulas, atendimento a dúvidas referentes a tais aulas, preparação de alguns materiais didáticos, exercícios e avaliações.

## 9. Avaliação

A avaliação do aluno será feita mediante a combinação de notas nas seguintes atividades (com notas na escala de 0 a 10):

- **L:** Leituras valendo nota na média da disciplina (DUAS, cujos resultados devem ser entregues no Moodle dentro prazos determinados)
- **E:** Exercícios valendo nota na média da disciplina (QUATRO, cujos resultados devem ser entregues no Moodle dentro prazos determinados ao final de cada módulo da disciplina)
- **P1:** Primeira prova individual
- **P2:** Segunda prova individual
- **T:** Trabalho individual ou em grupo

**Objetivos:**
- **Leituras (L):** Adquirir conhecimentos sobre assuntos relevantes relacionados aos tópicos da disciplina.
- **Exercícios (E):** Aferir, aplicar e sedimentar conhecimentos adquiridos na disciplina e desenvolver habilidades para solucionar problemas relacionados aos tópicos da disciplina.
- **Provas (P1 e P2):** Avaliar a capacidade do aluno em demonstrar, individualmente, os conhecimentos e habilidades aprendidos.
- **Trabalho (T):** Avaliar a capacidade dos alunos aplicarem e expandirem os conhecimentos e habilidades aprendidos em aula na solução de problemas práticos.

**Fórmula da Média Final:**

```
MF = 0,2*L + 0,2*E + 0,2*P1 + 0,2*P2 + 0,2*T
```

Será considerado aprovado o aluno com Nota Final >= 6 e frequência suficiente nas aulas.

Conforme parágrafo 2º do artigo 70 da Resolução 17/CUn/97, o aluno com frequência suficiente (FS) e média final no período (**MF**) entre 3,0 e 5,5 terá direito a uma nova avaliação ao final do semestre (**REC**), sendo a nota final (**NF**) calculada conforme parágrafo 3º do artigo 71 desta resolução: **NF = (MF + REC) / 2**.

## 10. Cronograma

A matéria será apresentada conforme descrito no tópico "Conteúdo Programático", procurando-se respeitar a seqüência e a carga horária indicadas.

As atividades envolvendo avaliação serão preferencialmente realizadas nas datas a seguir:

| Atividade | Período |
|---|---|
| Leituras (L) | 1ª a 12ª semana letiva |
| Exercícios (E) | 2ª a 14ª semana letiva |
| Prova 1 (P1) | 8ª semana letiva |
| Apresentações dos trabalhos (T) | 13ª a 15ª semanas letivas |
| Prova 2 (P2) | 17ª semana letiva |
| Recuperação (R) | 18ª semana letiva |

As datas exatas das provas (P1 e P2) e apresentações de trabalhos (T) serão marcadas na primeira semana de aula e publicadas no Moodle. As datas limites para entregas de cada atividade de leitura (L) e cada resolução de exercício (E) estarão especificadas junto às respectivas atividades no Moodle.

A responsabilidade e o cumprimento de prazos para a execução e entrega das atividades também serão avaliados. O atraso na entrega de atividades poderá resultar em desconto de até 0.5 ponto na nota do respectivo item.

Não será tolerada ausência em provas e apresentações de trabalhos. Em caso de não comparecimento no dia e horário marcados, só será concedida outra oportunidade em casos devidamente justificados e comprovados pelo aluno, além de reconhecidos pela administração da UFSC e conferidos pelo professor. Caso contrário será atribuída nota 0 (zero).

## 11. Bibliografia Básica

- Elmasri, R.; Navathe S. B. *Sistemas de Banco de Dados*. 6a edição. Editora Pearson. 2011. (em inglês: *Fundamentals of Database Systems*. 6th edition. Pearson. 2011).
- Korth, H. F.; Sudarshan, S; Silberschatz, A. *Sistema de Banco de Dados*. 5a edição. Editora Campus, 2006.
- Ramakrishnan, R., Gehrke, J. *Database Management Systems*. 3th ed. McGraw Hill. 2003.

## 12. Bibliografia Complementar

- Korth, H. F.; Sudarshan, S; Silberschatz, A. *Sistema de Banco de Dados*. 6a edição. Editora Campus, 2010.
- Garcia-Molina, H.; Ullma, J. D; Widom, J. *Implementação de sistemas de banco de dados*. Rio de Janeiro: Campus, 2001.
- Date, C.J. *An introduction to database systems*. Addison-Wesley, 8th edition, 2003. (Tradução: *Introdução a Sistemas de Bancos de Dados*. Editora Campus, 2004).
- Özsu, M.; Valduriez, P. *Princípios de Sistemas de Banco de Dados Distribuídos*. 2a ed. Editora Campus, 2001.
- Bernstein, P. A.; Hadzilacos, V.; Goodman, N. *Concurrency Control and Recovery in Database Systems*. Addison-Wesley, 1987.
