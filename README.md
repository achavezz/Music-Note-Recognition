# Music-Note-Recognition

We want to see if it was possible, given a music sheet if a performer can play the
correctly listed notes or how well can they harmonize with their own notes. One of the
challenges was determining how can a program read a music score file or audio file to
determine what notes are being played. We first started to build a Markov chain to first define
our initial distribution and the transition matrix. Then we need to be able to implement a
method to create midi templates for the notes being played. Afterwards, we can calculate the
likelihoods of all the notes to give the best estimate on what the note is and provide
functionality to convert and xml file to a stream. Running the second to last block asks the user
for input on the information they wish to validate. First, the user provides what the original
score is, and xml file what we called “test.xml”. Second, the user determines what file they are
wanting to check, either an xml file “1” or an audio file “2”. Our provided test cases were Test
1.xml, Test 2.xml, and Test audio.wav. Lastly, the last block, displays the results of what the
original score was, the notes from the score the user wanted to check, and their respective
intervals.