# Deck of Cards

This is a test repo for testing nbdev.

## Install

After cloning this repository:

`pip install -e .`
> There is already a project called [deck_of_cards on pypi](https://pypi.org/project/deck-of-cards/).  This project has no relation to that.  This project is an example of how to create python packages with [nbdev](https://github.com/fastai/nbdev).

## How to use

Playing cards in python!

```
from deck_of_cards.deck import Deck
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```
card = d.pop_card()
print(card)
```

    King of Spades


See [the docs](https://fastai.github.io/deck_of_cards/) for more info.
