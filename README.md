# 📦 RevisAuto Backend MVP

**RevisAuto Backend** é uma API RESTful construída com Flask e SQLite para gerenciar manutenções de veículos, focando em troca de óleo e filtros.

---

## 📝 Requisitos

- Python 3.8 ou superior  
- pip  
- Git  

---

## ⚙️ Instalação

```bash
git clone https://github.com/m-jr-dev/revisauto-backend-mvp.git
cd revisauto-backend-mvp
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 🚀 Uso

```bash
export FLASK_APP=app.py        # Windows: set FLASK_APP=app.py
flask run
```

- Acesse a API em: `http://localhost:5000/`
- Documentação OpenAPI (Swagger): `http://localhost:5000/apidocs/`

---

## 🔗 Endpoints Principais

| Método | Rota               | Descrição                |
|--------|--------------------|--------------------------|
| POST   | `/usuarios`        | Criar novo usuário       |
| GET    | `/usuarios`        | Obter lista de usuários  |
| POST   | `/manutencoes`     | Registrar manutenção     |
| GET    | `/manutencoes`     | Obter lista de manutenções |

---

## 🔒 Autenticação

Utilize credenciais administrativas para operações protegidas:

```text
Usuário: admin
Senha: Admin@123
```

