# Exercícios de Python — Aulas 41 a 62

Coleção de exercícios práticos em Python, organizada por aula. Os programas são interativos e foram pensados para praticar estruturas de decisão, ciclos, funções, listas e uma introdução a *machine learning*.

## Requisitos

- Python 3.10 ou superior recomendado.
- As aulas 41 a 60 utilizam apenas a biblioteca padrão do Python.
- As aulas 61 e 62 requerem bibliotecas adicionais:

```bash
pip install pandas scikit-learn matplotlib
```

## Como executar

No terminal, abra esta pasta e execute o ficheiro pretendido:

```bash
python aula_41.py
```

Substitua `aula_41.py` pelo nome do exercício que pretende executar. Os programas que pedem dados devem ser usados no terminal, respondendo às perguntas apresentadas.

## Conteúdo

| Aula | Ficheiro | Tema |
| --- | --- | --- |
| 41 | `aula_41.py` | Lê notas até receber `-1` e mostra a respetiva classificação. |
| 42 | `aula_42.py` | Valida uma idade e classifica-a por faixa etária. |
| 43 | `aula_43.py` | Simula autenticação por PIN, com um máximo de três tentativas. |
| 44 | `aula_44.py` | Jogo de adivinhação de um número secreto, com cinco tentativas. |
| 45 | `aula_45.py` | Calculadora em menu: adição, subtração, multiplicação e divisão. |
| 46 | `aula_46.py` | Registo de compras, aplicação de descontos e total acumulado. |
| 47 | `aula_47.py` | Conta positivos e zeros, e soma os números positivos introduzidos. |
| 48 | `aula_48.py` | Simulador de semáforo a partir de uma cor introduzida. |
| 49 | `aula_49.py` | Simulação simples de conta bancária: saldo, depósitos e levantamentos. |
| 50 | `aula_50.py` | Declara e chama uma função sem parâmetros. |
| 51 | `aula_51.py` | Função de saudação com parâmetros de nome e curso. |
| 52 | `aula_52.py` | Função que devolve a soma de dois números. |
| 53 | `aula_53.py` | Função que identifica se um número inteiro é par ou ímpar. |
| 54 | `aula_54.py` | Função para classificar uma nota entre 0 e 20. |
| 55 | `aula_55.py` | Criação, acesso, iteração e alteração de uma lista de disciplinas. |
| 56 | `aula_56.py` | Registo e apresentação de cinco produtos numa lista. |
| 57 | `aula_57.py` | Registo de cinco notas, cálculo de soma e média. |
| 58 | `aula_58.py` | Segundo exercício de registo de notas, soma e média. |
| 59 | `aula_59.py` | Pesquisa de um aluno numa lista, sem distinção de maiúsculas/minúsculas. |
| 60 | `aula_60.py` | Contagem de números positivos, negativos e iguais a zero. |
| 61 | `aula_61.py` | Árvore de decisão para classificar computadores por especificações. |
| 62 | `aula_62.py` | Regressão linear para estimar o preço de um computador. |

## Notas sobre machine learning

`aula_61.py` cria uma árvore de decisão com dados incluídos no próprio ficheiro. Além do resultado da classificação, mostra o gráfico da árvore, as regras aprendidas e a importância das características.

`aula_62.py` treina um modelo de regressão linear com dados incluídos no ficheiro e pede RAM, CPU, GPU e idade para estimar o preço de um computador.

## Estrutura

```
.
├── aula_41.py  # Ciclos e classificação de notas
├── ...
├── aula_60.py  # Listas e contagens
├── aula_61.py  # Árvore de decisão
├── aula_62.py  # Regressão linear
└── README.md
```

