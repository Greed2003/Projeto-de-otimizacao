# Projeto de Otimização Linear

Aplicação web desenvolvida em Python com Flask para resolução de problemas de Programação Linear. O sistema permite montar a função objetivo, inserir restrições, calcular a solução ótima, visualizar o preço sombra e realizar análise de sensibilidade.

## Funcionalidades

- Cadastro da quantidade de variáveis
- Cadastro da quantidade de restrições
- Montagem da função objetivo
- Inserção dos coeficientes das restrições
- Escolha dos operadores das restrições
- Cálculo da solução ótima
- Exibição dos valores das variáveis
- Cálculo do valor da função objetivo
- Cálculo do preço sombra
- Análise de sensibilidade
- Possibilidade de alterar restrições mantendo os dados preenchidos
- Interface web moderna com layout responsivo

## Tecnologias utilizadas

- Python
- Flask
- SciPy
- HTML
- CSS
- JavaScript

## Estrutura do projeto

```text
Projeto-de-otimizacao/
├── app/
│   ├── static/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── js/
│   │       └── particles.js
│   ├── templates/
│   │   ├── form.html
│   │   ├── result.html
│   │   └── post_optimization.html
│   ├── utils/
│   │   ├── __init__.py
│   │   ├── form_utils.py
│   │   ├── post_optimization_utils.py
│   │   └── shadow_price_process.py
│   ├── __init__.py
│   └── routes.py
├── .gitignore
├── config.py
├── README.md
├── requirements.txt
└── run.py