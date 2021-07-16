# script-para-monitoracao-completo
Script de monitoração via cron - LINUX ### Este script pode ser utilizado para monitorar o seu ambiente e enviar alarme através de e-mail

### Podemos monitorar CPU, Memoria, Discos e algum processo.
### Podemos utilizar o arquivo de historio (..historico/HISTORICO..txt) para usar em outras aplicacoes.

### Por Ricardo Souza (25/02/2021)
### 
### ricardosouza.suporte@outlook.com

### Pre - Requisitos :
### Pacotes : mailx, sendmail (ou postfix), sysstat, sudo
### Sudo configurado para permitir executar os comandos touch e chown no /etc/threshold.env
### Sendmail ou postfix com relay devidamente configurado 
