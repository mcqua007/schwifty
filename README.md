## Schwifty

This is **Schwifty One Dark** a syntax theme based on Atom One Dark. A few differences besides the colors is the addition of italics for certain tokens(i.e. HTML classes, functions, etc...). This helps for reading your code and being able to recognize patterns so you can find things quickly. There are also matching bracket colors to add to your settings so you can easily identify matching brackets and parenthesis. To get full use of italics I added some fonts that would suit you as well as baked them with Firacode ligatures so you get clean fonts and ligatures to have the best-looking syntax. Get Schwifty!

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Schwifty` - find the one by **decrypteddesign** - there is one other so make sure you have the right one!
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. Code > Preferences > Color Theme > **Schwifty**
6. Optional: Use the recommended settings below for best experience

## Screenshots

**Main Theme**
![ScreenShot](/images/regular-close.png)

**Puple Variant**
![ScreenShot](/images/purple-close-matching.png)


### Schwifty Main Theme ###
![ScreenShot](/images/import.png)


#### With [matching brackets](#setup-matching-brackets) ####

![ScreenShot](/images/regular-long.png)

![ScreenShot](/images/promises.png)

 ## Schwifty Purple (Variant) ##

 Below is an image of the variant I created of the orginal Schwifty. You can switch to this variant if you follwo the direction above but select *Schwifty Purple Dark Theme*

 ![Purple](/images/purple-long-matching.png)
 
 #### Shown with php ####

 ![Purple php](/images/purple-variant-php-code-2.jpg)

 #### Components styled when [Vetur Extension](https://marketplace.visualstudio.com/items?itemName=octref.vetur) installed ####

 ![Purple Vetur Component Style](/images/vue-vetur-screenshot.jpg)

## Setup Matching Brackets

Use the VS code Extenstion 'Bracket Pair Colorizer 2', for matching your brackets. 
Then paste this in your `settings.json` to have the colors match the Schwifty Theme:

`"bracket-pair-colorizer-2.colors": ["#f9a571","#56cbf9", "#9ba2ff"]`

For Purple variant: `"bracket-pair-colorizer-2.colors": [ "#F86AA3", "#56cbf9", "#9ba2ff" ],`

Then save, and restart VS code to get matching brackets like above.


## What Font am I using ?

 
 I am currenlty using [Dank Mono](https://dank.sh/) patched w/ [Fira Code's](https://github.com/tonsky/FiraCode) Ligatures. I patched these two together with [Ligaturizer](https://github.com/ToxicFrog/Ligaturizer). Below I have listed some alternatives to the above font and some other cool coding fonts.

 - **Paid Alternatives** (_*I am not affilated with any of the above fonts or companies._ )
    1. [Operator Mono](https://www.typography.com/fonts/operator/styles/operatormono) is another great font (though expensive) that you can expand with [Fira Code's](https://github.com/tonsky/FiraCode) ligatures using the tool above or I used [operator-mono-lig](https://github.com/kiliman/operator-mono-lig). 
 
    2. [Cartograph](https://connary.com/cartograph.html) is another decent font. I found a site that sells single variants of it [here](https://www.myfonts.com/fonts/connary-fagen/cartograph-cf/).
 
      
 
 - **Free Alternatives**
   1. [Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) has a italics variant. 
   2. [Ubunut Mono](https://fonts.google.com/specimen/Ubuntu+Mono) has a italics variant.
   3. [Victor Mono](https://rubjo.github.io/victor-mono/) - has italics-script variant & has it's own ligatures.
   4. [Fira Code](https://github.com/tonsky/FiraCode) has no italics version. Below Fira Code is mixed with italics-script fonts
        -  Fira Code with [Pacifco](https://github.com/kosimst/Firicico). 
        -  Fire Code with [FlottFlott](https://github.com/kosimst/FiraFlott)  

 - **Combined w/ Fira Code Ligatures**: I decided to bake Victor Mono, Plex Mono, and Ubuntu Mono with Fira Code Ligatures for all of you.
      1. [Plex Mono Liga](https://github.com/mcqua007/schwifty/tree/master/coding-fonts/Plex-Mono-Liga(FIra%20Code%20Ligatures))
      2. [Ubuntu Mono Liga](https://github.com/mcqua007/schwifty/tree/master/coding-fonts/Ubuntu-Mono-Liga(Fira%20Code%20Ligatures))
      3. [Victor Mono Liga](https://github.com/mcqua007/schwifty/tree/master/coding-fonts/Victor-Mono-Liga(Fira%20Code%20Ligatures)) - **My Favorite of the 3**
      
 #### This guy gets it ####

![ScreenShot](/images/rick-gets-schwifty.jpg)
