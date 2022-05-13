Hi, I extracted the `AnimInfo` data from the "Shinning Mask" [sic, acc. to website] app that controls the Ledtik masks.

The app itself is fairly reverse-engineerable if you're familiar with how to interface with bluetooth devices.

Here are all of the images. Some of the types were simply pixel arrays (through some trial and error I deduced that the **width** is 12, and that the images are flipped horizontally then rotated CCW 90deg, so do the inverse if processing the raw JSON data), and others are int arrays-of-arrays, the significance of which I'm not entirely sure.

I've gone ahead and converted all of the raw pixel data to PNGs - I'll leave it as an exercise to the reader to compile them to animated GIFs or whatever if you want.

Originally from this Reddit post: https://www.reddit.com/r/DidntKnowIWantedThat/comments/uocffh/this_ledtik_mask_is_really_cool/i8fmp0w/?utm_source=reddit&utm_medium=web2x&context=3

Enjoy!

\- [Qix-](https://github.com/qix-)