# mpdstate

The mpdstate is the current playlist and the location in the song.  
I made this because it was hard switching from listening to songs  
to listening to podcasts. This tool allows me to save my places 
in multiple podcasts and resume them exactly where I stopped.  

## Save
use `mpds sv NAME` to save the current mpdstate
  
  
## Load
use `mpds ls NAME` to load the saved mpdstate 'NAME'  
  
  
## Remove
use `mpds rm NAME` to delete the saved mpdstate 'NAME'
  
  
## List  
use `mpds ls` to list all saved mpdstates


## Rename
use `mpds mv NAME1 NAME2` to rename saved mpdstate NAME1
to NAME2.


### Notes  
saved states are stored in .local/share/mpdstates    
this is not very developed, submit a bug if you find one.  
it has to stop mpd and then start it again to get and load mpdstates, so you will hear a little blip.  
when you load an old playlist it automatically saves the current one as 'old'  
if you try to rename an mpdstate to a name that already exists it will tell you and exit without doing it.

## Install
```
sudo mv mpds /bin
```
