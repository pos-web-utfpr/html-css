#  Acessibilidade

## WCAG

Web Content Accessibility Guidelines

Diretrizes de Acessibilidade para Conteúdo Web


- https://www.w3.org/WAI/standards-guidelines/wcag/
- https://guia-wcag.com/en/ 

## Os 4 princípios
    1. Perceptível
    2. Operável
    3. Compreensível
    4. Robusto

## ARIA
    - Accessible Rich Internet Applications
    - Aplicações Ricas de Internet Acessíveis



Conjunto de atributos que tornam interfaces web mais acessíveis

ARIA é uma forma de dizer para o navegador — e principalmente para leitores de tela — o que cada elemento faz.”

Exemplo: `<div role="alert">Erro ao enviar</div>`


Developers https://developer.mozilla.org/pt-BR/docs/Web/Accessibility/ARIA

### Atributos ARIA
| Atributo           | Função                  | Exemplo                                          |
| ------------------ | ----------------------- | ------------------------------------------------ |
| `aria-label`       | Nome direto             | `<button aria-label="Fechar menu">X</button>`    |
| `aria-labelledby`  | Nome por referência     | `<div aria-labelledby="titulo"></div>`           |
| `aria-describedby` | Descrição extra         | `<input aria-describedby="erro">`                |
| `aria-hidden`      | Esconder do leitor      | `<span aria-hidden="true">🔍</span>`             |
| `aria-live`        | Atualizações dinâmicas  | `<div aria-live="polite">Mensagem enviada</div>` |
| `role`             | Papel do elemento       | `<div role="button">Clique</div>`                |
| `aria-pressed`     | Estado de botão         | `<button aria-pressed="true">Like</button>`      |
| `aria-expanded`    | Aberto/fechado          | `<button aria-expanded="false">Menu</button>`    |
| `aria-controls`    | Relação entre elementos | `<button aria-controls="menu">Abrir</button>`    |
| `aria-current`     | Item atual              | `<a aria-current="page">Home</a>`                |

