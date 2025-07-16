# 💰 Sistema Bancário GUI (Java Swing)

Um sistema bancário simples com interface gráfica feito em **Java** usando **Swing**, simulando operações como **criar conta, sacar, depositar e verificar saldo**.

## 📦 Funcionalidades

- ✅ Criar nova conta bancária com nome e saldo inicial  
- 💵 Depositar valor em uma conta existente  
- 💸 Sacar valor (se houver saldo suficiente)  
- 📊 Verificar saldo  
- ❌ Sistema com validações básicas (campos obrigatórios, saldo negativo)

## 🖼️ Interface

Interface gráfica construída com **Java Swing**, com layout simples e intuitivo:

- Campos de entrada (nome, valor)
- Botões de ação: Criar, Depositar, Sacar, Saldo
- Saída de mensagens (JOptionPane)

---

## 📂 Estrutura de Arquivos

```shell
SistemaBancarioGUI/
├── BancoGUI.java         # Classe principal com interface Swing
├── Conta.java            # Classe que representa uma conta bancária
├── Banco.java            # Gerenciador das contas (ArrayList)
├── SistemaBancarioGUI.jar # Arquivo executável (Release)
└── README.md             # Documentação
