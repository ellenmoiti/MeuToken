# Criando Token nos Padrões Web3

## Links Úteis
- https://metamask.io/​
- https://rpc.info/
- https://remix.ethereum.org/

## Passo a passo
### 1) Metamask/RPC
- Faça o download e instalação (https://metamask.io/)
- Adicione extensão ao Google Chrome
- Crie sua conta (lembre-se de armazenar a Frase de Recuperação em um local seguro; ela é a única forma de recuperação da sua conta)
- Clique em Ethereum Mainnet -> Add Network
- Acesse Blockchain RPCs (https://rpc.info/)
  - Em Filters -> Binance Smart Chain
  - Utilize os dados da Mainnet (1ª) para conectar com o Metamask.
- No Metamask, selecione a rede Goerli, que será usada para realizar testes
  - Ethereun Goerli Faucet (https://faucet.quicknode.com/ethereum/goerli)

### 2) Desenvolvimento do Smart Contract - REMIX
- Acesse o REMIX (https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js)
- Crie um novo workspace
- Crie um novo file e cole o código contido em token.sol 
- No construtor do código:
  - Altere YOUR_METAMASK_WALLET_ADDRESS para o seu endereço do Metamask
  - Persolanize outros campos, como symbol e name, de acordo com sua preferência
- Compile o código
- Para o deploy:
  -  Escolha o ambiente Inject Provider - Metamask
  -  Conecte com a Metamask
  -  Selecione o contrato criado
  -  Deploy

### Etherscan
- Acesse Etherscan (https://etherscan.io/)
- Verifique a criação do seu token
- Copie o número do seu contrato
- Importe no Metamask (caso não tenha aparecido automaticamente)
- Seu token está pronto para uso!


## Alternativa
### CherrySwap
- Acesse Blockchain RPCs (https://rpc.info/)
  - Em Filters -> OKEx
  - Utilize os dados da Mainnet para conectar com o Metamask.
- Acesse CherrySwap (https://www.cherryswap.net/#/swap)
- Utile a extensão do Metamask para estabelecer a conexão
- No menu, clique em Ferramentas -> Create Token
- Preencha os campos da página.
  - Obs.: é preciso ter OKT para gerar o contrato.
  


