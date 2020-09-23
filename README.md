<div align="center">

## Mouse Button Swapper


</div>

### Description

swap the mouse buttons with this API.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[LCSBSSRHXXX](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lcsbssrhxxx.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Jokes/ Humor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/jokes-humor__1-40.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lcsbssrhxxx-mouse-button-swapper__1-54102/archive/master.zip)

### API Declarations

```
Private Declare Function SwapMouseButton Lib "user32" (ByVal bSwap As Long) As Long
```


### Source Code

```
Private Declare Function SwapMouseButton Lib "user32" (ByVal bSwap As Long) As Long
Private Sub Form_Load()
DoEvents
  SwapMouseButton 1
DoEvents
  Unload Me
End Sub
```

