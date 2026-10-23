# Portfólio — Fabricio Gonçalves da Silva

Portfólio pessoal desenvolvido em React + Vite, com CSS responsivo, modo claro/escuro, projetos, trajetória, certificados e contatos.

## Executar localmente

Requisitos: Node.js 20+.

```bash
npm install
npm run dev
```

Abra o endereço exibido no terminal (normalmente `http://localhost:5173`).

## Build de produção

```bash
npm run build
npm run preview
```

## Publicar na Vercel

1. Crie um repositório no GitHub e envie os arquivos deste projeto (sem `node_modules`).
2. Acesse https://vercel.com/new e conecte sua conta do GitHub.
3. Importe o repositório do portfólio.
4. Confirme `Framework Preset: Vite`, `Build Command: npm run build`, `Output Directory: dist`.
5. Clique em **Deploy**. Após a publicação, a Vercel fornecerá um endereço `*.vercel.app`.
6. Novos commits na branch principal geram novos deploys automaticamente, se a integração estiver ativada.

## Atualizar conteúdo

Edite os arrays `skills`, `projects` e `certs` no arquivo `src/main.jsx`. Imagens e certificados ficam em `public/assets/`.

## Observações

- O portfólio contém imagens dos certificados fornecidos pelo titular. Ao publicar, elas ficarão acessíveis publicamente, incluindo códigos de validação e outros dados presentes nas imagens. Revise antes do deploy.
- Os certificados foram adicionados com base nas imagens recebidas. O certificado de Geopolítica mencionado anteriormente não foi enviado e, por isso, não está incluído.
- O visual de terminal nos cards dos projetos é ilustrativo, não uma captura real da execução dos programas.
- O deploy na Vercel não é realizado automaticamente ao baixar este projeto.
