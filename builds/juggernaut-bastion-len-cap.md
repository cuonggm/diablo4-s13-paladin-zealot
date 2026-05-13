# Juggernaut Bastion Lên Cấp - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Juggernaut Bastion Cuối Game](juggernaut-bastion-endgame.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: leveling Paladin theo hướng `Juggernaut Oath`, ưu tiên shield, Block, `Resolve`, sống ổn khi vào melee và vẫn đủ damage để clear campaign skip, Helltide, Whispers, Nightmare thấp.

Triết lý: đây là build "đỡ đòn trước, tối ưu sau". Guide cộng đồng `Blessed Shield` được dùng làm baseline, nhưng quyết định cuối cùng phải dựa trên vấn đề thật: chết, thiếu Faith, pack tản, hay boss quá lâu.

Dấu ấn riêng: `Bastion` không cố chạy nhanh như Zealot. Build giữ lõi `Clash / Blessed Shield / Defiance Aura / Rally`, rồi xoay slot `Aegis`, `Holy Light Aura`, `Condemn` theo mức độ đau của content.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Leveling nên dùng `Clash / Blessed Shield / Defiance Aura / Rally / Aegis / Holy Light Aura`. | Community + Inference | Đây là bản an toàn nhất cho Oath Juggernaut: có Basic generator, Core shield, aura phòng thủ, mobility/resource và nút Block. |
| `Juggernaut Oath` phù hợp fantasy shield/tank vì dùng `Resolve` để tăng damage/size cho skill cùng hệ. | Verified + Community | Không nên đánh giá build chỉ bằng tốc độ clear thấp cấp; giá trị chính là ít chết và giữ vị trí tốt. |
| `Blessed Shield` chỉ thật sự vào lõi Juggernaut khi lấy variant `Shield of Retribution`, vì base skill là Judicator. | Community | Nếu chưa mở variant này, dùng `Shield Bash` làm Core tạm để giữ đúng Oath. |
| `Blessed Shield`/`Shield Bash` là damage nền; `Aegis` và `Defiance Aura` là hai nút phản ứng khi bị burst/CC. | Community + Inference | Nếu bấm cả hai quá sớm, lúc elite burst thật sẽ không còn cooldown. |
| Khi pack tản làm shield path/pulse/ricochet trúng ít mục tiêu, có thể thử `Condemn` thay `Holy Light Aura`. | Inference + Needs testing | Chỉ đổi khi không còn cần sustain/heal từ Holy Light. |
| Khi boss quá lâu, ưu tiên weapon item power, rank `Blessed Shield`, Block scaling và debuff uptime trước khi tăng difficulty. | Inference | Tank sống lâu nhưng boss quá chậm là dấu hiệu damage package chưa đủ. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Blessed Shield Paladin Leveling, community guide Season 13: https://www.icy-veins.com/d4/guides/blessed-shield-paladin-leveling-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/

## Build Identity

Tên build: `Paladin - Juggernaut Bastion Lên Cấp`

| Mục | Chọn |
|---|---|
| Use case | Leveling 1-70, Hardcore mềm, Helltide/Whispers/Nightmare thấp, học boss mới |
| Oath | `Juggernaut` |
| Damage chính | `Blessed Shield` với variant `Shield of Retribution`; `Shield Bash` là fallback trước khi mở variant |
| Damage type chính | Kiểm tra tooltip variant; base `Blessed Shield` là Holy/Judicator, `Shield of Retribution` đổi tag sang Juggernaut |
| Resource | `Faith` từ `Clash`, `Rally`, kill/hit modifier nếu có |
| Defense | Shield, Block, `Resolve`, `Defiance Aura`, `Aegis`, Life/Armor/Resistance |
| Mobility | `Rally`; không phải build speed mặc định |
| Weapon đề xuất | 1H + shield gần như bắt buộc để giữ fantasy và scaling |

## Skill Tree Setup Theo Game

- Status: Community + Inference
- Checked: 2026-05-13

Skill bar mặc định:

```text
Clash / Blessed Shield / Defiance Aura / Rally / Aegis / Holy Light Aura
```

| Nhóm skill tree | Chọn mặc định | Vai trò trong leveling | Có bắt buộc không? |
|---|---|---|---|
| `Oath` | `Juggernaut` | Mở engine `Resolve`, tăng giá trị shield/Block/tank skill | Bắt buộc cho concept này |
| `Basic` | `Clash` | Generate Faith, đánh bằng vũ khí + shield, hợp Resolve | Rất nên giữ khi leveling |
| `Core` | `Blessed Shield` + `Shield of Retribution` | Spender chính, chuyển sang Juggernaut, tạo shield/Thorns pressure | Bắt buộc khi mở variant |
| `Aura` | `Defiance Aura` | Armor/Resistance, active Unstoppable | Bắt buộc khi leveling an toàn |
| `Aura` | `Holy Light Aura` | Holy damage quanh người, sustain/heal nhẹ, clear quái sát người | Flex an toàn |
| `Valor` | `Rally` | Movement Speed, Faith support, chạy pack-to-pack | Rất nên giữ |
| `Valor` | `Aegis` | Block/defensive button, phản ứng burst | Rất nên giữ |
| `Justice` | Không lấy mặc định | Dùng `Condemn` nếu cần pull/stun pack | Tùy vấn đề |
| `Ultimate` | Không bắt buộc trong leveling | Có thể test `Fortress` nếu muốn nút thủ lớn | Không bắt buộc |

