# Disciple Arbiter Lên Cấp - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Disciple Arbiter Cuối Game](disciple-arbiter-endgame.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: leveling Paladin theo hướng `Disciple Oath`, dùng cooldown/Disciple skill để mở `Arbiter` window, kết hợp Holy damage, aura và mobility. Đây là build cho fantasy thiên thần/caster-melee lai, không phải bản shield tank.

Triết lý: `Disciple` mạnh khi bạn hiểu window. Ngoài window, build cần đủ Faith/defense để không đứng chờ cooldown. Vì vậy leveling không bỏ `Advance`, `Rally` và `Defiance Aura` quá sớm.

Dấu ấn riêng: leveling dùng `Advance / Blessed Hammer / Falling Star / Defiance Aura / Rally / Condemn`. `Falling Star` là công tắc Disciple/mobility, `Blessed Hammer` là damage nền, `Condemn` gom pack để Holy damage trúng thật.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Leveling nên dùng `Advance / Blessed Hammer / Falling Star / Defiance Aura / Rally / Condemn`. | Community + Inference | Có generator/mobility, spender Holy, engage Disciple, defense, resource và pull. |
| `Disciple Oath` xoay quanh `Arbiter` window; không nên xả hết cooldown ngoài window nếu pack/elite sắp tới. | Verified + Inference | Cảm giác mạnh/yếu phụ thuộc cách canh window, không chỉ item. |
| `Falling Star` là skill then chốt vì vừa engage, vừa tạo nhịp cooldown/window. | Community + Inference | Dùng sai vị trí sẽ làm build chết nhanh dù damage ổn. |
| `Defiance Aura` giữ vai trò bảo hiểm; chỉ đổi sang `Holy Light Aura` khi đã đủ sống. | Inference | Disciple dễ tham damage/aura và mất Unstoppable. |
| Boss cần test uptime window: nếu cooldown lệch, build sẽ yếu dù pack clear tốt. | Needs testing | Pass nếu boss có window rõ; fail nếu chỉ chạy vòng chờ cooldown. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Blessed Hammer Paladin Leveling, community guide Season 13: https://www.icy-veins.com/d4/guides/blessed-hammer-paladin-leveling-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-talents/

## Build Identity

Tên build: `Paladin - Disciple Arbiter Lên Cấp`

| Mục | Chọn |
|---|---|
| Use case | Leveling 1-70, Holy caster-melee, speed vừa, pack đông |
| Oath | `Disciple` |
| Damage chính | `Blessed Hammer` ngoài window; Disciple/Arbiter window để burst |
| Setup chính | `Falling Star` engage/window, `Condemn` gom pack |
| Damage type chính | `Holy` cho hammer/aura; kiểm tra tooltip từng variant |
| Defense | `Defiance Aura`, reposition, Life/Armor/Resistance |
| Mobility | `Advance`, `Rally`, `Falling Star` |
| Weapon đề xuất | Weapon item power cao; 1H + shield nếu chết, 2H/offhand nếu content dễ |

## Skill Tree Setup Theo Game

- Status: Community + Inference
- Checked: 2026-05-13

Skill bar mặc định:

```text
Advance / Blessed Hammer / Falling Star / Defiance Aura / Rally / Condemn
```

| Nhóm skill tree | Chọn mặc định | Vai trò trong leveling | Có bắt buộc không? |
|---|---|---|---|
| `Oath` | `Disciple` | Mở engine `Arbiter`, tăng giá trị cooldown/Disciple skill | Bắt buộc cho concept này |
| `Basic` | `Advance` | Generate Faith, áp sát, thoát nhịp chậm | Rất nên giữ |
| `Core` | `Blessed Hammer` | Damage nền, Holy spender, clear pack sau khi gom | Bắt buộc |
| `Valor` | `Falling Star` | Engage, reposition, Disciple/window trigger theo variant | Rất quan trọng |
| `Aura` | `Defiance Aura` | Armor/Resistance, active Unstoppable | Mặc định an toàn |
| `Valor` | `Rally` | Movement Speed, Faith, pack-to-pack tempo | Rất nên giữ |
| `Justice` | `Condemn` | Pull/Stun, gom pack vào hammer/window | Rất nên giữ |
| `Aura` | `Holy Light Aura` | Flex thay Defiance khi đủ sống | Tùy vấn đề |

### Oath / Class Mechanic

Chọn:

```text
Oath: Disciple
```

Lý do:

- `Disciple` cho `Arbiter` window khi dùng cooldown/Disciple skill theo cơ chế hiện tại.
- `Falling Star`, aura và Holy skill hợp fantasy thiên thần hơn shield tank.
- Build có nhiều mobility, nhưng vẫn giữ `Defiance Aura` để không chết khi engage sai.

Rủi ro chính: cooldown lệch làm build yếu ngoài window. Nếu thấy downtime dài, sửa CDR/resource/rotation trước khi đổi toàn bộ skill.

## Tác Dụng Nhanh Của Skill Chính

| Skill | Nhóm / Oath / Type | Tác dụng chi tiết | Ý nghĩa cho Paladin |
|---|---|---|---|
| `Advance` | `Basic`, `Zealot`, `Physical` | Generate Faith, dash/áp sát. | Giữ nhịp leveling khi cooldown Disciple chưa đủ. |
| `Blessed Hammer` | `Core`, `Judicator`, `Holy` | Spender Holy, clear tốt khi enemy đứng đúng vùng. | Damage nền ngoài `Arbiter` window. |
| `Falling Star` | `Valor`, Disciple leaning theo variant | Leap/engage/reposition, có thể hỗ trợ Disciple window. | Nút mở combat và tạo cảm giác "thiên thần đáp xuống". |
| `Condemn` | `Justice`, utility | Pull/Stun/CC pack. | Gom enemy để hammer/window có giá trị thật. |
| `Defiance Aura` | `Aura`, `Juggernaut` | Armor/Resistance, active Unstoppable. | Bảo hiểm khi lao vào pack. |
| `Rally` | `Valor`, `Zealot` | Movement Speed/Faith. | Sửa tốc độ và resource. |

