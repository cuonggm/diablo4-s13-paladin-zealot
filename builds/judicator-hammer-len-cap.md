# Judicator Hammer Lên Cấp - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Judicator Hammer Cuối Game](judicator-hammer-endgame.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: leveling Paladin theo hướng `Judicator Oath`, dùng `Judgement` để mark mục tiêu rồi cho `Blessed Hammer` detonate/clear. Đây là build dành cho người muốn lối chơi crusader-style Holy hammer nhưng vẫn có cấu trúc test rõ, không chỉ ném búa ngẫu nhiên.

Triết lý: `Judicator` cần rotation rõ hơn Zealot/Juggernaut. Nếu không mark, không gom và không giữ Faith, `Blessed Hammer` sẽ chỉ là một spender đẹp mắt nhưng thiếu mục tiêu.

Dấu ấn riêng: leveling dùng `Holy Bolt` làm nút mark/generator an toàn, `Blessed Hammer` làm damage chính, `Condemn` gom pack, `Defiance Aura` giữ mạng. Khi gear đủ, endgame có thể bỏ Basic hoặc đổi sang aura package.

Ghi chú khác guide cộng đồng: Icy Veins leveling baseline dùng `Advance / Blessed Hammer / Rally / Falling Star / Defiance Aura / Condemn`. Dự án đổi `Advance/Falling Star` sang `Holy Bolt/Fanaticism Aura` để học rõ loop `Judgement + Blessed Hammer`; nếu bạn ưu tiên tốc độ hơn mark, dùng lại baseline cộng đồng.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Leveling nên dùng `Holy Bolt / Blessed Hammer / Defiance Aura / Rally / Condemn / Fanaticism Aura`. | Community + Inference | Có Basic để tạo Faith/mark, Core hammer, pull/stun, defense và damage window. |
| `Judicator Oath` nên được đọc như mark-and-burst: Basic tạo `Judgement`, Core Judicator skill khai thác mark. | Verified + Inference | Nếu bỏ Basic quá sớm, phải có nguồn mark khác từ variant/gear. |
| `Blessed Hammer` clear tốt khi enemy đứng trong quỹ đạo búa; vì vậy `Condemn` quan trọng hơn damage sheet trong leveling. | Community + Inference | Pack tản là nguyên nhân làm build thấy yếu. |
| `Defiance Aura` là mặc định an toàn; chỉ đổi sang `Holy Light Aura` nếu đã đủ sống và muốn thêm Holy pressure. | Inference | Leveling không nên bỏ Unstoppable nếu hay bị CC. |
| Boss cần test riêng vì hammer AoE không tự đồng nghĩa single-target mạnh. | Needs testing | Pass nếu boss chết ổn mà không cạn Faith; fail nếu phải chạy chờ resource/cooldown. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Blessed Hammer Paladin Leveling, community guide Season 13: https://www.icy-veins.com/d4/guides/blessed-hammer-paladin-leveling-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-talents/

## Build Identity

Tên build: `Paladin - Judicator Hammer Lên Cấp`

| Mục | Chọn |
|---|---|
| Use case | Leveling 1-70, Helltide/Whispers, dungeon đông quái, crusader hammer fantasy |
| Oath | `Judicator` |
| Damage chính | `Blessed Hammer` |
| Setup chính | `Holy Bolt` để generate/mark, `Condemn` để gom |
| Damage type chính | `Holy` theo tooltip `Blessed Hammer`/`Holy Bolt` |
| Defense | `Defiance Aura`, Life/Armor/Resistance, reposition bằng `Rally` |
| Mobility | `Rally`; có thể test `Falling Star` nếu content dễ |
| Weapon đề xuất | Weapon item power cao; 1H + shield nếu chết, 2H nếu farm dễ và thiếu damage |

## Skill Tree Setup Theo Game

- Status: Community + Inference
- Checked: 2026-05-13

Skill bar mặc định:

```text
Holy Bolt / Blessed Hammer / Defiance Aura / Rally / Condemn / Fanaticism Aura
```

