# Judicator Hammer Cuối Game - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Judicator Hammer Lên Cấp](judicator-hammer-len-cap.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: endgame Paladin `Judicator Oath` dùng `Blessed Hammer` làm damage engine, khai thác `Judgement` cho mark-and-burst, đủ rõ để test speed farm, boss và push mà không lẫn sang Zealot Zenith.

Triết lý: build này cần tempo và vị trí. `Blessed Hammer` mạnh khi enemy ở đúng vùng hit và mark/debuff được giữ ổn. Nếu thiếu setup, sheet damage cao vẫn không chuyển thành clear thật.

Dấu ấn riêng: endgame chia 3 mode: `Hammer Inquisitor` làm lõi hammer/aura, `Condemn Court` cho pack tản, `Bolt Inquisitor` cho lúc thiếu mark/resource. Mỗi mode giữ damage engine, chỉ đổi một slot.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Endgame nên giữ `Judicator Oath` khi muốn lối chơi mark-and-burst bằng `Blessed Hammer`. | Verified + Inference | Đây là Oath hợp nhất với fantasy thẩm phán/búa thánh. |
| Skill bar mặc định nên dùng `Rally / Blessed Hammer / Purify / Fanaticism Aura / Defiance Aura / Holy Light Aura`. | Community | Đây là baseline Hammerdin Judicator endgame của Icy Veins Season 13. |
| Dự án dùng `Condemn` hoặc `Holy Bolt` làm safety variant nếu pack tản, thiếu mark hoặc thiếu Faith. | Inference + Needs testing | Chỉ đổi khi bar mặc định không giải quyết đúng vấn đề thật. |
| `Fanaticism Aura` tăng nhịp spender và crit; `Defiance Aura` là nút an toàn khi đứng gần. | Community + Inference | Bỏ Defiance chỉ khi defense đã dư. |
| Điểm yếu cần test là boss di chuyển và Faith downtime. | Needs testing | Nếu hammer không trúng hoặc thiếu resource, build yếu do delivery chứ chưa chắc do damage thấp. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Blessed Hammer Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/blessed-hammer-paladin-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/

## Build Identity

Tên build: `Paladin - Judicator Hammer Cuối Game`

| Mục | Chọn |
|---|---|
| Use case | Endgame farm, Nightmare Dungeon, Pit vừa, boss/elite nếu setup tốt |
| Oath | `Judicator` |
| Damage chính | `Blessed Hammer` |
| Setup chính | `Judgement` qua `Holy Light Aura`/modifier, `Purify`, aura/debuff window |
| Damage type chính | `Holy` |
| Phong cách | Mark mục tiêu, gom hoặc cố định pack, tạo hammer zone, giữ Faith |
| Weapon đề xuất | 1H + shield nếu push; 2H/offhand nếu farm dễ và cần damage |
| Mức gear | Trung bình trở lên; cần resource/crit/skill rank |

## Bảng Điều Khiển Mode

### `Hammer Inquisitor` - Bản Mặc Định

```text
Rally / Blessed Hammer / Purify / Fanaticism Aura / Defiance Aura / Holy Light Aura
```

| Slot | Skill | Vai trò |
|---|---|---|
| Valor | `Rally` | Movement Speed, Faith, reposition |
| Core | `Blessed Hammer` | Damage chính |
| Justice | `Purify` | Cleanse/sustain/Holy setup cho elite/boss theo tooltip |
| Aura 1 | `Fanaticism Aura` | Attack Speed/Crit/debuff window |
| Aura 2 | `Defiance Aura` | Armor/Resistance, active Unstoppable |
| Aura 3 | `Holy Light Aura` | Holy damage/sustain, có hướng apply `Judgement` qua modifier |

### `Condemn Court` - Pack Tản

Đổi:

```text
Purify -> Condemn
```

Dùng khi:

- Pack tản làm hammer hụt.
- Activity có nhiều elite đi kèm quái nhỏ.
- Bạn không cần cleanse/sustain thêm từ `Purify`.

Rollback nếu boss/elite lâu hơn mà pack không clear nhanh hơn.

### `Bolt Inquisitor` - Safety Mark/Resource

