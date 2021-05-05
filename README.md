# "How to Build a Rock Paper Scissors Game in Vanilla Javascript"

✅ [Check out Dave Gray's YouTube Channel with all of my tutorials](https://www.youtube.com/DaveGrayTeachesCode).

**Description:**

Learn how to build a rock paper scissors game in vanilla javascript. This is next level rock paper scissors! This html, css, and javascript game has responsive design, css animations, persistent data for all time high scores, and accessibility considerations throughout. 

[YouTube Tutorial](https://youtu.be/3zr63z_q3cQ) for this repository.

I suggest completing Dave Gray's [8 hour JavaScript course tutorial video](https://youtu.be/EfAl9bwzVZk) if you are new to Javascript.

**My Modifications**
- Removing `tabindex="0"` from `computerBoard` images which will allow setting focus on them, otherwise the `listenForEnterKey` will trigger the click event on computer images too
- Using `transform: scale(1.1)` instead `width: 110%` on images hover/focus which will prevent the playerBoard height get increased and pushes `computerBoard` down a little
- Remove the hover/focus effect on computer images and make it specific to `.playerBoard .gameboard img`
- Setting `h2` height to the same `font-size` used for it, this will prevent winner message height getting increased a little bit (about 4 pixels) because of the Emoji
- Using `font-size: 3.9rem` instead of `5rem` for `.gameboard__square p` will fix shifting down the `cp_gameboard` when replacing computer images with `1 2 3`

### Academic Honesty

**DO NOT COPY FOR AN ASSIGNMENT** - Avoid plagiargism and adhere to the spirit of this [Academic Honesty Policy](https://www.freecodecamp.org/news/academic-honesty-policy/).
