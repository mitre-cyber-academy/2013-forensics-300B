Name: Blunt Force Duck Trauma

Description: It's story time at the CTF. There's even a pretty picture to
go along with it? What do a picture of a duck and a narrated story have
to do with each other? There couldn't be a hidden meaning behind it...

How to solve: First, install the program steghide. Next, extract the sequence
of files in the dino_duck.jpg image. Inside that will be a stegosaurus image.
Inside there will be a file containing the following text:

dinosaurs_rock

which is the passphrase to extract data from the .wav file. Inside the .wav
file is a sequence of archives, named `flag,' which contain an image of 
the flag at the bottom. Creative use of the `file' and `mv' commands may be
necessary before your preferred archive manager will extract the files.

Contents of Challenge:
dist/challenge.wav - the steghidden audio file
dist/dino_duck.jpg - the steghidden image containing the passphrase

What to Distribute:
dist/challenge-archive.zip

Flag: MCA-DEADFEE7
