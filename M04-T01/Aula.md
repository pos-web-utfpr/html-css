# Evolução para Design Responsivo

## Primeira etapa:

1. Trocar larguras fixas por %
2. Tornar imagens flexíveis
3. Trocar tipografia fixa em px por rem

### Antes
- .container tem width: 1400px
- .main-content tem width: 900px
- .sidebar tem width: 300px
- .car-image tem width: 400px
- Títulos e textos usam px

### Depois
- .container passa a usar largura relativa
- .main-content e .sidebar passam a usar %
- .car-image passa a se ajustar ao card
- Fontes passam a usar rem

### Medidas
- REM: rem significa “root em”. É uma unidade relativa baseada no tamanho da fonte do elemento raiz da página — o <html>.
- px: Unidade fixa que define um tamanho absoluto em pixels na tela.
- %: Unidade relativa que define um tamanho proporcional ao elemento pai.

#### Regra prática

- rem → fontes, espaçamentos, layout
- px → bordas finas (ex: 1px)
- % → casos específicos (largura, flex)


## Segunda etapa


Flexbox (organiza, mas NÃO resolve tudo)

Deixar o layout bonito, organizado… mas ainda quebrando no mobile.

Vamos:

- Trocar inline-block → flex
- Melhorar organização
- Manter %, rem, imagens flexíveis

Resultado esperado:

- Layout mais profissional
- Ainda não adaptável ao mobile


## Terceira etapa

Media Query e Mobile First

Até agora:

- ❌ Removeu px fixo
- ✅ Usou %
- ✅ Usou Flexbox
- ❌ Ainda não resolveu mobile

Agora:

Detectar tamanho da tela
Mudar o layout
