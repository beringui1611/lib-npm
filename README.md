
## lib-npm

Este é um breve tutorial sobre como criar e publicar uma biblioteca npm.

### Passo 1: Criar uma conta no npm

Acesse o [site do npm](https://www.npmjs.com/) e crie uma conta, se ainda não tiver uma.

### Passo 2: Preparar o código

Certifique-se de ter seu código pronto e compilado. Neste exemplo, usaremos o Hardhat, mas você pode escolher a ferramenta de sua preferência.

### Passo 3: Login no npm

No terminal, execute o seguinte comando para fazer login na sua conta npm:


```
npm login
```


### Passo 4: Configurar o arquivo package.json
No seu arquivo package.json, certifique-se de incluir as dependências necessárias e definir o nome da sua biblioteca:

```
{
  "name": "lib-test-sol-2",
  "devDependencies": {
    "@nomicfoundation/hardhat-toolbox": "^5.0.0",
    "hardhat": "^2.22.3"
  },
  "version": "0.0.1"
}

```
Se não tiver definido a versão, você pode executar o seguinte comando para corrigir isso:

```
npm pkg fix
```

### Passo 5: Publicar a biblioteca
Finalmente, para publicar sua biblioteca, execute o seguinte comando:
![tela-npm-tutorial](https://github.com/beringui1611/lib-npm/assets/132324277/7cbbfe8c-8e3a-41b5-a154-f6dfddb06963)

Após publicar sua biblioteca, outros desenvolvedores podem instalá-la e utilizá-la em seus projetos. Por exemplo:


```npm install lib-test-sol-2 ```
Em seguida, importe os módulos necessários em seu código.

![npm-run](https://github.com/beringui1611/lib-npm/assets/132324277/02c90805-57a6-4428-8270-32403c09811f)


Personalização
Você pode personalizar sua biblioteca de muitas maneiras, este é apenas um exemplo básico.






