# Shoes that I hate

> Open to prospective collaborators: send me an email at `benjamin [dot] lavelle {at} btinternet [dot] com`

A Generative Adversarial Network (with a focus on the 'adversarial') for coming up with shoe designs that I hate.

This is largely useless and experimental, and may well never work, but perhaps I can sell them back to [Kanye West](https://sneakernews.com/2019/06/28/adidas-yeezy-clog-shoes/) one day.

## Roadmap

* Establish how hard it is to build a shed GAN, and whether enough instructionals exist.
* Build a repository of images. Presumably I need to label some, including ones I don't hate, for the discriminator network.
* Find a way to regularise and downsample images as much as possible, possibly including huge simplifications (e.g. simple wireframe outlines + colour blocks).
  * Could I in fact abstract them to e.g. JSON colour-by-numbers?
  * Is there instead text-based GAN equivalent that is easier to make that could generate ideas from qualitative descriptions?
* Build a feed of objects/abstractions.
* Build the GAN.
* Host it on [bjml.uk](http://bjml.uk) for fun (this probably means buying rather more than the 512mb Lightsail option)
* Tweet @kanye
