# Paletas de cores

Paleta principal para a identidade visual do DevLearn.

## Neutros e base escura

| Cor | Valor | Uso |
| --- | --- | --- |
| Fundo do header | `#0c0e1c` | Fundo quase preto azulado |
| Fundo secundario | `#12142a` | Cards e secoes escuras |
| Texto principal | `#ffffff` | Titulos e textos sobre fundo escuro |
| Texto secundario | `#b7b9c9` | Paragrafos e informacoes auxiliares |

## Gradiente roxo e azul

| Cor | Valor | Uso |
| --- | --- | --- |
| Inicio | `#1a1440` | Inicio do gradiente principal |
| Meio | `#3d2fa8` | Transicao do gradiente |
| Destaque | `#5b3fe0` | Parte mais clara do gradiente |
| Intermediaria | `#4834d4` | Botoes secundarios e estados hover |

Gradiente sugerido para a secao principal:

```css
background: linear-gradient(180deg, #1a1440, #3d2fa8, #5b3fe0);
```

## Acento rosa e magenta

| Cor | Valor | Uso |
| --- | --- | --- |
| Rosa vibrante | `#e6376c` | Inicio do gradiente de CTA e destaques |
| Roxo vibrante | `#8b3ce0` | Final do gradiente de CTA |

Gradiente sugerido para o botao principal:

```css
background: linear-gradient(90deg, #e6376c, #8b3ce0);
```

## Acentos complementares

| Cor | Valor | Uso |
| --- | --- | --- |
| Laranja | `#f5a623` | Destaques pontuais e tags de Java |
| Preto com opacidade | `#000000` | Sombras e overlays sutis |

Exemplo de sombra:

```css
box-shadow: 0 12px 30px rgb(0 0 0 / 20%);
```

## Regras de uso

- Fundo geral: combinar `#0c0e1c`, `#1a1440` e `#5b3fe0` em um gradiente vertical.
- CTA principal: usar o gradiente de `#e6376c` para `#8b3ce0`.
- Titulos: usar `#ffffff`.
- Paragrafos: usar `#b7b9c9`.
- Usar `#f5a623` apenas como detalhe visual pontual.
- Reservar sombras e overlays pretos para criar profundidade sem esconder o conteudo.
