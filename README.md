# 🧪 Testes de API - Swagger UserStore

&gt; Collection do Postman para testes de API na Swagger UserStore (PetStore). Inclui testes de contrato, funcionais e Data-Driven Testing (DDT).

---

## 📋 O que esse projeto faz

Testa o CRUD completo de usuários na API pública da Swagger:

| Operação | Endpoint | Descrição |
|----------|----------|-----------|
| POST | `/user` | Cria novo usuário |
| GET | `/user/{username}` | Consulta usuário por nome |
| PUT | `/user/{username}` | Atualiza usuário |
| DELETE | `/user/{username}` | Remove usuário |
| GET | `/user/login` | Login no sistema |
| GET | `/user/logout` | Logout do sistema |
| POST | `/user/createWithArray` | Cria múltiplos usuários |

---

## 🚀 Como usar

### Pré-requisitos
- Postman instalado
- Conexão com internet (API é online)

### Importar no Postman
1. Abra o Postman
2. Clique em **Import** → **Upload Files**
3. Selecione o arquivo `Swagger UserStore.postman_collection.json`
4. A collection será importada com todos os endpoints e testes

### Rodar os testes
1. Selecione a collection importada
2. Clique em **Run** (Collection Runner)
3. Para DDT: selecione o arquivo de dados (CSV/JSON) antes de executar

---

## 🏗️ Estrutura da Collection
