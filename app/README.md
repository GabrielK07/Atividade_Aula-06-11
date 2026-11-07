# Atividade Aula 06-11

Servidor web feito com Node.js e Express que serve arquivos estáticos da pasta `public`.

## O que você precisa ter instalado

- [Node.js](https://nodejs.org/) versão 20 ou superior (já inclui o npm)
- [Git](https://git-scm.com/)

Para conferir, rode no terminal:

```bash
node -v
npm -v
```

## Como rodar o projeto

**1. Clone o repositório e entre na pasta do projeto:**

```bash
git clone https://github.com/GabrielK07/Atividade_Aula-06-11.git
cd Atividade_Aula-06-11/app
```

**2. Instale as dependências:**

```bash
npm install
```

**3. Crie o arquivo `.env`** na pasta `app` com o seguinte conteúdo:

```
PORT=3001
```

Esse arquivo não vem no repositório de propósito, então cada pessoa precisa criá-lo.

**4. Inicie o servidor:**

```bash
npm run dev
```

**5. Abra no navegador:**

http://localhost:3001

## Scripts disponíveis

| Comando | O que faz |
| --- | --- |
| `npm run dev` | Inicia o servidor e reinicia sozinho quando você altera um arquivo |
| `npm start` | Inicia o servidor normalmente |

## Estrutura do projeto

```
app/
├── public/        # arquivos estáticos (HTML, CSS, JS do navegador)
├── server/
│   └── main.js    # servidor Express
├── package.json
└── README.md
```

## Problemas comuns

- **`Missing script: "dev"`**: você está na pasta errada. Entre na pasta `app`, onde fica o `package.json`.
- **`Cannot find package ...`**: faltou instalar as dependências. Rode `npm install`.
- **A porta aparece como `undefined`**: falta criar o arquivo `.env` (passo 3).
