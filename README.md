# 🧾 Lista de Produtos em Python

Este é um projeto simples de **controle de lista de compra de produtos**, feito em Python, que permite adicionar, listar, editar, remover e salvar produtos em um arquivo `.json`.

---

## 🚀 Funcionalidades

- ✅ Adicionar novos produtos  
- 📋 Listar todos os produtos salvos  
- 📝 Editar um produto existente  
- ❌ Remover produtos da lista  
- 💾 Salvar os dados manualmente ou automaticamente  
- 🔁 Carregar a lista automaticamente ao iniciar o programa  

---

## 📦 Requisitos

- Python 3 instalado no computador

---

## ▶️ Como usar

1. Clone o repositório ou baixe o arquivo `lista_produtos.py`:

```bash
git clone https://github.com/katgmrs/lista-de-produtos
cd lista-de-produtos
Execute o script no terminal:

bash
Copiar
Editar
python lista_produtos.py
Use o menu interativo para adicionar, listar ou editar produtos:

markdown
Copiar
Editar
Escolha uma opção:
1. Adicionar produto
2. Listar produtos
3. Editar produto
4. Remover produto
5. Salvar lista
6. Sair
🛠️ Tecnologias usadas
Python

JSON (para salvar os dados)

🗃️ Estrutura de dados
Os produtos são armazenados em uma lista de dicionários com as seguintes chaves:

python
Copiar
Editar
{
  "nome": "Arroz",
  "qnt": 2
}
Esses dados são salvos automaticamente no arquivo lista.json.

🌱 Possíveis melhorias
Interface gráfica com Tkinter

Ordenação dos produtos por nome ou quantidade

Exportar para CSV ou Excel

Backup automático

Feito com 💙 por @katgmrs
