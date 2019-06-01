# PlayOnGit   
#### - Scripts do Wine - para iniciar sem precisar de PlayOnLinux, Proton ou Lutris, inicie direto do menu iniciar com um desempenho muito melhor e superior.
###### Criado por Felipe Facundes
###### Grupo do Telegram: https://t.me/winehq_linux
###### Canal do Telegram: https://t.me/PlayOnGit
###### Canal do YouTube: https://www.youtube.com/channel/UCfssKpnkpyUC4sedaZd6N3g
##### Licença: GPLv3

### PRIMEIRO. Aumente a performance com mais +50 de FPS - habilite o Esync.
### SEGUNDO. Diminua a prioridade de SWAP e REINICIE o PC.
```bash
su -c 'echo -e "* hard nofile 1048576" >> /etc/security/limits.conf'
su -c 'echo -e "vm.swappiness=0" > /etc/sysctl.conf'
reboot
```
### TERCEIRO. Certifique-se que o seu driver Vulkan está habilitado. Para plascas Nvídia, basta instalar o driver proprietário. Para placas RADEON da AMD, siga esse meu tutorial abaixo:
https://github.com/felipefacundes/desktop/tree/master/amdgpu
#
# Vamos aos Jogos:

### GTA V - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![GTA V](https://i.ytimg.com/vi/Lako69C_sw4/hqdefault.jpg)](https://youtu.be/Lako69C_sw4)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/GTAV.sh)`
##### Ou instale manualmente:
`wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/GTAV.sh`
##### Veja o vídeo, caso queira alterar o caminho do instalador do jogo: `xdg-open GTAV.sh`
```bash
bash GTAV.sh
```
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/GTAV/drive_c/ 
xdg-open ~/.jogos/scripts/run/GTAV-run.sh
```
#
### Steam Windows para Jogos do Windows via Steam - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Steam](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/steam.png)](https://telegra.ph/PlayOnGit-05-2)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/steam.sh)`
##### Ou instale manualmente:
`wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/steam.sh`
##### Veja o vídeo, caso queira alterar o caminho do instalador do jogo: `xdg-open steam.sh`
```bash
bash steam.sh
```
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/steam/drive_c/
xdg-open ~/.jogos/scripts/run/steam-run.sh
```
#
### Origin - com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![GTA V](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/origens.jpg)](https://telegra.ph/PlayOnGit-05-28)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Origin.sh)`
##### Ou instale manualmente:
`wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Origin.sh`
##### Veja o vídeo, caso queira alterar o caminho do instalador do jogo: `xdg-open Origin.sh`
```bash
bash Origin.sh
```
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/Origin/drive_c/ 
xdg-open ~/.jogos/scripts/run/Origin-run.sh
```
#
### Age Of Empires III - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Age Of Empires III](https://i.ytimg.com/vi/Di8j04UFY4c/hqdefault.jpg)](https://www.youtube.com/watch?v=Di8j04UFY4c)
```bash
wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/ageofempiresIII.sh
bash ageofempiresIII.sh
```
# Vamos aos Softwares de Windows no Linux:
###### Em construção...
# Vamos aos Jogos Nativos:
###### Em construção...
