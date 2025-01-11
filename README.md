https://www.nexusmods.com/stalker2heartofchornobyl/mods/128?tab=description

Created by
Zhukoniy

https://www.nexusmods.com/stalker2heartofchornobyl/mods/41

Created by
Fredrik

원본 모드는 이 모드들입니다. 이 레포는 이 모드를 조금 더 밸런싱하고 유니크 웨폰 획득 재미까지 추가한 수정버젼입니다.

또 플레이하다 보니 뭔가 이상해서 NPCHPx05랑 NPCHP 뜯어보니까 아예 같은파일이었습니다. 원래 버젼에는 npc 피가 10인데 둘다 수정해서 NPCx05는 15으로 NPC는 20으로 수정했습니다

**다수 유니크 웨폰 수정



기존 데미지 + 3~5 or 관통력 수치 일반아이템 대비 미세증가



라이노가 이 모드에선 좀 후져서 좀 상향함



유니크 샷건 10단위 증가 관통력도 조금 늘림



udp 9미리탄은 소음은 조금 늘리고 관통력 0.4 증가 데미지 45구경 대비 4 감소

npc 듣는 소음 증가 또한 45 acp는 아음속탄이기에 45acp 탄 소음 감소


mark ebr 308 탄인데 데미지가 너무 약한거 같아 상향 조정함.


rpg 매우 강하게 만듬 **


추천 조합 : 뮤턴트 체력 150% + NPCHPx05 + Ammorebalance + WeaponRebalance + WeaponRebalanceNPCx05 이렇게 조합하는게 가장 추천드림

무기별 밸런싱 기준 테이블
9X18 - damage = 25, piercing = 1.2  - PST GZ
9x19 - damage = 28, piercing = 1 .8  - FMJ m882
45.acp - damage = 38, piercing = 1.9  - Lasermatch FMJ
9x39 - damage = 31, piercing = 4.3  - PAB-9GS
5.45x39 damage = 26, piercing = 2.8 - PS gs
5.56x45 damage = 28, piercing = 3.2 - m855
7.62X39 damage = 28, piercing = 3.6 - PS gz
7.62x51 damage = 40, piercing = 4.1 - m80
7.62x54 damage = 40, piercing = 4.2 -LPS gz




탄약별 밸런싱 기준 테이블

9X18mm RG028       ﻿Penetration+0.1 ﻿Damage *1.3﻿     Cost=15
45.Acp AP    ﻿﻿      Penetration +1.9 ﻿Damage * 0.87 ﻿﻿ Cost=75
45.Acp R﻿﻿           Penetration -1.6 ﻿Damage * 1.7﻿﻿   Cost=35
9x19 AP﻿﻿﻿            Penetration + 1.2 ﻿Damage * 0.93﻿﻿ Cost=40
5.45x39 PP﻿﻿         Penetration + 0.6 ﻿Damage * 0.95 ﻿﻿Cost=50
5.45x39 MZHV-13    Penetration -0.7﻿ Damage * 1.9﻿﻿   Cost=5
9x39 SP-6    ﻿﻿      Penetration + 0.5 ﻿Damage * 0.97﻿﻿ Cost=100
9x39 SP-5    ﻿﻿      Penetration -1.5 ﻿ Damage * 1.15﻿﻿ Cost=20
9x39 SPP    ﻿﻿       Penetration -0.8﻿ Damage * 1.1﻿﻿   Cost=50
5.56x45 995    ﻿    Penetration + 2.2 ﻿Damage * 0.74 ﻿﻿Cost=300
5.56x45 Mk262﻿      Penetration + 0.2 ﻿Damage * 0.97﻿﻿ Cost=40
5.56x45 Hp         ﻿Penetration -2.4﻿Damage * 1.4﻿﻿    Cost=5
7.62X54 B-32       Penetration+ 1.3 ﻿Damage * 0.96﻿﻿  Cost=120
7.62X54 7N1        Penetration + 0.3﻿ Damage *1.04  Cost=110
7.62X39 BZ         Penetration + 1.2 ﻿Damage * 1.01﻿﻿ Cost=300
7.62X39 LAN        Penetration - 0.5﻿ Damage * 1.12 ﻿﻿Cost=25
7.62X51 AP         Penetration + 2.3 ﻿Damage * 0.88 ﻿﻿Cost=600



I appreciate for your making good balancing table and this mod. Zhukoniy


01/09 07:51


밸런스 테이블은 기본적으로 weaponbalance 모드를 따왔고

여기서 고려한 점은

1. 레벨 별 총기 입수 난이도 별 성능 증가(후반 총일 수록 관통력과 데미지 보정)

2. 탄의 종류 별 특징 도입(5.56과 7.62의 특징.. 5.56은 높은 관통력 낮은 데미지 7.62x39는 높은 데미지 조금 낮은 관통력 등등

, 소음의 정도 실제 총기, 탄약 별로 도입(예: 45acp가 가장 소음이 적고 권총이 가장 소음이 적다 같은 요소들 대입(GPT한테 검수))





3. 수정가능한 유니크 총기는 데미지와 관통력 일반 총기 대비 증가



4. rpg를 대 보스 뮤턴트용으로 개발 -> 원래 구하기 힘든 탄약+죽창 데미지로 보스전이나 긴급상황시 요긴하게 사용가능(1.5배 체력 붉은 숲 거인 3~4발컷)



5. 최대한 버려지는 총기 없도록 노력(성능이 답도 없이 후지면 유니크라도 좋게 만들도록 노력) + 총기의 실제 특징과 성능+ 레벨별 게임 디자인 하려고 노력함





이 정도로 정리 가능 현 시점(01/09 08:00)으로 80~90% 완성된듯 밸런스 뮤턴트 체력 뻥튀기, 감소 모드 필요하면 더 만들어드림

ㅡ
01/11 17:35 : 퀘스트 중 뮤턴트가 체력 뻥튀기가 심하게 된 것을 확인하였음. 대안을 생각하던 중, 탄환 종류별 데미지 밸런스 + 샷건 데미지 상승을 건드려서 좀 더 수월하게 만듦.. AP 탄을 데미지도 상향시키고 아머피어싱은 거의 그대로 놔둠 확산탄(덤덤탄)은 데미지 상승폭이 매우 큼 샷건의 경우 슬러그의 데미지 매우 많이 상향.. 뮤턴트가 안죽는다 싶으면 여러가지 시도해보길
+ NPCx15 부터 첫 스타트 하세요 그래야 더 올릴지 내릴지 대충 가늠이 되더라구요! 
