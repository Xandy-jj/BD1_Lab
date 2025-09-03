# BD1_Lab
Atividades desenvolvidas para o laboratório de banco de dados 1 do Instituto Nacional de Telecomunicações


# Projeto de Academia 🏋️‍♀️

Este projeto idealiza a estrutura de uma academia utilizando MySQL para modelar o banco de dados. Ele explora o básico de entidades e relacionamentos para gerenciar alunos, professores, modalidades e equipamentos.

# 🏢 Entidades

As principais entidades do sistema são:

Aluno 🧑‍🎓

Equipamento 🏋️‍♂️

Modalidade 🏅

Professor 👩‍🏫

Gestor 🧑‍💼

# 🔗 Relacionamentos

A seguir, estão os relacionamentos entre as entidades, definidos conforme o tipo de cardinalidade:

# (N:M) - Muitos para Muitos

  Um aluno pode ter vários professores, e um professor pode ter vários alunos.

  Um aluno pode praticar várias modalidades, e uma modalidade pode ter vários alunos.

# (1:N) - Um para Muitos

  Um gestor pode gerenciar vários professores, mas um professor tem apenas um gestor.

  Uma modalidade pode ter vários equipamentos, mas cada equipamento pertence a uma única modalidade.

# (1:1) - Um para Um

  Um professor pode atuar em apenas uma modalidade, e uma modalidade pode ter apenas um professor.
