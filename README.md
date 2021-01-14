# Deck of Cards
> A minimal example of using nbdev to create a python library.


https://nitinverma78.github.io/deck_of_cards/

This repo uses code from Allen Downey's ThinkPython2. This file was automatically generated from a Jupyter Notebook using nbdev. To change it you must edit `index.ipynb`

## Install

`pip install -e`
> There is already a project called deck_of_cards on pypi. This project has no relation to that. This project is an example of how to create python packages with nbdev.

## How to use

Playing cards in python!

```python
from deck_of_cards.deck import Deck
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```python
card = d.pop_card()
print(card)
```

    King of Spades

