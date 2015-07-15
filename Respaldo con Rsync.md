# Documentacion de Comandos en Linux

## Backup usando Rsync

<code>

*Localmente*
rsync -avhr directorioOrigen  directorioDestino

*Remotamente*

rsync -avhr directorioOrigen  usuario@ipdelServidor:/directorioDestino
</code>

##Conexion Remota usando SSH

Es necesario instalar el cliente SSH usando el siguiente comando:

<code>
sudo apt-get install openssh-server
</code>
