# 📋 CadastroCliente

Um sistema simples de **CRUD em memória** (Create, Read, Update, Delete) desenvolvido em **Java 21+**, com interface gráfica utilizando **Swing**.

> Projeto criado originalmente no IntelliJ IDEA, mas finalizado e estruturado utilizando **NetBeans**.

---

## 🖼️ Demonstração da Interface

![Tela do sistema] (/cadastrocliente/img/imgexemplo)
> Interface gráfica do sistema com campos de entrada, botões de ação e tabela para visualização dos dados dos clientes.

---

## 🚀 Funcionalidades

- ✅ Cadastro de clientes
- 🔍 Listagem de clientes em tabela
- ✏️ Edição de dados do cliente
- 🗑️ Remoção de clientes
- 🎨 Interface gráfica com **Swing**, simples e intuitiva

---

## 📂 Estrutura do Projeto

```
CadastroCliente/
├── src/
│   └── br/com/projeto/
│       ├── application/
│       ├── dao/
│       └── domain/
├── img
├── TelaPrincipal.form
├── manifest.mf
├── build.xml
└── README.md
```

- `domain`: contém a classe `Cliente`
- `dao`: camada de acesso aos dados (armazenamento em memória)
- `application`: lógica da aplicação e interface com o usuário

---

## 🛠️ Tecnologias Utilizadas

- 💻 Java 21+
- 🧱 Swing (Java GUI)
- 🛠️ IntelliJ IDEA (estrutura final do projeto)
- 🧪 NetBeans GUI Builder (para criação visual da interface)

---

## ▶️ Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/marcioluca/CadastroCliente
   ```

2. Abra o projeto no IntelliJ IDEA ou NetBeans

3. Compile e execute a classe principal (localizada em `br.com.projeto.application`)

4. A aplicação será iniciada com a interface gráfica carregada.

---

## 📌 Observações

- Este projeto **não utiliza banco de dados** – os dados são mantidos apenas enquanto o sistema está em execução.
- Durante o desenvolvimento deste projeto, foram aplicados diversos conceitos fundamentais da programação orientada a objetos e estruturas de dados.
---

## 📧 Contato

Desenvolvido por **Márcio Lucas**

- GitHub: [@marcioluca](https://github.com/marcioluca) | Linkendin: [@marciolucasdev](https://www.linkedin.com/in/marcio-lucas-dev/)

