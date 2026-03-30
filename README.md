📊 #Projeto: Análise e Estruturas de Dados — Listas Estáticas e Dinâmicas

📖 Descrição

Este projeto foi desenvolvido como parte da disciplina de Análise e Estruturas de Dados, com o objetivo de implementar e analisar operações fundamentais em:

- Listas estáticas (baseadas em arrays)
- Listas dinâmicas (baseadas em alocação dinâmica de memória)

O desenvolvimento foi realizado em dupla utilizando a prática de engenharia de software conhecida como Pair Programming (Programação em Par), que consiste em dois desenvolvedores trabalhando juntos no mesmo código, promovendo maior qualidade, revisão contínua e troca de conhecimento.

---

🎯 Objetivos

- Implementar estruturas de dados básicas em C
- Comparar listas estáticas vs. dinâmicas
- Exercitar manipulação de memória (malloc, free)
- Desenvolver operações clássicas em listas
- Aplicar boas práticas de desenvolvimento colaborativo com Pair Programming

---

👥 Metodologia: Pair Programming

O projeto foi desenvolvido utilizando a técnica de:

🧑‍💻 Pair Programming

Nesta abordagem:

- Um integrante atua como Driver (quem escreve o código)
- O outro atua como Navigator (quem revisa, sugere melhorias e pensa na lógica)

🔁 Os papéis são alternados ao longo do desenvolvimento.

✔ Benefícios observados:

- Redução de erros
- Melhor organização do código
- Aprendizado mais rápido
- Maior qualidade nas soluções implementadas

---

🧱 Estruturas Implementadas

🔹 Lista Estática

- Implementada com vetor de tamanho fixo
- Alocação feita em tempo de compilação

📌 Características:

- Acesso rápido por índice (O(1))
- Inserções e remoções podem exigir deslocamento de elementos
- Limitação de tamanho

---

🔹 Lista Dinâmica

- Implementada com alocação dinâmica de memória
- Utiliza ponteiros

📌 Características:

- Tamanho flexível
- Inserções e remoções eficientes
- Maior complexidade de implementação

---

⚙️ Operações Implementadas

As seguintes operações foram desenvolvidas para ambas as estruturas:

- Inserção de elementos
- Remoção de elementos
- Busca (sequencial)
- Atualização de valores
- Impressão da lista
- Verificação de lista cheia/vazia (quando aplicável)

---

🗂️ Estrutura do Projeto

📁 projeto-listas/
├── lista_estatica.h
├── lista_estatica.c
├── lista_dinamica.h
├── lista_dinamica.c
├── main.c

---

🧠 Conceitos Trabalhados

- Estruturas de dados lineares
- Alocação dinâmica de memória
- Ponteiros em C
- Complexidade de algoritmos
- Programação colaborativa

---

📈 Análise Comparativa

Critério| Lista Estática| Lista Dinâmica
Tamanho| Fixo| Variável
Alocação| Estática| Dinâmica
Inserção/Remoção| Mais custosa| Mais eficiente
Uso de memória| Pode desperdiçar| Mais otimizada
Complexidade| Menor| Maior

---

🚀 Como Executar

1. Compile os arquivos:

gcc *.c -o listas

2. Execute:

./listas

---

📝 Conclusão

O projeto permitiu compreender na prática as diferenças entre listas estáticas e dinâmicas, além de reforçar conceitos essenciais da linguagem C e da organização de código.

A utilização de Pair Programming contribuiu significativamente para a qualidade do desenvolvimento, promovendo colaboração ativa e melhor entendimento dos conceitos.

---

📌 Observações

- O foco do projeto é educacional
- Código desenvolvido com fins de aprendizado
- Pode ser expandido com outras estruturas (pilhas, filas, listas duplamente encadeadas, etc.)

---

👩‍💻 Autoria

Desenvolvido em dupla com Ana Paula Bernardo como parte da disciplina de Análise e Estruturas de Dados. 
