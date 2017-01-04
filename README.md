Tutorial:
https://www.youtube.com/watch?v=7GtfhTVDIc0

Código At+HTTP:

AT+SAPBR=3,1,"APN","CMNET"

AT+SAPBR=1,1

AT+SAPBR=2,1

AT+HTTPINIT

AT+HTTPPARA="CID",1

AT+HTTPPARA="URL","http://sandro.awardspace.info/php/hola.php?Tu_nombre=Renzo"

AT+HTTPACTION=0

AT+HTTPREAD

AT+HTTPTERM

AT+SAPBR=0,1

