# 🎫 Sistema de Chamados Help Desk

Sistema de gerenciamento de chamados de suporte técnico desenvolvido em **Python**, com armazenamento local em JSON e interface interativa via terminal.

O projeto tem como objetivo simular o funcionamento de um sistema de Help Desk, permitindo registrar solicitações de suporte, definir prioridades e acompanhar os chamados cadastrados.

---

## 📌 Sobre o projeto

O Sistema de Chamados Help Desk é um projeto desenvolvido para praticar conceitos fundamentais de programação e desenvolvimento de sistemas, incluindo:

- Lógica de programação.
- Programação estruturada em Python.
- Modularização de código.
- Manipulação de arquivos JSON.
- Validação de dados.
- Organização de projetos.

A aplicação permite que um usuário registre problemas técnicos e consulte os chamados armazenados.

## ⚙️ Funcionalidades

### Implementadas

- [x] Cadastro de chamados de suporte.
- [x] Identificação do solicitante.
- [x] Descrição do problema.
- [x] Definição de prioridade:
  - Baixa
  - Média
  - Alta
- [x] Validação de campos obrigatórios.
- [x] Geração de identificador para cada chamado.
- [x] Listagem de chamados cadastrados.
- [x] Definição inicial do status como Aberto.
- [x] Armazenamento persistente em arquivo JSON.

### Melhorias planejadas

- [ ] Atualização do status dos chamados.
- [ ] Exclusão de chamados.
- [ ] Pesquisa por ID ou solicitante.
- [ ] Filtros por prioridade e status.
- [ ] Data e horário de abertura.
- [ ] Sistema de autenticação de usuários.
- [ ] Interface gráfica.
- [ ] Banco de dados SQLite ou PostgreSQL.
- [ ] Relatórios e indicadores de atendimento.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| Python 3 | Linguagem principal |
| JSON | Armazenamento de dados |
| Git | Controle de versão |
| GitHub | Hospedagem do código |

**Dependências externas:** atualmente, o projeto utiliza recursos da biblioteca padrão do Python, sem necessidade de instalar pacotes adicionais.

## 📁 Estrutura do projeto

```text
Sistema-de-Chamados-Help-Desk/
│
├── dados/
│   └── chamados.json
│
├── src/
│   ├── main.py
│   ├── chamados.py
│   └── armazenamento.py
│
├── .gitignore
├── LICENSE
└── README.md
```

### Organização dos arquivos

- **main.py:** ponto de entrada da aplicação e menu principal.
- **chamados.py:** contém as funcionalidades relacionadas ao cadastro e à listagem de chamados.
- **armazenamento.py:** responsável pelas operações de armazenamento e recuperação dos dados.
- **chamados.json:** arquivo utilizado para persistir os chamados cadastrados.
- **.gitignore:** define os arquivos que não devem ser enviados ao Git.
- **LICENSE:** licença de utilização do projeto.

## 💻 Instalação e execução

### 1. Pré-requisitos

Antes de começar, você precisa ter:

- Python 3 instalado.
- Git instalado.
- Um terminal ou editor de código, como Visual Studio Code.

### 2. Clonar o repositório

Abra o terminal e execute:

```bash
git clone https://github.com/MiguelDouglassketch/Sistema-de-Chamados-Help-Desk.git
```

### 3. Acessar a pasta

```bash
cd Sistema-de-Chamados-Help-Desk
```

### 4. Executar o sistema

No Windows:

```powershell
py src/main.py
```

No Linux:

```bash
python3 src/main.py
```

Não é necessário instalar dependências adicionais no estágio atual do projeto.

## 🖥️ Demonstração

Ao executar a aplicação, o usuário encontrará um menu interativo semelhante a este:

```text
================================
      SISTEMA DE HELP DESK
================================
1 - Cadastrar chamado
2 - Listar chamados
0 - Sair
================================

Escolha uma opção:
```

Exemplo de cadastro:

```text
===== CADASTRO DE CHAMADO =====

Nome do solicitante: João
Descreva o problema: Computador com defeito

Prioridade (baixa, media ou alta): alta

Chamado cadastrado com sucesso!

Número do chamado: 1
Solicitante: João
Prioridade: Alta
Status: Aberto
```

## 📚 Conhecimentos aplicados

Durante o desenvolvimento deste projeto, foram trabalhados conceitos importantes para a área de desenvolvimento de software e suporte técnico:

- Separação de responsabilidades entre módulos.
- Manipulação de dados estruturados.
- Persistência de informações.
- Tratamento de entradas do usuário.
- Organização e manutenção de código.
- Versionamento utilizando Git e GitHub.

## 🚀 Próximos passos

O objetivo é evoluir gradualmente a aplicação
