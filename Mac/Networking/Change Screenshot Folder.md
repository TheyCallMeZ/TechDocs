## Change the folder in which screenshots are saved to

Ensure that the folder exists before running these commands  
This will put screenshots in the Pictures folder of the logged in user's home directory  
```  
defaults write com.apple.screencapture location ~/Pictures/Screenshots  
killall SystemUIServer  
```

To revert the change back to the system default  
```  
defaults delete com.apple.screencapture location  
killall SystemUIServer  
```
