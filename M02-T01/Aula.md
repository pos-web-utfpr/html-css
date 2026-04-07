# Estilização Essencial e Box Model com CSS3

## Seletores, Especificidade e Herança

- Introdução: Cascading Style Sheets
- Herança
- Gabarito do CSS: Processo de Decisão

### Gabarito de Decisão:

**A. Origem e Importância**
O navegador verifica de onde vem o código:

- **User Agent**: Estilos padrão do navegador (ex: o azul sublinhado dos links).
- **Autor**: O código que você escreve no seu arquivo `.css`.
- **!important**: Uma "marreta" que ignora as próximas regras (deve ser usada com cautela).

**B. Especificidade (O Sistema de Pontos)**
Se as origens forem iguais, o navegador calcula quem foi mais específico na seleção:

- **Inline** (`style="..."`): 1000 pontos.
- **ID** (`#meu-id`): 100 pontos.
- **Classe, Atributo ou Pseudo-classe** (`.item, [type="text"], :hover`): 10 pontos.
- **Elemento ou Pseudo-elemento** (`h1, div, ::before`): 1 ponto.

**C. Ordem de Aparição**
Se a origem e a especificidade forem idênticas, a regra que foi escrita por último no código é a que vence.
