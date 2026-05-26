# Um estilo comum de 'modal'
Este é outro padrão muito comum na web. A solução para este é _simples_... mas pode não ser imediatamente óbvia para você. Você vai precisar editar um pouco o HTML para colocar tudo onde precisa ficar.

### Uma dica
Dependendo de como você abordar este exercício, pode ser necessário revisar a propriedade `flex-shrink` para evitar que um item flex seja esmagado. Além disso, preste atenção na estrutura do HTML; especificamente, considere adicionar um contêiner adicional envolvendo as divs do cabeçalho, botão, texto principal, cancelar e continuar; e considere mover a div do cabeçalho para abranger também o botão.

## Resultado desejado

![desired outcome](./desired-outcome.png)

### Verificação Própria

- O ícone azul está alinhado à esquerda.
- Há espaço igual em ambos os lados do ícone (os espaços entre o ícone e a borda do cartão, e entre o ícone e o texto, são iguais).
- Há padding ao redor da borda do modal.
- O cabeçalho, o texto e os botões estão alinhados entre si.
- O cabeçalho está em negrito e com tamanho de texto ligeiramente maior que o texto.
- O botão de fechar está alinhado verticalmente com o cabeçalho e posicionado no canto superior direito do cartão.
