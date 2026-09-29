# 🌍 GeoBot

Bot de Discord desenvolvido em **Python** para servidores de **simulação de países**. Ele funcionava como uma **grande economia**: cada país tinha seu próprio **PIB**, podia **enviar e receber dinheiro**, **comprar e vender** itens e usar o bot para interagir com os outros participantes. Tudo ficava registrado em um **banco de dados**.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Database](https://img.shields.io/badge/[Banco_de_dados]-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

## 📌 Sobre o projeto

O GeoBot foi criado para servidores de simulação de países no Discord, onde cada participante representa uma nação. O bot cuidava da parte de economia e dados, para que os jogadores pudessem focar na simulação.

## ⚙️ Funcionalidades

- 💰 **Economia com PIB por país**: cada nação tem seu próprio saldo e PIB
- 🔄 **Transferências**: enviar e receber dinheiro entre países
- 🛒 **Compra e venda**: mercado com lista de vendas
- 🍞 **Alimentos**: lista de venda de comidas
- 🪖 **Armamento**: lista de venda de armamento (fictício, da simulação)
- 🎲 **Dados**: rolagem de dados para eventos da simulação
- ✉️ **Envio de textos**: mensagens e comunicados pelo bot
- 🗄️ **Banco de dados**: registro persistente de países, saldos e operações

## 🤖 Comandos

| Comando | O que faz |
|---|---|
| `/vender` | [escolhe o produto que pretende vender |
| `/lista` | [Mostra variedades de lista |
| `/pib` | [consultar PIB do seu país ou de outro |


## 🛠️ Tecnologias

- Python
- discord.py
- [SQLite / PostgreSQL / MySQL]
- Git e GitHub

## 🚀 Como rodar

1. Clone o repositório:
```bash
   git clone https://github.com/MatheusRuivo365/GeoBot.git
   cd GeoBot
```
2. Instale as dependências:
```bash
   pip install -r requirements.txt
```
3. Crie um arquivo `.env` na raiz do projeto:
```
   DISCORD_TOKEN=seu_token_aqui
```
4. Execute o bot:
```bash
   python [arquivo_principal].py
```

> ⚠️ Nunca compartilhe o token do seu bot. O arquivo `.env` deve estar no `.gitignore`.

## 📸 Prints

(Vou adicionar as imagens dele funcionando)

## 📚 O que aprendi

- Modelagem e uso de banco de dados em um projeto real
- Regras de negócio: saldo, transferências, compra e venda
- Desenvolvimento de bots com Python e a API do Discord
- Organização de código e versionamento com Git

## 🔮 Próximos passos

- [uma melhoria que você gostaria de fazer]

## 👨‍💻 Autor

**Matheus Ruivo**
[LinkedIn](https://www.linkedin.com/in/matheus-ruivo-9197b4311) | [GitHub](https://github.com/MatheusRuivo365)
