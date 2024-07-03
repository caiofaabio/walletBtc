# Resumo do Projeto
Este projeto utiliza as bibliotecas bip32, bip39 e bitcoinjs-lib para gerar carteiras HD (Hierarchical Deterministic) na rede de testes do Bitcoin. O processo inclui a geração de uma frase mnemônica, derivação de uma semente, criação de uma raiz de carteira HD, e a derivação de chaves públicas e privadas para a criação de um endereço Bitcoin.

### Passos do Projeto 
1. Importação das Dependências:
 - bip32: Biblioteca para manuseio de carteiras HD.
 - bip39: Biblioteca para geração e manipulação de mnemônicos.
 - bitcoinjs-lib: Biblioteca para operações com Bitcoin.
2. Configuração da Rede:
 - A rede utilizada é a testnet, adequada para testes e desenvolvimento.

3. Definição do Caminho de Derivação:
 - Utiliza-se o caminho m/49'/1'/0'/0 para derivar a carteira.

4. Geração do Mnemônico e Semente:
 - Um mnemônico é gerado para a seed, que é então convertida para uma semente criptográfica.

5. Criação da Raiz da Carteira HD:
 - A raiz da carteira HD é criada a partir da semente, configurada para a rede de testes.

6. Derivação da Conta e Chaves:
 - Uma conta é derivada a partir do caminho especificado, seguida da derivação de um par de chaves (pública e privada).

7. Geração do Endereço Bitcoin:
 - Um endereço Bitcoin é gerado usando a chave pública derivada.