Đổi:

```text
Holy Light Aura -> Holy Bolt
```

Dùng khi:

- Bạn chưa có modifier/gear giúp apply `Judgement` đủ ổn.
- Faith khựng trong boss.
- Muốn học rõ nhịp mark trước khi tối ưu aura package.

Rollback khi đã có đủ mark/resource, vì mất `Holy Light Aura` sẽ giảm aura/Holy pressure.

## Luật Flex Của Hammer Inquisitor

Judicator endgame cần ưu tiên delivery trước multiplier. `Blessed Hammer` chỉ mạnh khi có `Judgement` và mục tiêu ở trong vùng hit đủ lâu. Vì vậy flex slot nên trả lời câu hỏi: thiếu mark, thiếu vị trí, thiếu sống hay thiếu boss damage?

| Trục cần chỉnh | Skill ứng viên | Khi chọn | Vì sao hợp cơ chế |
|---|---|---|---|
| Nguồn Judgement | `Holy Light Aura`, `Holy Bolt` | Aura khi farm mượt; Basic khi boss/resource khựng | Không có mark thì Core Judicator mất phần lớn lý do tồn tại |
| Giữ mục tiêu | `Condemn` | Pack tản, elite kéo minion, Helltide đông | Hammer zone cần enemy đứng lại, không chỉ cần damage cao |
| Boss/sustain | `Purify` | Boss, elite nguy hiểm, cần cleanse/sustain | Boss không cần pull nhiều; cần window ổn định hơn |
| Damage window | `Fanaticism Aura` | Mặc định khi spender là nguồn damage chính | Attack Speed/Crit giúp hammer spam và proc ổn hơn |
| Defensive latch | `Defiance Aura`, shield | Push, Hardcore, CC nhiều | Đứng cast mà bị CC chết thì mọi setup Judgement vô nghĩa |

Tự suy luận variant hợp lý: nếu boss chậm nhưng pack nhanh, đừng đổi `Blessed Hammer`; đổi nguồn window trước (`Purify`, `Holy Bolt`, debuff). Nếu pack chậm nhưng boss ổn, đừng thêm single-target; đổi delivery (`Condemn`, vị trí đứng, hammer size).

## Gear Priority

### Power Package

| Package | Status | Vì sao |
|---|---|---|
| `Hammer Engine` | Community | Rank, size, orbit, cost, cast speed hoặc damage cho `Blessed Hammer`. |
| `Judgement Engine` | Verified + Inference | Tăng hiệu quả mark/detonate hoặc damage lên target bị `Judgement`. |
| `Pack Court` | Inference | Pull/Stun/CC để enemy ở trong hammer zone. |
| `Aura Window` | Community + Inference | Attack Speed/Crit/Vulnerable/Weaken để tăng burst window. |
| `Safe Tribunal` | Inference | Defense đủ để đứng gần mà không chết khi hammer quay. |

### Unique / Aspect Cần Theo Dõi

| Power | Status | Ghi chú |
|---|---|---|
| Aspect/Unique tăng `Blessed Hammer` | Community | Ưu tiên cao nhất sau defensive breakpoint. |
| Aspect tăng `Judgement` hoặc Judicator Skill | Inference | Đáng test nếu giúp boss/elite chết nhanh hơn. |
| Aspect tăng aura/debuff | Community + Inference | Hợp `Fanaticism Aura`, `Holy Light Aura` và baseline Hammer Inquisitor. |
| Defensive shield/DR aspect | Inference | Cần khi đứng gần hoặc dùng shield. |
| Resource/cooldown aspect | Inference | Dùng nếu build cạn Faith hoặc Condemn/Rally lệch nhịp. |

### Stat Tấn Công

1. `+Rank Blessed Hammer`.
2. Critical Strike Chance.
3. Resource Generation / Cost Reduction.
4. Attack Speed hoặc cast speed nếu hưởng lợi.
5. Holy/Core/Judicator Skill Damage.
6. Damage to marked/Vulnerable/CC target nếu setup uptime tốt.
7. Critical Strike Damage.
8. Cooldown Reduction.

### Stat Phòng Thủ

