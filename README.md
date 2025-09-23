```
apt install -y git apt-utils mc
git clone https://github.com/triuk/killinuxfloor.git
cd killinuxfloor
./install.sh
```

```
firewall-cmd --add-port=8080/tcp --permanent
```

```
klf stop && klf update && klf config && klf start
```

```
Survival:
?Difficulty=3?GameLength=1?Mutator=UnofficialKFPatch.UKFPMutator?MaxPlayers=20?LoadFHUD=1?LoadYAS=1?BroadcastPickups=1?DropAllWepsOnDeath=1?AllowDamagePopups=1?UseEnhancedTraderMenu=1?AllowGamemodeVotes=1?DisableMapRanking=1?MaxMonsters=100

Endless:
?Difficulty=3?Mutator=UnofficialKFPatch.UKFPMutator?MaxPlayers=20?LoadFHUD=1?LoadYAS=1?BroadcastPickups=1?DropAllWepsOnDeath=1?AllowDamagePopups=1?UseEnhancedTraderMenu=1?AllowGamemodeVotes=1?DisableMapRanking=1?MaxMonsters=100

Game Difficulty: 0 = Normal, 1 = Hard, 2 = Suicidal, 3 = Hell on Earth Game
Length: 0 = Short, 1 = Medium, 2 = Long
```

```
Setbind N "TossMoney | TossMoney | TossMoney | TossMoney"
```
