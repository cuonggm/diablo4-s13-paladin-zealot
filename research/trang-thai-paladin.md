# Trạng Thái Paladin

Checked: 2026-05-13

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Tổng Quan Mùa 13](tong-quan-mua-13.md), [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Zealot Zenith Lên Cấp](../builds/zealot-zenith-len-cap.md), [Zealot Zenith Cuối Game](../builds/zealot-zenith-endgame.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

## Kết Luận

Paladin là class chính thức của Diablo IV trong Lord of Hatred, không còn chỉ là concept roleplay. Với dự án này, hướng chơi nên được xem là Paladin thật nếu account có Lord of Hatred.

| Kết luận | Status | Sources | Impact on Paladin |
|---|---|---|---|
| Paladin là class mới của Lord of Hatred. | Verified | Blizzard Lord of Hatred overview, Blizzard Paladin overview | Không cần dùng class thay thế nếu có expansion. |
| Paladin dùng fantasy sword/shield, Holy Light, Aura, protection, justice. | Verified | Blizzard Paladin overview | Paladin nên ưu tiên shield, Holy damage, Aura, defensive layer. |
| Resource `Faith` xuất hiện trong nguồn chính thức; số liệu cost/generation cụ thể vẫn nên đối chiếu tooltip hoặc guide cộng đồng. | Verified + Community | Blizzard Paladin overview, Wowhead, Icy Veins | Khi test rotation, theo dõi cảm giác thiếu Faith và cách generate. |
| Class mechanic là `Oaths` với 4 hướng: `Zealot`, `Juggernaut`, `Judicator`, `Disciple`. | Verified | Blizzard Paladin overview | Chọn Oath theo cách chơi, không chỉ theo damage sheet. |

Sources:

- Blizzard - Paladin overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Blizzard - Lord of Hatred overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Wowhead - Paladin class overview: https://www.wowhead.com/diablo-4/guide/classes/paladin/overview
- Icy Veins - Paladin skills: https://www.icy-veins.com/d4/guides/paladin-skills/

## Bản Sắc Gameplay

| Trụ cột | Status | Nghĩa thực chiến |
|---|---|---|
| `Sword and Shield` | Verified | Đánh gần, có block/defense, phù hợp người thích đứng vững trong pack. |
| `Holy Damage` | Verified | Damage type cần khớp gem, affix, Talisman, Aspect. |
| `Auras` | Verified | Aura có passive effect và active effect; dùng để buff bản thân/party hoặc tạo utility. |
| [`Oaths`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified | Oath định hình build: tốc đánh, tank, mark/detonate, hoặc angelic transformation. |
| [`Faith`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified + Community | Resource chính để xài nhiều skill; nếu thiếu Faith thì build sẽ khựng. |

## Oaths

| Oath | Status | Fantasy | Khi nên thử |
|---|---|---|---|
| [`Zealot`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified | Holy warrior đánh nhanh, tạo Fervor, hợp tốc độ và crit. | Khi muốn leveling/speed farm cảm giác mượt, nhiều hit. |
| [`Juggernaut`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified | Tank templar, Resolve, shield, size/damage cho skill phòng thủ. | Khi chơi Hardcore, push khó, hoặc muốn Paladin là guardian. |
| [`Judicator`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified | Judge enemy, detonate bằng Core Skill, tăng damage lên mục tiêu. | Khi muốn bossing hoặc gameplay mark-and-burst. |
| [`Disciple`](../docs/thuat-ngu-va-co-che.md#paladin) | Verified | Angelic form, Arbiter, skill cooldown và ultimate fantasy. | Khi muốn Holy caster/melee lai, mobility và visual mạnh. |

## Skill Nhắc Đến Trong Nguồn Chính Thức

| Nhóm | Skill | Ghi chú tiếng Việt |
|---|---|---|
| `Basic Skills` | Brandish, Holy Bolt, Clash, Advance | Basic thường dùng để generate resource hoặc lấp nhịp. |
| `Core Skills` | Zeal, Blessed Shield, Blessed Hammer, Divine Lance, Shield Bash | Core là nguồn damage chính, thường tốn Faith. |
| `Auras` | Fanaticism Aura, Defiance Aura, Holy Light Aura | Aura có passive và active; chọn theo damage, defense hoặc sustain. |
| `Valor Skills` | Shield Charge, Aegis, Falling Star, Rally | Mobility, defense, Faith generation, engage. |
| `Justice Skills` | Purify, Consecration, Condemn, Spear of the Heavens | Control, healing, AoE, burst setup. |
| `Ultimate Skills` | Heaven's Fury, Fortress, Zenith, Arbiter of Justice | Nút power lớn; dùng cho boss, elite pack, hoặc lúc nguy hiểm. |

## Hướng Paladin Nên Test

### Paladin - Blessed Hammer Disciple

- Status: Community + Inference
- Checked: 2026-05-13
- Sources: Blizzard Paladin skills, Icy Veins Blessed Hammer leveling
- Use case: Leveling 1-70, clear pack, fantasy Holy hammer
- Impact on Paladin: Nên test đầu tiên nếu muốn lên level nhanh mà vẫn đúng fantasy Paladin.

### Paladin - Blessed Shield / Judicator

- Status: Inference
- Checked: 2026-05-13
- Sources: Blizzard Paladin skills, Wowhead class overview
- Use case: Pack clear, shield fantasy, possible boss setup bằng Judgement
- Impact on Paladin: Hợp fantasy khiên, nhưng cần test single-target và Faith cost.

### Paladin - Juggernaut Guardian

- Status: Inference / Needs testing
- Checked: 2026-05-13
- Sources: Blizzard Paladin skills, community Oath summary
- Use case: Hardcore, defensive endgame, learning boss mechanics
- Impact on Paladin: Rất hợp guardian fantasy, nhưng có thể chậm hơn khi speed farm.

## Nếu Không Có Lord of Hatred

- Status: Inference
- Checked: 2026-05-13
- Impact on Paladin:
  - Chọn Barbarian nếu muốn melee bền, shield-like/tank fantasy bằng defensive skills, shout như aura.
  - Chọn Spiritborn nếu có Vessel of Hatred và muốn martial mobility.
  - Chọn Druid nếu muốn bền, shapeshift, nature guardian.
  - Không gọi các lựa chọn này là Paladin thật; chỉ là roleplay thay thế.
