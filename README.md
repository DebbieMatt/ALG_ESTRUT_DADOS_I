# 📚 Algoritmos e Estrutura de Dados I — em C

<div align="center">

![C](https://img.shields.io/static/v1?label=Linguagem&message=C&color=00599C&style=for-the-badge&logo=c)
![Status](https://img.shields.io/static/v1?label=STATUS&message=EM%20ANDAMENTO&color=green&style=for-the-badge)
![License](https://img.shields.io/static/v1?label=LICENÇA&message=MIT&color=blueviolet&style=for-the-badge)

</div>

> Resolução em **C** dos exercícios e listas da disciplina de **Algoritmos e Estrutura de Dados I**.  
> Os programas cobrem desde fundamentos de ponteiros e alocação de memória até estruturas de dados clássicas como pilhas, filas e listas encadeadas.

## 📋 Índice

1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Conteúdos Abordados](#-conteúdos-abordados)
3. [Estrutura do Repositório](#-estrutura-do-repositório)
4. [Saiba Antes de Executar](#-saiba-antes-de-executar)
5. [Como Compilar e Executar](#-como-compilar-e-executar)
6. [Enunciados](#-enunciados)
7. [Contribuindo](#-contribuindo)
8. [Licença](#-licença)

## 🎯 Sobre o Projeto

Este repositório reúne a resolução dos exercícios desenvolvidos ao longo da disciplina de **Algoritmos e Estrutura de Dados I**. O foco está nos fundamentos da programação em C, abordando desde manipulação de ponteiros e alocação de memória até estruturas de dados lineares e algoritmos de ordenação.

> ⚠️ **Nota:** Como os exercícios fazem parte de um curso introdutório, algumas boas práticas avançadas de engenharia de software foram omitidas intencionalmente, priorizando a clareza dos conceitos fundamentais.

## 🧠 Conteúdos Abordados

| Unidade | Tema |
|---|---|
| 🔵 Unidade 1 | Passagem de Parâmetros, Alocação de Memória e Ponteiros |
| 🟢 Unidade 1 | Aritmética de Ponteiros, Vetores e Matrizes |
| 🟡 Unidade 1 | Manipulação de Ponteiros (void, malloc, calloc) |
| 🟠 Unidade 2 | Typedef, Struct, Union e Enumerador |
| 🔴 Unidade 3 | Manipulação de Arquivos (texto e binário) |
| 🟣 Unidade 4 | Pilha, Fila e Lista (estática e dinâmica) |
| ⚫ Unidade 5 | Algoritmos de Ordenação |

## 📁 Estrutura do Repositório

```
ALG_ESTRUT_DADOS_I/
│
├── PONTEIROS/                              # Unidade 1 — Ponteiros, Vetores e Matrizes
│   ├── UNID.01_ATV_00.c                    # Aposentadoria com ponteiros
│   ├── UNID.01_ATV_01.c                    # Comparação de endereços de memória
│   ├── UNID.01_ATV_02.c                    # CuiaBank — controle de saques
│   ├── UNID.01_ATV_03.c                    # Reajuste salarial por departamento
│   ├── UNID.01_ATV_04.c                    # Troca de vetores com aritmética de ponteiros
│   ├── UNID.01_ATV_05.c                    # Vetor C com maior valor entre A e B
│   ├── UNID.01_ATV_06.c                    # Vetor → Matriz de multiplicação
│   ├── UNID.01_ATV_07.c                    # Produto das diagonais de matriz NxN
│   └── UNID.01_ATV_08.c                    # Ponteiros genéricos (void**)
│
├── UNID. 1 - MEMÓRIA/                      # Alocação Dinâmica
│   ├── UNID.01_ATV_10.c                    # Interruptor com ponteiros de função
│   └── UNID.01_ATV_12.c                    # Vetor dinâmico com malloc/realloc
│
├── UNID. 2 - TIPOS ABSTRATOS DE DADOS/     # Struct, Union, Enum
│   ├── UNID.02_ATV_01.c                    # Sistema de inventário de produtos
│   ├── UNID.02_ATV_02.c                    # Gerenciamento de estacionamento
│   ├── UNID.02_ATV_03.c                    # Sistema de funcionários e departamentos
│   └── UNID.02_ATV_04.c                    # Sensores de automação residencial (union)
│
├── UNID. 3 - MANIPULAÇÃO DE ARQUIVOS/      # Leitura e escrita em arquivos
│   ├── UNID.03_ATV_01.c                    # Memória de estado da lâmpada
│   ├── UNID.03_ATV_02.c                    # Criptografia de mensagens em arquivo
│   └── UNID.03_ATV_03.c                    # Concessionária — registros em arquivo
│
├── UNID.4 - PILHA, FILA E LISTA/           # Estruturas de dados lineares
│   ├── UNID.04_ATV_v01.c                   # Garagem com pilha estática
│   ├── UNID.04_ATV_02.c                    # Playlist com desfazer/refazer (pilha dinâmica)
│   └── UNID.04_ATV_03.c                    # Fila de atendimento — clínica médica
│
└── UNID.5 - ALGORITMO DE ORDENAÇÃO/        # Algoritmos de ordenação
    ├── UNID.05_ATV_01.c                    # Ordenação de strings
    ├── UNID.05_ATV_02.c                    # Cadastro com ordenação múltipla
    ├── UNID.05_ATV_03.c                    # Desempilhamento recursivo com soma
    └── UNID.05_ATV_04.c                    # Quick Sort em ordem decrescente
```

## ⚠️ Saiba Antes de Executar

- Os programas são escritos em **C padrão (C99/C11)** e compilados com **GCC**
- Cada arquivo `.c` é independente — compile e execute individualmente
- Alguns exercícios utilizam **alocação dinâmica de memória** (`malloc`, `calloc`, `realloc`, `free`)
- Exercícios marcados como `(POR FAZER)` ainda estão em desenvolvimento

## ▶️ Como Compilar e Executar

### Pré-requisitos

Certifique-se de ter o GCC instalado:

```bash
gcc --version
```

### Clonando o repositório

```bash
git clone https://github.com/DebbieMatt/ALG_ESTRUT_DADOS_I.git
cd ALG_ESTRUT_DADOS_I
```

### Compilando um arquivo

```bash
# Sintaxe básica
gcc -o saida nome_do_arquivo.c

# Com flags recomendadas (exibe avisos e erros detalhados)
gcc -Wall -Wextra -o saida nome_do_arquivo.c
```

### Executando

```bash
./saida
```

### Exemplo completo

```bash
gcc -o garagem "UNID.4 - PILHA, FILA E LISTA/UNID.04_ATV_v01.c"
./garagem
```

## 📖 Enunciados

<details>
<summary><strong>🔵 Unidade 1 — Passagem de Parâmetros e Ponteiros</strong></summary>

> Tópicos: passagem de parâmetros por referência, conceito de ponteiros, uso de ponteiros em funções.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.01_ATV_00](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_00.c) | Calcula tempo restante para aposentadoria usando ponteiros |
| 02 | [UNID.01_ATV_01](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_01.c) | Compara endereços de memória entre variáveis de tipos distintos |
| 03 | [UNID.01_ATV_02](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_02.c) | CuiaBank — simulação de saque com saldo especial |
| 04 | [UNID.01_ATV_03](https://github.com/DebbieMatt/Alg_II/blob/ec932aefd31a65b0ba1d8d8175260461f53ebbe8/PONTEIROS/UNID.01_ATV_03.c) | Reajuste salarial de funcionários por departamento |

</details>

<details>
<summary><strong>🟢 Unidade 1 — Aritmética de Ponteiros, Vetores e Matrizes</strong></summary>

> Tópicos: operações de adição e subtração com endereços, acesso a vetores e matrizes via ponteiros.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.01_ATV_04](https://github.com/DebbieMatt/Alg_II/blob/2b809813961e2f9929de2947287335964f5f299c/PONTEIROS/UNID.01_ATV_04.c) | Troca de valores entre dois vetores |
| 02 | [UNID.01_ATV_05](https://github.com/DebbieMatt/Alg_II/blob/4aa95ef573439409a5ef5688460644b4e3c27708/PONTEIROS/UNID.01_ATV_05.c) | Vetor C recebe o maior valor entre vetores A e B por posição |
| 03 | [UNID.01_ATV_06](https://github.com/DebbieMatt/Alg_II/blob/312395a5ed3b3fcca30d546a12d83213342a58d2/PONTEIROS/UNID.01_ATV_06.c) | Gera matriz NxN de multiplicação a partir de vetor de entrada |
| 04 | [UNID.01_ATV_07](https://github.com/DebbieMatt/Alg_II/blob/312395a5ed3b3fcca30d546a12d83213342a58d2/PONTEIROS/UNID.01_ATV_07.c) | Produto das diagonais principal e secundária de matriz NxN |

</details>

<details>
<summary><strong>🟡 Unidade 1 — Manipulação de Ponteiros (void, malloc, calloc)</strong></summary>

> Tópicos: ponteiros genéricos, ponteiros para funções, alocação dinâmica de vetores e matrizes.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.01_ATV_08](https://github.com/DebbieMatt/Alg_II/blob/662120258cea1293fead3882e9d2abb8b5e89c20/PONTEIROS/UNID.01_ATV_08.c) | Acesso a variável via ponteiro duplo `void**` |
| 02 | [UNID.01_ATV_10](https://github.com/DebbieMatt/Alg_II/blob/74a9def4a464562218ce6d26168ac7c18d6c84d7/UNID.%201%20-%20MEM%C3%93RIA/UNID.01_ATV_10.c) | Sistema de interruptor de lâmpada com ponteiros de função |
| 03 | *(Por fazer)* | Vetor de ponteiros para funções com chamadas múltiplas |
| 04 | [UNID.01_ATV_12](https://github.com/DebbieMatt/Alg_II/blob/74a9def4a464562218ce6d26168ac7c18d6c84d7/UNID.%201%20-%20MEM%C3%93RIA/UNID.01_ATV_12.c) | Módulo de vetor dinâmico: criar, inserir, imprimir e redimensionar |

</details>

<details>
<summary><strong>🟠 Unidade 2 — Typedef, Struct, Union e Enumerador</strong></summary>

> Tópicos: tipos abstratos de dados, structs aninhadas, union para economia de memória, enum.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.02_ATV_01](https://github.com/DebbieMatt/Alg_II/blob/9d4779da431f9945831471dc56cc3ce42ec98b64/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_01.c) | Sistema de inventário de produtos (CRUD + valor em estoque) |
| 02 | [UNID.02_ATV_02](https://github.com/DebbieMatt/Alg_II/blob/9d4779da431f9945831471dc56cc3ce42ec98b64/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_02.c) | Gerenciamento de estacionamento com tarifa por hora |
| 03 | [UNID.02_ATV_03](https://github.com/DebbieMatt/Alg_II/blob/a2a3745139ee4955b9b6ebbe5a83bfa0a6dd39cf/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_03.c) | Sistema de funcionários e departamentos com structs aninhadas |
| 04 | [UNID.02_ATV_04](https://github.com/DebbieMatt/Alg_II/blob/f8cf03975c4472bcebb5563213f9adeda54399ed/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_04.c) | Sensores de automação residencial com `union` (temperatura, luminosidade, movimento) |

</details>

<details>
<summary><strong>🔴 Unidade 3 — Manipulação de Arquivos em C</strong></summary>

> Tópicos: leitura e escrita em arquivos de texto e binários com `fopen`, `fread`, `fwrite`, `fprintf`.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.03_ATV_01](https://github.com/DebbieMatt/Alg_II/blob/12c720607987006863e6b682e26b65af966aa0fc/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_01.c) | Persiste estado da lâmpada entre execuções do programa |
| 02 | [UNID.03_ATV_02](https://github.com/DebbieMatt/Alg_II/blob/6b412798a3000ba8894a07b6892b81b0144046cf/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_02.c) | Criptografia simples de mensagens em arquivo (deslocamento de caracteres) |
| 03 | [UNID.03_ATV_03](https://github.com/DebbieMatt/Alg_II/blob/8d341680576407f0b03f6fc2f68f6df699aee818/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_03.c) | Cadastro de veículos de concessionária com persistência em arquivo |

</details>

<details>
<summary><strong>🟣 Unidade 4 — Pilha, Fila e Lista</strong></summary>

> **Pilha (LIFO):** último a entrar, primeiro a sair — operações `push` e `pop`  
> **Fila (FIFO):** primeiro a entrar, primeiro a sair — operações `enqueue` e `dequeue`  
> **Lista:** sequência encadeada com inserção, remoção e busca em qualquer posição

| # | Exercício | Implementação | Descrição |
|---|---|---|---|
| 01 | [UNID.04_ATV_v01](https://github.com/DebbieMatt/Alg_II/blob/d4f73dd38d74ead50e76821cc1035421e1368847/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_v01.c) | Pilha estática | Garagem estreita — sistema de remoção de veículos |
| 02 | [UNID.04_ATV_02](https://github.com/DebbieMatt/Alg_II/blob/806a2ae29af77d145c83aef6f3234715554b8e22/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_02.c) | Pilha dinâmica | Playlist com desfazer/refazer inserção de músicas |
| 03 | [UNID.04_ATV_03](https://github.com/DebbieMatt/Alg_II/blob/5aa9185a7790105b8db40095f04649caa0be24a1/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_03.c) | Fila estática | Sistema de atendimento de clínica médica (máx. 10 pacientes) |

</details>

<details>
<summary><strong>⚫ Unidade 5 — Algoritmos de Ordenação</strong></summary>

> Tópicos: Bubble Sort, Insertion Sort, Selection Sort, Quick Sort, Merge Sort e recursividade.

| # | Exercício | Descrição |
|---|---|---|
| 01 | [UNID.05_ATV_01](https://github.com/DebbieMatt/Alg_II/blob/d67cfb45845688e287ed0a09ed284cc204799d49/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_01.c) | Adaptar algoritmo de ordenação para ordenar strings |
| 02 | [UNID.05_ATV_02](https://github.com/DebbieMatt/Alg_II/blob/d67cfb45845688e287ed0a09ed284cc204799d49/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_02.c) | Sistema de cadastro com ordenação por nome, valor e quantidade |
| 03 | [UNID.05_ATV_03](https://github.com/DebbieMatt/Alg_II/blob/3669c8926270cbc26ff73da9d8dd3189d681c671/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_03.c) | Desempilhamento recursivo com soma das chaves |
| 04 | [UNID.05_ATV_04](https://github.com/DebbieMatt/Alg_II/blob/3669c8926270cbc26ff73da9d8dd3189d681c671/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_04.c) | Quick Sort adaptado para ordenação decrescente |

</details>

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um **fork** do repositório
2. Crie um branch: `git checkout -b minha-contribuicao`
3. Faça suas alterações e confirme: `git commit -m 'Descrição da mudança'`
4. Envie para o branch: `git push origin minha-contribuicao`
5. Abra um **Pull Request**

Consulte a documentação do GitHub sobre [como criar um Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## 📝 Licença

Este projeto está sob licença. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

<div align="center">
  Feito com 💙 e muito <code>malloc</code>
</div>
