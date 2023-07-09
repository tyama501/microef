# microef
Mini game for Basic on the ELKS 
Micro E-Forest

Embeddable Linux Kernel Subset (ELKS)上のBasic向けのサンプルminiゲームです。  
現状ELKSのBasicのグラフィック機能はPC-98向け限定なので  
このminiゲームもPC-9801/PC-9821向けです。  
森でやんちゃなモンスターが暴れています。  
できるだけ少ないターンでモンスターを追い出し森を救いましょう。  
攻撃で木も切れますがターン数が加算されます。

ELKSはIntel IA16アーキテクチャ向けに以下で開発されているLinux-like OSです。  
ELKS is Linux-like OS that has been developed in the repository below.  
https://github.com/jbruchon/elks

This is the mini game for the Basic on the ELKS.  
Save the forest from monsters in minimum turns.  
You can also cut trees by the attack, but extra turns are added.  
It is an example for the Basic.  
It uses graphic fucntios only for PC-98, so this mini game is for PC-9801/PC-9821 for now.  

## Schreenshots
<img src=picture/microef_opening.png width="400pix">
<img src=picture/microef_game_screen.png width="400pix">

## Keys
| Keys | Function |
| ---- | ---- |
| 8 | Move Up |  
| 2 | Move Down |  
| 4 | Move Left |  
| 6 | Move Right |  
| a | Attack toward moving direction<br>or Cut the tree (+10 Turns) |  
| q | Quit |  

## Variables
| Variable | Fuction |  
| ---- | ---- |  
| MAP(20,10) | Map array |  
| MDATA(9) | Character data selector |  
| XINI, YINI | Initial coordinate for graphic |
| TURN | Number of turn |
| DIST | Distance of monsters used when success |
| PX, PY | Player coordicate |  
| PAKX, PAKY | Player Attack coordinate |
| PH | Player Health point |
| EX(4), EY(4) | Monster coordicate |
| EAKX(4), EAKY(4) | Monster Attack coordinate |
| EH(4) | Monster Health point |


