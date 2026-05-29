# slopfest

This is a repository for SillyTavern regex. Here you can find a single .json file with all kinds of patterns that LLMs generate way too often. Feel free to contribute if you want to add a pattern you see often or fix an existing one.

### How does it work?

Like this:

<img width="499" height="763" alt="image" src="https://github.com/user-attachments/assets/7cc25102-217d-426f-a5fd-bf04dd1d2b7e" />

### Does it help?

It does. But, treat regex as a secondary clean-up tool.

If you use only regex, you allow the model to generate slop. Then you cut it. So you have wasted tokens on generating slop... and then removed it. That shortens the response, lowers its quality, and regex editing can mess up sentences in edge cases.

For better results, you should have an anti-slop prompt that asks the AI to never use certain words to begin with. Do not use contrast negations, do not write "question hung in the air". Depending on the model, that helps a lot, or at least a little.

However, the AI will absolutely ignore your preset at some point, driving you insane. That's what this regex editing is for.

### How to install?

1. Download the .json from here.

2. SillyTavern --> Extensions --> Regex --> Import (global or for a preset, you choose)

3. Done.

### What's in there?

Asterisk remover *

-Those

-Just stay

Ozone remover

Firmirin

They didn't pull away.

Didn't pull away.

They didn't notice.

Breath hitched

Silence stretched

Oh. Oh, that's...

X was Y-ing. X knew X was Y-ing.

and something uniquely *him/her/their*

Buddy. Pal.

Instead,

X didn't fix it. (!!! MESSY ONE !!!)

Traitor that it was

their X came out Y-er than intended.

"X," they repeated.

They didn't X. Didn't Y. Just Z...

They didn't X. Didn't Y or Z. Just...

Not X. Not Y. Just… Z.

not X, not Y. Just... Z.

—not X, not Y, just... Z

—not X, just... Y.

—not in X, but in Y

question hung

X, rather than Y. (!!! MESSY ONE !!!)

Filing that away

It's not nothing

Nightbird

Somewhere a door X-ed

Mouth opened. Closed. Opened again.
