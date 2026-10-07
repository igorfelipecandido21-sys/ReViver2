# ReViver — versão para GitHub Pages

Esta pasta é a versão do **frontend** pronta para publicação no GitHub Pages.

## O que funciona no GitHub Pages
- Tela inicial
- Login
- Cadastro
- Entrada anônima
- Página inicial
- Chatbot local
- Salvamento de usuários e conversas no `localStorage`
- Meus dados
- Informações sobre substâncias
- Mapa/tela de pontos de acolhimento
- Busca dos pontos
- Geolocalização do navegador
- Navegação entre as telas

## Publicação
1. Crie ou abra o repositório no GitHub.
2. Coloque **todo o conteúdo desta pasta** na raiz do repositório.
3. No GitHub, entre em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde a publicação.

O GitHub fornecerá o endereço do site em:
`https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`

### Importante
O GitHub Pages hospeda o frontend. O backend Python/FastAPI/Ollama não roda diretamente no GitHub Pages. Para colocar também o backend 24 horas no ar, ele precisa ser hospedado separadamente em um serviço que execute Python e depois conectado ao frontend pela API.
