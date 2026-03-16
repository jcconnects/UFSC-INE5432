# INE5432 - Banco de Dados II

## Objetivo

Esta disciplina apresenta técnicas implementadas internamente em sistemas de gerenciamento de bancos de dados, incluindo processamento de consultas e controle de transações, além de conceitos e técnicas de bancos de dados distribuídos e não convencionais e uma visão das tendências atuais da pesquisa e das aplicações de bancos de dados. Ao final da disciplina, o aluno deverá ser capaz de entender e avaliar as técnicas utilizadas por sistemas de gerenciamento de bancos de dados, ficando mais capacitado para bem utilizá-los e para acompanhar a evolução dessa tecnologia.

## Programa

### Introdução ao processamento de consultas

- Organização e indexação de dados em memória de massa
- O processo de tradução, otimização e execução de consultas
- Algoritmos para os operadores básicos de consulta

### Otimização algébrica e plano de execução de consultas

- Regras de equivalência algébrica
- Heurísticas e algoritmo de otimização
- Estimativas de distribuição dos valores de dados no catálogo do SGBD

### Introdução ao processamento de transações

- Motivação: controle de concorrência e recuperação dos sistema
- Definição, propriedades e estados de uma transação
- Escalonamentos de operações de sistemas transacionais

### Recuperação de falhas

- Tipos de falhas e gerenciamento de buffer de dados
- Backup e log do sistema
- Escalonamentos recuperáveis, livres de roll-back em cascata e estritos
- Técnicas de recuperação

### Controle de concorrência no processamento de transações

- Teoria da serializabilidade
- Mecanismos otimistas
- Controle de transações baseado em trancas
- Detecção e tratamento de deadlocks

### Banco de dados distribuído (BDD)

- Conceitos e arquiteturas fundamentais de BDD
- Fragmentação e replicação de dados
- Projeto de BDD
- Processamento e otimização de consultas em BDD
- Recuperação de falhas em BDD
- Controle de concorrência no processamento de transações em BDD

### Tópicos em BDs

- SQL embutida (estática e dinâmica) e cursores
- Integração de dados
- Noções de BDs não convencionais
- Introdução à recuperação de informação

## Bibliografia

### Bibliografia Principal

