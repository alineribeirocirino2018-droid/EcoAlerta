# 🌱 EcoAlerta

### Sistema de gerenciamento de ocorrências ambientais

O **EcoAlerta** é um sistema desenvolvido como projeto acadêmico da disciplina de Projeto de Desenvolvimento de Sistemas II, do curso de Sistemas de Informação da Universidade Paulista (UNIP).

Registros de desmatamento, queimadas e descarte irregular podem ficar espalhados em mensagens, planilhas e pastas. O EcoAlerta reúne essas ocorrências e suas evidências em uma aplicação desktop, facilitando o acompanhamento e o controle de acesso.

## 🎯 Objetivo do projeto

Desenvolver uma aplicação desktop que permita cadastrar, consultar e gerenciar ocorrências ambientais de maneira organizada, oferecendo recursos para diferentes níveis de acesso e controle das informações.

## ⚙️ Funcionalidades

- **Login:** autenticação de usuários no sistema.
- **Recuperação de senha:** redefinição de senha com código temporário exibido na tela para demonstração.
- **Gerenciamento de usuários:** cadastro de usuários com perfis de Técnico e Coordenador.
- **Cadastro de ocorrências:** registro de ocorrências ambientais, como desmatamento, queimadas e descarte irregular de lixo.
- **Consulta e gerenciamento:** pesquisa, filtragem, edição e exclusão de ocorrências conforme as permissões de acesso.
- **Evidências:** inclusão e visualização de arquivos de imagem relacionados às ocorrências.
- **Integridade das evidências:** recursos de verificação da integridade dos arquivos.
- **Histórico de atividades:** registro das ações realizadas no sistema.
- **Importação e exportação:** recursos para transferência de dados entre instalações do sistema.

## 💻 Tecnologias utilizadas

- Python 3.10 ou superior.
- Tkinter – construção da interface gráfica.
- Pillow – processamento de imagens.
- Cryptography – criptografia Fernet para evidências.
- SQLite em memória e JSON para salvar os registros localmente.

## 📂 Estrutura do projeto

```text
EcoAlerta/
│
├── ecoalerta.py
├── requirements.txt
└── README.md
```

## 🚀 Instalação e execução

### 1. Pré-requisitos

- Python 3.10 ou superior, com Tkinter.
- Git (opcional, para clonar o repositório).

### 2. Clonar o repositório

```bash
git clone https://github.com/alineribeirocirino2018-droid/EcoAlerta.git
```

### 3. Acessar a pasta do projeto

```bash
cd EcoAlerta
```

### 4. Instalar as dependências

```bash
python -m pip install -r requirements.txt
```

### 5. Executar o sistema

```bash
python ecoalerta.py
```

## 🖥️ Telas do sistema

As capturas abaixo mostram a interface do EcoAlerta na versão demonstrativa.

<img width="1317" height="892" alt="Tela do EcoAlerta" src="https://github.com/user-attachments/assets/8c185df8-ef6d-4c01-aae2-e3f1862a0bdf" />
<img width="1316" height="887" alt="Tela do EcoAlerta" src="https://github.com/user-attachments/assets/9f4d3725-a659-4fcb-ad93-eb9590cd41d0" />


## Contas demonstrativas

| Perfil | E-mail | Senha de demonstração |
| --- | --- | --- |
| Coordenador | `coordenador@ecoalerta.local` | `EcoAlerta@123` |
| Técnico | `tecnico@ecoalerta.local` | `Tecnico@123` |

## Dados locais

Na primeira execução, o programa gera os dados de exemplo na pasta `ecoalerta_dados`. Cada computador guarda seus próprios registros. O coordenador pode transferir os exemplos pelo botão **Importar / Exportar**. Compartilhe o ZIP em privado, pois ele pode incluir evidências e a chave de criptografia.

## 👥 Integrantes do grupo

Projeto desenvolvido coletivamente pelos alunos:

- Alexandry Ravara Vanin
- Aline Ribeiro Cirino
- Gustavo Santana Cardoso
- Ivan Mendes
- Larissa Barbosa da Silva

## 🎓 Instituição de ensino

**Universidade Paulista – UNIP**

**Curso:** Sistemas de Informação

**Disciplina:** Projeto de Desenvolvimento de Sistemas II

**Professor:** Marcus Leite

---

*Projeto acadêmico desenvolvido com o objetivo de aplicar conhecimentos de programação Python e desenvolvimento de interfaces gráficas com Tkinter.*
