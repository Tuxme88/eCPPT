## Tags
1. Tecniche
	1.  #postexploitation  #powersehell
2. Ambiente
	1. #windows
3. Contesto
	1. #network

## Comandi usati
Solo quelli eseguiti realmente.
```

1. .\example.ps1
	1. Call a script
	
2. Powershell PortScanner Script example:
   
C:\> $ports=(81,444) ;$ip="192.168.13.250"; foreach ($port in $ports) {try{$socket=-New-Object Sys
em.Net.Sockets.TcpClient($ip,$port);} catch{}; if ($socket -eq $null) {echo $ip":"$port™ - Closed"
; }else{echo $ip":"$port™ - Open"; $socket = $null;}}
92.168.13.250:81 - Open
92.168.13.250:444 - Open

```

