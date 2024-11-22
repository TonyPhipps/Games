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
Scryfall for cards under .10c are thinned out. Assuming the above sorting methods are used, the scry search below will help thin out the Extra Cards boxes.

```
usd>.10 r:c id:w t:creature name:/^A/
```

This search does the following
- ```usd>.10``` cards over 10c
- ```r:c``` cards with rarity of common (c, u, r, m)
- ```id:w``` cards with identity WHITE (wubrgc)
- ```t:creature``` cards with type creature (creature, instant, sorcery, enchantment, artifact, planeswalker, battle)
- ```name:/^A/``` cards starting with the letter A