# 📚 Algoritmos e Estrutura de Dados I — em C

<div align="center">

![C](https://img.shields.io/static/v1?label=Linguagem&message=C&color=00599C&style=for-the-badge&logo=c)
![Status](https://img.shields.io/static/v1?label=STATUS&message=EM%20ANDAMENTO&color=green&style=for-the-badge)

</div>

> Resolução em **C** dos exercícios e atividades da disciplina de **Algoritmos e Estrutura de Dados I**, organizados por aula.

## 📋 Índice

1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Estrutura do Repositório](#-estrutura-do-repositório)
3. [Como Compilar e Executar](#-como-compilar-e-executar)
4. [Conteúdo por Aula](#-conteúdo-por-aula)
5. [Avaliações e Provas](#-avaliações-e-provas)
6. [Diversos](#-diversos)
7. [Autora](#-autora)

## 🎯 Sobre o Projeto

Este repositório reúne os exercícios resolvidos ao longo da disciplina de Algoritmos e Estrutura de Dados I. Os programas cobrem desde operações aritméticas básicas e estruturas condicionais até estruturas de repetição, vetores e outros tópicos fundamentais da linguagem C.

> ⚠️ **Nota:** Por se tratar de um curso introdutório, o objetivo principal é o aprendizado dos fundamentos — boas práticas avançadas foram deixadas em segundo plano intencionalmente.

## 📁 Estrutura do Repositório

```
ALG_ESTRUT_DADOS_I/
│
├── AULA 01/            # Tipos de dados e variáveis
├── AULA 02/
├── AULA 03/
├── AULA 04/
├── AULA 05/
├── AULA 06/
├── AULA 07/
├── AULA 08/
├── AULA 09/
├── AULA 10/
├── AULA 11/
├── AULA 12/
├── AULA 13/
├── AULA 14/
├── AULA 15/
├── AULA 16/
├── AULA 17/
│
├── AVALIAÇÃO 01/
├── AVALIAÇÃO 02/
├── AVALIAÇÃO 03/
├── AVALIAÇÃO 04/
├── AVALIAÇÃO 05/
│
├── PROVA 01/
├── PROVA 02/
│
├── __QUEST EXTRA__/
└── DIVERSOS/           # Exercícios complementares e extras
```

## ▶️ Como Compilar e Executar

### Pré-requisitos

```bash
gcc --version
```

### Clonar o repositório

```bash
git clone https://github.com/DebbieMatt/ALG_ESTRUT_DADOS_I.git
cd ALG_ESTRUT_DADOS_I
```

### Compilar e executar

```bash
gcc -Wall -o saida nome_do_arquivo.c
./saida
```

## 📖 Conteúdo por Aula

<details>
<summary><strong>📘 Aula 1 — Tipos de Dados e Variáveis</strong></summary>

> Introdução à linguagem C: declaração de variáveis, tipos primitivos (`int`, `float`, `char`, `double`) e entrada/saída com `scanf` e `printf`.

| # | Descrição |
|---|---|
| Atv 2 - 01 | Calcula o **IMC** de uma pessoa a partir do peso e altura |
| Atv 2 - 02 | Lê o valor de um produto e aplica **5% de desconto**, exibindo o valor final |
| Atv 2 - 03 | Calcula e imprime a **área de um trapézio** |
| Atv 2 - 04 | Recebe dois números e imprime **qual é o maior** usando `if/else` |

</details>

<details>
<summary><strong>📘 Aula 2 — Operadores e Conversão de Datas</strong></summary>

> Operadores aritméticos, relacionais e lógicos. Operações com tempo e datas.

| # | Descrição |
|---|---|
| Atv 2 - 01 | Recebe a idade em **anos, meses e dias** e converte tudo para **dias** |
| Atv 2 - 02 | Recebe a idade em **dias** e converte para **anos, meses e dias** |
| Atv 3 - 03 | Lê o custo de produção de um caminhão e calcula o **preço final**, considerando 45% de lucro e 20% de impostos |

</details>

<details>
<summary><strong>📘 Aula 3 — Estrutura Condicional switch/case e Pagamentos</strong></summary>

> Estruturas condicionais com `switch/case`, operador módulo e lógica de desconto.

| # | Descrição |
|---|---|
| Atv 5 - 04 | Lê 3 inteiros, soma os **2 maiores** e retorna o dobro se par, ou o valor original se ímpar |
| Atv 5 - 05 | Simula uma **venda em posto de combustível** — álcool R$4,50 / gasolina R$5,10 / diesel R$5,25 |
| Atv 6 - 06 | Calcula o valor de uma **peça de vestuário** com desconto por forma de pagamento: Pix (-10%), Débito (-5%), Crédito à vista (-2%), Parcelado (sem desconto) |

</details>

<details>
<summary><strong>📘 Aula 4 — Constantes em C</strong></summary>

> Uso de `#define` e `const` para declaração de constantes.

> 🚧 Conteúdo em desenvolvimento.

</details>

<details>
<summary><strong>📘 Aula 5 — if/else e Média Ponderada</strong></summary>

> Aprofundamento em estruturas condicionais e cálculos com pesos dinâmicos.

| # | Descrição |
|---|---|
| Atv 1 - 01 | Calcula o **IMC** de uma pessoa usando `if/else` |
| Atv 1 - 02 | Calcula a **média ponderada** de 3 números com pesos automáticos: **5.5** para pares e **4.5** para ímpares |

</details>

<details>
<summary><strong>📘 Aula 6 — Estruturas Condicionais</strong></summary>

> Uso avançado de `switch/case` com múltiplos casos e `default`.

| # | Descrição |
|---|---|
| Atv 1 - 01 | **Verificador de Vogal ou Consoante** — identifica se a letra digitada é vogal ou consoante |
| Atv 1 - 02 | **Identificador de Mês** — lê um número (1–12) e exibe o nome do mês correspondente |
| Atv 1 - 03 | **Lanchonete "Chapa Quente"** — lê o código do produto (200–205) e a quantidade, calculando o custo total |
| Atv 1 - 04 | **Pulverização Agrícola** *(incompleta / bug matemático)* — calcula custo de serviço com descontos progressivos por área |

</details>

<details>
<summary><strong>📘 Aula 7 — Estrutura while (enquanto)</strong></summary>

> 🚧 Conteúdo em desenvolvimento.

</details>

<details>
<summary><strong>📘 Aulas 8 a 17 — Tópicos Avançados</strong></summary>

> 🚧 Descrições em desenvolvimento. Os arquivos já estão disponíveis nas respectivas pastas do repositório.

| Aula | Pasta |
|---|---|
| Aula 8  | `AULA 08/` |
| Aula 9  | `AULA 09/` |
| Aula 10 | `AULA 10/` |
| Aula 11 | `AULA 11/` |
| Aula 12 | `AULA 12/` |
| Aula 13 | `AULA 13/` |
| Aula 14 | `AULA 14/` |
| Aula 15 | `AULA 15/` |
| Aula 16 | `AULA 16/` |
| Aula 17 | `AULA 17/` |

</details>

## 📝 Avaliações e Provas

<details>
<summary><strong>📋 Avaliações</strong></summary>

| Pasta | Descrição |
|---|---|
| `AVALIAÇÃO 01/` | Primeira avaliação da disciplina |
| `AVALIAÇÃO 02/` | Questionário avaliativo corrigido |
| `AVALIAÇÃO 03/` | Quest 01 |
| `AVALIAÇÃO 04/` | Atualização de exercícios avaliativos |
| `AVALIAÇÃO 05/` | Quest 02 *(em C++)* |

</details>

<details>
<summary><strong>📋 Provas</strong></summary>

| Pasta | Descrição |
|---|---|
| `PROVA 01/` | Resolução corrigida da Prova 01 |
| `PROVA 02/` | Resolução atualizada da Prova 02 |
| `__QUEST EXTRA__/` | Questões extras da disciplina |

</details>

## 🗂️ Diversos

A pasta `DIVERSOS/` contém exercícios complementares e experimentos fora do escopo das aulas regulares, incluindo implementações alternativas como a **Média Ponderada** (`Media_Ponde2.c`).

## 👩‍💻 Autora

**Debbie Matt**

[![GitHub](https://img.shields.io/badge/GitHub-DebbieMatt-181717?style=flat&logo=github&logoColor=white)](https://github.com/DebbieMatt)

<div align="center">
  Feito com 💙 e muito <code>printf</code>
</div>
