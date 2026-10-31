# Currículo – Gustavo Pereira Lima

Projeto acadêmico de uma página de currículo, desenvolvido com Vue 3 e Vite. O conteúdo de perfil, formação, experiências e contato é **fictício e demonstrativo**; não deve ser interpretado como informação biográfica real.

> Este repositório é uma adaptação de um projeto-base recebido para estudo. A estrutura e os componentes originais foram mantidos e configurados para publicação; personalize o código e registre os créditos necessários conforme as orientações da sua instituição.

## Tecnologias

- Vue 3
- Vite
- Tailwind CSS via CDN

## Executar localmente

Requisito: Node.js 22 ou superior compatível com o `package.json`.

```bash
npm ci
npm run dev
```

## Gerar versão de produção

```bash
npm run build
npm run preview
```

Os arquivos prontos para publicação são gerados na pasta `dist/`.

## Publicar no GitHub Pages

1. Crie um repositório público chamado **`curriculo-gustavo-pereira-lima`**.
2. Envie todos os arquivos deste projeto para a branch `main` (não envie a pasta `node_modules`).
3. No GitHub, abra **Settings → Pages** e selecione **GitHub Actions** em *Build and deployment*.
4. A cada envio para `main`, o workflow `.github/workflows/deploy.yml` instala as dependências, gera a versão de produção e publica o site.

Com o nome de repositório indicado, o endereço esperado será:

`https://SEU-USUARIO.github.io/curriculo-gustavo-pereira-lima/`

Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub. Se mudar o nome do repositório, atualize também a propriedade `base` em `vite.config.js`.
