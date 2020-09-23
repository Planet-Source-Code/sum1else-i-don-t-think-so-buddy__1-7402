<div align="center">

## I Don't Think So Buddy\!


</div>

### Description

Keeps the form the same size no matter what, while your form can still look good with the MIN/MAX buttons....Makes a cool effect when those buttons are Pressed
 
### More Info
 
Make:

A form called         Form1

2 text box called    H  and  W

A timer called        timer1

Leave all defaults


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sum1Else](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sum1else.md)
**Level**          |Advanced
**User Rating**    |4.0 (12 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sum1else-i-don-t-think-so-buddy__1-7402/archive/master.zip)





### Source Code

```
Private Sub Form_Load()
Form1.WindowState = vbDefault
Timer1.Enabled = True
Timer1.Interval = 1
H.Visible = False
W.Visible = False
H.Text = Form1.Height
W.Text = Form1.Width
End Sub
Private Sub Timer1_Timer()
If Form1.WindowState = vbMaximized Or Form1.WindowState = vbMinimized Then
 Form1.WindowState = vbDefault
  Else
  Form1.Height = H
  Form1.Width = W
End If
End Sub
```

