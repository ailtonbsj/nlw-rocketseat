# Histórico de comandos executados

## Primeiro dia

> Código na pasta `web`

Cria um projeto React usando typescript.
```bash
yarn create react-app web --template typescript
```

Inicializa servidor com hot reload.
```bash
yarn start
```

Instala modulo de icones. [Documentação aqui!](https://react-icons.github.io/react-icons/)
```bash
yarn add react-icons
```

Instala modulo de rotas. [Documentação aqui!](https://reactrouter.com/web/guides/quick-start)
```bash
yarn add react-router-dom
```

Instala modulo de definição de tipos como dependência de desenvolvimento.
```bash
yarn add @types/react-router-dom -D
```

Instala modulo javascript leaflet e wrapper dele como componente React. [Documentação aqui!](https://react-leaflet.js.org/)
```bash
yarn add leaflet react-leaflet
```

Instala modulo de definição de tipos como dependência de desenvolvimento.
```bash
yarn add @types/react-leaflet -D
```

## Segundo dia

> Código na pasta `backend`

Inicializa pasta como modulo js/node
```bash
yarn init -y
```

Instala framework Express ([Documentação](https://expressjs.com/pt-br/)) e definição de tipos
```bash
yarn add express

yarn add @types/express -D
```

Instala modulo TypeScript como dependência de desenvolvimento
```bash
yarn add typescript -D
```

Cria arquivo de coniguração do TypeScript `tsconfig.json`
```bash
yarn tsc --init
```

Instala modulo que reinicializa servidor node se houver mudança de arquivo
```bash
yarn add ts-node-dev -D
```

Instala os modulos TypeORM ([Documentação](https://typeorm.io/#/)) e SQLite3
```bash
yarn add typeorm sqlite3
```

Comandos utilizados para gerar e executar migrations
```bash
yarn typeorm migration:create -n create_orphanages

yarn typeorm migration:run

yarn typeorm migration:revert

yarn typeorm migration:create -n create_images

yarn typeorm migration:run
```

Modulo para envio de arquivos
```bash
yarn add multer

yarn add @types/multer -D
```

Adiciona modulo de suporte a erros async/await no Express
```bash
yarn add express-async-errors
```

Instala modulo de validação do node
```bash
yarn add yup

yarn add @types/yup -D
```

Adiciona modulo para habilitar CORS no node
```bash
yarn add cors

yarn add @types/cors -D
```
