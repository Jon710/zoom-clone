
## Como executar
#### Para rodar a aplicação Web você precisa ter instalado no seu ambiente: 

- [Git](https://git-scm.com)
- [Node.js][nodejs]


```
# Clone o repositorio
git clone https://github.com/capelaum/ZoomClone
```

### Instale dependências pelo npm ou yarn

Execute o comando para instalar dependências dentro de cada uma das pastas public, server e peer-server: 

```
 npm install # ou yarn install
```

### Rode o servidor dentro da pasta server

```
npm start 
# app running at :::3000
```

### Rode o servidor peer dentro da pasta peer-server

```
npm run dev 
# npx peerjs --port 9000 --key peerjs --path / "9000"
```

### Rode a interface da aplicação dentro da pasta public:

```
npm start 
# Available at http://127.0.0.1:8080
```
