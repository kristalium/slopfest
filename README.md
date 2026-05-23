# slopfest

This is a repository for SillyTavern regex. Here you can find a single .json file with all kinds of patterns that LLMs generate way too often. Feel free to contribute if you want to add a pattern you see often or fix an existing one.

### How does it work?

Like this:

<img width="499" height="763" alt="image" src="https://github.com/user-attachments/assets/7cc25102-217d-426f-a5fd-bf04dd1d2b7e" />

### Does it help?

It does. But treat regex as a *secondary* clean-up tool.

If you use only regex, you allow the model to generate slop. Then you cut it. So you have wasted tokens on slop and then removed it. That shortens the response, lowers its quality, and can mess up a sentence in edge cases.

For better results, you should have an anti-slop prompt that asks the AI to never use certain words to begin with. Depending on the model, that helps a lot, or at least a little.

However, the AI will absolutely ignore your preset at some point, driving you insane. That's what the regex is for.

### How to install?

1. Download the .json from here.

2. SillyTavern --> Extensions --> Regex --> Import (global or for a preset, you choose)

3. Done.
