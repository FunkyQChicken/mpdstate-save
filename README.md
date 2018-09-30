# mpdstate

The mpdstate is the current playlist and the location in the song.  
I made this because it was hard switching from listening to songs  
to listening to podcasts. This tool allows me to save my places 
in multiple podcasts and resume them exactly where I stopped.  

## Save
use `mpdstate sa NAME` to save the current mpdstate
  
  
## Load
use `mpdstate lo NAME` to load the saved mpdstate 'NAME'  
  
  
## Delete
use `mpdstate de NAME` to delete the saved mpdstate 'NAME'
  
  
## List  
use `mpdstate li` to list all saved mpdstates
  
  
### Notes  
saved states are stored in .local/share/mpdstates    
this is not very developed, submit a bug if you find one.  
it has to stop mpd and then start it again to get and load mpdstates, so you will hear a little blip.  
when you load an old playlist it automatically saves the current one as 'old'

## Install
```
sudo mv mpdstate /bin
```
