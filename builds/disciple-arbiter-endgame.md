# Disciple Arbiter Cuối Game - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Disciple Arbiter Lên Cấp](disciple-arbiter-len-cap.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: endgame Paladin `Disciple Oath` dùng `Arbiter` window, aura và Holy mobility để farm nhanh, burst pack/elite, giữ fantasy thiên thần rõ ràng mà vẫn có fallback phòng thủ.

Triết lý: Disciple không nên chơi như tank đứng lì hay Zealot spam hit. Build cần vào đúng window, ra khỏi vị trí xấu, rồi dùng aura/skill Holy để giữ áp lực giữa các cooldown.

Dấu ấn riêng: endgame chia 3 mode: `Arbiter Wing` mặc định, `Auradin Runner` để speed farm bằng aura, `Aegis Seraph` để push an toàn. Giữ lõi `Advance / Falling Star / Fanaticism Aura / Defiance Aura`, đổi một slot theo mục tiêu.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Endgame Disciple nên xoay quanh `Arbiter` window, không chỉ spam một Core skill. | Verified + Inference | Oath này mạnh khi cooldown/window được canh đúng. |
| Skill bar mặc định nên dùng `Advance / Falling Star / Aegis / Fanaticism Aura / Defiance Aura / Holy Light Aura`. | Community + Inference | Có generator, engage/window, defensive button, aura damage và Unstoppable. |
| `Holy Light Aura` là damage/sustain nền; `Fanaticism Aura` tạo tempo/crit; `Defiance Aura` giữ an toàn. | Community + Inference | Ba aura/utility làm build khác Zealot và Juggernaut rõ rệt. |
| Nếu thiếu Faith/tốc độ farm, đổi `Aegis -> Rally`; nếu chết, giữ `Aegis` và shield/DR. | Inference + Needs testing | Đây là công tắc chính giữa speed và push. |
| Điểm yếu cần test là downtime ngoài Arbiter và boss di chuyển khỏi window. | Needs testing | Cần log boss time, số lần chết, cảm giác cooldown. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Arbiter Disciple Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/arbiter-paladin-build/
- Icy Veins - Auradin Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/auradin-paladin-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/

## Build Identity

Tên build: `Paladin - Disciple Arbiter Cuối Game`

| Mục | Chọn |
|---|---|
| Use case | Endgame farm, speed farm, Holy aura fantasy, Nightmare/Pit vừa, boss nếu window tốt |
| Oath | `Disciple` |
| Damage chính | `Arbiter` window + `Holy Light Aura`/Disciple skill package |
| Setup chính | `Falling Star`, aura active, positioning |
| Damage type chính | `Holy` cho aura/Disciple package; kiểm tra tooltip từng variant |
| Phong cách | Vào pack bằng mobility, bật window, dọn bằng aura/Holy pressure, reposition liên tục |
| Weapon đề xuất | 1H + shield khi push; offhand/2H nếu farm dễ và cần damage/CDR |
| Mức gear | Trung bình đến cao; cần CDR/resource/defense cân bằng |

## Bảng Điều Khiển Mode

### `Arbiter Wing` - Bản Mặc Định

```text
Advance / Falling Star / Aegis / Fanaticism Aura / Defiance Aura / Holy Light Aura
```

| Slot | Skill | Vai trò |
|---|---|---|
| Basic | `Advance` | Generate Faith, bám mục tiêu, lấp downtime |
| Valor | `Falling Star` | Engage, reposition, mở Disciple/window |
| Valor | `Aegis` | Defensive button, Block/Unstoppable package |
| Aura 1 | `Fanaticism Aura` | Attack Speed/Crit/debuff window |
| Aura 2 | `Defiance Aura` | Armor/Resistance, active Unstoppable |
| Aura 3 | `Holy Light Aura` | Holy damage/sustain nền |

Đây là bản nên test trước vì có đủ fantasy, damage nền và defense.

### `Auradin Runner` - Speed Farm

Đổi:

```text
Aegis -> Rally
```

Dùng khi:

- Content đang farm không giết bạn.
- Cần chạy War Plans/Helltide/Whispers nhanh hơn.
- Faith hoặc movement là bottleneck chính.

