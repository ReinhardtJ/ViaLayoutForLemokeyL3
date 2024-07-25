# ViaLayoutForLemokeyL3
The via layout config file I use for my [Lemokey L3](https://www.lemokey.com/products/lemokey-l3-qmk-via-wireless-custom-mechanical-keyboard), used with the [Programmer Dvorak](https://www.kaufmann.no/roland/dvorak/) keyboard layout.

## Features
### Macro Keys
The L3 features 4 distinct macro keys on the right side of the main key block. They are bound to the following shortcuts

1. Quick Action
2. Go to Definition or Usages 
3. Find Usages
4. Select in (usually used to open the project panel with the current file selected)


### Umlauts
The right FN key is bound to the layer 1 by default (FN1). The right windows key is bound to FN2 (as I don't see any use to have 2 windows keys).

The key combinations provided by the keyboard layout to write ÄÖÜ and äöü are encoded usind macros as follows:
- Ä -> fn1 + A
- Ö -> fn1 + O
- Ü -> fn1 + U
- ä -> fn2 + A
- ö -> fn2 + O
- ü -> fn2 + U

### Navigating with the right hand

Sometimes it's useful to operate the arrow keys without having to take the right hand off. For this reason, 
I have bound the caps lock key to FN2 as well (as I also don's see a use for the caps lock key).

- Up -> fn2 + C
- Left -> fn2 + H
- Down -> fn2 + T
- Right -> fn2 + N