# Tetrahedral Interpolation DCTL

A tweaked version of Yedlin's Tetra script, ported to Resolve by [Nick Eason](https://github.com/npeason/Tetra-DCTLOFX).

![](https://i.postimg.cc/vHnFzzq7/tetra.png)

## Features

My version includes the black and white point controls, an expanded slider range and minor code clarity "improvements".

The parameters are normalized in the UI params section, rather than in the vectorization. This means that the UI will show the actual default values for each corner (for example, `Red-Red` is `1.000`), as opposed to being zeroed out. This may not be your preferred behaviour, in which case you can use Nick's original code.

The slider range has been significantly expanded. I don't really see a reason the the minimum amount should allow a primary corner to subtract past gray. It does keep
the sliders centered, though. You can easily set them to whatever you like.

I tried keeping the sliders fairly similar to the Nuke expression, but couldn't replicate it completely, since it doesn't have hard limits on numerical input, only sliders.

## Credits

- Originally [reconstructed for Nuke](https://github.com/calvinsilly/Tetrahedral-Interpolation) by calvinsilly
- [Ported to Fusion](https://github.com/EmberLightVFX/Tetrahedral-Interpolation-for-Fusion) by EmberLightVFX
- [Ported to DCTL](https://github.com/xavijulez/Tetrahedral-Interpolation-DCTL) by Xavi Julia
- [Separately ported to DCTL](https://github.com/npeason/Tetra-DCTLOFX) by Nick Eason

And tweaked by me.

## Threads/Resources

- LGG [thread](https://liftgammagain.com/forum/index.php?threads/tetrahedral-interpolation.15364/#post-153503)
- Nuke script [release](https://old.reddit.com/r/cinematography/comments/k6ggq4/steve_yedlins_tetrahedral_script/)
- Steak Underwater [dev post](https://www.steakunderwater.com/wesuckless/viewtopic.php?t=4319)
- And the Foundry Community [topic](https://community.foundry.com/discuss/topic/154699/blinkscript-stuck-solving-missing-code-tetrahedral-interpolation)

Now if someone could figure out how [Tetra Automator](https://i.postimg.cc/C5F7qwQ6/tetra-automator.png) works, that would be great.
