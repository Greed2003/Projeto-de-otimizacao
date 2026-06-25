# 🚀 Projeto de Otimização

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-black?style=for-the-badge&logo=flask)
![License](https://img.shields.io/badge/Status-Em%20Desenvolvimento-success?style=for-the-badge)

---

## 🧩 Descrição

Este é um **projeto acadêmico** desenvolvido para a disciplina de **Otimização**.  
A aplicação web permite **resolver problemas de programação linear**, com **função objetivo** e **restrições definidas pelo usuário**, através de uma interface moderna construída com **Flask** e **Bootstrap**.

---

## ⚙️ Funcionalidades

✅ Inserção da **função objetivo**  
✅ Definição das **restrições** (≤ ou ≥)  
✅ Visualização dos **resultados da otimização**  
✅ **Análise de viabilidade** após alterações nas restrições

---

## 🧠 Tecnologias Utilizadas

| Tecnologia                    | Descrição                                           |
| ----------------------------- | --------------------------------------------------- |
| 🐍 **Python 3**               | Linguagem principal do projeto                      |
| 🌐 **Flask**                  | Framework web para criação da aplicação             |
| 🧩 **Jinja2**                 | Template engine para renderização das páginas       |
| 🎨 **HTML / CSS / Bootstrap** | Criação e estilização da interface                  |
| 📊 **SciPy – Linprog**        | Função usada para resolver o problema de otimização |

---

## 🏗️ Estrutura do Projeto

```
Projeto-Otimizacao/
│
├── app/
│   ├── templates/          # Arquivos HTML (interface)
│   ├── utils/              # Funções auxiliares
│   └── routes.py           # Rotas Flask
│
├── config.py               # Configurações globais
├── run.py                  # Arquivo principal da aplicação
├── requirements.txt        # Dependências do projeto
└── README.md
```

---

## 🧪 Como Executar

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/SEU_USUARIO/Projeto-Otimizacao.git
cd Projeto-Otimizacao
```

### 2️⃣ Crie e ative o ambiente virtual

```bash
python -m venv venv
venv\Scripts\activate   # Windows
# ou
source venv/bin/activate  # Linux/Mac
```

### 3️⃣ Instale as dependências

```bash
pip install -r requirements.txt
```

### 4️⃣ Execute a aplicação

```bash
python run.py
```

### 5️⃣ Acesse no navegador

👉 [http://localhost:5000](http://localhost:5000)

---

## 🧭 Exemplo de Uso

> O usuário escolhe o número de variáveis e restrições, define a função objetivo e as condições, e o sistema retorna a solução ótima e a análise de sensibilidade visualmente organizada.

---

## 📸 Interface (Preview)

_(adicione aqui prints da sua tela `form.html` e `result.html` quando quiser mostrar o visual final)_

---
