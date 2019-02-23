# ITERIS HACKATON 2019

**URL BASE**: https://us-central1-hackaton-c9598.cloudfunctions.net

# API HEROIS (/heroes)

contrato da **API**

```json
{
    "nome": string,
    "nome_verdadeiro": string,
    "genero": string,
    "descricao": string,
    "icone": string,
    "image": string
}
```

**ex**:

```json
{
    "nome": "Batman",
    "nome_verdadeiro": "Bruce Wayne",
    "genero": "homem",
    "descricao": "Bruce Wayne, who witnessed the murder of his billionaire parents as a child, swore to avenge their deaths. He trained extensively to achieve mental and physical perfection, mastering martial arts, detective skills, and criminal psychology. Costumed as a bat to prey on the fears of criminals, and utilizing a high-tech arsenal, he became the legendary Batman.",
    "icone": "https://comicvine.gamespot.com/api/image/square_avatar/6733777-4.jpg",
    "image": "https://comicvine.gamespot.com/api/image/scale_medium/6733777-4.jpg"
}
```

## API POKEMON (/pokemon)

contrato da **API**

```json
{ 
    "nome": string,
    "cardURL": string,
    "card_hdURL": string,
    "tipo": string,
    "subTipo": string,
    "descricao": string
}
```

*ex*:

```json
{
    "nome": "Hariyama ex",
    "cardURL": "https://images.pokemontcg.io/ex8/100.png",
    "card_hdURL": "https://images.pokemontcg.io/ex8/100_hires.png",
    "tipo": "Pokémon",
    "subTipo": "EX",
    "descricao": "When Pokémon-ex has been Knocked Out, your opponent takes 2 Prize cards."
}
```

## API CERVEJA (/beers)

contrato da **API**

```json
{
    "nome": string,
    "slogan": string,
    "descricao": string,
    "abv": double,
    "tira_gosto": [string]
}
```

**ex**:

```json
{
    "nome": "Buzz",
    "slogan": "A Real Bitter Experience.",
    "descricao": "A light, crisp and bitter IPA brewed with English and American hops. A small batch brewed only once.",
    "abv": 4.5,
    "tira_gosto": [
        "Spicy chicken tikka masala",
        "Grilled chicken quesadilla",
        "Caramel toffee cake"
    ]
}
```
