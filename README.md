<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=180&section=header&text=Ticketinho&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=6366F1&size=30&center=true&vCenter=true&width=1000&lines=Sistema+de+Gestão+de+Chamados;Estruturas+de+Dados+na+Prática)](https://git.io/typing-svg)

</div>

---

<div align="center">

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Java-Swing-blue?style=for-the-badge)
![Desktop](https://img.shields.io/badge/Desktop-Application-green?style=for-the-badge)
![Data Structures](https://img.shields.io/badge/Data-Structures-purple?style=for-the-badge)
![BST](https://img.shields.io/badge/BST-Search_Tree-red?style=for-the-badge)

</div>

<br>

<div align="center">

### 🎓 Universidade São Judas Tadeu

**Estrutura de Dados e Análise de Algoritmos**

📅 2026

👨‍🏫 **Professor: Nicolas Kassalias**

</div>

# 👥 Nossa Equipe

<div align="center">

<table>
  <tr>
    <td align="center" width="14%">
      <a href="https://github.com/atr3ssa">
        <img src="https://avatars.githubusercontent.com/u/162994271?s=400&u=b6be7807d4f38c164926fbeb108a7e29ad502503&v=4" width="100px;" alt="Andressa"/><br>
        <sub><b>Andressa Rabêlo</b></sub>
      </a><br>
      <sub>RA: 823213904</sub>
    </td>
    <td align="center" width="14%">
      <a href="https://github.com/Julia-Olive">
        <img src="https://i.imgur.com/hrQ4GAz.jpeg" width="100px;" alt="Júlia"/><br>
        <sub><b>Júlia Oliveira</b></sub>
      </a><br>
      <sub>RA: 823214680</sub>
    </td>
    <td align="center" width="14%">
      <a href="https://github.com/Marzocca99">
        <img src="https://i.imgur.com/lYWliFF.jpeg" width="100px;" alt="Lucas"/><br>
        <sub><b>Lucas Marzocca</b></sub>
      </a><br>
      <sub>RA: 823116813</sub>
    </td>
    <td align="center" width="14%">
      <a href="https://github.com/Elmarquitoos">
        <img src="https://i.imgur.com/RcjtqUi.jpeg" width="100px;" alt="Marcos"/><br>
        <sub><b>Marcos V. Santos</b></sub>
      </a><br>
      <sub>RA: 82327399</sub>
    </td>
    <td align="center" width="14%">
      <a href="https://github.com/matheushfg">
        <img src="https://i.imgur.com/YBAtoF4.jpeg" width="100px;" alt="Matheus"/><br>
        <sub><b>Matheus H. F.</b></sub>
      </a><br>
      <sub>RA: 823141914</sub>
    </td>
    <td align="center" width="14%">
      <a href="https://github.com/b3ery">
        <img src="https://i.imgur.com/B7MrE2M.png" width="100px;" alt="Mylena"/><br>
        <sub><b>Mylena Soares</b></sub>
      </a><br>
      <sub>RA: 824144075</sub>
    </td>
  </tr>
</table>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br>
---

# 🎯 Sobre o Projeto

O **Ticketinho** é um sistema desktop de gerenciamento de chamados de suporte técnico desenvolvido em Java.

O projeto foi criado com o objetivo de aplicar, de forma prática, os conceitos estudados na disciplina de **Estrutura de Dados e Análise de Algoritmos**, utilizando implementações próprias de estruturas clássicas sem recorrer ao Java Collections Framework.

Além do gerenciamento completo do ciclo de vida dos chamados, o sistema demonstra como diferentes estruturas de dados podem coexistir dentro de uma aplicação real.

## ✨ Principais Recursos

- 🎫 Abertura de chamados
- 👨‍💻 Atendimento técnico
- ✅ Resolução de chamados
- ❌ Cancelamento de chamados
- 📜 Histórico completo
- 🔎 Busca rápida por ID
- 📊 Dashboard com indicadores
- 👥 Cadastro de usuários
- 💻 Cadastro de equipamentos
- 🏢 Cadastro de setores
- 🌙 Tema escuro
- ☀️ Tema claro

---

# 🏗️ Arquitetura do Sistema

```text
src/
└── com/suporte/
    ├── model/
    ├── estruturas/
    ├── service/
    └── ui/
```

## 📦 Camada Model

Responsável pelas entidades de domínio:

- Chamado
- Usuário
- Equipamento
- Setor
- Prioridade
- Status

## ⚙️ Camada Estruturas

Implementações manuais das estruturas de dados:

- ListaLigada<T>
- FilaChamados
- PilhaHistorico
- ArvoreBinariaChamados

## 🔧 Camada Service

Centraliza toda a lógica de negócio.

Principais operações:

- abrirChamado()
- atenderProximoChamado()
- resolverChamado()
- cancelarChamado()
- buscarChamadoPorId()
- buscarChamadoPorTitulo()

## 🖥️ Camada UI

Interface gráfica construída em Java Swing.

Painéis:

- Dashboard
- Chamados
- Histórico
- Cadastros
- Busca

---

# 🧠 Estruturas de Dados Utilizadas

O diferencial do projeto está na implementação manual das estruturas estudadas em sala.

| Estrutura | Implementação | Utilização |
|------------|------------|------------|
| Lista Ligada | ListaLigada<T> | Repositório geral |
| Fila FIFO | FilaChamados | Ordem de atendimento |
| Pilha LIFO | PilhaHistorico | Histórico |
| BST | ArvoreBinariaChamados | Busca por ID |

---

# 📈 Complexidade das Operações

| Operação | Estrutura | Complexidade |
|-----------|------------|-------------|
| Buscar por ID | BST | O(log n) |
| Buscar por assunto | Lista Ligada | O(n) |
| Inserção em fila | Fila | O(1) |
| Remoção da fila | Fila | O(1) |
| Empilhar histórico | Pilha | O(1) |
| Desempilhar histórico | Pilha | O(1) |

---

# 🔄 Fluxo de Funcionamento
```text
Novo Chamado
      │
      ▼
Fila de Atendimento
      │
      ▼
Em Atendimento
   ├──────────► Resolvido
   │                 │
   │                 ▼
   └──────────► Histórico
                     ▲
                     │
             Cancelado
```

### 1️⃣ Abertura

O chamado é criado e inserido em:

- Lista Ligada
- Fila
- BST

### 2️⃣ Atendimento

O primeiro chamado da fila é removido e passa para:

**EM_ATENDIMENTO**

### 3️⃣ Encerramento

O chamado é:

- Resolvido
ou
- Cancelado

E posteriormente enviado para a pilha de histórico.

---

# 📊 Dashboard

O sistema possui um painel de indicadores contendo:

- Chamados abertos
- Chamados em atendimento
- Chamados encerrados
- Chamados críticos

Além disso são exibidas tabelas resumidas de acompanhamento operacional.

---

# 🔍 Sistema de Busca

## Busca por ID

Utiliza:

```text
Árvore Binária de Busca (BST)
```

Complexidade média:

```text
O(log n)
```

## Busca por Assunto

Utiliza:

```text
Lista Ligada
```

Complexidade:

```text
O(n)
```

---

# 🎨 Interface

O Ticketinho possui uma interface moderna construída com Java Swing.

### Recursos visuais

- Sidebar de navegação
- Dashboard dinâmico
- Tabelas interativas
- Componentes customizados
- Tema claro
- Tema escuro

---

# 💻 Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| Java 21 | Linguagem principal |
| Java Swing | Interface gráfica |
| Java2D | Componentes customizados |
| LocalDateTime | Datas e horários |

### Dependências

✅ Nenhuma dependência externa

Todas as estruturas e componentes foram implementados manualmente.

---

# 🚀 Como Executar

## Pré-requisitos

- Java 17+
- JAVA_HOME configurado

---

## Executar via JAR

```bash
java -jar Ticketinho.jar
```

---

## Linux / macOS

```bash
bash run.sh
```

---

## Windows

```powershell
.\run.sh
```

---

## Compilar Manualmente

```bash
mkdir -p out

find src -name "*.java" > sources.txt

javac --release 17 -d out @sources.txt

echo "Main-Class: com.suporte.Main" > MANIFEST.MF

jar cfm Ticketinho.jar MANIFEST.MF -C out .

java -jar Ticketinho.jar
```

---


# 📚 Referências

- Cormen et al. — Introduction to Algorithms
- Sedgewick & Wayne — Algorithms
- Goodrich, Tamassia & Goldwasser — Data Structures and Algorithms in Java
- Deitel & Deitel — Java: Como Programar

---

# 🎓 Objetivo Acadêmico

Este projeto demonstra como estruturas de dados fundamentais podem ser utilizadas para resolver problemas reais de software.

A aplicação integra Lista Ligada, Fila, Pilha e Árvore Binária de Busca em um fluxo completo de atendimento técnico, permitindo visualizar na prática as vantagens e características de cada estrutura.

---

<div align="center">

⭐ Projeto desenvolvido para a disciplina de Estrutura de Dados e Análise de Algoritmos

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=120&section=footer"/>

</div>