Nếu chưa mở được `Shield of Retribution`, dùng tạm:

```text
Clash / Shield Bash / Defiance Aura / Rally / Aegis / Holy Light Aura
```

`Shield Bash` là `Core`, `Juggernaut`, `Physical`, nên giữ Oath engine rõ hơn trong giai đoạn chưa có variant.

### Oath / Class Mechanic

Chọn:

```text
Oath: Juggernaut
```

Lý do:

- `Juggernaut` thưởng cho skill cùng hệ bằng `Resolve`.
- `Clash`, `Shield Bash`, `Aegis`, `Defiance Aura` và `Blessed Shield - Shield of Retribution` cùng phục vụ một vòng lặp: đứng vững, tích phòng thủ, rồi biến phòng thủ thành damage ổn định.
- Build leveling này không cần nhanh nhất; nó cần không chết khi gear còn rác và resistance chưa cap.

Rủi ro chính: nếu quá nhiều slot phòng thủ, pack/boss sẽ chậm. Khi thấy ít chết nhưng clear tệ, chỉ đổi một slot sang utility/damage, không phá toàn bộ lõi shield.

## Tác Dụng Nhanh Của Skill Chính

| Skill | Nhóm / Oath / Type | Tác dụng chi tiết | Ý nghĩa cho Paladin |
|---|---|---|---|
| `Clash` | `Basic`, `Juggernaut`, `Physical` | Basic generator dùng vũ khí + shield, hợp Block/Resolve. | Nguồn Faith và nhịp melee an toàn hơn `Advance` nếu cầm shield. |
| `Blessed Shield - Shield of Retribution` | `Core`, base `Judicator`, variant thành `Juggernaut`, shield | Base ném shield ricochet; `Shield of Retribution` đổi thành Juggernaut Skill, đi thẳng, pulse Thorns rồi burst. | Damage nền của bản Bastion khi đã mở variant; giúp Blessed Shield khớp Oath. |
| `Shield Bash` | `Core`, `Juggernaut`, `Physical`, shield | Charge/bash trước mặt, hit có thể tính như Block, Stun/Knockback hoặc scale với Resolve. | Fallback đúng Oath trước khi có `Shield of Retribution`, hoặc dùng nếu muốn melee tank rõ hơn. |
| `Defiance Aura` | `Aura`, `Juggernaut` | Passive Armor/All Resistance; active cho `Unstoppable` ngắn. | Nút sống sót trước CC/burst, không bấm chỉ vì đang sẵn cooldown. |
| `Rally` | `Valor`, `Zealot` | Movement Speed, Faith ngay khi cast, giúp chuyển pack. | Sửa hai lỗi của tank: chậm và đôi khi thiếu Faith. |
| `Aegis` | `Valor`, `Juggernaut` | Defensive button liên quan shield/Block/Unstoppable tùy modifier. | Nút phản ứng khi elite/boss chuẩn bị burst. |
| `Holy Light Aura` | `Aura`, `Disciple` | Holy damage định kỳ quanh người, active bolt/heal theo tooltip. | Sustain và clear quái sát người; không phải nguồn boss damage chính. |

## Rotation Thực Chiến

### Pack Thường

1. Dùng `Rally` trước khi vào pack nếu cần tốc độ hoặc Faith.
2. Đứng ở rìa pack, không lao vào giữa ground effect.
3. Ném `Blessed Shield - Shield of Retribution` xuyên qua pack; nếu dùng fallback thì `Shield Bash` vào mục tiêu dày nhất.
4. Dùng `Clash` khi Faith thấp hoặc cần giữ nhịp.
5. Giữ `Defiance Aura` active cho lúc bị CC; dùng `Aegis` khi thấy burst sắp tới.

### Pack Đông / Elite

1. Bật `Defiance Aura` nếu pack có CC nguy hiểm hoặc đang thiếu resistance.
2. Dùng `Aegis` sau khi đã nhận aggro, không bấm trước khi pack đánh vào bạn.
3. Spam `Blessed Shield` khi enemy gom đủ gần; nếu chưa có variant Juggernaut thì dùng `Shield Bash` cho đúng Oath.
4. Nếu pack tản, test `Condemn` thay `Holy Light Aura` để kéo/stun.
5. Nếu hết Faith, dùng `Clash` 2-3 nhịp rồi quay lại shield.

