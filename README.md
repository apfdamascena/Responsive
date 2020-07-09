# Responsive

# Layout :

- Fixo 
`px` - Pixels.

- Fluido
`%` - Porcentagem.
`auto` - Automatico.
`vh` - viewport height.
`vw` - viewport width.

# Texto :

- fixos
`1px` = 0.75pt

- fluidos
`em` - multiplicado pelo pai.
`rem` - multiplicado pelo root.


# Estrategias :
- Primeira estrategia:
    `Colocar width : 100%. E ,caso precise, definir o max-width.`

- Segunda estrategia:
    `Definir body com font-size: 62.5% e trabalhar o resto do texto com 1.0rem para 10px;`

- Terceira estrategia:
    `Breakpoints: Media Queries --> @media (max-width: numberpx){}`

# Media Queries :
```css
@media (max-width: 320px){
    #form h3{
        font-size: 2rem;
    }
}
```
