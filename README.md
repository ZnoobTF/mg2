# minigame 2
## Devlog
1. The issue I got for the If statement on Step 2 was a syntax error where a ( is missing, and also another error where a ) is missing. The error was that the if statement did not have a () around its conditional expression. To fix this, just put () around _timeLeft <= 0.0.
2. The line of code "_spriteRenderer.color = new Color(r, 0.2f, 0.2f);" sets a new color for the chest prop GameObject. The Sprite Renderer component in the chest prop GameObject has a color variable (? idk if this should be considered a variable, maybe more a component of a component) that lets the color be changed. The period seperates the parent and the child, and tells the machine that we are changing the color variable for the _spriteRenderer variable. The word "new" is because a new Color object needs to be created and stored in memory.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
