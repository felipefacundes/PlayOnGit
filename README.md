# PlayOnGit 🕹
##### Conteúdo atualizado em 07/06/2019
#### Inicie seus Jogos direto do menu iniciar, sem precisar de PlayOnLinux, Proton ou Lutris, e com um desempenho muito melhor e superior.
###### Criado por Felipe Facundes
###### Grupo do 切 Telegram 切, para pedido de inclusão de novos Jogos: https://t.me/winehq_linux
###### Canal do 切 Telegram 切: https://t.me/PlayOnGit
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
### QUARTO. Além de estar habilitado, como já relatado acima, igualmente é necessário ter o driver Vulkan instalado. Basta instalar o driver, siga esse meu tutorial abaixo:
https://github.com/felipefacundes/dicas
#
# Vamos aos Jogos:

### GTA V - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![GTA V](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/gtav.gif)](https://youtu.be/Lako69C_sw4)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/GTAV.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/GTAV/drive_c/
xdg-open ~/.jogos/scripts/run/GTAV-run.sh
```
#
### Devil May Cry 5 (2019)- com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC5](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/dmc5.gif)](https://youtu.be/Lako69C_sw4)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/dmc5.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/dmc5/drive_c/
xdg-open ~/.jogos/scripts/run/dmc5-run.sh
```
#
### Devil May Cry (2013) - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC2013](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/dmc-2013.gif)](https://youtu.be/Lako69C_sw4)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/dmc-2013.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/dmc-2013/drive_c/
xdg-open ~/.jogos/scripts/run/dmc-2013-run.sh
```
#
### Warframe - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/warframe.gif)](https://telegra.ph/PlayOnGit-05-2)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/warframe.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/warframe/drive_c/
xdg-open ~/.jogos/scripts/run/warframe-run.sh
```
#
### The Sims 4 OFFLINE - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![TheSims4](https://i1.ytimg.com/vi/7wr91-wgNfU/hqdefault.jpg)](https://telegra.ph/PlayOnGit-05-2)
##### Instale manualmente, mas antes altere o caminho do instalador do Jogo:
`wget https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/TheSims4.sh`
##### Veja o vídeo, caso queira alterar o caminho do instalador do jogo: `xdg-open TheSims4.sh`
```bash
bash TheSims4.sh
```
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/TheSims4/drive_c/
xdg-open ~/.jogos/scripts/run/TheSims4-run.sh
```
#
### A Tribute a Donkey Kong Country  - com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![TDKC](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/TDKC.gif)](https://telegra.ph/PlayOnGit-05-2)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/TDKC.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/TDKC/drive_c/
xdg-open ~/.jogos/scripts/run/TDKC-run.sh
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
### GTA SA - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Minecraft](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/gtasamta.gif)](https://telegra.ph/PlayOnGit-05-28)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/gtasamta.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/gtasamta/drive_c/
xdg-open ~/.jogos/scripts/run/gtasamta-run.sh
```
#
### Minecraft Windows - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Minecraft](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/Minecraft-480.png)](https://telegra.ph/PlayOnGit-05-28)
##### Dependências:
`Para rodar esse jogo você precisará do jre8-openjdk (OpenJDK 1.8) e java-openjfx`
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/nativos/minecraft.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/nativos/minecraft/
xdg-open ~/.jogos/scripts/run/minecraft-run.sh
```
#
### Teste BETA do Origin - com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Origin](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/origens.jpg)](https://telegra.ph/PlayOnGit-05-28)
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
### Tibia - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Tibia](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/tibia.jpg)](https://telegra.ph/PlayOnGit-05-28)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/nativos/tibia.sh)`
#
### Albion Online MMORPG de fantasia medieval - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC5](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/albion.gif)](https://youtu.be/Lako69C_sw4)
##### Dependências necessárias:
`flatpak sld sld2 qt5-webengine sndio`
##### Instale via flatpak:
```
flatpak install flathub com.albiononline.AlbionOnline

flatpak run com.albiononline.AlbionOnline
```