### Boss

1. Giữ khoảng cách vừa đủ để `Blessed Shield` hit ổn định.
2. Không dùng `Aegis` và `Defiance Aura` cùng lúc nếu boss chưa vào phase burst.
3. Dùng `Rally` khi cần Faith hoặc reposition.
4. Nếu boss không có add, đừng kỳ vọng shield bounce/pulse tự giải quyết single-target; ưu tiên weapon, rank skill, Block scaling và debuff.

## Gear Và Stat Priority

### Gear Nền

| Slot / Nhóm | Ưu tiên |
|---|---|
| Weapon | 1H item power cao, `+Rank Blessed Shield` hoặc `+Rank Shield Bash` nếu có, damage/crit/attack speed hợp skill |
| Shield | Block Chance, Block Damage Reduction, Armor, Maximum Life, affix hỗ trợ `Blessed Shield`/`Shield Bash` |
| Armor | Armor cap theo difficulty, All Resistance, Life, DR Close/Fortified |
| Jewelry | Resistance tới cap, Cooldown Reduction, Resource Generation, Critical Strike Chance |
| Boots | Movement Speed, Evade/utility; tank chậm quá sẽ farm kém |

### Aspect / Unique Package

| Package | Status | Dùng khi |
|---|---|---|
| `Shield Engine` | Community | Aspect/Unique tăng `Blessed Shield`, `Shield of Retribution`, `Shield Bash`, Block, shield hit. |
| `Resolve Wall` | Community + Inference | Power tăng `Resolve`, DR, Fortify hoặc size/damage cho Juggernaut skill. |
| `Defensive Baseline` | Inference | Aspect DR/Barrier/Fortify nếu mới lên difficulty và chết nhanh. |
| `Tempo Fix` | Inference | Movement Speed, `Rally`, CDR nếu farm quá chậm. |

Đừng đợi Unique mới chơi được. Leveling chỉ cần shield tốt, weapon đúng cấp, resistance không rách và một vài aspect phòng thủ/damage đúng hướng.

### Tempering / Masterworking Priority

Trong leveling chỉ cần temper rẻ, không chase roll hoàn hảo:

1. `Blessed Shield` hoặc `Shield Bash` damage/rank/size nếu hệ temper có.
2. Block/Armor/Life/Resistance cho shield/armor.
3. Resource Generation hoặc Cost Reduction nếu rotation khựng.
4. Movement Speed hoặc Rally/Aegis CDR nếu chạy map chậm.

Masterworking chỉ nên đầu tư sâu sau khi chuyển sang endgame và đã xác nhận build đáng giữ.

## Paragon Tổng Quan

- Status: Inference + Needs testing
- Checked: 2026-05-13

Khi mở Paragon, ưu tiên:

| Mục tiêu | Hướng node/glyph |
|---|---|
| Sống sót melee | Armor, Life, DR, Fortify, Block |
| Scale shield | Block Chance, Block Damage Reduction, shield skill damage |
| Scale Holy/Core | Core Skill, Holy Damage, damage to CC/Close nếu khớp tooltip |
| Resource ổn định | Resource, cost reduction, kill/hit recovery nếu có |

Không respec sâu chỉ vì planner endgame. Nếu đang level, một board sống sót đúng lúc thường giá trị hơn vài node damage chưa đủ điều kiện kích.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì | Rollback |
|---|---|---|
| Chết vì CC/burst | Giữ `Defiance Aura`, ưu tiên `Aegis`, thêm shield/DR | Không rollback cho tới khi hết chết vô lý |
| Pack tản, shield bay kém | `Holy Light Aura -> Condemn` | Nếu mất sustain/chết, quay lại Holy Light |
| Cạn Faith | Giữ `Clash`, nâng resource/Rally, giảm spam spender | Nếu vẫn khựng, hạ difficulty |
| Boss quá lâu | Tăng weapon/rank/debuff, test modifier single-target | Nếu mất sống sót, quay lại bản tank |
| Farm quá chậm nhưng không chết | Thêm Movement Speed hoặc thử `Falling Star` thay `Holy Light Aura` | Nếu lao vào sai và mất potion, quay lại |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | 3 pack đông liên tiếp không chết, shield path/pulse/ricochet có giá trị | Phải đuổi từng quái lẻ, mất nhịp liên tục |
| Elite | Giết elite trong 1-2 defensive cycle, không hết potion | Elite sống quá lâu hoặc burst chết khi cooldown chưa hồi |
| Boss | Có thể giữ vị trí và dùng `Blessed Shield` đều | Boss quá lâu, hết Faith, phải chạy vòng nhiều |
| Defense | `Defiance Aura`/`Aegis` cứu được khi bị CC/burst | Chết trước khi kịp phản ứng |
| Resource | Ít khi đánh chay quá 2-3 nhịp | Cạn Faith thường xuyên dù có `Clash`/`Rally` |