| Nhóm skill tree | Chọn mặc định | Vai trò trong leveling | Có bắt buộc không? |
|---|---|---|---|
| `Oath` | `Judicator` | Mở logic `Judgement`, mark rồi burst/detonate | Bắt buộc cho concept này |
| `Basic` | `Holy Bolt` | Generate Faith, đánh an toàn, hỗ trợ mark theo Oath/variant | Rất nên giữ khi leveling |
| `Core` | `Blessed Hammer` | Damage chính, clear pack, tiêu Faith | Bắt buộc |
| `Aura` | `Defiance Aura` | Armor/Resistance, active Unstoppable | Mặc định an toàn |
| `Aura` | `Fanaticism Aura` | Attack Speed/Crit/debuff window | Damage/tempo |
| `Valor` | `Rally` | Movement Speed, Faith support | Rất nên giữ |
| `Justice` | `Condemn` | Pull/Stun để hammer trúng nhiều mục tiêu | Rất nên giữ |
| `Ultimate` | Không bắt buộc | Có thể test `Heaven's Fury` nếu muốn burst Holy | Không bắt buộc |

### Oath / Class Mechanic

Chọn:

```text
Oath: Judicator
```

Lý do:

- `Judicator` cho mục tiêu bị `Judgement` trở thành điểm nổ/damage ưu tiên.
- `Holy Bolt` giúp build có Basic an toàn để giữ Faith và tạo nhịp mark.
- `Blessed Hammer` khai thác pack đã gom: càng nhiều enemy đứng đúng vị trí, hammer càng có giá trị.

Rủi ro chính: nếu bạn chỉ spam `Blessed Hammer` vào pack tản, build sẽ thấy thiếu damage. Cần mở combat bằng mark/gom rồi mới xả spender.

## Tác Dụng Nhanh Của Skill Chính

| Skill | Nhóm / Oath / Type | Tác dụng chi tiết | Ý nghĩa cho Paladin |
|---|---|---|---|
| `Holy Bolt` | `Basic`, `Judicator`, `Holy` | Basic tầm xa, generate Faith, có thể Slow/ricochet/pierce/Vulnerable tùy modifier. | Nút mark/generator an toàn cho Judicator leveling. |
| `Blessed Hammer` | `Core`, `Judicator`, `Holy` | Spender ném búa xoáy/quỹ đạo, tốt khi enemy ở trong vùng hit. | Damage chính; cần vị trí và gom pack. |
| `Condemn` | `Justice`, utility | Pull/Stun/CC theo modifier. | Đưa enemy vào quỹ đạo hammer, tăng hiệu quả AoE thực tế. |
| `Fanaticism Aura` | `Aura`, `Zealot` | Passive Attack Speed/Crit khi tiêu Faith; active debuff gần người. | Damage window cho hammer spam, nhất là elite. |
| `Defiance Aura` | `Aura`, `Juggernaut` | Armor/Resistance, active Unstoppable. | Giữ mạng khi phải đứng gần để hammer trúng. |
| `Rally` | `Valor`, `Zealot` | Movement Speed và Faith. | Sửa downtime giữa pack và lúc Faith tụt. |

## Rotation Thực Chiến

### Pack Thường

1. Dùng `Rally` để vào pack và lấy Faith nếu cần.
2. Bắn `Holy Bolt` vào mục tiêu trung tâm hoặc elite để tạo nhịp mark.
3. Dùng `Condemn` kéo pack vào nhau.
4. Xả `Blessed Hammer` khi enemy đã gom.
5. Bật `Fanaticism Aura` cho pack dày/elite, không cần dùng ở pack nhỏ.
6. Giữ `Defiance Aura` active cho CC/burst.

### Pack Đông / Elite

1. Mark mục tiêu ưu tiên bằng `Holy Bolt`.
2. `Condemn` để kéo/stun.
3. Bật `Fanaticism Aura`.
4. Spam `Blessed Hammer` khi mục tiêu đứng yên hoặc bị gom.
5. Nếu bị CC hoặc mất máu nhanh, dùng `Defiance Aura`, rồi reposition bằng `Rally`.

### Boss

1. Dùng `Holy Bolt` để giữ Faith và nhịp `Judgement`.
2. Chỉ xả nhiều `Blessed Hammer` khi boss đứng yên hoặc vừa hết movement mechanic.
3. Bật `Fanaticism Aura` trước damage window.
4. Giữ `Defiance Aura` cho boss CC/burst, không dùng chỉ để lấy aura đẹp.
5. Nếu boss quá lâu, test modifier single-target hoặc đổi weapon trước khi đổi Oath.