Rollback nếu mất `Aegis` làm bạn chết hoặc bị CC/burst quá nhiều.

### `Aegis Seraph` - Push/Boss Lạ

Giữ `Aegis`, dùng shield và ưu tiên defensive package. Nếu vẫn chết, cân nhắc đổi một aura offense sang `Purify` hoặc defensive utility tùy tooltip hiện tại.

Dùng khi:

- Pit/Nightmare/boss lạ có burst khó đọc.
- Hardcore.
- Bạn cần học mechanic hơn là tối đa clear speed.

## Luật Flex Của Arbiter Wing

Disciple endgame phải giữ một câu hỏi trung tâm: làm sao giữ `Arbiter` window đủ lâu mà không chết khi window hết? Vì vậy flex không chỉ là damage, mà là cân bằng giữa uptime, Faith bridge, defensive latch và tốc độ map.

| Trục cần chỉnh | Skill ứng viên | Khi chọn | Vì sao hợp cơ chế |
|---|---|---|---|
| Window uptime | `Falling Star`, `Arbiter of Justice`, CDR package | Boss hoặc elite sống qua nhiều cycle | Càng nhiều thời gian trong Arbiter, Disciple scaling càng có giá trị |
| Resource/tempo | `Advance`, `Rally` | Faith khựng hoặc War Plans cần chạy nhanh | `Advance` bám mục tiêu, `Rally` sửa Faith và pack-to-pack |
| Defensive latch | `Aegis`, `Defiance Aura` | Push, Hardcore, burst khó đọc | Window mạnh không đủ nếu hết window là chết |
| Aura pressure | `Holy Light Aura`, `Fanaticism Aura` | Farm pack đông, muốn ít thao tác hơn | Aura giữ damage nền khi đang di chuyển |
| Grouping | `Condemn` | Pack tản làm aura/window tick vào mục tiêu lẻ | Gom mục tiêu để Holy pressure và Wing Strike có giá trị hơn |

Tự suy luận variant hợp lý: nếu đã có đủ CDR để gần perma-window, ưu tiên `Aegis` hoặc aura damage hơn thêm Basic. Nếu chưa có CDR/resource, giữ `Advance`/`Rally` lâu hơn; build chậm nhưng không khựng thường farm nhanh hơn build đẹp mà đứng chờ cooldown.

## Gear Priority

### Power Package

| Package | Status | Vì sao |
|---|---|---|
| `Arbiter Engine` | Community + Inference | Tăng uptime, damage hoặc hiệu quả window của `Arbiter`. |
| `Auradin Core` | Community | Tăng `Holy Light Aura`, aura damage, aura radius hoặc tick rate nếu có. |
| `Falling Star Tempo` | Community + Inference | Charge/CDR/mobility giúp vào pack đúng nhịp. |
| `Safe Seraph` | Inference | Shield, DR, Aegis, Defiance để không chết khi window kết thúc. |
| `Resource Bridge` | Inference | Faith/cost/CDR giúp ngoài window không bị đứng đánh chay. |

### Unique / Aspect Cần Theo Dõi

| Power | Status | Ghi chú |
|---|---|---|
| Unique/Aspect tăng `Arbiter` hoặc Disciple Skill | Community | Ưu tiên cao nếu không phá defensive breakpoint. |
| Unique/Aspect tăng aura/Holy Light | Community | Hợp `Auradin Runner` và farm pack đông. |
| Aspect tăng `Falling Star` charge/CDR | Community + Inference | Tăng tempo và window uptime. |
| Shield/Block/DR aspect | Inference | Cần cho `Aegis Seraph`, boss lạ và push. |
| Resource/cooldown aspect | Inference | Rất quan trọng nếu build bị downtime ngoài window. |

### Stat Tấn Công

1. Cooldown Reduction.
2. `+Rank` Disciple/Holy Light/Falling Star nếu có và đúng package.
3. Critical Strike Chance.
4. Attack Speed/cast speed nếu tăng aura/window throughput.
5. Holy/Disciple/Aura damage.
6. Critical Strike Damage.
7. Damage during buff/window hoặc damage to debuffed target.

### Stat Phòng Thủ

