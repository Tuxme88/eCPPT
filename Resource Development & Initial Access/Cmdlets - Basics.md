
## Tags
1. Tecniche
	1.  #postexploitation  #powersehell
2. Ambiente
	1. #windows
3. Contesto


## Comandi usati
Solo quelli eseguiti realmente.

```
1. Get-Process chrome, firefox | Sort-Object -Unique | Format-List Path
	   Prende il processo, chiede solo un processo (unico), vuole solo il percorso
	   
2. Get-WmiObject -class win32_operatingsystem | select -Property *
	   Prende dal WMI le informazioni, vuole solo le proprietà di sistema
	   
3. Get-Service "s*" | Sort-Object Status -Descending
	   Prende tutti i servizi che ci sono che iniziano con "s*", gli ordina per lo stato
```
