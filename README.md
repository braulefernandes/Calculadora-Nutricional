# 🥗 Tabela Nutricional

Este repositório reúne uma **API RESTful** e uma **aplicação de terminal**, ambos desenvolvidos em **Clojure**, para registrar consumo de alimentos e atividades físicas, calcular calorias e consultar informações nutricionais usando APIs externas.

---

## 📂 Estrutura do Projeto

* \`\`
  Gerencia dados de usuários, alimentos, atividades físicas e integra com APIs externas para informações nutricionais e cálculo de gasto calórico.

* \`\`
  Aplicação de terminal para interação prática com a API.

---

## 🚀 Como Executar

1️⃣ **Configurar as chaves de API**
Defina as variáveis de ambiente:

```bash
export USDA_API_KEY="sua_chave_usda_aqui"
export API_NINJAS_KEY="sua_chave_api_ninjas_aqui"
```

2️⃣ **Rodar a API**

```bash
cd tabela-nutricional-api
lein ring server
```

3️⃣ **Rodar a aplicação de terminal**

```bash
cd tabela-nutricional-terminal
lein run
```

Ou gere o JAR:

```bash
lein uberjar
java -jar target/tabela-nutricional-terminal-0.1.0-standalone.jar
```

---

## 🎯 Funcionalidades Principais

* Registrar usuários, alimentos e atividades físicas.
* Consultar informações de alimentos via API externa.
* Calcular calorias consumidas e gasto calórico.
* Gerar extratos de consumo e atividades por período.

> **Exemplos de endpoints:** `/usuarios`, `/alimentos/:query`, `/atividade`, `/consumo`, `/extrato/alimento`.

---

#### Desenvolvido por Cícero Braule ✨
