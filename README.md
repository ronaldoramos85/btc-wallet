# 📊 Criação de carteira e envio de criptomoedas

Bem-vindo ao projeto "Criação de carteira e envio de criptomoedas". Este  projeto é resultado de um Lab DIO (Digital Innovation One), onde foram exercitados os conhecimentos adquiridos ao longo do curso "Introdução à Blockchain". Através deste projeto foram exercitadas a criação de uma cateira de teste na Blockchain Testnet do Bitcoin (cadeia de blocos de teste do Bitcoin), com os dados de endereço, chave privada e seed. Com esses dados em mãos, foi realizada a transferência de faucets (moedas de teste, sem valor de mercado) para a carteira criada.

## 📋 Pré-requisitos

Para a realização deste Lab (também chamado de desafio de projeto) foi necessário instalar o VSCode, Node.js e Electrum em suas versões mais recentes.


## 🎯 Objetivos Deste Desafio de Projeto (Lab)


- Como resultado do referido Lab DIO foi criado este [passo a passo] com a descrição dos passos necessários para a realizar todo o processo de criação de criação de carteira e envio de criptomoedas de teste.
- A URL deste repositório com a solução foi fornecido na plataforma da DIO para avaliação de meu desempenho no referido Bootcamp.


## 🚀 Passo a Passo

### 0. Primeiros passos
-   É necessário baixar o [VSCode](https://code.visualstudio.com/Download), o [Electrum](https://electrum.org/#download) e o [Node.js](https://nodejs.org/en/download/prebuilt-installer) nas versões mais recentes, de acordo com sua plataforma e sistema operacional.
-	Após o download, é necessário instalar cada produto conforme instruções do fornecedor.

### 1. Criação da carteira

-   Abra o VSCode.
-	Crie uma pasta BTCWALLET.
-	Clique em Terminal > New Terminal.
-	No terminal, digite "node -v" para verificar a versão do Node.js instalado.
-	Ainda no terminal, digite "npm -v" para verificar a versão do Node Package Manager.
-	Seguindo no terminal, digite "npm init -y" para criar o projeto.
-	Para instalar as dependências necessárias digite "npm install bip39 bip32@2.0.6 bitcoinjs-lib --save" no terminal.
-	Crie uma pasta chama "src".
-	Dentro da pasta "src" crie o arquivo "createWallet.js" e coloque nele o conteúdo que está no arquivo e pasta de mesmo nome neste diretório.
-	No terminal,digite "cd src" para entrar no diretório onde se encontra o programa a ser executado.
-	Digite "node .\createWallet.js" para executar o programa e obter os dados de endereço, chave privada e seed da carteira para uso na Testnet, conforme a imagem a seguir:
![image](https://github.com/ronaldoramos85/btc-wallet/blob/main/prints/JS_Geracao_Carteira.jpg)

### 2. Verificar a carteira na Testnet Bitcoin

-   Após a criação da carteira,verifique a existência da mesma na Tesnet Bitcoin através de consulta ao [BlockStream](https://blockstream.info/testnet). Se a carteira foi criada com sucesso, será exibida uma imagem semelhante à seguinte:
![image](https://github.com/ronaldoramos85/btc-wallet/blob/main/prints/wallet.jpg)

### 3. Transferir criptomoedas para a carteira

-   Entre no [BitcoinFaucet](https://bitcoinfaucet.uo1.net/send.php) para transmitir Faucets (criptomoedas sem valor de mercado) para a carteira criada, conforme a imagem abaixo:
![image](https://github.com/ronaldoramos85/btc-wallet/blob/main/prints/send_faucet.jpg)

### 4. Consultar saldo e transações

-   Para consultar a transação efetuada e o saldo da carteira basta consultar novamente a carteira em [BlockStream](https://blockstream.info/testnet), rolar a página e verificar a transação e saldo:
![image](https://github.com/ronaldoramos85/btc-wallet/blob/main/prints/transactions.jpg)
![image](https://github.com/ronaldoramos85/lab-aws-sagemaker-canvas-estoque/blob/main/images/Predict_002.jpg)
-	Outro modo de realizar tal consulta é através do Electrum, por importar a carteira criada nele e consultar o histórico.

### 5. Considerações Finais

-	O desafio de projeto proposto possibilitou o entendimento prático da criação de uma carteira e da realização de transações em um ambiente seguro de testes.