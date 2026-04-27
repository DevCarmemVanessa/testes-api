# 🧪 Testes de API

## Teste 1 — Listagem de usuários

**Endpoint:**  
https://jsonplaceholder.typicode.com/users  

**Método:**  
GET  

---

## 🎯 Cenário
Validar se a API retorna corretamente a lista de usuários  

---

## 📌 Passos
1. Abrir o Postman  
2. Selecionar método GET  
3. Inserir a URL do endpoint  
4. Clicar em "Send"  

---

## ✅ Resultado esperado
A API deve retornar status 200 e uma lista de usuários em formato JSON  

---

## 📊 Resultado obtido
A API retornou status 200 OK e uma lista de usuários com dados estruturados  

---

## 📌 Status
✅ Aprovado

## Teste 2 — Usuário inexistente

**Endpoint:**  
https://jsonplaceholder.typicode.com/users/999  

**Método:**  
GET  

---

## 🎯 Cenário
Validar o comportamento da API ao buscar um usuário inexistente  

---

## 📌 Passos
1. Abrir o Postman  
2. Selecionar método GET  
3. Inserir a URL do endpoint com ID inexistente  
4. Clicar em "Send"  

---

## ❌ Resultado esperado
A API deve retornar status 404 indicando que o recurso não foi encontrado  

---

## 📊 Resultado obtido
A API retornou status 404 Not Found, indicando que o usuário não existe  

---

## 📌 Status
✅ Aprovado
