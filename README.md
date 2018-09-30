# mpdstate

The mpdstate is the current playlist and the location in the song.  
I made this because it was hard switching from listening to songs  
to listening to podcasts. This tool allows me to save my places 
in multiple podcasts and resume them exactly where I stopped.  

## Save
use `mpds sa NAME` to save the current mpdstate
  
  
## Load
use `mpds lo NAME` to load the saved mpdstate 'NAME'  
  
  
## Delete
use `mpds de NAME` to delete the saved mpdstate 'NAME'
  
  
## List  
use `mpds li` to list all saved mpdstates
  
  
### Notes  
saved states are stored in .local/share/mpdstates    
this is not very developed, submit a bug if you find one.  
it has to stop mpd and then start it again to get and load mpdstates, so you will hear a little blip.  
when you load an old playlist it automatically saves the current one as 'old'

## Install
```
sudo mv mpds /bin
```
