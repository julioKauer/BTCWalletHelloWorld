# BTC Wallet Hello World

## 🇧🇷 Português Brasileiro

### Sobre o Projeto

Este é um projeto educacional que demonstra como criar uma carteira Bitcoin (BTC) do zero utilizando JavaScript. O projeto implementa a geração de carteiras HD (Hierarchical Deterministic) seguindo o padrão BIP-32 e BIP-39, gerando um endereço Bitcoin funcional junto com sua chave privada e seed (mnemônico).

### Funcionalidades

- ✅ Geração de mnemônico (12 palavras em inglês)
- ✅ Derivação de seed a partir do mnemônico
- ✅ Criação de carteira HD (Hierarchical Deterministic)
- ✅ Geração de par de chaves pública/privada
- ✅ Geração de endereço Bitcoin (P2PKH)
- ✅ Suporte à rede testnet do Bitcoin

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 12 ou superior)
- npm (gerenciador de pacotes do Node.js)

### Como Instalar e Executar

1. **Clone ou navegue até o diretório do projeto:**
   ```bash
   cd BTCWalletHelloWorld
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Execute o script para gerar uma carteira:**
   ```bash
   npm run create
   ```

### Exemplo de Saída

```
Carteira gerada
Endereço:  tb1q2wx...
Chave privada: cV5...
Seed: abandon ability able... (12 palavras)
```

### Dependências do Projeto

- **bip32**: Implementação do BIP-32 para carteiras hierárquicas determinísticas
- **bip39**: Implementação do BIP-39 para geração de mnemonics
- **bitcoinjs-lib**: Biblioteca completa para trabalhar com Bitcoin em JavaScript

### ⚠️ Segurança

Este é um projeto educacional. **Não use em produção com fundos reais**. As chaves privadas geradas são apenas para fins de aprendizado e demonstração.

---

## 🇺🇸 English

### About the Project

This is an educational project that demonstrates how to create a Bitcoin (BTC) wallet from scratch using JavaScript. The project implements HD (Hierarchical Deterministic) wallet generation following the BIP-32 and BIP-39 standards, generating a functional Bitcoin address along with its private key and seed (mnemonic).

### Features

- ✅ Mnemonic generation (12 English words)
- ✅ Seed derivation from mnemonic
- ✅ HD (Hierarchical Deterministic) wallet creation
- ✅ Public/private key pair generation
- ✅ Bitcoin address generation (P2PKH)
- ✅ Support for Bitcoin testnet

### Prerequisites

- [Node.js](https://nodejs.org/) (version 12 or higher)
- npm (Node.js package manager)

### How to Install and Run

1. **Navigate to the project directory:**
   ```bash
   cd BTCWalletHelloWorld
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the script to generate a wallet:**
   ```bash
   npm run create
   ```

### Example Output

```
Carteira gerada
Endereço:  tb1q2wx...
Chave privada: cV5...
Seed: abandon ability able... (12 words)
```

### Project Dependencies

- **bip32**: Implementation of BIP-32 for hierarchical deterministic wallets
- **bip39**: Implementation of BIP-39 for mnemonic generation
- **bitcoinjs-lib**: Complete library for working with Bitcoin in JavaScript

### ⚠️ Security

This is an educational project. **Do not use in production with real funds**. The private keys generated are for learning and demonstration purposes only.

---

**Autor:** Julio Kauer  
**Licença:** ISC  
**Versão:** 1.0.0