## Rotation Thực Chiến

### Pack Thường

1. `Rally` để tăng tốc và chuẩn bị Faith.
2. `Falling Star` vào rìa pack, không đáp giữa ground effect.
3. `Condemn` để gom pack.
4. Xả `Blessed Hammer` trong vùng enemy đã gom.
5. Dùng `Advance` khi thiếu Faith hoặc cần bám mục tiêu.
6. Giữ `Defiance Aura` cho CC/burst.

### Pack Đông / Elite

1. Canh `Falling Star` khi pack đủ đông hoặc có elite.
2. Vào rìa pack, `Condemn` kéo enemy vào vị trí.
3. Xả hammer trong window.
4. Nếu bị trả damage mạnh, dùng `Defiance Aura`, rồi `Rally` ra vị trí sạch.
5. Không chase quái lẻ bằng toàn bộ cooldown; dùng `Advance`/hammer tiết kiệm.

### Boss

1. Không mở bằng `Falling Star` nếu boss sắp nhảy/teleport.
2. Dùng `Advance` giữ Faith và bám boss.
3. Chỉ xả hammer mạnh khi boss đứng yên hoặc vừa hết mechanic.
4. Giữ `Defiance Aura` cho burst/CC.
5. Nếu window ngắn quá, test CDR/variant trước khi đổi damage engine.

## Gear Và Stat Priority

### Gear Nền

| Nhóm | Ưu tiên |
|---|---|
| Weapon | Item power cao, Holy/Core/cooldown-friendly affix |
| Armor | Life, Armor, Resistance, DR Close |
| Jewelry | CDR, Resource Generation, Critical Strike Chance, Resistance |
| Boots | Movement Speed, evade utility |
| Shield/offhand | Shield nếu chết; offhand nếu muốn CDR/damage |

### Aspect / Unique Package

| Package | Status | Dùng khi |
|---|---|---|
| `Arbiter Window` | Verified + Inference | Tăng thời lượng/giá trị window, giảm downtime cooldown. |
| `Holy Hammer` | Community | Tăng `Blessed Hammer`, Holy damage, cast/size/cost. |
| `Falling Star Tempo` | Community + Inference | Thêm charge/CDR/damage cho engage. |
| `Pack Control` | Inference | Tăng hiệu quả `Condemn`/CC. |
| `Safe Descent` | Inference | DR/Barrier/Fortify khi lao vào pack. |

### Stat Priority

1. Cooldown Reduction đủ để window không quá thưa.
2. `+Rank Blessed Hammer` hoặc Core/Holy damage.
3. Resource Generation / Cost Reduction.
4. Critical Strike Chance.
5. Attack Speed/cast speed nếu hưởng lợi.
6. Movement Speed.
7. Life/Armor/Resistance khi tăng difficulty.

## Tempering / Masterworking Priority

| Vấn đề | Temper nên tìm |
|---|---|
| Window thưa | CDR, `Falling Star` charge/CDR, Disciple cooldown support |
| Pack clear chậm | `Blessed Hammer` size/damage/rank, Holy damage |
| Boss chậm | Crit, damage during window, debuff/Vulnerable nếu có |
| Chết khi engage | Life, DR, Armor, Resistance, Barrier/Fortify |
| Cạn Faith | Resource Generation, Cost Reduction, Rally support |

## Paragon Tổng Quan

- Status: Inference + Needs testing
- Checked: 2026-05-13

| Mục tiêu | Hướng node/glyph |
|---|---|
| Arbiter/window | Disciple Skill, cooldown/window damage nếu có |
| Holy damage | Holy/Core damage, damage during buff/window |
| Mobility engage | Damage after movement/close nếu khớp |
| Resource | Faith/cost/recovery |
| Defense | Life, Armor, Resistance, DR Close |

Disciple leveling không cần Paragon phức tạp; cần nhất là window không lệch và không chết khi đáp xuống.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì | Rollback |
|---|---|---|
| Chết khi lao vào | Giữ `Defiance Aura`, dùng shield, thêm DR | Không đổi sang Holy Light cho tới khi ổn |
| Pack tản | Giữ `Condemn`, tăng pull/CC | Nếu boss chậm hơn mà pack không nhanh hơn, rollback |
| Window downtime | Thêm CDR, charge, resource; dùng cooldown đúng pack | Nếu vẫn thưa, hạ difficulty |
| Boss chậm | Canh boss đứng yên, thêm crit/debuff, test skill variant | Nếu mất pack clear, ghi log rồi rollback |
| Farm dễ | `Defiance Aura -> Holy Light Aura` hoặc thêm damage aura | Nếu mất Unstoppable gây chết, rollback |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | `Falling Star + Condemn + Hammer` xóa pack rõ | Cooldown xả xong pack vẫn sống rải rác |
| Elite | Window làm elite mất máu rõ | Elite sống lâu và bạn chạy chờ cooldown |
| Boss | Có window rõ, không hụt vì boss di chuyển | Boss nhảy khỏi damage liên tục |
| Defense | Defiance cứu được khi engage sai | Chết trong pack trước khi kịp cast |
| Resource | Advance/Rally đủ Faith | Cạn Faith ngoài window |
