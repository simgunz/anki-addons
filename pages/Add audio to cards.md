title: Add audio to cards
id: addaudiocard
type: subpage
ankiweb_id: 3100585138
parent: Download audio

Without a bit of set-up, audio may be downloaded but not played during
review. For that the audio field has to be added to a card template.


## Template editor

<figure>
<img src="images/card_types.png" alt="Window with tabs reading Forward
Reverse Example at the top. The left of the main area is split in
three parts, Front template, Styling and Back template. The right is
split in two: Front preview and Back preview.">
<figcaption>The card template editor for a moderately complex note type.</figcaption>
</figure>
To get the template editor, start reviewing. Then click the “Edit”
button at the bottom left. In the “Edit Current” window click “Cards...”


### Adding fields

Once you have the template editor open, the hardest thing is to decide
when to play the audio. Should it be played along with the question?
or only with the answer?

When there is more than one tab above the “Front Template” editor, you
have to decide to which card you want to add the audio. Add it to
only one or to all, as you see fit.


To add the audio to the question, add `{{Audio}}`, with a double pair
of curly braces, to the top left “Front Template” editor. To add it to
the answer, type it into the bottom left “Back Template” editor.

When you had to pick a different field name when you
[added the field](Add%20audio%20field.html) to the note, use that name
inside the braces.

While typing in, the text on the right should be visible on the right,
too. When the whole field, with the curly braces, has been entered, it
should disappear. When `Unknown field NN` appears on the right,
compare the spelling with the list in the “Edit Current” window.