# FransMat Burger

Site estático preparado para publicação gratuita no **GitHub Pages**. Mantém o design original e carrega produtos e configurações a partir dos ficheiros JSON.

## Publicar no GitHub Pages

1. Cria um repositório no GitHub chamado `fransmat-burger`.
2. Envia **o conteúdo desta pasta** para a raiz do repositório (o `index.html` deve ficar na raiz).
3. No GitHub, abre **Settings → Pages**.
4. Em **Build and deployment**, escolhe **Deploy from a branch**.
5. Selecciona a branch `main` e a pasta `/ (root)`, depois clica **Save**.
6. Aguarda a publicação. O endereço será semelhante a `https://TEU-UTILIZADOR.github.io/fransmat-burger/`.

## Alterar produtos sem mexer no HTML

1. No repositório, abre `data/produtos.json`.
2. Clica no lápis (**Edit this file**).
3. Altera o preço ou os dados de um produto, ou acrescenta um novo objecto seguindo o exemplo em `GUIA-EDITAR-PRODUTOS.md`.
4. Clica **Commit changes**.
5. Aguarda alguns minutos e actualiza o site.

Para adicionar uma fotografia, carrega o ficheiro de imagem para a raiz do repositório e indica o nome exacto no campo `image`.

## Alterar WhatsApp, entrega e contas bancárias

Edita `data/config-site.json` da mesma forma. Usa apenas o indicativo e número no campo `whatsapp`, sem `+` ou espaços.

## Notas importantes

- O GitHub Pages publica ficheiros estáticos. A edição é feita pelo próprio GitHub, não por um painel `/admin`.
- Qualquer pessoa com permissão de escrita no repositório poderá alterar o site. Mantém o repositório e a conta protegidos.
- Depois de cada commit, o GitHub Pages volta a publicar o conteúdo.
- Se alterares o nome do repositório, o endereço público também muda.
