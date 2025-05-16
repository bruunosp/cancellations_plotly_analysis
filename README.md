# Python Insights - Análise de Cancelamento de Clientes

Este projeto realiza uma análise visual de dados de cancelamentos de clientes, com o objetivo de identificar padrões e possíveis motivos para os cancelamentos. Através de gráficos interativos gerados com Plotly Express, é possível obter insights valiosos que auxiliam na tomada de decisões estratégicas para reduzir os cancelamentos e melhorar a retenção de clientes.

---

### 📌 Dependências utilizadas

- [Pandas](https://pandas.pydata.org/)
- [Plotly.express](https://plotly.com/python/plotly-express/)

---

### ⚙️ Installation and Setup
Instale as dependências:
```bash
pip install -r requirement.txt
```

---

### ▶️ Running the Project

Existem duas maneiras de rodar o código:
    1. Rodar uma célular de cada vez, evitando que contenha erros 
    2. Rodar tudo de uma vez clicando em "RUN ALL" no topo da tela
    [img](./Docs/run-all-buttom.png)

---

### 📁 Project Structure

``` bash
cancellations_plotly_analysis/
│
├── database/
│   ├── cancellations_examples.csv          # Banco de dados de cancelamento reduzido (mais leve)
│   └── cancellations.csv                   # Banco de dados de cancelamento completo
│
├── docs/
│   ├── Python_Journey_Guide.pdf            # Apostila
│   └── run-all-buttom.png                  # Imagem para guiar como rodar todo código
│
├── scripts/
│   └── cancelation_dashboard.py            # Cancelation graphics and insights script
│
├── template/
│   └── template.py                         # Reference script
│
├── .env.example                            # Vazio
├── .gitignore                              # Vazio
├── README.md                               # Documentação do projeto
└── requirement.txt                         # Lista de dependências para serem instaladas

```

---

### 🙋‍♂️ Author
Projeto criado durante a Jornada Python da [Hashtag Treinamentos](https://portalhashtag.com/). Repositório mantido por Bruno Felipe Passareli.

---

### 🧠 Future Improvements

- Trazer os a base de dados de um banco de dados via API
- Permitir que o usuário escolha o tipo de dados que ele gostaria de analisar
- Permitir que o usuário escolha quais variaveis ele gostaria de analisar
- Permitir que o usuário armazene suas analises como forma de comentário
- Executar o código com orientação a objeto, melhorando a organização
- Visualizar os gráficos em um navegador

---

Sinta-se livre para contribuir ou deixar uma ⭐ se achou útil!