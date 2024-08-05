---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# [03] Move Your Body! [I]
<!--  -->
Hi, we recite Basmallah together before start our session

> **Bismillahirrahmanirrahim**

## We are able to shoot! What we gonna do now?
<!-- Introduction -->

On the last session, we already made our Shooter character with the ability of shooting some projectiles. Unfortunately, we need more time to make it move to the right and to the left. In this session, we will make it happen after we do another 'magic trick' to make our Shooter able to jump!

Long story short, let's do it now!

---
## Jumping? What are the step for it?
<!-- Connection -->
```{figure} ../_static/images/content/jumping_mario.webp
:label: Limitless Jump!
:alt: Jumping Mario
:height: 200px
:align: center

He is jumping to the top endlessly! But, let's think about it. There must be a button that player needs to press!
```

Jumping needs some movement in a sequence. The character jumps after we push a button, like {kbd}`Up` or {kbd}`Space`!

Let's break it down 👇🏻:
```{figure} ../_static/images/content/breakdown.webp
:label: Limitless Jump!
:alt: Jumping Mario
:height: 200px
:align: center
```

1. Player presses the jump button
1. The character starts to move up
1. The character then move down to the ground

That's it!

---
## Let's break the leg!
<!-- Application -->

Determine what components/blocks we need first, Lets jump into Scratch app to see it live!
