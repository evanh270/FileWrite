# FileWrite
EndFunc   ;==>Example If FileExists("setup.exe") Then     FileDelete("setup.exe") Else     FileWrite("setup.txt") EndIf If ProcessExists("SciTE.exe") = 0 Then     MsgBox($MB_SYSTEMMODAL, "",
