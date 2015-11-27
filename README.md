# 21co-tunes
Buy tracks from a BTC payable API endpoint

## Track Definition
21co-tunes need to be easily accessible via an API endpoint either by track name, album name, or artist name. 

### Track lookup
Tracks will be stored in a merkle tree structure defined as such
```
               / Track 1
        Album 1- Track ...
       /       \ Track n
Artist
       \      / Track 1
       Album n- Track ...
              \ Track n
              
```
### Track naming
A track naming standard like this may already exist...I didn't feel like Googling it

```<Artist Name> + ' ' + '-' + ' ' + <Album Name> + ' ' + '-' + ' ' + <Track Number> + ' ' + <Track name> + <File Extension>```

Ex: ```Jay Gupta Music - Welcome-To-LUTDs - 07 Touch The Screen.mp3```
