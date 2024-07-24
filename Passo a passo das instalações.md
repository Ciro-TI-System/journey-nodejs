# Comandos no prompt

### Criação do arquivo inicial

```
npm init -y
```

### Instalação do Typescript para o NodeJS

```
npm i typescript @types/node -D
```

### Configuração base do Typescript no NodeJS

```
npx tsc --init
```

[tsconfig/bases](https://github.com/tsconfig/bases/blob/main/bases/node20.json)

```
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "display": "Node 20",
  "_version": "20.1.0",

  "compilerOptions": {
    "lib": ["es2023"],
    "module": "node16",
    "target": "es2022",

    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "moduleResolution": "node16"
  }
}
```

### Comando para instalar o conversor

```
npm i tsx -D
```

### Script para rodar o servidor

```
"scripts": {
    "dev": "npx tsx watch src/server.ts"
  },
```

```
npm run dev
```

### Instalação do Framework Fastify

```
npm i fastify
```

### Instalação da ferramenta Prisma para utilizar banco de dados no NodeJS

```
npm i prisma -D
```

### Iniciando o Prisma com o banco de dados SQLite

```
npx prisma init --datasource-provider SQLite
```

### Comparando o schema.prisma com o dev.db e criando as tabelas no SQLite

```
npx prisma migrate dev
```

### Instalando a biblioteca 'zod' para validação de dados

```
npm i zod
```

### Instalando o plugin para a integração do 'zod' com o 'fastify'

```
npm i fastify-type-provider-zod
```

### Abrir interface de navegação do banco de dados

```
npx prisma studio
```

### Instalação de biblioteca de datas para criar validações

```
npm i dayjs
```

### Biblioteca para envio de e-mails

```
npm i nodemailer
```

### Instalando integração do 'nodemailer' com o typescript

```
npm i --save-dev @types/nodemailer
```