- Armor cap.
- All Resistance cap.
- Maximum Life.
- DR Close / DR while Fortified / DR while Barriered nếu có.
- Block Chance/Block DR nếu dùng shield.
- Movement Speed đủ để ra khỏi mechanic sau window.

## Tempering / Masterworking Priority

| Giai đoạn | Ưu tiên |
|---|---|
| Vừa vào endgame | CDR/resource + defense nền. |
| Farm ổn | Temper aura/Holy/Disciple damage, Falling Star charge/CDR. |
| Speed farm | Movement Speed, Rally/Falling Star uptime, aura radius/damage nếu có. |
| Push | Masterwork shield/armor/amulet defensive trước; giữ Aegis/Defiance breakpoint. |
| Boss | Masterwork item tăng Arbiter window, crit, CDR, debuff uptime. |

## Paragon Tổng Quan

- Status: Community + Inference
- Checked: 2026-05-13

| Mục tiêu | Board/Glyph hướng tới |
|---|---|
| Arbiter/window | Disciple Skill, damage during cooldown/window, CDR nếu có |
| Aura/Holy | Holy Damage, Aura Skill, damage over area/tick nếu có |
| Mobility burst | Damage after movement/skill cast nếu khớp |
| Resource bridge | Faith/recovery/cost |
| Defense | Life, Armor, Resistance, DR, Block nếu dùng shield |

Không chase full damage nếu ngoài window chết hoặc thiếu Faith. Disciple cần tính liền mạch hơn là một window đẹp trên planner.

## Rotation Thực Chiến

### Pack Thường

1. `Advance` hoặc `Rally` nếu dùng Runner để vào tầm.
2. `Falling Star` vào rìa pack, tránh ground effect.
3. Bật `Fanaticism Aura` khi pack dày hoặc có elite.
4. Giữ `Holy Light Aura` active/passive để dọn quái sát người.
5. Dùng `Aegis` khi bắt đầu ăn burst, không bấm trước khi pack chạm bạn.
6. Dùng `Advance` để bám mục tiêu còn sót và hồi Faith.

### Pack Đông / Elite

1. Chờ pack đủ đông rồi `Falling Star`.
2. Bật damage aura/window.
3. Dùng `Aegis` hoặc `Defiance Aura` tùy nguy cơ: Block/burst hay CC.
4. Đứng ở rìa pack để aura hit nhưng vẫn có đường thoát.
5. Khi window hết, `Advance`/reposition thay vì đứng trong ground effect.

### Boss

1. Không dùng `Falling Star` nếu boss sắp đổi phase.
2. Bật `Fanaticism Aura` và Holy package khi boss đứng yên.
3. Giữ `Aegis` cho hit lớn, `Defiance Aura` cho CC.
4. Dùng `Advance` để bám boss giữa các window.
5. Nếu boss di chuyển khỏi window quá nhiều, đổi thời điểm cast trước khi đổi gear.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì | Tiêu chí pass |
|---|---|---|
| Farm chậm nhưng không chết | `Aegis -> Rally` | Pack-to-pack nhanh hơn, Faith mượt hơn |
| Chết khi window hết | Giữ `Aegis`, thêm shield/DR, giảm aura offense | Số lần chết giảm rõ |
| Downtime dài | Thêm CDR, Falling Star charge, resource bridge | Ít chạy vòng chờ cooldown |
| Boss chậm | Canh window vào lúc boss đứng yên, thêm crit/debuff | Boss mất máu rõ trong window |
| Pack clear yếu | Tăng Holy Light/Aura package hoặc thêm CC/pull nếu có | Pack chết trong window, ít quái sót |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | Window/aura xóa pack, không cần chase nhiều | Pack sống rải rác sau window |
| Elite | Elite mất máu rõ trong Arbiter window | Elite sống lâu, cooldown hết rồi chạy vòng |
| Boss | Window trúng lúc boss đứng yên | Boss né window liên tục |
| Defense | Aegis/Defiance giải quyết burst/CC | Chết ngoài window hoặc sau khi đáp xuống |
| Resource | Advance/Rally package đủ Faith | Cạn Faith, phải đánh chay quá lâu |
