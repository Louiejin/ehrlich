# Ehrlich

## Requirements

For development, you will need the following installed in your environment:

1. [Node.js](https://nodejs.org)
2. [Yarn](https://yarnpkg.com)
3. [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
4. [Serverless Framework CLI](https://www.serverless.com/framework/docs/getting-started/)

## How to

- #### Run localy
  - ```sh
    yarn run local
    ```
- #### Test
  - ```sh
    yarn run test
    ```
- #### Deploy database to local machine
  - ```sh
    yarn prisma db push
    ```

## Directory sturcture

```sh
ehrlich
 ┣ database
 ┃ ┣ model
 ┃ ┣ seeder
 ┃ ┗ migration
 ┣ serverless
 ┃ ┣ function
 ┃ ┗ permissions
 ┣ src
 ┃ ┣ feature
 ┃ ┃ ┗ <feature api>
 ┃ ┃ ┃ ┣ datasource
 ┃ ┃ ┃ ┗ presentation
 ┃ ┗ utility
 ┣ .env.example
 ┣ .gitignore
 ┣ package.json
 ┗ README.md
```

## Reference

| Technology | Documentation                                                                                                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Serverless | [https://www.serverless.com/framework/docs/providers/aws]                                                                                  |
| Prisma     | [https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/using-prisma-migrate-typescript-postgres] |
| Typescript | [https://www.typescriptlang.org/docs/handbook/intro.html]                                                                                  |
| Webpack    | [https://webpack.js.org/concepts/]                                                                                                         |
| Middy      | [https://github.com/middyjs/middy#readme]                                                                                                  |
