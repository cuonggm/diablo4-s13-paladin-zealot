# Zealot Zenith Lên Cấp - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Zealot Zenith Cuối Game](zealot-zenith-endgame.md), [Checklist Nhân Vật Hiện Tại](../docs/checklist-nhan-vat-hien-tai.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: leveling Paladin theo đúng yêu cầu hiện tại: phải dùng `Zenith` khi mở Ultimate, xoay quanh `Zealot Oath` / `Fervor`, clear được pack đông, xử lý elite/boss ổn, di chuyển cao, và không quá mỏng khi lao vào melee.

Ghi chú: trước khi mở được Ultimate, build chỉ là giai đoạn "chuẩn bị cho Zenith". Khi `Zenith` mở, skill bar mới đúng bản build này.

Triết lý: bản này không phải copy 1:1 từ một guide có sẵn. Guide cộng đồng được dùng để đối chiếu skill và điểm yếu, còn lựa chọn cuối cùng dựa trên mục tiêu `Zealot + Zenith`, tooltip skill, cơ chế `Fervor`, nhu cầu leveling và kết quả test.

Dấu ấn riêng: leveling không bị ép thành một planner cố định. Đây là một hệ module: giữ `Zealot / Zeal / Zenith / Fanaticism`, còn slot còn lại xoay giữa `Defiance Aura`, `Condemn`, `Falling Star` hoặc `Aegis` theo vấn đề thật. Xem thêm [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md).

