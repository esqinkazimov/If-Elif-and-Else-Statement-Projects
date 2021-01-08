The following table lists an octave of music notes, beginning with middle C, along
with their frequencies.

Note    Frequency (Hz)

C4-261.63

D4-293.66

E4-329.63

F4-349.23

G4-392.00

A4-440.00

B4-493.88

The program reads the name of a note from the user and
displays the note’s frequency.The program supports all of the notes listed
previously.
Once program worked correctly for the notes listed previously, I
added support for all of the notes from C0 to C8. While this could be done by
adding many additional cases to your if statement, such a solution is cumbersome,
inelegant and unacceptable for the purposes of this project. Instead, I
exploited the relationship between notes in adjacent octaves. In particular, the frequency
of any note in octave n is half the frequency of the corresponding note in octave n+1.
By using this relationship, I was able to add support for the additional notes
without adding additional cases to my if statement.
