# RevisAuto - Back-end (API Flask)

Este é o back-end do MVP de um sistema web desenvolvido com Python + Flask. O sistema permite cadastrar, buscar, listar e deletar usuários utilizando API RESTful com documentação via Swagger. Utiliza banco de dados SQLite.

## 🚀 Tecnologias utilizadas

- Python 3.10+
- Flask
- Flask-SQLAlchemy
- Flask-Cors
- SQLite
- Swagger (OpenAPI via flasgger)

## 📦 Instalação e execução

### 1. Clone o repositório

```bash
git clone https://github.com/m-jr-dev/revisauto-backend-mvp.git
cd backend-mvp
```

### 2. Crie um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute a aplicação

```bash
python app.py
```

A API estará disponível em: `http://localhost:5000`

### 5. Acesse a documentação Swagger

Abra no navegador:

```
http://localhost:5000/apidocs/
```

---

## 🧪 Rotas disponíveis

- `POST /cadastrar_usuario`
- `GET /buscar_usuario/<id>`
- `GET /buscar_usuarios`
- `DELETE /deletar_usuario/<id>`

---

## 📁 Estrutura de arquivos

```
backend/
├── app.py
├── models.py
├── database.db
├── requirements.txt
└── README.md
```
