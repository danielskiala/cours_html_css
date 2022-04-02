# Réssoudre le probleme de Bloc Formatting Context où le Contexte de Formatage de block
## Résolution avec du proprietés CSS
### Exemple
padding : `padding:10px;`
overflow : `overflow:auto;`
border : `border-top:1px solid blue;`
display : `display:inline-block;`

## Résolution avec pséudo élément du CSS
### Exemple

parent : `.parent::before{content:""; display:table; clear:both;`