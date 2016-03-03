# MemoChord

MemoChord is a Max for Live chord trigger effect that doesn't have a built-in selection of generated chords, instead allowing you to assign your own. You can assign and re-assign chords on the fly, entering as many notes as you want. This is useful if you want to make a custom chord set for a performance, or if you're like me and can't play the keyboard as well as you can hit pads on a grid.

**[This video should help to explain what's going on](https://www.youtube.com/watch?v=MohiTdEk5FU)**

There are a few known issues at the moment:

<s>1. You can't save presets. The positions of the knobs and the states of the buttons are saved, but the actual chord assignments disappear when you close your live set or remove the plugin. I'm not yet sure how to save a JavaScript variable to a `.adv` preset file.</s>

1. Fixed! [You can now save presets.](https://github.com/zshall/MemoChord/pull/1)

2. If you have two chords that use the same notes, and you play the second chord while holding the first and then release the first chord, the notes common to each of them will turn off. This is due to how notes are detected as being played. This will be worked on.

3. I've experienced drop-outs and stuck notes when playing many notes very quickly. I can't always reproduce it and it doesn't happen very often, so I'm not yet sure why it is.
