# Can I link cards together?

Anki supports links between cards of a note, but not between unrelated
cards. Imagine you are studying Japanese and aiming to be able to both
recognize and reproduce the Japanese. You may enter the word "ookii",
which means "big", and tell Anki to generate two cards - ookii→big and
big→ookii.

In the above situation Anki can space reviews of those two sibling cards
out so that they don’t appear one after the other.

Some people want to extend this link between arbitrary cards. They want
to be able to tell Anki "after showing me this card, show me that card",
or "don’t show me that card until I know this card well enough". This
might sound like a nice idea in theory, but in practice it is not
practical.

For one, unlike the sibling card case above, you would have to define
all the relations yourself. Entering new notes into Anki would become a
complicated process, as you’d have to search through the rest of the
deck and assign relationships between the old and new material.

Secondly, remember that Anki is using an algorithm to determine when the
optimum time to show you material again is. Adding constraints to card
display that cause cards to display earlier or later than they were
supposed to will make the spaced repetition system less effective,
leading to more work than necessary, or forgotten cards.

The most effective way to use Anki is to make each note you see
independent from other notes. Instead of trying to join similar words
together, you’ll be better off if you can determine the differences
between them. Synonyms are rarely completely interchangeable - they tend
to have nuances attached, and it’s not unusual for a sentence to become
strange if one synonym is replaced with another.

Continuing with the Japanese example earlier, imagine you want to learn
the word "dekai", which also roughly translates to "big", but is a more
colloquial expression. If you still want to review in both directions,
you might make the English prompt of this word "big (more casual)". The
further you progress in your language studies though, the more of a
burden it becomes to define the differences between similar words, which
is why cards asking you to produce a particular word are best left to
the early stage of your studies. With a strong base vocabulary, moving
towards recognition-based study makes more sense, as we all have a much
larger passive vocabulary than our active vocabulary.

As for ensuring that difficult material is introduced after easier
material, a number of existing tools are available. New cards are by
default introduced in the order they are added to the deck, so as long
as the learning materials or sources of information you are using are
adequately graded for your level, material should appear in order of
easiness.
