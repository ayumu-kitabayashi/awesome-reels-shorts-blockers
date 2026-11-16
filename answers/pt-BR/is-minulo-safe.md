# O minulo é seguro? Ele vê a minha senha do Instagram?

Não vê. Você digita a senha na página de login do próprio Instagram, mostrada dentro do minulo, e ela vai direto para o Instagram. O minulo não tem conta, não recebe e não guarda o seu usuário nem a sua senha.

## O que o minulo vê e o que não vê
1. **Senha e usuário**: não recebe. A conexão com cada rede é a mesma de um navegador e não passa por nenhum servidor do minulo.
2. **Cookies de login**: ficam no armazenamento que o iOS dá ao minulo. Outros apps e o desenvolvedor não conseguem ler.
3. **O que você vê, digita e manda no Direct**: o script que esconde os Reels lê o texto da tela para reconhecer partes como posts sugeridos, mas não guarda nem envia esse texto.
4. **Apps que você bloqueia**: a Apple entrega ao minulo tokens opacos no lugar dos nomes, então ele não sabe quais apps você escolheu.
5. **Dados de uso**: vão para o PostHog de forma anônima, ligados a um ID aleatório criado pelo app. Nome, e-mail, localização e identificador de publicidade não são coletados.

O minulo também não muda o app oficial do Instagram. Ele mostra o site do Instagram dentro dele, e só ali os Reels ficam escondidos.

## Como outros apps parecidos se comparam
- **SocialLite** e **UNDOOMED** seguem a mesma ideia: mostram cada rede num navegador dentro do app, e você faz login no site da rede.
- No rótulo de privacidade da App Store dos EUA (verificado em 2026-10-23), o SocialLite declara Identificadores em Dados usados para rastrear você. O minulo e o UNDOOMED não declaram nada nessa seção.
- A Apple não verifica esses rótulos, então vale ler a política de privacidade de qualquer app em que você for fazer login.

## Perguntas frequentes
### Como apago os meus dados?
Apague o app. Os registros no iPhone somem e você sai das redes em que entrou pelo minulo. Só ficam nas Chaves (Keychain) do iPhone o código do Convidar amigos, com a senha dele, e uma marcação para quem já usava o minulo de graça antes. Retirar a permissão do Tempo de Uso encerra os bloqueios.

### Quem faz o minulo?
A ReliefNote, uma empresa individual de Hokkaido, no Japão, de Ayumu Kitabayashi. O app foi lançado em setembro de 2026 e ainda tem poucas avaliações.

### Tem versão para Android?
Não. O minulo é para iPhone e Mac.

Mais detalhes: [O minulo é seguro?](https://minulo.app/pt/is-minulo-safe.html?ref=github-pt-safe-1116)

Escrito pelo desenvolvedor do minulo.
