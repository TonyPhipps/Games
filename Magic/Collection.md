# Sorting
## Latest Sets
- 1/2 binder per set, Ultrapro platinum pages
- Sorted by collector number
- Sets that were ever standard legal get a white binder
- Cards ever used in a deck are left in their inner sleeves

## Older Sets
- 3inch Binder Per Color
- Sorted by card name (starting letter only)
  - Each letter gets a separator page/tab to enable quick finding
- 1 card per set
- Cards ever used in a deck are left in their inner sleeves

## Extra Cards
- Any doubles go into boxes.
- Sorted by color identity > type > card name (starting letter only)
- Uncommons/Rares are sleeved with any extra sleeves or inner sleeves
- Cards ever used in a deck are left in their inner sleeves

# Thinning
My average $100 budget deck has 0-3 cards worth under 0.10c USD.

Cards worth under .10c (TCG Market price) are thinned out. This reduces my "extra cards" by about 50%.

The Scryfall search below will help identify keepers.

```
usd>=.10 r:c id:w t:creature name:/^a/
usd>=.10 (r:u or r:r or r:m) id:w t:creature name:/^a/
```

These searches do the following
- ```usd>=.10``` cards worth 10c and above
- ```r:c``` cards with rarity of common (c, u, r, m)
- ```id:w``` cards with identity WHITE (wubrgc)
- ```t:creature``` cards with type creature (creature, instant, sorcery, enchantment, artifact, planeswalker, battle)
- ```name:/^A/``` cards starting with the letter A