<div align="center">

## EASIEST way to have scrolling marquee text\!


</div>

### Description

This is the EASIEST way to have scrolling marquee text in a label.

'No long useless code.
 
### More Info
 
Create a timer called 'Timer1' (with an interval of 1) and a label called 'Label1'


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Crash404](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/crash404.md)
**Level**          |Unknown
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/crash404-easiest-way-to-have-scrolling-marquee-text__1-4343/archive/master.zip)





### Source Code

```
Private Sub Timer1_Timer()
 If Label1.Left < -1000 Then
 Label1.Left = 7000
Else
 Label1.Left = Val(Label1.Left) - 40
End If
End Sub
```

