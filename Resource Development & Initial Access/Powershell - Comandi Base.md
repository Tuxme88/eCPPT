## Tags
1. Tecniche
	1. #powersehell #enum
2. Ambiente
	1. #windows
## Comandi usati

Solo quelli eseguiti realmente.

```
1. powershell.exe -ExecutionPolicy Bypass cmd.exe
	   Bypassa ogni policy sul sistema
	   
2. powershell.exe -WindowStyle Hidden calc.exe
	   Nasconde la finestra powershell
	   
3. powershell.exe -Command Get-Process
	   processi attivi
	   
4. powershell.exe -Command "& { Get-EventLog -LogName security }"
	   Cerca negli event log security
	   
5. Get-Command -Name *Firewall*
	   come grep su linux
```


