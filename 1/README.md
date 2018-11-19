Here we try to understand if we call one shell file(2) from another(1), which are in different directories, then what is current directory of file(2).
My guess is it should be the same as the one for file(2).
No its the place from where test/2.sh is called, which of course makes sense.
