[![PlayOnGit](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/PlayOnGit2.png)](https://github.com/felipefacundes/dicas/blob/master/PlayOnGit.md)
# PlayOnGit 🕹
##### Conteúdo atualizado em 03/07/2019
#### Inicie seus Jogos direto do menu iniciar, SEM precisar de Playonlinux, Proton ou Lutris, e com um desempenho muito melhor e superior.
###### Criado por Felipe Facundes
###### Grupo do Telegram 切, para pedido de inclusão de novos Jogos: https://t.me/winehq_linux
###### Canal do Telegram 切: https://t.me/PlayOnGit
###### Canal do YouTube: https://www.youtube.com/channel/UCfssKpnkpyUC4sedaZd6N3g
##### Licença: GPLv3

### PRIMEIRO. Aumente a performance com mais +50 de FPS - habilite o Esync. SEGUNDO. Diminua a prioridade de SWAP e REINICIE o PC.
```bash
su -c 'echo -e "* hard nofile 1048576" >> /etc/security/limits.conf'
su -c 'echo -e "vm.swappiness=0" > /etc/sysctl.conf'
reboot
```
### TERCEIRO. Certifique-se que o seu driver Vulkan está habilitado. Para plascas Nvídia, basta instalar o driver proprietário. Para placas RADEON da AMD, siga esse meu tutorial abaixo:
https://amdgpu.github.io/

### QUARTO. Além de estar habilitado, como já relatado acima, igualmente é necessário ter o driver Vulkan instalado. Basta instalar o driver, siga esse meu tutorial abaixo:
https://github.com/felipefacundes/dicas

[![Vamos_aos_Jogos](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/vamos_aos_jogos.gif)](https://github.com/felipefacundes/dicas/blob/master/PlayOnGit.md)
# Vamos aos Jogos:
[![Manual de instalação](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/manual_de_instalac.png)](https://github.com/felipefacundes/dicas/blob/master/instalar.md)
### Já foram postados 34 jogos no PlayOnGit. Pesquise o seu jogo com Ctrl F no seu navegador.
#
### Vortex Online Cloud Games
###### Finalmente jogue Fortnite, PUBG, e muitos outros títulos no Linux.
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![EpicGamesStore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/VortexOnline.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/VortexOnline.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/VortexOnline/drive_c/
xdg-open ~/.jogos/scripts/run/VortexOnline-run.sh
```
#
### Sekiro Shadows Die Twice
#### Com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![EpicGamesStore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/Sekiro.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Sekiro.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/Sekiro/drive_c/
xdg-open ~/.jogos/scripts/run/Sekiro-run.sh
```
#
### Last Day Of June - EpicGamesStore
#### Com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![EpicGamesStore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/LastDayOfJune.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/LastDayOfJune.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/LastDayOfJune/drive_c/
xdg-open ~/.jogos/scripts/run/LastDayOfJune-run.sh
```
#
### City Of Brass - EpicGamesStore
#### Com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![EpicGamesStore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/CityOfBrass.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/EpicGamesStore.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/EpicGamesStore/drive_c/
xdg-open ~/.jogos/scripts/run/EpicGamesStore-run.sh
```
#
### EpicGamesStore - lançamento em 24-06-2019
#### Com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![EpicGamesStore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/EpicGamesStore.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/EpicGamesStore.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/EpicGamesStore/drive_c/
xdg-open ~/.jogos/scripts/run/EpicGamesStore-run.sh
```
#
### GTA V 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
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
### Devil May Cry 5 (2019) 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC5](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/dmc5.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/dmc5.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/dmc5/drive_c/
xdg-open ~/.jogos/scripts/run/dmc5-run.sh
```
#
### Rocket League
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Rocket League](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/RocketLeague.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/RocketLeague.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/RocketLeague/drive_c/
xdg-open ~/.jogos/scripts/run/RocketLeague-run.sh
```
#
### Borderlands: The Pre-Sequel
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Borderlands: The Pre-Sequel](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/Borderlands.The.Pre.Sequel.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Borderlands.The.Pre.Sequel.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/Borderlands.The.Pre.Sequel/drive_c/
xdg-open ~/.jogos/scripts/run/Borderlands.The.Pre.Sequel-run.sh
```
#
### Devil May Cry (2013) 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC2013](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/dmc-2013.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/dmc-2013.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/dmc-2013/drive_c/
xdg-open ~/.jogos/scripts/run/dmc-2013-run.sh
```
#
### GOG Galaxy (GOG Store) a loja da GOG 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC5](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/goggalaxy.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/goggalaxy.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/goggalaxy/drive_c/
xdg-open ~/.jogos/scripts/run/goggalaxy-run.sh
```
#
### F1 2016 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Steam](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/F1-2016.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/steam.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/F1-2016/drive_c/
xdg-open ~/.jogos/scripts/run/F1-2016-run.sh
```
#
### Grid 2 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![SASRT](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/grid2.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/grid2.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/grid2/drive_c/
xdg-open ~/.jogos/scripts/run/grid2-run.sh
```
#
### Kabounce
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![SASRT](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/Kabounce.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Kabounce.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/Kabounce/drive_c/
xdg-open ~/.jogos/scripts/run/Kabounce-run.sh
```
#
### Sonic All Star Racing Transformed 
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![SASRT](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/SASRT.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/SASRT.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/SASRT/drive_c/
xdg-open ~/.jogos/scripts/run/SASRT-run.sh
```
#
### Warframe 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/warframe.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/warframe.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/warframe/drive_c/
xdg-open ~/.jogos/scripts/run/warframe-run.sh
```
#
### Eve Online 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/eve-online.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/eve-online.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/eve-online/drive_c/
xdg-open ~/.jogos/scripts/run/eve-online-run.sh
```
#
### Teste BETA (não funciona corretamente ainda) - Creative Destruction Battle Royale 
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/creativedestruction.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/creativedestruction.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/creativedestruction/drive_c/
xdg-open ~/.jogos/scripts/run/creativedestruction-run.sh
```
#
### LoL - League of Legends 
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![TDKC](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/LoL.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/LoL.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.wine-appimage-lol/drive_c
xdg-open ~/.jogos/scripts/run/LoL-run.sh
```
#
### A Tribute a Donkey Kong Country  
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![TDKC](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/TDKC.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/TDKC.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/TDKC/drive_c/
xdg-open ~/.jogos/scripts/run/TDKC-run.sh
```
#
### Steam Windows para Jogos do Windows via Steam 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Steam](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/steam.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/steam.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/steam/drive_c/
xdg-open ~/.jogos/scripts/run/steam-run.sh
```
#
### Sonic The Hedgehog 4 - Episode 2 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Sonic The H4 E2](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/sonicthehedgehog4.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/sth4e2.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/sth4e2/drive_c/
xdg-open ~/.jogos/scripts/run/sth4e2-run.sh
```
#
### Spore (controle a evolução de uma espécie) 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Spore](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/spore.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/spore.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/spore/drive_c/
xdg-open ~/.jogos/scripts/run/spore-run.sh
```
#
### GTA SA 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Minecraft](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/gtasamta.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/gtasamta.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/gtasamta/drive_c/
xdg-open ~/.jogos/scripts/run/gtasamta-run.sh
```
#
### FlatOut 2 com GameRanger 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Minecraft](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/flatout2.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/flatout2.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/flatout2/drive_c/
xdg-open ~/.jogos/scripts/run/flatout2-run.sh
```
#
### Minecraft Windows 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Minecraft](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/minecraft.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
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
### Teste BETA (não funciona corretamente ainda) do Origin 
#### Com suporte a DXVK - Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Origin](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/Origin.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/Origin.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/Origin/drive_c/
xdg-open ~/.jogos/scripts/run/Origin-run.sh
```
#
### The Sims 4 OFFLINE 
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![TheSims4](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/TheSims4.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instale manualmente, mas antes altere o caminho do instalador do Jogo:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/TheSims4.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/TheSims4/drive_c/
xdg-open ~/.jogos/scripts/run/TheSims4-run.sh
```
#
### Age Of Empires III - Rev. 26/06/2019
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Age Of Empires III](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/ageofempires3.gif)](https://www.youtube.com/watch?v=Di8j04UFY4c)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/ageofempiresIII.sh)`
###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/ageofempiresIII/drive_c/
xdg-open ~/.jogos/scripts/run/ageofempiresIII-run.sh
```
#
### Open Sonic 
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/opensonic.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/opensonic.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/opensonic/drive_c/
xdg-open ~/.jogos/scripts/run/opensonic-run.sh
```
#
### Victoria II
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/VictoriaII.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/VictoriaII.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/VictoriaII/drive_c/
xdg-open ~/.jogos/scripts/run/VictoriaII-run.sh
```
#
### PCSX2 - Emulador de PlayStation 2
#### Com suporte a DXVK - Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Warframe](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/PCSX2.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/PCSX2.sh)`

###### Opcional para quem quiser fazer alterações:
```bash
xdg-open ~/.jogos/wineprefixes/PCSX2/drive_c/
xdg-open ~/.jogos/scripts/run/PCSX2-run.sh
```
# Vamos aos Softwares de Windows no Linux:
###### Em construção...

# Vamos aos Jogos Nativos:
### Tibia 
#### Veja primeiro o tutorial no Youtube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![Tibia](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/tibia.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Instalar automaticamente:
`bash <(curl -s https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/nativos/tibia.sh)`
#
### Albion Online MMORPG de fantasia medieval 
#### Veja primeiro o tutorial no YouTube:
###### Clique na figura ▼↓abaixo↓▼ para acessar o tutorial do YouTube:
[![DMC5](https://raw.githubusercontent.com/felipefacundes/desktop/master/wine-jogos/imagens/albion.gif)](https://github.com/felipefacundes/dicas/blob/master/TutoConstruction.md)
##### Dependências necessárias:
`flatpak sld sld2 qt5-webengine sndio`
##### Instale via flatpak:
```
flatpak install flathub com.albiononline.AlbionOnline

flatpak run com.albiononline.AlbionOnline
```