## Gear Và Stat Priority

### Gear Nền

| Nhóm | Ưu tiên |
|---|---|
| Weapon | Item power cao, `+Rank Blessed Hammer`, Holy/Core damage nếu có |
| Offhand/Shield | Shield nếu chết; focus/offhand damage nếu sống ổn và cần speed |
| Armor | Life, Armor, Resistance, DR Close/Fortified |
| Jewelry | Critical Strike Chance, Resource Generation, CDR, Resistance |
| Boots | Movement Speed, evade utility |

### Aspect / Unique Package

| Package | Status | Dùng khi |
|---|---|---|
| `Hammer Engine` | Community | Tăng damage, size, orbit, cast speed hoặc cost của `Blessed Hammer`. |
| `Judgement Burst` | Verified + Inference | Tăng giá trị mark/detonate, damage lên target bị `Judgement`. |
| `Pack Control` | Inference | Pull/Stun/CC hỗ trợ `Condemn`, giúp hammer trúng thật. |
| `Safe Caster` | Inference | DR/Barrier/Fortify để đứng trong tầm hammer mà không chết. |

### Stat Priority

1. `+Rank Blessed Hammer`.
2. Critical Strike Chance.
3. Resource Generation / Cost Reduction.
4. Attack Speed hoặc cast speed nếu tooltip hưởng lợi.
5. Holy/Core/Judicator damage.
6. Critical Strike Damage.
7. Cooldown Reduction cho `Condemn`, `Rally`, aura.
8. Life/Armor/Resistance nếu vừa tăng difficulty.

## Tempering / Masterworking Priority

Leveling chỉ temper để sửa vấn đề:

| Vấn đề | Temper nên tìm |
|---|---|
| Pack chết chậm | `Blessed Hammer` damage/size/rank, Holy/Core damage |
| Boss chậm | Crit, Judicator damage, damage to marked/Vulnerable nếu có |
| Cạn Faith | Resource Generation, Cost Reduction, Rally support |
| Chết | Armor, Resistance, Life, DR |
| Map chậm | Movement Speed, cooldown/mobility support |

## Paragon Tổng Quan

- Status: Inference + Needs testing
- Checked: 2026-05-13

Khi mở Paragon, ưu tiên:

| Mục tiêu | Hướng node/glyph |
|---|---|
| Scale `Blessed Hammer` | Core Skill, Holy Damage, Judicator Skill |
| Scale `Judgement` | Damage to marked/debuffed target nếu board có |
| Giữ resource | Resource/cost/kill recovery nếu rotation khựng |
| Sống khi đứng gần | Life, Armor, Resistance, DR Close |
| Pack clear | AoE/CC/damage to CC nếu khớp `Condemn` |

Không cần respec quá sớm. Leveling Judicator mạnh hơn khi rotation đúng; Paragon chỉ sửa phần còn thiếu.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì | Rollback |
|---|---|---|
| Pack tản | Giữ `Condemn`, tăng pull/CC, đổi modifier hammer rộng hơn | Nếu boss chậm hơn mà pack không nhanh hơn, rollback |
| Chết khi đứng gần | Giữ `Defiance Aura`, dùng shield, thêm Life/DR | Chỉ giảm defense khi đã hết chết vô lý |
| Cạn Faith | Giữ `Holy Bolt`, thêm resource/Rally | Đừng bỏ Basic trước khi gear đủ |
| Boss chậm | Thử modifier single-target, debuff/Vulnerable, weapon cao hơn | Nếu mất pack clear, ghi rõ và rollback |
| Muốn speed farm | Test `Falling Star` thay `Defiance Aura` chỉ khi không chết | Nếu chết vì CC, quay lại Defiance |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | `Condemn` gom được pack, hammer hit nhiều mục tiêu | Pack tản, hammer quay hụt |
| Elite | Elite chết trong 1-2 damage window | Elite sống lâu, bạn phải kite chờ Faith |
| Boss | Có nhịp mark + hammer rõ | Boss di chuyển làm mất phần lớn damage |
| Defense | Có Unstoppable khi cần | Chết vì CC/burst trước khi đánh |
| Resource | `Holy Bolt`/`Rally` đủ giữ nhịp | Cạn Faith thường xuyên |
