# Fonts-stack

Hey guys,

So given that over time we keep creating web based applications for CcHUB, there's need to unify the experience across different offerings. Our font-stack is just one way we are doing that.

What does this mean? well it means your next project begins here.

## What are the fonts
Well, we decided to go with [**Poppins**](https://fonts.google.com/specimen/Poppins) for our headers and [**Rubik**](https://fonts.google.com/specimen/Rubik) for normal text. 

Poppins is only available in `700` weight
Rubik is only available in `300` & `400`.


##To Get Started
Simply add the code below in the head of your HTML 

    <link rel="stylesheet" href="http://fonts.cchub.xyz/fonts.css" integrity="sha384-Q2pxT853PmKAFxZjo1IJRG7w7uhXPlHpr6v1QilQR7eTbwpzhUleXhsHB1bY1TVR" crossorigin="anonymous">

Then in your stylsheet, you can specify it in your stylesheet as: 
`font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Rubik", sans-serif;`
`font-family: 'Poppins', sans-serif;`

##Why? Just Why?


##Things to note
Rubik is a fall back font for -apple-system (Mac) & Segoe UI (Windows) in cases where they are not available. So your font declaration shoul:
`font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Rubik", sans-serif;`

System fonts for Ubuntu & Debian didn't play well with the rest so we switch the font to Rubik if we're rendering on any of those OSs.

If you're curious about system fonts, the guys at [**CSS Tricks**](https://css-tricks.com/snippets/css/system-font-stack/) did the topic justice.

Know how we can improve this process? Let's talk.

Daz All!
