# Gerenciador de Notas
Este projeto foi desenvolvido como atividade da disciplina de Técnicas de Programação, do curso da FATEC de Registro, durante o 2º semestre da graduação.

Aplicação desktop desenvolvida em **Java**, com interface gráfica baseada em **JOptionPane**, voltada para o gerenciamento de notas de alunos.  
O projeto demonstra conceitos fundamentais de **Programação Orientada a Objetos**, estruturação de classes, controle de fluxo e validação de dados.



##  Funcionalidades

-  Cadastro de aluno
-  Lançamento de até **3 notas** (valores entre 0 e 10)
-  Cálculo automático da média
-  Avaliação de desempenho:
  - Reprovado (média < 6)
  - Aprovado (6 ≤ média ≤ 9)
  - Ótimo Aproveitamento (média > 9)
-  Limpeza e controle das notas
-  Interface gráfica simples com **JOptionPane**



##  Estrutura do Projeto

- **Aluno.java**
  - Armazena nome e lista de notas
  - Realiza o cálculo da média
  - Avalia o desempenho do aluno

- **GerenciadorNotas.java**
  - Classe principal (`main`)
  - Controla o menu e a interação com o usuário
  - Gerencia o fluxo da aplicação



##  Tecnologias Utilizadas

- **Java** — Linguagem principal
- **Java Swing (JOptionPane)** — Interface gráfica
- **Apache Ant** — Automação de build
- **NetBeans** — IDE utilizada no desenvolvimento
