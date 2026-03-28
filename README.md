# bootcamp-II

Este repositório foi criado para a matéria de Bootcamp com o objetivo de apresentar a realização de um projeto social simples a partir das habilidades aprendidas na faculdade. 

---
### 💰 Sistema de Controle de Gastos Pessoais (FinanceControl)

    Status do Projeto: v1.0.0 (Versão Inicial)

### 🎯 1. Visão Geral e Problema Real

Muitas pessoas perdem o controle de suas finanças por não registrarem pequenos gastos diários, o que leva ao endividamento ou à falta de previsibilidade financeira.

O Problema: A complexidade de grandes aplicativos financeiros desestimula o uso frequente.
A Solução: Uma aplicação leve, rápida e com interface CLI (Linha de Comando) que permite registrar despesas em segundos, garantindo que o usuário saiba exatamente para onde seu dinheiro está indo.

Público-alvo: Estudantes e jovens adultos que buscam uma ferramenta minimalista para organização financeira inicial.

### 🚀 2. Funcionalidades Principais


    [x] Registro de despesas com categoria e data.

    [x] Listagem completa de gastos realizados.

    [x] Cálculo automático de saldo total.

    [x] Validação de entradas (impede valores negativos).

### 🛠️ 3. Tecnologias Utilizadas

    Linguagem: Java 17

    Gerenciador de Dependências: Maven

    Persistência de Dados: Arquivo JSON / SQLite (escolha um)

    Testes: JUnit 5

    CI/CD: GitHub Actions

### 📦 4. Como Instalar e Rodar

    Pré-requisitos: Ter o JDK 17 e Maven instalados.

    Clonar o repositório:
    Bash

    git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git

    Compilar o projeto:
    Bash

    mvn clean install

    Executar a aplicação:
    Bash

    mvn exec:java -Dexec.mainClass="com.projeto.Main"

### 🧪 5. Testes e Qualidade

Para garantir a confiabilidade, o projeto conta com testes automatizados e análise estática.

    Rodar Testes: mvn test

    Rodar Lint (Checkstyle): mvn checkstyle:check

Casos de Teste Implementados:

    Caminho Feliz: Adição de gasto e verificação do saldo atualizado.

    Entrada Inválida: Tentativa de inserção de valor negativo (deve disparar exceção).

    Caso Limite: Consulta de saldo em uma lista de despesas vazia.

### 📈 6. Versionamento Semântico

Este projeto segue o padrão SemVer:

    MAJOR: Mudanças incompatíveis.

    MINOR: Novas funcionalidades.

    PATCH: Correção de bugs.
    Versão atual: 1.0.0

👩‍💻 7. Autor

    Nome: Bruna Bonifácio Soares Santos

    Instituição: CEUB

