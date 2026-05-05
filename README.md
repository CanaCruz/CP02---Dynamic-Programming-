# FIAP — Dynamic Programming — **Checkpoint 2 — Em Grupo**

Trabalho sobre **grafos ponderados** (Beijing, BART/San Francisco Bay, São Paulo), **recursão com memoização** (menor custo), **backtracking** (maior caminho simples), **fatores por horário** (5h–7h ×0,6; 7h–9h ×1,5; 9h–17h ×1; 17h–20h ×2), **análise com `time`/`tracemalloc`** e **mapas Folium** (um por cidade).

O código e a documentação do checkpoint estão na pasta **`Checkpoint_2_em_grupo/`**, com o mesmo nome indicado no enunciado.

## Integrantes

| Nome completo | RA / RM |
|---------------|---------|
| Arthur Canaverde da Cruz | 563029 |
| Murilo Canestri | 564053 |

**Disciplina:** FIAP — Dynamic Programming  
**Checkpoint:** Checkpoint 2 — Grafos, recursão e memoização

## Notebook principal

- [**Checkpoint_2_em_grupo/notebook.ipynb**](Checkpoint_2_em_grupo/notebook.ipynb) — código, Markdown, resultados e visualização Folium.

Na secção **[1]** do notebook, a tabela de identificação deve coincidir com esta.

## Como executar

Requisitos: Python 3.10+ recomendado.

**No Windows**, se `jupyter` não estiver no PATH (ex.: Python da Microsoft Store), usa `python -m`:

```bash
cd Checkpoint_2_em_grupo
python -m pip install -r requirements.txt
python -m notebook notebook.ipynb
```

**Alternativa:** abre o `notebook.ipynb` no **Cursor** / VS Code, escolhe o **kernel Python** e **Run All**.

## Estrutura (repositório)

```
(raiz do repositório GitHub)
├── README.md
├── .gitignore
└── Checkpoint_2_em_grupo/
    ├── notebook.ipynb
    └── requirements.txt
```

A pasta **`.ipynb_checkpoints/`** (se aparecer dentro do projeto) é cópia automática do Jupyter — podes apagá-la; o `.gitignore` evita enviá-la para o GitHub.

## Repositório no GitHub

1. Repositório **público** (a raiz deve conter este `README.md` e a pasta **`Checkpoint_2_em_grupo/`**).
2. Confirma que o link do notebook abre em: `Checkpoint_2_em_grupo/notebook.ipynb`.

---

*Conteúdo educacional / dados aproximados para fins de modelagem.*
