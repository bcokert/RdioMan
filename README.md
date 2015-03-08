# RdioMan
An Rdio app that will download all your favorites to your mobile device

# Install
## OSX/Linux
- cd projects
- git clone git@github.com:bcokert/RdioMan.git
- sudo pip install oauth2

## Windows
- TBD

# How to use
## OSX/Linux
- cd RdioMan
- python
```
>>> import rdio
>>> # Copy the url into the browser, login, then enter the given code into the terminal
>>> alreadyDownloaded = rdio.getSynced() # array
>>> favorites = rdio.getFavorites() # array
>>> rdio.addToSynced(['uafsjkhad', 'aksdfhads']) # add songs with the given keys, returns bool
>>> # Feck, added the wrong ones
>>> rdio.clearSynced() # returns bool
>>> # I don't want to copy paste all my favorites...
>>> rdio.addFavoritesToSynced() # returns bool
>>> # Yay! But I just added a bunch of songs online...
>>> rdio.syncFavorites() # clear favs, then re-sync with favs
>>> # Yay! Now I can go for a run
>>> rdio.burn1000Calories() # Just kidding
```
## Windows
- TBD
