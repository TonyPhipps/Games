# Quick Reference
These are 99% of what you'll ever use:

- -f is FORMAT
- id is COLOR IDENTITY
- o is ORACLE TEXT
- t is TYPE
- otag is ORACLE TAG (community-driven tagging system)

# Samples
**Add this before any search below**
Be sure to change them to match your format/deck colors

```f:commander id=wubrg```

Ramp

```(t:artifact OR t:land) (o:"add {r}" OR o:"add {c}")```

Protection

```(o:protection OR o:hexproof OR o:shroud OR o:indestructible OR o:"can't be" OR o:"gets +")```

Instant Protection

```t:instant (o:protection OR o:hexproof OR o:indestructible OR o:"can't be")```

Evasion

```(o:"double strike" OR o:trample OR o:flying OR o:menace)```

Stax / slowdown to allow your deck to do its thing

```(otag:tax OR otag:stax OR o:"opponents can't" OR o:"each opponent sacrifices")```

Goad Synergy

```(o:goad OR o:"must attack" OR o:"attacks each combat")```

Combat Synergy

```(o:"whenever a creature deals combat damage" OR o:"when ~ deals combat damage")```

Synergy - Get stuff back or affect stuff you OWN, even if another player CONTROLS it

```o:"you own"```
