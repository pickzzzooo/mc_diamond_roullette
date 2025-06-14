# mc_diamond_roullette

투네이션 - 마인크래프트 룰렛 / 후원 연동

# 🔧 개발환경
### 서버
arclight-forge-1.20.1-1.0.6 - https://github.com/IzzelAliz/Arclight/releases

### Plugin
skript - 2.11.1 - https://github.com/SkriptLang/Skript/releases<br/>
skrayfall - 1.9.28 - https://dev.bukkit.org/projects/skrayfall/files<br/>

### Mods
pehkui - 1.20.1 - https://www.curseforge.com/minecraft/mc-mods/pehkui<br/>
alex's mob - 1.20.1 - https://www.curseforge.com/minecraft/mc-mods/alexs-mobs<br/>
citadel - 1.20.1 - https://www.curseforge.com/minecraft/mc-mods/citadel<br/>
ITALIAN BRAINROT - 1.20.1 - https://www.curseforge.com/minecraft/mc-mods/italian-brainrot <br/>
GeckoLib - 1.20.0 - https://www.curseforge.com/minecraft/mc-mods/citadel<br/>

# 💾 파일경로
치즈 연동 : .\plugins\chzzk\config.yml<br/>
투네 연동 : .\plugins\MCToon\config.yml<br/>
룰렛 설정 : .plugins\Skript\scripts\mc_diamond_roullette\roullete\config_roullete.sk<br/>

# 📝 명령어
/다이아룰렛 : 스코어보드 시작, 유저 데이터(다이아 갯수, 진행시간) 초기화 <br/>


**/다이아룰렛 을 입력한 뒤에 아래 명령어들이 작동합니다. /다이아룰렛을 입력한 유저만 적용됩니다. 멀티 xxx**<br/>

/목표다이아조정 [<추가/감소/수정>] [<number>]<br/>
/얻은다이아조정 [<추가/감소/수정>] [<number>]<br/>

/몬스터 [<랜덤/소환/수정>] [<값>]<br/>
/몬스터 : 현재 랜덤으로 나오는 몬스터 리스트 조회<br/>
/몬스터 소환 <몬스터> : 해당 몬스터 소환<br/>
/몬스터 수정 <몬스터> : 해당 몬스터 랜덤 리스트 포함/제외<br/>
/몬스터 랜덤 : 랜덤 리스트에 있는 몬스터 랜덤 소환 (확률은 모두 동일)<br/>

/동물 [<랜덤/소환/수정>] [<값>]<br/>
/동물 : 현재 랜덤으로 나오는 동물 리스트 조회<br/>
/동물 소환 <동물> : 해당 동물 소환<br/>
/동물 수정 <동물> : 해당 동물 랜덤 리스트 포함/제외<br/>
/동물 랜덤 : 랜덤 리스트에 있는 동물 랜덤 소환 (확률은 모두 동일)<br/>

/버프 [<랜덤/부여/수정>] [<값>]<br/>
/버프 : 현재 랜덤으로 나오는 버프 리스트 조회<br/>
/버프 부여 <버프> : 해당 버프 부여<br/>
/버프 수정 <버프> : 해당 버프 랜덤 리스트 포함/제외<br/>
/버프 랜덤 : 랜덤 리스트에 있는 버프 랜덤 부여 (확률은 모두 동일)<br/>

/디버프 [<랜덤/부여/수정>] [<값>]<br/>
/디버프 : 현재 랜덤으로 나오는 디버프 리스트 조회<br/>
/디버프 부여 <디버프> : 해당 디버프 부여<br/>
/디버프 수정 <디버프> : 해당 디버프 랜덤 리스트 포함/제외<br/>
/디버프 랜덤 : 랜덤 리스트에 있는 디버프 랜덤 부여 (확률은 모두 동일)<br/>

/음식 [<랜덤/주기/수정>] [<값>]<br/>
/음식 : 현재 랜덤으로 나오는 음식 리스트 조회<br/>
/음식 주기 <음식> : 해당 음식 주기<br/>
/음식 수정 <음식> : 해당 음식 랜덤 리스트 포함/제외<br/>
/음식 랜덤 : 랜덤 리스트에 있는 음식 랜덤 주기 (확률은 모두 동일)<br/>

/알렉스 [<랜덤/소환/수정>] [<값>]<br/>
/알렉스 : 현재 랜덤으로 나오는 알렉스 리스트 조회<br/>
/알렉스 소환 <알렉스> : 해당 알렉스 소환<br/>
/알렉스 수정 <알렉스> : 해당 알렉스 랜덤 리스트 포함/제외<br/>
/알렉스 랜덤 : 랜덤 리스트에 있는 알렉스 랜덤 소환 (확률은 모두 동일)<br/>

/이탈리안 [<랜덤/소환/수정>] [<값>]<br/>
/이탈리안 : 현재 랜덤으로 나오는 이탈리안 리스트 조회<br/>
/이탈리안 소환 <이탈리안> : 해당 음이탈리안 소환<br/>
/이탈리안 수정 <이탈리안> : 해당 이탈리안 랜덤 리스트 포함/제외<br/>
/이탈리안 랜덤 : 랜덤 리스트에 있는 이탈리안 랜덤 소환 (확률은 모두 동일)<br/>

/랜덤능력 [<랜덤/부여/수정>] [<값>]<br/>
/랜덤능력 : 현재 랜덤으로 나오는 랜덤능력 리스트 조회<br/>
/랜덤능력 부여 <랜덤능력> : 해당 랜덤능력 부여<br/>
/랜덤능력 수정 <랜덤능력> : 해당 랜덤능력 랜덤 리스트 포함/제외<br/>
/랜덤능력 랜덤 : 랜덤 리스트에 있는 랜덤능력 랜덤 주기 (확률은 모두 동일)<br/>



/용암설치 : 주변 4칸 용암생성<br/>
/다버리기 : 만렙곡괭이 빼고 다 버리기<br/>

/크기조정 <크기> : default 1 / 플레이어 크기 조정<br/>
/랜덤텔포 : 플레이어 주변으로 랜덤 텔포<br/>
/tnt소환 <숫자>: 플레이어 위치에 점화된 tnt <숫자> 소환<br/>
/용수철 <숫자>: 플레이어 <숫자> 만큼 점프 1~10 
/거미줄설치 : 플레이어 위치 거미줄 설치<br/>

/룰렛 : 룰렛 돌리기 <br/>
/룰렛설정 : 룰렛설정 변경 후 변수 재설정 <br/>
/룰렛확인 : 현재 남은 룰렛 큐 메시지 출력 <br/>

## 유용한 사운드
entity.player.levelup : 레벨업 <br/>
entity.experience_orb.pickup : 경험치 <br/>
entity.generic.explode : tnt 폭발 <br/>
entity.dragon_fireball.explode : 드래곤 구체 폭발 <br/>
entity.firework_rocket.blast : 폭죽 폭발 <br/> 
entity.firework_rocket.launch : 폭줄 발사 <br/>
entity.ender_dragon.growl : 드래곤 포효 <br/>
entity.player.attack.crit : 크리티컬 소리 <br/>
block.note_block.harp : harp 노트 <br/>