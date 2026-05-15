# 🔐 Infraestrutura e Segurança da Informação

Este diretório é dedicado a projetos, scripts e simulações focados na proteção de dados e arquitetura de redes seguras.

## 🛠️ Projetos em Destaque

### 1. Criptografia Simétrica: Algoritmo Triple DES (3DES) em Java
* **Arquivo:** `DES.java`
* **Descrição:** Implementação prática de criptografia e descriptografia utilizando a API `javax.crypto` nativa do Java. 
* **Conceitos Abordados:** * Cifragem de blocos com o padrão `DESede`.
  * Manipulação de chaves secretas (`SecretKeySpec`) de 24 caracteres (192 bits).
  * Conversão e codificação de dados em Base64 para tráfego seguro de informações.
  * Tratamento de exceções e manipulação de fluxos de entrada de dados do utilizador.

Esta implementação demonstra conceitos fundamentais de **Confidencialidade**, um dos pilares da Segurança da Informação, garantindo que o texto original só possa ser lido por quem possui a chave secreta de 24 bytes correspondente.
