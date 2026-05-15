# 🔐 Infraestrutura e Segurança da Informação

Este diretório é dedicado a projetos, scripts e simulações focados na proteção de dados e arquitetura de redes seguras.

## 🛠️ Projetos em Destaque

### 1. Criptografia Simétrica: Padrão AES (Advanced Encryption Standard)
* **Arquivo:** `AES.java`
* **Descrição:** Implementação do padrão AES, o algoritmo de criptografia simétrica mais utilizado mundialmente, utilizando a API `javax.crypto`.
* **Conceitos Abordados:**
  * Uso do modo de operação **CBC (Cipher Block Chaining)** com preenchimento `PKCS5Padding`.
  * Implementação de **Vetor de Inicialização (IV)** via `IvParameterSpec` para garantir a aleatoriedade dos blocos cifrados.
  * Codificação em Base64 para tráfego e armazenamento seguro.

### 2. Criptografia Simétrica: Algoritmo Triple DES (3DES)
* **Arquivo:** `DES.java`
* **Descrição:** Implementação prática de criptografia e descriptografia legada utilizando o padrão `DESede`. 
* **Conceitos Abordados:**
  * Manipulação de chaves secretas (`SecretKeySpec`) de 24 caracteres (192 bits).
  * Tratamento de exceções e manipulação de fluxos de entrada de dados do utilizador.
