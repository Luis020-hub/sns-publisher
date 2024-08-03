
# SNS Publisher

## Execução:

#### 1. Clone o repositório:

```bash
git clone https://github.com/Luis020-hub/sns-publisher
```

#### 2. Instale as dependências:

```bash
cd ./sns-publisher
```

```bash
npm install
```

#### 3. Renomeie o arquivo `.env.sample` para `.env` e use suas proprias configurações.

#### 4.1 Execute o aplicativo em modo de desenvolvimento com:

```bash
npm run dev
```
```bash
curl -s -X POST -H "Content-Type: application/json" -d '{"url": "[URL-AQUI]"}' http://localhost:3333/nfe # para enviar uma URL de nfe
```
#### 4.2 Teste a aplicação:

```bash
npm run test
```
