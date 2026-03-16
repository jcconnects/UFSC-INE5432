# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a study repository for **INE5432 - Banco de Dados II** (Database Systems II) at UFSC (Universidade Federal de Santa Catarina), 1st semester of 2026, taught by Prof. Renato Fileto.

This is not a software project — it contains course materials, personal study notes, and references. All content is in Brazilian Portuguese.

## Repository Structure

- `informações.md` — Course overview, program, bibliography, and useful links
- `plano_de_ensino.md` — Official course syllabus with schedule, grading formula, and objectives
- `conteudo_p1.md` — Reading references for P1 (chapters from Elmasri & Navathe on storage, indexing, query processing, transactions, and recovery)
- `conteudo_p2.md` — Reading references for P2 (distributed databases chapter)
- `notas_de_aula_p1.md` — Personal class notes for P1 content
- `livro_base_1 - Fundamentals of Database Systems 7ed [2015].pdf` — Main textbook (Elmasri & Navathe, 7th ed.)

## Course Topics

The course covers advanced DBMS internals:
1. **Query Processing** — Storage organization, indexing, query translation and execution algorithms
2. **Query Optimization** — Algebraic equivalence rules, heuristics, cost estimation using catalog statistics
3. **Transaction Processing** — ACID properties, transaction states, scheduling
4. **Failure Recovery** — Buffer management, logging, rollback, recovery techniques
5. **Concurrency Control** — Serializability theory, locking, optimistic methods, deadlock handling
6. **Distributed Databases (BDD)** — Architecture, fragmentation, replication, distributed query processing and transaction management
7. **Embedded SQL** — Static/dynamic SQL, cursors
8. **Advanced Topics** — Non-conventional databases (NoSQL, spatial, temporal, multimedia, semi-structured)

## Grading

`MF = 0.2×L + 0.2×E + 0.2×P1 + 0.2×P2 + 0.2×T`

- **L** — 2 graded readings (submitted on Moodle)
- **E** — 4 graded exercises (submitted on Moodle, one per module)
- **P1** — First individual exam (~8th week)
- **P2** — Second individual exam (~17th week)
- **T** — Group project with presentation (~weeks 13–15)

Approval requires MF ≥ 6 with sufficient attendance.

## Primary Reference

**Elmasri & Navathe, *Fundamentals of Database Systems*, 7th ed. (2017)** is the main textbook. Content files map directly to chapters in this book (Part 7, 8, 9, and Chapter 23).
