# O Santo Graal do Layout

Neste último exercício de flexbox você vai recriar um layout de site incrivelmente comum. Ele é tão comum que costuma ser chamado de layout [Santo Graal](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img)... e com flexbox é realmente bem fácil de realizar.

Como no exercício anterior, deixamos um pouco mais por sua conta.

### Dicas
- Você precisará alterar o `flex-direction` para empurrar o rodapé para baixo.
- Você precisará adicionar alguns divs como contêineres para fazer as coisas se alinharem corretamente.
- `flex-wrap` ajudará a alinhar corretamente os cards.
- Certifique-se de definir quanto espaço os cards devem ocupar, para que o `flex-wrap` funcione como pretendido.

## Resultado desejado

![desired outcome](./desired-outcome.png)

O número de cards alinhados nessa seção mudará com base na largura da sua tela, então não se preocupe em obter _exatamente_ uma grade 2x3 ou 3x2.

Em uma tela menor, ficará assim:

![smaller](./desired-outcome-smaller.png)

Nota: Os emojis podem aparecer como um ou vários símbolos de texto (por exemplo, &#9734;&#9794;) se você não tiver uma família de fontes com emoji instalada no seu sistema operacional. Isso não afeta o exercício e pode ser ignorado.

### Verificação
- O texto do cabeçalho tem tamanho 32px e peso 900.
- O texto do cabeçalho está centralizado verticalmente e a 16px da borda da tela.
- O rodapé está empurrado para a parte inferior da tela (o rodapé pode ficar _abaixo_ da parte inferior da tela se o conteúdo da seção de 'cards' transbordar e/ou se sua tela for mais curta).
- O texto do rodapé está centralizado horizontal e verticalmente.
- A barra lateral e os cards ocupam todo o espaço disponível acima do rodapé.
- A barra lateral tem 300px de largura (e não encolhe).
- Os links da barra lateral têm tamanho 24px, são brancos e não possuem decoração de texto sublinhada.
- A barra lateral tem 16px de padding.
- Há 48px de padding ao redor da seção de 'cards'.
- Os cards estão dispostos horizontalmente, mas quebram em várias linhas quando ficam sem espaço na página.
