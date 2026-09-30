# ⭐ Star Schema - Foco no Professor

![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-blue)
![DIO Project](https://img.shields.io/badge/DIO-Project-purple)
![Tool](https://img.shields.io/badge/Tool-dbdiagram.io-orange)

Projeto da DIO - Modelagem Dimensional com foco na análise dos professores.

### 📊 Diagrama em Estrela

<img width="780" height="479" alt="diagramaestrela" src="https://github.com/user-attachments/assets/034fcfba-e383-485f-9c77-a984092fbbb3" />

### 🧠 Estrutura do Modelo
- **Tabela Fato Central:** `FATO_PROFESSOR`
    - idProfessor, idDepartamento, idDisciplina, idCurso, idTempo
    - qtd_disciplinas (medida)

- **5 Dimensões em volta:**
    - DIM_PROFESSOR, DIM_DEPARTAMENTO, DIM_DISCIPLINA, DIM_CURSO, DIM_TEMPO

A dimensão DIM_TEMPO foi criada por mim com data_oferta, semestre e ano para analisar a oferta ao longo do tempo.

### 🎯 Foco
Esse modelo NÃO inclui dados de alunos. O foco é 100% na análise dos professores.


### 💻 Linguagem DBML utilizada
<img width="1022" height="568" alt="codigo" src="https://github.com/user-attachments/assets/aeee3503-ca0f-40f4-ad0f-a96f7864b97c" />




Feito por Melisa Machado 💙 para DIO