Nếu chỉ muốn setup nhanh: đọc [Kết Luận Nhanh](#kết-luận-nhanh), [Skill Tree Setup Theo Game](#skill-tree-setup-theo-game), [Rotation](#rotation), rồi [Gear Và Stat Priority](#gear-và-stat-priority). Các phần mô tả skill bên dưới là reference để tra khi cần.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Leveling nên dùng `Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith`. | Community + Inference | Đây là bản ổn định nhất: có Basic generator, damage nền, mobility, defense và Zenith burst. |
| `Zeal` là damage nền khi leveling; `Zenith` là nút burst cho pack dày, elite và boss window. | Community + Inference | Đừng cố chơi Zenith như damage duy nhất khi chưa có cooldown/gear endgame. |
| [`Fervor`](../docs/thuat-ngu-va-co-che.md#paladin) vẫn là cơ chế chính: Zealot hit nhiều, crit nhiều, giữ Fervor tốt thì clear pack mượt hơn và có Fortify khi đạt max Fervor. | Verified + Community | Build càng đánh liên tục càng mạnh, nên tránh downtime do thiếu Faith hoặc chạy quá xa pack. |
| Leveling nên ưu tiên `Sunder` cho Zenith nếu boss/elite chậm; dùng `Empyrean Edge` nếu farm thấp và cần tốc độ. | Community + Inference | `Sermon of Steel` để dành giai đoạn gần endgame khi đã có Attack Speed/CDR tốt. |
| Khi đạt level 70 và đủ gear/resource, chuyển sang build endgame bằng cách thay `Advance -> Falling Star`. | Inference | Đây là điểm chuyển rõ từ leveling sang `Zealot Zenith Cuối Game` endgame. |
| Có thể thay skill/variant nếu tooltip hoặc gear hiện tại giải quyết vấn đề tốt hơn guide cộng đồng. | Inference + Needs testing | Ghi giả thuyết vào Nhật Ký Test trước khi kết luận mạnh/yếu. |
| Dự án ưu tiên lối chơi `problem-first`: đổi skill để sửa vấn đề đang gặp, không đổi vì planner khác nhìn đẹp hơn. | Inference | Mỗi biến thể phải có mục tiêu test rõ: sống hơn, gom pack tốt hơn, boss nhanh hơn hoặc chạy map nhanh hơn. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Zeal Paladin Leveling, community guide Season 13: https://www.icy-veins.com/d4/guides/zeal-paladin-leveling-build/
- Icy Veins - Zealot Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/zealot-paladin-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/

## Build Identity

Tên build: `Paladin - Zealot Zenith Lên Cấp`

| Mục | Chọn |
|---|---|
| Use case | Leveling 1-70, campaign skip, Helltide/Whispers/Nightmare thấp, War Plans sớm |
| Oath | `Zealot` |
| Damage chính khi leveling | `Zeal` cho nhịp thường; `Zenith` cho burst |
| Damage type chính | `Physical` theo tooltip hiện tại của `Advance`, `Zeal`, `Zenith`; kiểm tra lại nếu item/variant đổi damage type |
| Mobility | `Advance` + `Rally`; thêm `Falling Star` chỉ khi bỏ bớt defense |
| Defense | `Defiance Aura`, Fortify từ Fervor, gear Life/Armor/Resistance |
| Weapon đề xuất | Weapon damage cao nhất ở đầu game; 1H + shield nếu chết, 2H nếu farm dễ |

## Skill Tree Setup Theo Game

- Status: Community + Inference
- Checked: 2026-05-13
- Sources: Blizzard Paladin overview + Icy Veins Paladin Skills/Zeal leveling

Skill tree Paladin hiện chia active skill theo 6 nhóm chính: `Basic`, `Core`, `Aura`, `Valor`, `Justice`, `Ultimate`. Build leveling này setup theo đúng thứ tự đó để dễ mở cây trong game, thay vì chỉ nhìn như 6 slot skill bar.

Ghi chú số liệu: các giá trị Faith/cooldown/damage phần dưới là [`Community`](../docs/thuat-ngu-va-co-che.md#source-status) từ Icy Veins skill guide Season 13 và nên đối chiếu tooltip trong game sau mỗi hotfix.

Skill bar mặc định khi đã mở `Ultimate`:

```text
Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith
```

| Nhóm skill tree | Chọn mặc định | Vai trò trong leveling | Có bắt buộc không? |
|---|---|---|---|
| `Oath` | `Zealot` | Mở cơ chế `Fervor`, crit echo, Fortify khi tiếp tục gain Fervor ở max stack | Bắt buộc cho concept này |
| `Basic` | `Advance` | Generate Faith, áp sát, bám boss, refresh nhịp khi cạn resource | Rất nên giữ khi leveling |
| `Core` | `Zeal` | Damage nền, spender chính, clear pack thường | Bắt buộc |
| `Aura` | `Fanaticism Aura` | Attack Speed, Critical Strike, debuff khi active | Bắt buộc |
| `Aura` | `Defiance Aura` | Armor/Resistance, active Unstoppable khi bị CC/burst | Mặc định an toàn |
| `Valor` | `Rally` | Movement Speed, Faith support, chạy pack-to-pack | Rất nên giữ |
| `Justice` | Không lấy ở bản mặc định | Chỉ thêm khi cần pull/CC/zone sustain | Tùy vấn đề |
| `Ultimate` | `Zenith` | Burst pack dày, elite, boss phase | Bắt buộc theo yêu cầu build |

Đây là bản nên chơi trong leveling vì `Advance` giải quyết hai vấn đề lớn: thiếu Faith và thiếu khả năng bám mục tiêu. Bản endgame có thể bỏ Basic, nhưng leveling bỏ `Advance` quá sớm thường làm rotation khựng.

### Khung Suy Luận Khi Muốn Đổi Skill

Không đổi vì guide khác nói mạnh hơn; đổi vì một vấn đề cụ thể:

| Vấn đề | Suy luận hợp lý | Test nhanh |
|---|---|---|
| Cạn Faith | Giữ `Advance`, nâng `Rally`, ưu tiên resource/Attack Speed thay vì thêm spender mới | 15 phút Helltide/Whispers, đếm số lần phải đánh chay |
| Pack thường chết chậm | Nâng `Zeal`, thêm modifier nhiều hit/AoE, hoặc dùng `Condemn` nếu cần gom quái | So thời gian clear 3 pack đông liên tiếp |
| Elite/boss chậm | Dùng `Sunder`, giữ buff `Fanaticism Aura` cho burst window, kiểm tra weapon item power | Test 3 elite hoặc 1 boss cùng difficulty |
| Chết khi lao vào | Giữ `Defiance Aura`, dùng 1H + shield, thêm Life/Armor/Resistance trước khi thêm damage | Test pack elite có CC/burst |
| Map chạy chậm | Thử `Empyrean Edge` hoặc thêm `Falling Star`, nhưng chỉ khi không chết và không thiếu Faith | Chạy 1 vòng Whispers/Helltide thấp |

Kết luận sau test nên ghi `Inference` nếu mới có lý thuyết, `Needs testing` nếu chưa đủ số lần thử, và chỉ giữ lâu dài nếu vấn đề ban đầu thật sự giảm.

### Tác Dụng Nhanh Của Skill Chính

| Skill | Nhóm / Oath / Type | Tác dụng chi tiết | Ý nghĩa cho Paladin |
|---|---|---|---|
| `Advance` | `Basic`, `Zealot`, `Physical` | Basic generator tạo khoảng 18 Faith; lao/tiến tới trước bằng vũ khí và gây Physical damage. Modifier có thể thêm `Weaken`, +Critical Strike Chance, Fortify khi hit đầu tiên, `Unhindered`, hoặc biến thành rush tạo `Fervor` qua `Vanguard's Rush`. | Nút vào combat, bám mục tiêu và chống cạn Faith. Đây là lý do leveling không nên bỏ Basic quá sớm. |
| `Zeal` | `Core`, `Zealot`, `Physical` | Spender tốn khoảng 20 Faith: đánh hit đầu rồi nối nhiều strike phụ. Modifier có thể thêm Fortify khi crit, thêm strike, `Weaken`, +Critical Strike Chance cao hơn lên enemy Weakened, auto-seek quanh người qua `Zealot's Legacy`, hoặc đổi sang biến thể high-risk dùng Life thay Faith. | Damage nền của build; càng nhiều hit càng tận dụng tốt `Fervor`, Attack Speed và crit. |
| `Fanaticism Aura` | `Aura`, `Zealot` | Aura tấn công, cooldown khoảng 15s và active tốn Faith. Passive kích khi tiêu Faith, tăng Attack Speed/Critical Strike Chance cho bản thân/đồng minh theo stack. Active debuff enemy gần người bằng `Weaken`; modifier có thể đổi sang `Vulnerable`, thêm resource, thêm stack, Critical Strike Damage, heal/Fortify khi enemy Weakened chết gần bạn. | Tạo damage window trước `Zeal`/`Zenith`; đây là aura không nên bỏ trong Zealot leveling. |
| `Defiance Aura` | `Aura`, `Juggernaut` | Aura phòng thủ, cooldown khoảng 20s và active tốn Faith. Passive tăng Armor và All Resistance; active cho `Unstoppable` khoảng 2s. Modifier có thể thêm Maximum Life, Healing Received, tự kích Unstoppable khi bị injured, Resolve support, heal định kỳ hoặc Thorns nova. | Nút sống sót chính khi melee, đặc biệt lúc chưa đủ gear hoặc đang tăng difficulty. |
| `Rally` | `Valor`, `Zealot` | Valor skill có khoảng 3 charge, cooldown khoảng 16s mỗi charge; tăng khoảng 20% Movement Speed trong 8s và tạo khoảng 22 Faith ngay khi cast. Modifier có thể thêm Critical Strike Chance, kéo dài thời lượng, thêm `Unhindered`, giảm cooldown/cost, tăng Faith và thêm charge qua `Words of Rejuvenation`, hoặc giảm cooldown Justice skill qua `Words of Inspiration`. | Giữ tốc độ chạy dungeon và cứu nhịp resource khi `Zeal` tiêu Faith nhanh. |
| `Zenith` | `Ultimate`, `Physical` | Ultimate cooldown khoảng 25s; gọi kiếm thần chém chiến trường, recast tạo nhát chém tiếp theo và Knockdown khoảng 2s. Modifier có thể cho `Unstoppable`, apply `Weaken`, giảm cooldown khi giết enemy Weakened, tăng Critical Strike Chance lớn trong vài giây. Variant lớn gồm `Sunder` burst/rift, `Empyrean Edge` mobility + crit damage, `Sermon of Steel` cho window spam ngắn. | Nút burst bắt buộc của build; dùng cho pack dày, elite và boss window, không dùng như damage duy nhất khi leveling. |

### Oath / Class Mechanic

Chọn:

```text
Oath: Zealot
```

Lý do:

- `Zealot` thưởng cho việc dùng nhiều `Zealot Skill` liên tục.
- `Advance`, `Zeal`, `Fanaticism Aura`, `Rally`, `Zenith` đều phục vụ trực tiếp loop này.
- `Fervor` làm các hit crit của Zealot có giá trị hơn; khi tiếp tục gain Fervor ở max stack còn có thêm Fortify, rất quan trọng vì build phải đứng gần.

Ghi chú setup: nếu chưa mở hoặc chưa chọn được `Oath`, cứ build theo `Advance -> Zeal -> Fanaticism/Rally`. Khi mở cơ chế class, chọn `Zealot` rồi mới đánh giá sức mạnh thật của build.

### Basic Skill Node

Chọn mặc định:

```text
Advance
```

Vai trò thực chiến:

- Mở combat vào đúng mục tiêu thay vì đi bộ vào pack.
- Generate Faith để `Zeal` không bị khựng.
- Giữ nhịp đánh khi `Rally` đang cooldown.
- Bám boss hoặc elite hay nhảy vị trí.

Tác dụng chi tiết:

- `Advance` là `Basic Skill`, `Oath Type: Zealot`, `Damage Type: Physical`, tạo khoảng 18 Faith mỗi lần dùng.
- Skill tạo Faith khi đánh trúng, nên nó là nguồn resource nền trước khi gear có đủ Resource Generation.
- Bản gốc là một cú tiến/lướt ngắn về phía trước và gây damage bằng vũ khí.
- Modifier phòng thủ có thể cho Fortify khi hit enemy lần đầu hoặc `Unhindered` để thoát slow/body block.
- Modifier tấn công có thể cho Critical Strike Chance hoặc `Weaken` enemy trong vài giây.
- `Vanguard's Rush` là hướng hợp Zealot nhất: biến `Advance` thành cú rush tạo `Fervor` trên mỗi strike và scale thêm damage theo số Fervor đang có.
- `Wave Dash` kéo skill sang Juggernaut/Resolve, còn `Flash of the Blade` kéo sang Disciple/Vulnerable. Hai hướng này chỉ nên test khi bạn chủ động đổi build khỏi pure Zealot.

Ưu tiên modifier:

| Ưu tiên | Hướng chọn | Khi nào đáng lấy |
|---|---|---|
| 1 | Crit / Fervor / Zealot support như `Vanguard's Rush` nếu tooltip trong game đúng với nhu cầu | Mặc định cho Paladin vì build cần Fervor ổn định |
| 2 | Fortify / defensive support | Khi lên difficulty mới hoặc dùng 2H hơi mỏng |
| 3 | Mobility / Unhindered | Khi hay bị slow/body block hoặc cần bám boss nhiều hơn |

Phương án thay thế:

| Thay thế | Tác dụng chính | Dùng khi | Đánh đổi |
|---|---|---|---|
| `Clash` | `Basic`, `Juggernaut`, `Physical`; đánh bằng vũ khí + shield, tạo Faith cao, có hướng tạo `Resolve`. `Skirmish` có thể biến thành Zealot cleave và cho Critical Chance thay vì Block/Resolve. | Chơi 1H + shield, hay chết, muốn thêm shield/Resolve/Block package | Ít linh hoạt hơn `Advance`; nếu không lấy `Skirmish` thì lệch khỏi Zealot loop. |
| `Brandish` | `Basic`, `Disciple`, `Holy`; phóng/unleash arc ánh sáng, có thể thêm Faith, cast speed, Vulnerable, thêm arc hoặc đường kiếm quay lại. | Muốn thử Disciple/Holy hybrid hoặc cần Basic có cảm giác an toàn hơn | Lệch khỏi Physical Zealot, không phải hướng leveling mặc định. |
| `Holy Bolt` | `Basic`, `Judicator`, `Holy`; ném Holy hammer tầm xa, có thể thêm Faith, `Judgement`, Slow, ricochet, pierce + Vulnerable hoặc biến thành Justice cooldown gây Stun. | Muốn đánh từ xa hoặc chuyển sang Judicator/Holy | Xem như đổi build, không còn là Zealot Zenith leveling chuẩn. |

Khuyến nghị: trong leveling, chỉ bỏ `Advance` nếu đã chắc chắn `Rally` + gear giải quyết được Faith và bạn không cần dash để bám mục tiêu.

### Core Skill Node

Chọn mặc định:

```text
Zeal
```

Vai trò thực chiến:

- Là spender chính và damage nền trước khi `Zenith` sẵn sàng.
- Đánh nhiều hit, hợp với `Fervor`, Attack Speed và Critical Strike.
- Dọn pack thường để không phải phí `Zenith` cho mọi nhóm quái nhỏ.

Tác dụng chi tiết:

- `Zeal` là `Core Skill`, `Oath Type: Zealot`, `Damage Type: Physical`, tốn khoảng 20 Faith mỗi lần cast.
- Bản gốc là chuỗi đánh nhanh: một hit mở đầu rồi nối tiếp bằng nhiều strike phụ. Vì vậy mỗi lần cast có nhiều cơ hội crit, proc và tương tác với `Fervor`.
- Modifier `Additional Strikes` tăng thêm 2 strike, rất hợp leveling vì pack thường chết nhanh hơn mà không cần đổi rotation.
- Modifier `Weaken` tự tạo debuff cho enemy, sau đó các nhánh tăng Critical Strike Chance hoặc damage lên enemy Weakened có giá trị hơn.
- `Zealot's Legacy` làm chuỗi đánh tìm thêm enemy quanh người, giảm cảm giác phải xoay từng mob lẻ.
- `Cull the Wicked` hợp khi uptime `Weaken` tốt: cleave rộng hơn, thêm strike và tăng damage lên enemy Weakened.
- `Death or Glory` đổi chi phí từ Faith sang Maximum Life và biến Zeal thành đánh vòng quanh người. Đây là biến thể nhiều damage/rủi ro cao, không nên lấy sớm nếu defense chưa ổn.

Ưu tiên modifier:

| Ưu tiên | Hướng chọn | Khi nào đáng lấy |
|---|---|---|
| 1 | Additional strikes / hit thêm / auto-seek như `Zealot's Legacy` | Mặc định cho leveling vì pack clear quan trọng hơn sheet damage |
| 2 | Critical Strike Chance hoặc tăng hiệu quả khi enemy bị `Weaken` | Khi đã có `Fanaticism Aura`, `Advance`, hoặc `Zenith` tạo debuff đều |
| 3 | Damage cao/rủi ro cao như `Death or Glory` | Chỉ cân nhắc khi đã có sustain/DR tốt; không ưu tiên sớm |

Phương án thay thế:

| Thay thế | Tác dụng chính | Dùng khi | Đánh đổi |
|---|---|---|---|
| `Divine Lance` | `Core`, `Disciple`, `Holy`; đâm nhiều hit bằng lance, có nhánh tăng damage liên tiếp lên cùng mục tiêu, tăng damage lên Vulnerable, giảm cost sau kill. `Zealous Joust` biến nó thành Zealot, thêm spear rộng hơn và Critical Strike Damage. | Boss/elite quá chậm và bạn muốn test single-target phụ | Chia Faith, rank và damage type; không nên dùng song song lâu trong leveling. |
| `Shield Bash` | `Core`, `Juggernaut`, `Physical`, shield; charge/bash trước mặt, có nhánh tính hit như Block, tăng size/range, Stun/Knockback qua `Smite`, hoặc scale với Resolve. | Cầm shield, cần Stun/control, muốn tank hơn | Chuyển dần sang Juggernaut hybrid; damage Zealot có thể yếu đi. |
| `Blessed Hammer` | `Core`, `Judicator`, `Holy`; ném búa xoáy, cost thấp, có nhánh giảm cost, tăng damage theo hit, Slow, cast speed, orbit quanh người hoặc mortar. | Muốn Holy caster/crusader style | Đây là hướng build khác, không phải bản Zenith leveling này. |
| `Blessed Shield` | `Core`, `Judicator`, `Holy`, shield; ném shield ricochet, có nhánh scale theo Block Chance, tăng Armor/Block, hồi Faith khi hit CC enemy, hoặc đổi sang boomerang/Thorns. | Muốn shield Holy fantasy | Cần gear shield/Block và thường kéo build khỏi Zealot Physical. |

Khuyến nghị: giữ một Core chính là `Zeal` cho tới level 70. Nếu `Zeal` yếu, sửa weapon, rank, Attack Speed/Crit hoặc difficulty trước khi đổi Core.

### Aura Skill Nodes

Chọn mặc định:

```text
Fanaticism Aura + Defiance Aura
```

`Fanaticism Aura` là aura tấn công chính:

- Tăng nhịp đánh và cơ hội crit cho `Zeal`.
- Tạo damage window trước `Zenith`.
- Hợp trực tiếp với `Fervor` vì build càng crit nhiều càng có giá trị.

Tác dụng chi tiết:

- `Fanaticism Aura` là `Aura Skill`, `Oath Type: Zealot`, cooldown khoảng 15s và active tốn khoảng 10 Faith.
- Passive kích khi bạn tiêu Faith: tỏa aura tăng Attack Speed và Critical Strike Chance cho bạn và đồng minh trong thời gian ngắn, có thể stack tới giới hạn của skill.
- Active debuff enemy gần người bằng `Weaken`, giúp giảm áp lực khi lao vào pack và mở đường cho các modifier đánh mạnh lên enemy Weakened.
- Modifier resource có thể thêm Maximum Resource hoặc Resource Generation cho bạn/đồng minh, rất đáng lấy nếu `Zeal` làm cạn Faith.
- `Rite of Vengeance` thêm Critical Strike Damage và cho crit tự kích passive, hợp khi crit chance đã ổn.
- `Rite of Humility` đổi active sang apply `Vulnerable`, tốt cho boss/elite nếu thiếu damage window.
- `Rite of Redemption` biến enemy Weakened chết gần aura thành nguồn heal/Fortify nhỏ, hợp farm pack đông.

Ưu tiên modifier cho `Fanaticism Aura`:

| Ưu tiên | Hướng chọn | Khi nào đáng lấy |
|---|---|---|
| 1 | Attack Speed / Critical Strike / extra passive stack | Mặc định |
| 2 | Resource Generation / Maximum Resource support | Khi hay cạn Faith trong dungeon dài |
| 3 | Vulnerable hoặc debuff active như `Rite of Humility` | Khi boss/elite chậm và cần damage window rõ hơn |

`Defiance Aura` là aura phòng thủ mặc định:

- Tăng Armor/Resistance nền.
- Active dùng như nút Unstoppable khi bị CC, freeze, knockdown hoặc bị kẹt trong pack.
- Giúp leveling ít chết hơn khi chưa đủ gear.

Tác dụng chi tiết:

- `Defiance Aura` là `Aura Skill`, `Oath Type: Juggernaut`, cooldown khoảng 20s và active tốn khoảng 25 Faith.
- Passive tăng Armor và All Resistance cho bạn/đồng minh, tức là nó có giá trị ngay cả khi bạn chưa bấm active.
- Active cho `Unstoppable` khoảng 2s, dùng để phá CC hoặc đứng đánh nốt khi pack/elite đang nguy hiểm.
- Modifier `Maximum Life` tăng độ dày máu trực tiếp, thường là lựa chọn rất tốt khi leveling.
- Modifier `Bonus Healing` tăng Healing Received, hợp nếu bạn đang không bị one-shot nhưng potion/heal chưa đủ.
- Nhánh Unstoppable tự kích khi injured có thể cứu lỗi timing, nhưng cần kiểm tra cooldown nội tại trong tooltip.
- `Rite of Prayer` thêm heal định kỳ và Resolve support; `Rite of Thorns` chỉ đáng xét nếu đã build Thorns/Retaliation rõ ràng.

Ưu tiên modifier cho `Defiance Aura`:

| Ưu tiên | Hướng chọn | Khi nào đáng lấy |
|---|---|---|
| 1 | Unstoppable / Potency / Maximum Life | Mặc định cho melee leveling |
| 2 | Healing hoặc sustain | Khi potion pressure cao nhưng không bị one-shot |
| 3 | Resolve/Thorns package | Chỉ lấy nếu đang chuyển sang shield/Juggernaut hybrid |

Phương án thay thế:

| Thay thế | Tác dụng chính | Dùng khi | Đánh đổi |
|---|---|---|---|
| `Defiance Aura -> Falling Star` | `Valor`, `Disciple`, `Holy`; bay lên rồi đáp xuống gây damage lúc cất cánh/hạ cánh, có thể apply Vulnerable, thêm charge, reset cooldown khi giết Vulnerable enemy, hoặc `Fanatic Descent` biến thành Zealot và apply Weaken. | Content đang dễ, không chết vì CC/burst, muốn speed farm nhanh hơn | Mất defensive aura và Unstoppable chủ động. |
| `Defiance Aura -> Condemn` | `Justice`, `Disciple`, `Holy`; sau nhịp delay sẽ kéo enemy vào, stun ngắn và gây damage. Có thể thêm Weaken, Vulnerable, size, cooldown refund hoặc kéo enemy về vị trí của bạn qua `Shepherd the Flock`. | Pack tản, cần pull để `Zeal`/`Zenith` đánh trúng nhiều mục tiêu | Mất phòng thủ, không nên dùng khi đang bị CC chết. |
| `Defiance Aura -> Holy Light Aura` | `Aura`, `Judicator`, `Holy`; passive gây Holy damage định kỳ lên enemy gần, active bắn/chuyền bolt ánh sáng và heal khi bolt quay về. Có nhánh thêm bounce, Fortify hoặc Stun. | Chơi party, cần sustain nhẹ hoặc muốn Holy aura fantasy | Damage/Zealot loop yếu hơn, không phải lựa chọn tối ưu mặc định. |

Khuyến nghị: không bỏ `Fanaticism Aura`. Skill được thay thường là `Defiance Aura`, và chỉ thay khi bạn đã sống ổn ở difficulty hiện tại.

### Valor Skill Node

Chọn mặc định:

```text
Rally
```

Vai trò thực chiến:

- Giữ tốc độ di chuyển giữa các pack.
- Bù Faith khi `Zeal` tiêu resource quá nhanh.
- Tạo nhịp chuẩn trước pack dày: `Rally -> Advance -> Fanaticism Aura -> Zeal/Zenith`.

Tác dụng chi tiết:

- `Rally` là `Valor Skill`, `Oath Type: Zealot`, có khoảng 3 charge và cooldown khoảng 16s.
- Khi cast, bạn nhận khoảng 20% Movement Speed trong 8s và nhận ngay khoảng 22 Faith, nên skill này vừa là mobility vừa là resource button.
- Modifier Critical Strike Chance giúp burst window tốt hơn nếu dùng `Rally` trước `Fanaticism Aura`/`Zenith`.
- Duration và Movement Speed/`Unhindered` giúp chạy map, thoát slow/body block và giữ tempo giữa pack.
- `Words of Rejuvenation` là hướng leveling rất ổn vì tăng lượng Faith tạo ra và thêm charge.
- `Words of Inspiration` chỉ đáng lấy nếu bản build đã dùng Justice skill như `Condemn`; nó tiêu charge để giảm cooldown Justice.
- `Words of Sacrifice` dùng Maximum Life làm chi phí và stack hiệu ứng, nên không hợp khi Paladin còn mỏng.

Ưu tiên modifier:

| Ưu tiên | Hướng chọn | Khi nào đáng lấy |
|---|---|---|
| 1 | Movement Speed / duration / Unhindered | Mặc định cho leveling |
| 2 | Faith hoặc cost reduction như `Words of Rejuvenation` | Khi `Zeal` bị ngắt nhịp vì thiếu Faith |
| 3 | Justice cooldown support | Chỉ lấy nếu đã thêm `Condemn`, `Purify` hoặc `Consecration` |

Phương án thay thế hoặc thêm vào slot khác:

| Skill | Tác dụng chính | Dùng khi | Đánh đổi |
|---|---|---|---|
| `Falling Star` | `Valor`, `Disciple`, `Holy`; leap/dive gây damage khi bay lên và khi đáp xuống. Modifier có thể apply Vulnerable, thêm charge, refund cooldown, tăng damage khi cast nối tiếp, tạo nhiều vụ nổ, biến thành Zealot qua `Fanatic Descent`, hoặc Knockdown + fissure qua `Faster Than Light`. | Muốn engage lớn, speed farm, hoặc vào pack nhanh hơn `Advance` | Nên thay `Defiance Aura`, không nên thay `Rally` nếu còn thiếu Faith. |
| `Aegis` | `Valor`, `Juggernaut`; tạo khiên ánh sáng, Taunt enemy gần và tăng Block Chance. Modifier có thể giảm cooldown, cho `Unstoppable`, kéo dài duration, tăng Block DR, tạo Resolve hoặc thêm Thorns/Retribution. | Hay chết vì burst, đang dùng shield, cần thêm Unstoppable/Block | Chậm hơn nhưng an toàn hơn; tốt cho Hardcore hoặc boss lạ. |
| `Shield Charge` | `Valor`, `Juggernaut`, `Physical`; channel charge bằng shield, đẩy enemy, có Damage Reduction khi channel và gây damage trong lúc lao. Modifier có thể tạo Resolve, tính hit như Block, tăng Retribution, biến thành Core hoặc tạo wave/knockback. | Shield build cần mobility và knockback/control | Lệch Juggernaut hơn, cần test với gear shield. |

Khuyến nghị: với leveling, `Rally` là skill giữ nhịp. Nếu thấy phải bấm Basic quá nhiều, đừng bỏ `Rally`; hãy nâng hoặc chỉnh modifier/resource trước.

### Justice Skill Node

Bản mặc định không lấy Justice skill trên skill bar vì đã đủ 6 slot. Justice chỉ nên thêm khi nó giải quyết một vấn đề cụ thể.

| Skill Justice | Tác dụng chính | Dùng khi | Thường thay slot nào |
|---|---|---|---|
| `Condemn` | `Justice`, `Disciple`, `Holy`; tụ lực ngắn rồi kéo enemy vào, stun ngắn và gây damage. Modifier quan trọng: `Weaken`, cooldown refund theo enemy hit, tăng size, Movement Speed, thêm charge + Vulnerable qua `Gather the Guilty`, hoặc kéo enemy về vị trí của bạn qua `Shepherd the Flock`. | Pack tản, cần pull/stun để `Zeal` và `Zenith` đánh vào một cụm | `Defiance Aura` nếu đã đủ sống |
| `Purify` | `Justice`, `Judicator`; phủ ánh sáng làm enemy bị Daze. Modifier có thể tạo Faith theo số enemy hit, giảm cooldown theo số enemy hit, tăng size, echo nhiều đợt, đổi sang Stun qua `Surrender`, hoặc biến thành cast lên enemy gây damage + Vulnerable qua `Absolution`. | Cần CC nhanh, Daze/Stun/Vulnerable, hoặc hồi Faith theo pack dày | `Defiance Aura` hoặc slot tạm trước khi có `Zenith` |
| `Consecration` | `Justice`, `Judicator`, `Holy`; tạo vùng sáng trong vài giây, heal bạn/đồng minh theo Maximum Life mỗi giây và gây Holy damage theo thời gian lên enemy trong vùng. Modifier có thể apply `Weaken`, tăng duration, Resource Generation, Fortify theo số enemy hit, tăng size/damage/resource discount qua `Hallowed Ground`, Immobilize/cast xa qua `Bastion`, hoặc nổ heal/damage cuối vùng qua `Sanctify`. | Boss kéo dài, cần zone sustain/heal/Fortify, hoặc chơi party | `Defiance Aura` ở content dễ, hoặc slot tạm trước `Zenith` |
| `Spear of the Heavens` | `Justice`, `Judicator`, `Holy`; gọi nhiều spear từ trời xuống, gây damage, Knockdown và nổ sau delay. Modifier có thể apply Vulnerable, thêm projectile, scale với Judgement hoặc đổi thành `Fist of the Heavens` dạng Core Holy. | Muốn test Holy burst/ranged control | Không khuyến nghị trong bản mặc định |

Khuyến nghị: nếu thêm Justice, bắt đầu bằng `Condemn`. Nếu đổi xong chết nhiều hơn hoặc bị CC chết, quay lại `Defiance Aura`.

### Ultimate Skill Node

Chọn bắt buộc:

```text
Zenith
```

Vai trò thực chiến:

- Burst pack dày, elite và boss window.
- Không dùng như damage duy nhất khi leveling, vì cooldown/gear chưa đủ để xoay quanh Ultimate hoàn toàn.
- Dùng tốt nhất sau khi pack đã tụ và `Fanaticism Aura` đang tạo damage window.

Tác dụng chi tiết:

- `Zenith` là `Ultimate Skill`, `Damage Type: Physical`, cooldown khoảng 25s và chỉ nên chọn khi build thật sự xoay quanh nó.
- Bản gốc gọi một divine sword chém qua chiến trường. Khi cast lại trong lúc active, Zenith tạo nhát chém tiếp theo và Knockdown enemy khoảng 2s.
- Modifier `Unstoppable` giúp bạn không bị CC khi đang ở Zenith window, rất đáng giá cho melee.
- Hai hướng `Weaken` gồm apply Weaken lên enemy hit hoặc giảm cooldown khi Zenith giết enemy đang Weakened. Hướng này hợp pack clear nếu bạn đã có nhiều Weaken từ `Fanaticism Aura`, `Advance`, `Zeal` hoặc `Condemn`.
- Modifier Critical Strike Chance cho một buff crit lớn sau khi cast, khoảng +30% trong 8s theo community tooltip, hợp với `Fervor` và `Zeal` ngay sau Zenith.
- `Empyrean Edge` biến Zenith thành Mobility Skill, dash tới enemy và thêm khoảng +25% Critical Strike Damage. Dùng khi farm dễ và muốn tốc độ.
- `Sermon of Steel` mở một window cast Zenith liên tục khoảng 4s trước khi cooldown bắt đầu; nhát thứ hai không Knockdown mà kéo dài window. Cần Attack Speed/CDR/resource/gear tốt hơn nên không ưu tiên quá sớm.
- `Sunder` biến Zenith thành một rift burst: một nhát lớn Knockdown rồi rift nổ sau khoảng 1s. Hợp elite/boss đứng yên hoặc boss stagger.

Ưu tiên modifier:

| Variant | Dùng khi | Ghi chú |
|---|---|---|
| `Sunder` | Elite/boss chậm, cần burst rõ trong một window | Khuyến nghị mặc định nếu leveling thấy single-target yếu |
| `Empyrean Edge` | Content dễ, muốn speed farm và thêm mobility/crit damage | Tốt cho Helltide/Whispers thấp, nhưng không phải bản an toàn nhất |
| `Sermon of Steel` | Gần 70, đã có Attack Speed/CDR/resource đủ để tập lối chơi endgame | Đừng lấy quá sớm nếu Zenith downtime vẫn dài |

Khuyến nghị: trước level 70, xem `Zenith` là nút kết thúc pack hoặc nuke elite. Nếu phải dùng `Zenith` cho mọi pack nhỏ, vấn đề thường nằm ở weapon, `Zeal` rank, Attack Speed/Crit hoặc difficulty.

## Thứ Tự Mở Và Nâng Skill

### Giai Đoạn Chưa Có Zenith

- Status: Inference
- Mục tiêu: mở đúng khung skill tree, giữ leveling mượt, không đổi build lung tung.

Ưu tiên theo thứ tự trong game:

1. `Basic`: lấy `Advance` trước để có Faith generator và mobility.
2. `Core`: lấy `Zeal`, rồi ưu tiên modifier giúp đánh nhiều mục tiêu hoặc thêm hit.
3. `Oath`: khi mở class mechanic, chọn `Zealot`.
4. `Aura`: lấy `Fanaticism Aura` để tăng Attack Speed/Crit.
5. `Valor`: lấy `Rally` nếu thấy thiếu Faith/tốc độ; lấy `Defiance Aura` trước nếu đang chết nhiều sau khi mở Aura tier.
6. Slot tạm trước Ultimate: dùng `Falling Star` để farm nhanh, `Condemn` để gom pack, hoặc `Aegis`/`Consecration` nếu cần sống.
7. Khi mở `Ultimate`, lấy `Zenith` và thay slot tạm ít cần nhất.

### Giai Đoạn Đã Có Zenith

- Status: Community + Inference
- Mục tiêu: giữ `Zeal` làm damage nền, dùng `Zenith` đúng window.

Ưu tiên nâng tiếp:

1. Nâng `Zeal` nếu pack thường chết chậm hoặc phải dùng `Zenith` quá thường xuyên.
2. Lấy modifier `Zenith` theo vấn đề đang gặp: `Sunder` cho elite/boss, `Empyrean Edge` cho speed farm thấp, `Sermon of Steel` khi gần endgame và đã có Attack Speed/CDR.
3. Nâng `Fanaticism Aura` nếu damage window chưa rõ hoặc crit/Fervor chưa ổn.
4. Nâng `Rally` nếu Faith cạn hoặc chạy map chậm.
5. Nâng `Defiance Aura` nếu tăng difficulty bắt đầu làm Paladin tụt máu nhanh.
6. Chỉ thêm `Condemn`, `Falling Star`, `Aegis` hoặc `Consecration` sau khi biết rõ mình đang thiếu pull, mobility hay defense.

## Rotation

### Pack Thường

1. `Advance` vào pack hoặc mục tiêu gần trung tâm.
2. Bật `Fanaticism Aura` nếu pack đông; pack nhỏ thì giữ cooldown.
3. Dùng `Zeal` cho tới khi pack gần chết.
4. Dùng `Zenith` nếu pack vẫn dày, có elite, hoặc cần kết thúc nhanh.
5. `Rally` để hồi Faith/chạy sang pack tiếp theo.

Không dùng `Zenith` cho mọi pack nhỏ. Nếu pack nhỏ vẫn phải dùng Zenith, hạ difficulty hoặc nâng weapon/Zeal trước.

### Pack Đông / Elite

1. `Advance` vào rìa pack, không lao vào ground effect.
2. Bật `Fanaticism Aura`.
3. `Zeal` vài nhịp để build/giữ Fervor.
4. `Zenith` khi quái tụ quanh người hoặc elite đang đứng yên.
5. `Defiance Aura` active khi bị CC, bị kẹt, hoặc thấy elite chuẩn bị burst.
6. `Rally` để hồi Faith hoặc thoát khỏi vị trí xấu.

Nếu pack tản làm Zenith hụt giá trị, ưu tiên tìm `Wildbolt Aspect` hoặc thử biến thể `Condemn`.

### Boss

1. Giữ `Zeal` làm damage nền và giữ Fervor.
2. Dùng `Advance` để bám boss, nhưng không dash mù vào lúc boss chuẩn bị AoE.
3. Bật `Fanaticism Aura` trước damage window.
4. Dùng `Zenith` khi boss đứng yên, vừa stagger, hoặc vừa hết phase di chuyển.
5. Giữ `Defiance Aura` cho CC/burst, không bấm sớm chỉ để "cho đủ rotation".
6. `Rally` khi thiếu Faith hoặc cần reposition.

Boss leveling không cần chết cực nhanh. Chỉ cần boss không kéo dài tới mức bạn cạn potion hoặc phải kite liên tục.

## Biến Thể Theo Vấn Đề

Các tên dưới đây là quy ước riêng để ghi log nhanh, không phải tên build từ guide cộng đồng.

### `Iron Pilgrim` - An Toàn Và Mượt

```text
Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith
```

Dùng khi:

- Đang lên level.
- Chưa biết defense có đủ không.
- Muốn ít chết, ít respec, ít phụ thuộc gear.

Logic riêng: `Advance` giải quyết Faith + bám mục tiêu, `Defiance Aura` giữ mạng, `Rally` giữ tempo. Đây là bản kiểm tra nền trước khi thêm ý tưởng tham lam.

### `Star Pilgrim` - Farm Nhanh Hơn

Đổi:

```text
Defiance Aura -> Falling Star
```

Dùng khi:

- Pack thường chết nhanh.
- Không bị CC/burst chết.
- Muốn di chuyển cao hơn và lao vào pack nhanh hơn.

Rủi ro: nếu chết vì lao vào sai vị trí, quay lại `Defiance Aura`.

### `Bellringer` - Pack Tản / Cần Gom Quái

Đổi:

```text
Defiance Aura -> Condemn
```

Dùng khi:

- Pack tản làm `Zeal` đánh lẻ.
- `Zenith` khó trúng nhiều mục tiêu.
- Bạn đã đủ Armor/Resistance/Life ở độ khó hiện tại.

Rủi ro: mất Unstoppable từ `Defiance Aura`; không nên dùng khi đang bị CC chết.

### `Aegis Pilgrim` - Khi Hay Chết

Giữ:

```text
Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith
```

Sau đó chỉnh:

- Dùng 1H + shield thay vì 2H.
- Thêm `Aspect of Might` hoặc defensive aspect.
- Ưu tiên Armor, Resistance, Maximum Life.
- Giữ active `Defiance Aura` cho thời điểm nguy hiểm, không dùng để mở pack thường.
- Hạ difficulty nếu elite mất quá lâu.

Nếu vẫn chết dù đã giữ `Defiance Aura`, test thay slot tạm hoặc slot mobility bằng `Aegis`. Đây là hướng chậm hơn nhưng hợp Paladin shield fantasy và giúp học boss/elite mới an toàn hơn.

## Gear Và Stat Priority

### Trong Leveling

| Giai đoạn | Ưu tiên |
|---|---|
| Đầu game | Weapon damage / item power cao hơn affix đẹp |
| Khi đã có `Zeal` | Attack Speed, Critical Strike Chance, `+Rank Zeal`, Movement Speed |
| Khi đã có `Zenith` | Critical Strike Chance, Critical Strike Damage, Zealot Skill Damage, cooldown/resource support |
| Khi tăng difficulty | Armor, All Resistance, Maximum Life, Damage Reduction, Fortify support |
| Khi gần level 70 | Giữ item có Greater Affix đúng stat để chuẩn bị endgame |

### Aspect Nên Để Ý

| Aspect | Status | Tác dụng |
|---|---|---|
| `Aspect of the Zealot's Covenant` | Community | Tăng giá trị Fervor/Zealot Oath, rất hợp cả leveling lẫn endgame. |
| `Revelator's Aspect` | Community | Tăng Zealot Skill damage khi giữ Fervor tốt. |
| `Aspect of Jacques' Fervor` | Community | Fervor thành Critical Strike Damage, tốt khi crit chance đã ổn. |
| `Virtuous Aspect` | Community | Valor Skill tạo damage window, hợp `Rally` trước Zenith/elite. |
| `Aspect of Glynn's Anvil` | Community | Tăng Resolve/DR package; đáng giữ nếu bản đang dùng `Aspect of Valiance`, shield hoặc cần phòng thủ. Patch 3.0.2 đã sửa lỗi aspect này. |
| `Aspect of Might` | Community | Basic Skill cho Damage Reduction, hợp vì leveling dùng `Advance` thường xuyên. |
| `Aspect of Valiance` | Community | Valor Skill tạo Resolve, tăng độ ổn định khi melee. |
| `Wildbolt Aspect` | Community | Kéo enemy lại gần, giúp Zeal/Zenith clear pack tản tốt hơn. |
| `Duelist's Aspect` | Community | Tăng Attack Speed khi dùng one-handed weapon, hợp bản 1H + shield. Patch 3.0.2 đã sửa một lỗi với one-handed/offhand. |

Không chase perfect roll lúc leveling. Có đúng power và giúp clear nhanh/sống ổn là đủ.

## Gems / Runes / Talisman

| Slot | Gợi ý |
|---|---|
| Weapon | Nếu damage chính là Physical, dùng gem hỗ trợ Physical theo hệ gem hiện tại; kiểm tra tooltip `Zeal`/`Zenith`. |
| Armor | Life hoặc Strength tùy điểm yếu hiện tại. |
| Jewelry | All Resistance cho tới khi ổn định ở difficulty đang chơi. |
| Rune | Movement, Critical Strike, resource hoặc defensive proc. |
| Talisman/Charm | Movement Speed, Attack Speed, Critical Strike Chance, Zealot/Fervor support, Resistance, Life. |

## Khi Nào Chuyển Sang Endgame Build

Chuyển sang [Zealot Zenith Cuối Game](zealot-zenith-endgame.md) sau level 70 hoặc khi thỏa ít nhất 4 điều:

- `Zeal` không còn làm bạn cạn Faith liên tục.
- Có đủ Attack Speed/Critical Strike Chance để Fervor/echo hoạt động rõ.
- `Zenith` giết elite tốt trong một damage window.
- Armor/Resistance không bị tụt quá thấp khi tăng Torment.
- Có ít nhất 2-3 Aspect chính của Zealot/Fervor/Zenith.
- Bạn có Movement Speed đủ để bỏ bớt Basic mobility.

Điểm chuyển thực tế:

```text
Leveling: Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith
Endgame:  Zeal / Zenith / Fanaticism Aura / Defiance Aura / Rally / Falling Star
```

Nếu bỏ `Advance` mà thấy thiếu Faith hoặc hụt nhịp bám boss, quay lại bản leveling thêm vài level/gear.

### Lộ Trình Chuyển Mượt

Không chuyển toàn bộ build trong một lần nếu đang chơi ổn. Dùng các bước nhỏ để giữ cảm giác tay:

| Bước | Đổi gì | Điều kiện giữ lại | Rollback |
|---|---|---|---|
| 1 | `Iron Pilgrim -> Star Pilgrim`: `Defiance Aura -> Falling Star` | Clear nhanh hơn và không chết vì CC/burst | Quay lại `Defiance Aura` |
| 2 | `Iron Pilgrim -> Bellringer`: `Defiance Aura -> Condemn` | Pack gom tốt hơn, Zenith trúng nhiều mục tiêu hơn | Quay lại `Defiance Aura` |
| 3 | Bản chuyển tiếp endgame: `Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith` giữ nguyên gear, chỉ nâng stat endgame | Faith vẫn mượt, elite chết ổn | Chưa cần bỏ `Advance` |
| 4 | `Advance -> Falling Star` để thành `Zenith Sentinel` | Không còn thiếu Faith, không hụt bám boss, mobility tốt hơn | Đổi lại `Advance` |
| 5 | Sau khi Sentinel ổn, mới test `Condemn Harvester`, `Aegis Bulwark` hoặc `Sunder Duelist` | Mode mới giải quyết đúng vấn đề | Quay lại `Zenith Sentinel` |

Ưu tiên giữ chung gear `Fervor Engine`, crit/attack speed, resource và defense nền trong suốt quá trình. Chỉ đổi skill slot trước; gear/paragon chỉ tối ưu sau khi mode mới thật sự đáng giữ.

## Dấu Hiệu Build Đang Đúng

- Pack thường chết bằng `Advance + Zeal`, không cần Zenith mỗi lần.
- Pack dày/elite mất phần lớn máu khi bật `Fanaticism Aura + Zenith`.
- `Rally` chủ yếu giúp chạy nhanh và hồi Faith, không phải cứu rotation liên tục.
- `Fervor` ít rơi mất trong chuỗi combat.
- Bạn không uống potion mỗi pack.
- Boss không quá nhanh nhưng vẫn chết trong nhịp ổn định, không kéo dài tới mức hết potion.

## Checklist Test

Ghi vào [Nhật Ký Test](../notes/nhat-ky-test.md):

```md
### Zealot Zenith Lên Cấp Test

- Date:
- Patch:
- Level:
- Difficulty:
- Mode tested: Iron Pilgrim / Star Pilgrim / Bellringer / Aegis Pilgrim
- Weapon setup: 1H+Shield / 2H
- Skill bar: Advance / Zeal / Fanaticism / Defiance / Rally / Zenith
- Zenith variant: Sunder / Empyrean Edge / Sermon of Steel
- Pack clear:
- Elite clear:
- Boss kill time:
- Fervor uptime: Good / Medium / Bad
- Faith issue: None / Mild / Bad
- Deaths / potion pressure:
- Change next run:
- Verdict: Keep / Adjust / Drop
```

## Khuyến Nghị Hiện Tại

- Status: Inference + Community
- Checked: 2026-05-13
- Impact on Paladin: Đây là bản leveling nên dùng trước build endgame `Zealot Zenith Cuối Game`.

Chơi theo lộ trình riêng của dự án:

1. Bắt đầu bằng `Iron Pilgrim` để lấy nền sống sót/resource.
2. Nếu pack tản hoặc Zenith hụt nhiều mục tiêu, test `Bellringer`.
3. Nếu content đã dễ và không chết, test `Star Pilgrim`.
4. Nếu tăng difficulty bắt đầu đau, quay lại `Iron Pilgrim` hoặc test `Aegis Pilgrim`.

Mặc định ban đầu:

```text
Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith
```

Chỉ đổi `Defiance Aura` sang `Falling Star` hoặc `Condemn` khi đã chắc mình không chết vì thiếu defensive button. Với leveling, ổn định quan trọng hơn damage sheet: chết hoặc đứng chờ Faith đều làm tốc độ thực tế chậm hơn.
