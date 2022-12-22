# Curso BaltaIO - 2804

Criando um App com React, TypeScript, Hooks, Context e Forms

Principais alterações para poder executar o App com dependências legadas:

Alterações package.json -> dependencies
"@hookform/resolvers": "^1.3.7"
"react-hook-form": "^6.8.0"
"react-scripts": "5.0.1"

Alterações package.json -> scripts
"start": "react-scripts --openssl-legacy-provider start"

Alteração src -> components -> AddTodo.tsx
import { yupResolver } from "@hookform/resolvers/yup";
// npm install react-hook-form@6.8.0 yup @types/yup @hookform/resolvers@1.3.7