- **[Elmasri, R. and Navathe, S.B. *Fundamentals of database systems*, 7th. edition, Pearson, 2017.](https://moodle.ufsc.br/pluginfile.php/3525432/mod_resource/content/2/Fundamentals%20of%20Database%20Systems%207ed%20%5B2015%5D.pdf)** (Tradução: Sistemas de Banco de Dados, Pearson, 2019.) -- [6a. edição (2011) em português](https://moodle.ufsc.br/pluginfile.php/3606020/mod_resource/content/1/Sistemas%20de%20Banco%20de%20Dados%20navathe%206%C2%AA%20Edicao.pdf)
- **Ramakrishnan, R. and Gehrke, J. *Database management systems*, McGraw-Hill, 3rd edition, 2014.**
- **Wilfried Lemahieu, Seppe vanden Broucke, Bart Baesens. [Principles of Database Management: The Practical Guide to Storing, Managing and Analyzing Big and Small Data](http://www.pdbmbook.com/), Cambridge University Press, 2018.** [GoogleBooks](https://books.google.com.br/books?id=79p8tAEACAAJ&printsec=frontcover#v=onepage&q&f=false), [YouTube Playlist](https://www.youtube.com/watch?v=o36Z_OqC2ac&list=PLdQddgMBv5zHcEN9RrhADq3CBColhY2hl)
- **Edward Sciore. [Database Design and Implementation](https://www.springer.com/gp/book/9783030338350) (2nd edition), 2020, XIII, 458p.** Softcover, ISBN 978-3-030-33835-0 e-Book, ISBN 978-3-030-33836-7. ([link to on-line version](https://link.springer.com/book/10.1007%2F978-3-030-33836-7))
- **SASHA, D.; BONNET, P. Database Tuning: principles, experiments, and troubleshooting techniques. Morgan Kaufman, 2003. ISBN-13: 978-0132052467**

### Bibliografia Complementar

- Korth, H.F. and Silberschatz, A. and Sudarshan, S. *Database System Concepts*, 6th. edition, McGraw-Hill, 2010. (Tradução: Conceitos de Banco de Dados, Makron Books.)
- Mannino, M. Database Design, Application Development and Administration, 6th edition, Chicago Business Press, 2015.
- Date, C.J. *An introduction to database systems*, Addison-Wesley, 8th edition, 2003. (Tradução: Introdução a Sistemas de Bancos de Dados, Editora Campus, 2004)
- Ullman, J.D. and Widom, J. *A first course in database systems*, Prentice-Hall, 1997.
- O'Neil, D. and O'Neil, E. *Database: Principles, Programming Performance*, Morgan Kaufmann, 2001.
- Garcia-Molina, H. and Ullman, J.D. and Widom, J. *Database System Implementation*, Prentice-Hall, 2000.
- Bernstein, P. A.; Hadzilacos, V.; Goodman, N. Concurrency Control and Recovery in Database Systems. Addison-Wesley, 1987.
- **Özsu, M.T. and Valduriez, P. Principles of Distributed Database Systems. Springer New York, 2020. XIX, 845p. 4rd edition (2020)** -- [3rd edition (2011) on-line](http://dx.doi.org/10.1007/978-1-4419-8834-8)
- Bertino, E. and Catania, B. and Zarri, G.P. *Intelligent Database Systems*, Addison-Wesley, 2001.
- Longley, P. A., Goodchild, M., Maguire, D. J., Rhind, D. W. [Geographic Information Systems and Science](http://books.google.com.br/books/about/Geographic_Information_Systems_and_Scien.html?id=-FbVI-2tSuYC&redir_esc=y). 3rd edition, Willey, 2011.
- Bolstad, P. [GIS Fundamentals: A First Text on Geographic Information Systems](http://www.paulbolstad.net/gisbook.html). 4th edition, Eider Press, 2012.
- Rigaux, P. and Scholl, M. and Voisard, A. *Spatial Databases: with application to GIS*, Morgan Kaufmann, 2002.
- Câmara, G. and Casanova, M.A. and Hemerly, A. and Magalhães, G.C. and Medeiros, C. B. *Anatomia de Sistemas de Informação Geográfica*, Depto. de Ciência da Computação da Unicamp, 1996.
- Vaisman, Alejandro and Zimányi, Esteban. [Data Warehouse Systems - Design and Implementation](http://link.springer.com/book/10.1007%2F978-3-642-54655-6). Series: Data-Centric Systems and Applications, XVI, 625 p. Hardcover: ISBN 978-3-642-54654-9, e-Book: ISBN 978-3-642-54655-6, 2014.
- Abiteboul, S. and Buneman, P. and Suciu, D. *Data on the Web: From Relations to Semistructured Data and XML*, Morgan Kaufmann, 2000.
- Fensel, D. and Hendler, J. and Lieberman, H. and Wahlster, W. (editors) *Spinning the Semantic Web*, MIT Press, 2003.
- Wierzbicki, Adam. [Web Content Credibility](https://link.springer.com/book/10.1007%2F978-3-319-77794-8). Springer, 2018, XII, 221p.
- Matteo Lissandrini, Davide Mottin, Themis Palpanas, Yannis Velegrakis. [Data Exploration Using Example-Based Methods](http://www.morganclaypoolpublishers.com/catalog_Orig/product_info.php?products_id=1334). Morgan Clay, 2018, 164 pages.
- Joy Arulraj, Andrew Pavlo. [Non-Volatile Memory Database Management Systems](http://www.morganclaypoolpublishers.com/catalog_Orig/product_info.php?products_id=1360). Paperback ISBN: 9781681734842. eBook ISBN: 9781681734859. Hardcover ISBN: 9781681734866. February 2019, 191 pages.

**Obs.: O curso seguirá principalmente as porções avançadas dos livros de Elmassri/Navathe e Ramakrishnan. Material adicional de leitura será distribuído ao longo do curso.**

## Links

### Materiais de cursos e e-books

- [Principles of Database Systems Playground Environment](https://www.pdbmbook.com/practice)
- [Introduction to Databases](https://cs.stanford.edu/people/widom/DB-mooc.html) (Jennifer Widom, Stanford University)
- [Bancos de Dados Geográficos](http://www.dpi.inpe.br/livros/bdados) (M. Casanova, G. Câmara, C. Davis, L. Vinhas, G. Ribeiro (Editores))
- [GIS Commons: An Introductory Textbook on Geographic Information Systems](http://giscommons.org/)
- [URI online Judge Problems SQL](https://www.urionlinejudge.com.br/judge/en/problems/index/9)

### Busca de artigos e informações técnicas e científicas

- [SQL Magazine](http://www.sqlmagazine.com.br/)
- [BDComp - Biblioteca Digital Brasileira de Computação](http://www.lbd.dcc.ufmg.br/bdbcomp/bdbcomp.jsp)
- [DBLP](https://dblp.uni-trier.de/)
- [CiteSeer - Scientific Digital Library](http://citeseer.ist.psu.edu/)
- [ACM Digital Library](http://portal.acm.org/)
- [ACM SIGMOD - Special Interest Group on Management of Data](http://www.sigmod.org/)
- [IEEE Xplore Digital Library](https://ieeexplore.ieee.org)
- [IEEE Data Engineering Bulletin](https://tc.computer.org/tcde/data-engineering-bulletin/)
- [VLDB - Very Large Data Base Endowment](http://www.vldb.org/)
- [SBBD](https://sol.sbc.org.br/index.php/sbbd/issue/archive)

### SGBDs relacionais

- [Firebird](http://firebird.sourceforge.net/)
- [HSQL](http://hsqldb.org/)
- [MySQL](http://www.mysql.com/products/database/mysql/community_edition.html)
- [PostgreSQL](http://www.postgresql.org/)
- [SimpleDBM](http://www.simpledbm.org/)
- [SQLite](http://www.sqlite.org/)
- [Comparação na Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems)

### Ferramentas para acesso e/ou administração de SGBDs

- [DBeaver](https://dbeaver.jkiss.org/)
- [DbVisualizer](http://www.dbvis.com)
- [iQAL](http://isql.sourceforge.net/)
- [PHPMyAdmin](http://www.phpmyadmin.net/home_page/index.php)
- [SQL Fiddle](http://sqlfiddle.com/)
- [SQLite Database Browser](http://sqlitebrowser.sourceforge.net/)
- [SQuirrel SQL](http://www.squirrelsql.org/)
- [Webyog](http://www.webyog.com/en/)
- [Lista na TechTalk](https://techtalk.gfi.com/top-10-free-database-tools-for-sys-admins)
- [Lista na Wikipedia](https://en.wikipedia.org/wiki/Category:Database_administration_tools)

### Ferramentas CASE para modelagem de bancos de dados

- [Aqua Data Studio](http://www.aquafold.com/)
- [BR-Modelo](http://www.sis4.com/brModelo)
- [DB-Designer](http://fabforce.net/dbdesigner4)
- [EERCASE](https://sites.google.com/a/cin.ufpe.br/eercase/)
- [MySQL Workbench](http://dev.mysql.com/downloads/workbench)
- [Open System Architect](http://www.codebydesign.com/)
- [pgModeler](http://www.pgmodeler.com.br)
- [Resenha de ferramentas](http://www.databaseanswers.org/modelling_tools.htm)
- [Comparação na Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_data_modeling_tools)

## Avaliação

- Leituras (**L - 2 leituras cujos resultados devem ser entregues**)
- Exercícios (**E - 4 exercícios cujos resultados devem ser entregues**)
- Duas provas individuais (**P1 e P2**)
- Trabalho em grupo (**T**)

### Fórmula da Nota

**Nota Disciplina = 0,2 × L + 0,2 × E + 0,2 × P1 + 0,2 × P2 + 0,2 × T**

### Recuperação

Uma prova de recuperação (**PR**), abrangendo todo o conteúdo ministrado na disciplina, será aplicada aos alunos com frequência suficiente e **3,0 <= Nota Disciplina < 5,75**. Nesse caso, a nova nota da disciplina será:

**NotaFinal = (NotaDisciplina + PR) / 2**

Caso contrário: **NotaFinal = NotaDisciplina**

### Aprovação

Será considerado aprovado o aluno com **Nota Final >= 6** e frequência suficiente nas aulas.

## Ressalvas Importantes

- Os alunos devem estar cientes de que esta disciplina exige tempo de dedicação extraclasse de aproximadamente duas horas semanais.
- O Fórum de Notícias da disciplina no Moodle será usado para divulgar informações sobre a disciplina e algumas discussões referentes aos tópicos da mesma.
- Recomenda-se que os alunos apresentem dúvidas sobre conteúdos da disciplina principalmente nas aulas, na medida do possível, visando o melhor rendimento de todos. Porém, se necessário também poderão ser usados video conferências adicionais ou chats em horários acordados, ou, no caso de questões que não requeiram muita interatividade, o próprio fórum de discussão ou mensagem de e-mail encaminhada a r.fileto@ufsc.br.
- Colegas especialistas na área e um estagiário docente poderão auxiliar em algumas aulas, atendimento a dúvidas referentes a tais aulas, preparação de alguns materiais didáticos, exercícios e avaliações.
- As datas exatas das provas (P1 e P2) e apresentações de trabalhos (T) serão marcadas na primeira semana de aula e publicadas no Moodle. As datas limites para entregas de cada atividade de leitura (L) e cada resolução de exercício (E) estarão especificadas junto às respectivas atividades no Moodle. Em caso de qualquer modificação, os alunos serão avisados via Moodle.
- A responsabilidade e o cumprimento de prazos para a execução e entrega das atividades também serão avaliados. O atraso na entrega de resultados poderá resultar em desconto de até 0.5 ponto na nota do respectivo item.

## Atendimento

- Quartas-feiras das 14:00 às 16:00 horas presencialmente na sala INE-517 ou via webconferência na sala virtual https://meet.google.com/vmt-nnth-wsi
- Para atendimento via webconferência recomenda-se agendamento antecipado através de mensagem no Moodle ou e-mail r.fileto@ufsc.br
