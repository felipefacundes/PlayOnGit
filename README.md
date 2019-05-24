# PlayOnGit
###### Criado por Felipe Facundes
###### Grupo do Telegram: https://t.me/winehq_linux
###### Canal do Telegram: https://t.me/comandos_linux
##### Licença: GPLv3

### PRIMEIRO. Aumente a performance com mais +50 de FPS - habilite o Esync.
### SEGUNDO. Diminua a prioridade de SWAP e REINICIE o PC.
```bash
su -c 'echo -e "* hard nofile 1048576" >> /etc/security/limits.conf'
su -c 'echo -e "vm.swappiness=0" > /etc/sysctl.conf'
reboot
```
#
# Vamos aos Jogos:

##### Local dos scripts de jogos:

https://github.com/felipefacundes/desktop/tree/master/wine-jogos/

### GTA V - Veja primeiro o tutorial no youtube:

```bash
wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/GTAV.sh
bash GTAV.sh
```
### Age Of Empires III - Veja primeiro o tutorial no youtube:

```bash
wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/ageofempiresIII.sh
bash ageofempiresIII.sh
```
[![Age Of Empires III](https://i.ytimg.com/vi/Di8j04UFY4c/hqdefault.jpg)](https://www.youtube.com/watch?v=Di8j04UFY4c)