- Armor cap và All Resistance cap theo Torment.
- Maximum Life.
- DR Close / DR while Fortified.
- Block Chance / Block DR nếu cầm shield.
- Movement Speed đủ để tránh boss mechanic.

## Tempering / Masterworking Priority

| Giai đoạn | Ưu tiên |
|---|---|
| Mới endgame | Temper `Blessed Hammer` + defense nền. |
| Farm ổn | Temper resource/cost và aura/CC support. |
| Boss | Masterwork weapon, ring/amulet có crit/resource, item tăng hammer/Judgement. |
| Push | Masterwork defensive armor/shield trước khi chase damage. |

## Paragon Tổng Quan

- Status: Community + Inference
- Checked: 2026-05-13

| Mục tiêu | Board/Glyph hướng tới |
|---|---|
| Hammer damage | Core Skill, Holy Damage, Judicator Skill |
| Mark burst | Damage to marked/debuffed/Vulnerable target |
| Pack control | Damage to CC, area/range nếu có |
| Resource | Resource Generation, Cost Reduction, Faith recovery |
| Defense | Life, Armor, Resistance, DR Close, Block nếu dùng shield |

Paragon nên giữ nhịp build trước. Nếu thiếu Faith, lấy node resource có thể tăng DPS thật hơn node damage xa.

## Rotation Thực Chiến

### Pack Thường

1. `Rally` để vào pack và lấy Faith.
2. Bật `Holy Light Aura`/modifier để tạo Holy pressure và `Judgement` nếu đang dùng hướng đó.
3. Bật `Fanaticism Aura` nếu pack dày.
4. Dùng `Purify` cho sustain/setup hoặc `Condemn` nếu đang ở mode pack tản.
5. Xả `Blessed Hammer` khi enemy đứng trong vùng hit.
6. Giữ `Defiance Aura` cho CC/burst.

### Pack Đông / Elite

1. Dùng `Holy Light Aura`/`Purify` để chuẩn bị Holy/Judgement window.
2. Nếu dùng `Condemn Court`, kéo pack vào elite.
3. Bật `Fanaticism Aura`.
4. Spam `Blessed Hammer`, giữ vị trí để hammer không quay hụt.
5. Nếu bị CC/burst, dùng `Defiance Aura`, rồi `Rally` ra khỏi ground effect.

### Boss

1. Dùng `Rally` để giữ Faith và reposition.
2. Đợi boss đứng yên hoặc sau mechanic rồi bật `Fanaticism Aura`.
3. Dùng `Purify` cho window boss/elite.
4. Xả `Blessed Hammer` trong window.
5. Nếu thiếu mark/Faith, chuyển sang `Bolt Inquisitor` để thêm `Holy Bolt`.
6. Nếu hammer trượt vì boss di chuyển, đổi cách đứng trước khi đổi gear.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì | Tiêu chí pass |
|---|---|---|
| Pack tản | `Purify -> Condemn`, tăng pull/CC | Hammer hit nhiều hơn, clear nhanh hơn |
| Boss chậm | Giữ `Purify`, thêm debuff/single-target hoặc test `Holy Bolt` mark | Boss mất máu rõ trong window |
| Chết vì CC | Giữ `Defiance Aura`, dùng shield/DR | Ít chết hơn, potion pressure giảm |
| Farm dễ nhưng chậm | Thêm Movement Speed/CDR, không bỏ `Holy Light Aura` nếu nó đang là nguồn mark | Clear nhanh hơn mà không chết |
| Cạn Faith | Giữ `Rally`, thêm resource/cost; test `Holy Bolt` nếu boss khựng | Rotation không còn khựng |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | Hammer zone giết pack sau setup/pull | Enemy tản, hammer quay hụt |
| Elite | Elite chết trong 1-2 window | Phải kite chờ cooldown/resource |
| Boss | Mark + hammer window rõ | Boss di chuyển làm mất damage |
| Defense | Defiance đủ cứu khi bị CC | Chết khi đứng cast |
| Resource | Faith đủ khi dùng Rally/resource package hoặc `Holy Bolt` variant | Cạn Faith liên tục |
