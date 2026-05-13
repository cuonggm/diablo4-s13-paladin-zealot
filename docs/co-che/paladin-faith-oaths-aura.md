# Paladin: Faith, Oaths, Auras

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Trạng Thái Paladin](../../research/trang-thai-paladin.md), [Skill Tree](skill-tree-va-skill-variants.md), [Combat](combat-defense-rotation.md), [Zealot Zenith Lên Cấp](../../builds/zealot-zenith-len-cap.md), [Zealot Zenith Cuối Game](../../builds/zealot-zenith-endgame.md), [Juggernaut Bastion](../../builds/juggernaut-bastion-len-cap.md), [Judicator Hammer](../../builds/judicator-hammer-len-cap.md), [Disciple Arbiter](../../builds/disciple-arbiter-len-cap.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Paladin là class chính thức trong Lord of Hatred. | Verified | Dự án không còn phải giả lập Paladin bằng class khác nếu có expansion. |
| Paladin dùng sword, flail, shield và Holy/Light fantasy. | Verified | Gear ưu tiên phải xét cả weapon/offhand/shield, không chỉ DPS sheet. |
| `Faith` là resource cần quản trị trong rotation. | Verified | Build mạnh trên giấy nhưng thiếu Faith sẽ bị khựng trong thực chiến. |
| Class mechanic là `Oaths`: Zealot, Juggernaut, Judicator, Disciple. | Verified | Oath quyết định engine build, không nên đổi chỉ vì một item rơi. |
| Auras có passive và active, vừa là buff nền vừa là nút chiến thuật. | Verified | Phải dùng active đúng thời điểm, không chỉ cắm aura rồi quên. |

## Faith

| Vấn đề | Cách đọc | Recommend |
|---|---|---|
| Hết Faith khi clear | Spender spam quá nhiều hoặc thiếu generator | Dùng Basic/`Rally`/resource modifier, gom pack rồi burst. |
| Hết Faith khi boss | Boss ít target nên generator theo hit/kill yếu hơn | Giữ generator trong bar tới khi gear đủ mạnh. |
| Có Faith nhưng damage thấp | Resource không phải bottleneck; thiếu scaling hoặc burst window | Sửa weapon, skill rank, Aspect, Talisman, Paragon. |
| Faith ổn nhưng gameplay chậm | Có thể thiếu mobility/cooldown, không phải resource | Thêm `Rally`, `Falling Star`, Movement Speed hoặc giảm activity khó. |

Nguyên tắc: không bỏ công cụ generate Faith cho tới khi đã test 2-3 activity liền không bị đứng đánh chay.

## Oaths

| Oath | Cơ chế chính | Nên dùng khi | Rủi ro | Test pass/fail |
|---|---|---|---|---|
| `Zealot` | Zealot Skills tạo `Fervor`; crit echo damage theo stack; max Fervor có Fortify. | Leveling/speed farm, nhiều hit, crit, `Zeal`/`Zenith`. | Cần uptime và crit; nếu bị ngắt nhịp sẽ giảm giá trị. | Pass nếu pack clear nhanh và Fervor không tụt liên tục. |
| `Juggernaut` | Juggernaut Skills dùng `Resolve` để tăng damage/size. | Hardcore, shield/tank, push, build cần đứng vững. | Có thể chậm hơn khi farm dễ. | Pass nếu giảm chết/potion mà không làm boss quá lâu. |
| `Judicator` | Basic apply `Judgement`; Core Judicator Skills detonate và tăng damage lên target. | Bossing, mark-and-burst, mục tiêu ưu tiên. | Cần rotation rõ; có thể khó hơn khi pack tản. | Pass nếu elite/boss chết nhanh hơn trong 1-2 window. |
| `Disciple` | Cooldown Disciple Skill cho `Arbiter`; Disciple Skills mạnh hơn trong Arbiter. | Holy caster/melee lai, mobility, fantasy thiên thần. | Có thể lệ thuộc cooldown/window. | Pass nếu window rõ và không chết ngoài window. |

## Auras

| Aura | Passive | Active | Nên dùng khi |
|---|---|---|---|
| `Fanaticism Aura` | Spending Faith buff Attack Speed/Crit cho bản thân/ally. | Weaken nearby enemies. | Damage window, Zealot, party, speed farm. |
| `Defiance Aura` | Buff Armor/All Resistances cho bản thân/ally. | Unstoppable ngắn. | Leveling an toàn, Hardcore, push, thiếu resist/armor. |
| `Holy Light Aura` | Gây Holy damage định kỳ quanh người/ally. | Bắn bolt, chain và heal khi bolt trở về. | Sustain, Holy fantasy, content đông quái gần người. |

Recommend:

- Leveling chưa đủ gear: `Defiance Aura` giúp sửa lỗi chết rẻ.
- Zealot Zenith mặc định: `Fanaticism Aura` là damage/tempo engine.
- Push/boss lạ: giữ hoặc đưa lại `Defiance Aura` nếu bị CC/burst.
- Party: Aura có giá trị nhóm, nhưng đừng hi sinh sống sót cá nhân nếu bạn là người mở combat.

## Skill Categories Cần Nhớ

| Nhóm | Skill nổi bật | Vai trò |
|---|---|---|
| `Basic` | Brandish, Holy Bolt, Clash, Advance | Generate/lấp nhịp, có thể apply Judgement nếu Judicator. |
| `Core` | Zeal, Blessed Shield, Blessed Hammer, Divine Lance, Shield Bash | Damage chính, thường tiêu Faith. |
| `Aura` | Fanaticism, Defiance, Holy Light | Buff nền + active tactical. |
| `Valor` | Shield Charge, Aegis, Falling Star, Rally | Mobility, defense, Faith, engage. |
| `Justice` | Purify, Consecration, Condemn, Spear of the Heavens | CC, heal, pull, AoE/burst setup. |
| `Ultimate` | Heaven's Fury, Fortress, Zenith, Arbiter of Justice | Burst, defense lớn, form/window. |

## Recommend Theo Mode Dự Án

| Mode | Oath/Aura ưu tiên | Dùng khi | Rollback |
|---|---|---|---|
| `Iron Pilgrim` | Zealot + Fanaticism + Defiance | Leveling hoặc gear yếu | Nếu quá chậm, đổi Defiance sang Condemn/Falling Star. |
| `Zenith Sentinel` | Zealot + Fanaticism, flex defense/mobility | Endgame mặc định | Nếu chết, quay về thêm Defiance/Aegis. |
| `Condemn Harvester` | Zealot + Fanaticism + Condemn | Pack đông/tản | Nếu chết vì bỏ defense, quay về Sentinel. |
| `Aegis Bulwark` | Zealot/Juggernaut leaning + Defiance/Aegis | Push, boss lạ, Hardcore | Nếu clear quá chậm, chỉ đổi lại 1 slot mobility. |
| `Sunder Duelist` | Zealot hoặc Judicator leaning | Boss/elite là nút nghẽn | Nếu farm pack chậm, quay lại Zenith. |
| `Bastion Sentinel` | Juggernaut + Defiance + Fanaticism; thêm Aegis khi push | Shield/tank, farm ổn định, Hardcore leaning | Nếu bị burst, đổi mobility sang Aegis; nếu farm chậm, quay lại Falling Star/Rally. |
| `Hammer Inquisitor` | Judicator + Fanaticism + Defiance | Holy hammer, mark-and-burst, pack cần gom | Nếu boss/pack hụt damage, kiểm tra mark và vị trí hammer trước. |
| `Arbiter Wing` | Disciple + Holy Light + Fanaticism | Holy aura/window, speed farm có mobility | Nếu chết ngoài window, quay về Aegis/Defiance/shield package. |

## Nguồn

- Blizzard - Paladin overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
