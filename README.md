# htgo-tts
[https://github.com/MarlikAlmighty/htgo-tts/](https://github.com/MarlikAlmighty/htgo-tts/)

### Requirement:
- mplayer (optional)

### Install
```
go get "github.com/MarlikAlmighty/htgo-tts"
```

### Update
```
go get -u "github.com/MarlikAlmighty/htgo-tts"
```

### Remove
```
go clean -i "github.com/MarlikAlmighty/htgo-tts"
```

### Import
```go
import "github.com/MarlikAlmighty/htgo-tts"
```

### Use
```go
speech := htgotts.Speech{Folder: "audio", Language: "en"}
speech.Speak("Your sentence.")
```

### Use with Handlers
```go
import (
    hs "ggithub.com/MarlikAlmighty/htgo-tts"
)

speech := hs.Speech{Folder: "audio", Language: "en", Handler: &handlers.MPlayer{}}
speech.Speak("Your sentence.")
```

Have Fun!