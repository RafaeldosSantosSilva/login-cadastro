readme_content = """# 🔐 Sistema de Login e Cadastro com Supabase

Este projeto é uma aplicação simples de Login e Cadastro de Usuários desenvolvida utilizando HTML, CSS e JavaScript puro, integrada ao Supabase como banco de dados.

O sistema permite:
- Cadastro de novos usuários
- Login de usuários cadastrados
- Validação de usuário existente
- Exibição de mensagens de sucesso e erro
- Interface simples e responsiva

---

# 🚀 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript** (Vanilla JS)
- **Supabase** (Backend as a Service)

---

# 📁 Estrutura do Projeto

```bash
📦 projeto-login
├── index.html       # Tela de Login
├── cadastro.html    # Tela de Cadastro
├── css
│   └── style.css    # Estilização Global
└── js
    ├── script.js    # Lógica de Login e Conexão Supabase
    └── cadastro.js  # Lógica de Cadastro de Usuários

---

# 📄 Funcionalidades

### ✅ Tela de Login
A tela principal permite que o usuário realize o acesso ao sistema.
* **Inputs**: Usuário e Senha.
* **Lógica**: Busca de dados no Supabase e validação de credenciais.
* **Feedback**: Mensagens visuais de sucesso ou erro.

### ✅ Tela de Cadastro
Permite o registro de novos usuários na base de dados.
* **Validação**: Verifica se o usuário já existe antes de inserir.
* **Automação**: Limpeza de formulário após o sucesso no registro.

---

# 🗄️ Banco de Dados

O projeto utiliza o **Supabase** para persistência de dados.

### Estrutura da Tabela `users`:

| Campo | Tipo | Descrição |
| :--- | :--- | :--- |
| `id` | `int8` | Chave primária (auto-incremento) |
| `username` | `text` | Nome de usuário único |
| `password` | `text` | Senha do usuário |

## ⚠️ Aviso Importante

Este projeto foi desenvolvido para fins de estudo.

⚠️ As senhas estão sendo armazenadas como texto plano, o que não é recomendado para aplicações em produção.

## 👨‍💻 Autor

- **Rafael Santos** - Estudante de Engenharia de Software