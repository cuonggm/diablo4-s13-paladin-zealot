# Zealot Zenith Fervor - Voryn

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [README](../README.md)
- Liên quan: [Zealot Zenith Leveling](zealot-zenith-leveling.md), [Current Character Checklist](../docs/current-character-checklist.md), [Testing Log](../notes/testing-log.md)

Mục tiêu: build Paladin dùng `Zenith` bắt buộc, xoay quanh `Zealot Oath` / `Fervor`, đánh được pack đông lẫn elite/boss, di chuyển nhanh, và vẫn có lớp phòng thủ đủ cho melee.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Voryn |
|---|---|---|
| Build nên lấy `Zealot Oath`, vì `Fervor` làm Critical Strike của Zealot Skills echo thêm hit và khi max Fervor có thêm Fortify. | Verified | Đây là cơ chế chính, không chỉ là flavor. |
| `Zenith` là damage/burst bắt buộc, nên chọn variant theo mục tiêu: `Sermon of Steel` để spam/sustain, `Sunder` để boss burst, `Empyrean Edge` để speed farm. | Community + Inference | Voryn dùng `Zenith` như nút kết liễu pack/elite/boss, không chỉ để trang trí rotation. |
| Skill bar mặc định nên dùng `Zeal`, `Zenith`, `Fanaticism Aura`, `Defiance Aura`, `Rally`, `Falling Star`. | Community + Inference | Đủ damage nền, Zenith burst, tốc độ di chuyển, Faith support và Unstoppable. |
| Nếu chết nhiều, giữ `Defiance Aura` và dùng 1H + shield. Nếu sống ổn, đổi `Defiance Aura` sang `Condemn` để clear pack tản nhanh hơn. | Inference | Có hai mode rõ: an toàn và farm nhanh. |
| Build này phụ thuộc gear hơn build leveling đơn giản; đừng kỳ vọng mạnh ngay nếu thiếu crit, attack speed, cooldown/resource và Zealot aspect. | Needs testing | Cần test theo Torment hiện tại của Voryn trước khi Masterwork sâu. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Zealot Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/zealot-paladin-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/
- Mobalytics - Zenith Paladin, community guide Season 12, dùng để tham khảo cơ chế `Sermon of Steel`/Zenith spam: https://mobalytics.gg/diablo-4/builds/zenith-paladin

## Build Identity

Tên build: `Voryn - Zealot Zenith Fervor`

| Mục | Chọn |
|---|---|
| Use case | Endgame farm, War Plans, Nightmare Dungeon, Pit vừa, boss/elite nếu có burst window |
| Oath | `Zealot` |
| Damage chính | `Zenith` trong burst/spam window; `Zeal` làm damage nền và Fervor/Faith sink |
| Damage type chính | `Physical` theo tooltip hiện tại của `Zeal`/`Zenith`; kiểm tra lại nếu variant/item đổi damage type |
| Phong cách | Lao vào pack, giữ Fervor, bật Fanaticism, xả Zenith, chạy tiếp |
| Weapon đề xuất | 1H + shield cho bản ổn định; 2H chỉ khi không còn chết và muốn damage cao hơn |
| Mức gear | Trung bình đến cao |

Điểm quan trọng: đừng biến build này thành `Zeal` thuần. `Zeal` ở đây là nền để giữ nhịp khi `Zenith` chưa vào window tốt. Khi đã có đủ cooldown/attack speed/aspect, phần lớn quyết định kill elite/boss phải đến từ `Zenith`.

## Skill Bar Mặc Định

### Bản An Toàn Để Bắt Đầu

| Slot | Skill | Vai trò |
|---|---|---|
| Core | `Zeal` | Damage nền, nhiều hit, giữ nhịp Zealot/Fervor, xử lý quái còn sót |
| Ultimate | `Zenith` | Nút bắt buộc; xóa pack dày, elite, boss window |
| Aura 1 | `Fanaticism Aura` | Attack Speed, Critical Strike, active Weaken; bật trước Zenith window |
| Aura 2 | `Defiance Aura` | Armor/Resistance, active Unstoppable để không chết vì CC/burst |
| Valor 1 | `Rally` | Movement Speed, Faith support, giữ nhịp pack-to-pack |
| Valor 2 | `Falling Star` | Engage lớn, reposition, thêm mobility và setup elite/pack |

Đây là bản nên dùng trước nếu bạn chưa biết mình có đủ chịu đòn không. Nó không có pull, nhưng an toàn hơn vì giữ `Defiance Aura`.

### Bản Farm Pack Đông / Pack Tản

Đổi:

```text
Defiance Aura -> Condemn
```

Chỉ đổi khi:

- Armor/Resistance đã ổn ở Torment đang farm.
- Không chết vì CC trong pack.
- Pack tản làm `Zeal`/`Zenith` phải đuổi từng mục tiêu.

`Condemn` kéo/stun pack, giúp `Zenith` và `Zeal` đánh vào một cụm thay vì phí hit vào quái lẻ.

### Bản Push An Toàn Hơn

Đổi:

```text
Falling Star -> Aegis
```

Dùng khi elite/boss burst quá mạnh. Bạn mất một phần mobility, nhưng có thêm Block/Unstoppable/defensive button. Bản này hợp 1H + shield.

## Modifier / Variant Ưu Tiên

| Skill | Chọn trước | Ghi chú |
|---|---|---|
| `Zenith` | `Sermon of Steel` | Mặc định cho build xoay quanh Zenith; spam để kéo dài window nếu đủ Attack Speed/CDR. |
| `Zenith` | `Sunder` | Dùng cho boss hoặc khi chưa đủ điều kiện spam Zenith ổn định. |
| `Zenith` | `Empyrean Edge` | Dùng cho speed farm khi muốn Zenith kiêm Mobility; không phải bản tank nhất. |
| `Zeal` | Additional Strikes, Critical Strike Chance, `Zealot's Legacy`, Weaken/Cull nếu có uptime Weaken tốt | Giữ làm damage nền, không dồn toàn bộ gear vào `Zeal` nếu mục tiêu là Zenith. |
| `Fanaticism Aura` | Resource/Attack Speed/Crit, `Rite of Vengeance` hoặc `Rite of Humility` | `Rite of Humility` tốt nếu cần Vulnerable/debuff cho boss. |
| `Defiance Aura` | Max Life, Potency, Unstoppable, `Rite of Might` hoặc `Rite of Prayer` | Giữ active cho lúc bị CC hoặc trước elite burst, đừng bấm quá sớm. |
| `Rally` | Movement Speed, Duration, Faith support, `Words of Rejuvenation` | Nếu hay cạn Faith, sửa Rally/gear trước khi đổi build. |
| `Falling Star` | Additional Charge, Cooldown Reduction, Vulnerable/Weaken, `Fanatic Descent` nếu muốn gần Zealot hơn | Không lao thẳng vào ground effect; vào rìa pack rồi xoay vị trí. |
| `Condemn` | Pull size, cooldown, Weaken/Vulnerable | Chỉ thay defensive slot khi đã đủ sống. |
| `Aegis` | Cooldown Reduction, Unstoppable, Block DR | Bản shield/push dùng khi Voryn bị burst chết. |

## Gear Priority

### Aspect / Unique Quan Trọng

| Ưu tiên | Power | Status | Vì sao |
|---|---|---|---|
| Rất cao | `Aspect of the Zealot's Covenant` | Community | Tăng Fervor cap/duration và tăng giá trị echo hit; nên đặt ở slot mạnh như amulet nếu roll tốt. |
| Rất cao | `Revelator's Aspect` | Community | Tăng Zealot Skill damage, đặc biệt khi giữ Fervor cao. |
| Cao | `Aspect of Jacques' Fervor` | Community | Biến Fervor thành Critical Strike Damage, hợp Zenith/Zeal nhiều crit. |
| Cao | `Aspect of Apogeic Furor` | Community | Casting Ultimate giúp reset/giảm cooldown các skill khác, làm rotation Zenith mượt hơn. |
| Cao | `Virtuous Aspect` | Community | Dùng Valor Skill trước Zenith để tạo damage window. |
| Cao nếu thiếu sống | `Aspect of Might`, `Aspect of Valiance`, defensive/Barrier/Fortify aspect | Inference | Melee Zealot chết nhanh nếu chỉ đeo full offense. |
| Cao nếu có | `Griswold's Opus` | Verified item + Inference | Hợp lối đánh nhiều direct hit, crit, heal; tốt cho 1H + shield. |
| Tình huống | `Red Sermon` | Verified item + Needs testing | Tốt nếu muốn tăng `Zeal`, nhưng dùng 2H và hướng `Death or Glory` có rủi ro Life; không phải bắt buộc cho Zenith. |
| Tình huống | Shield Unique tốt hoặc Legendary Shield roll đẹp | Inference | Dùng khi ưu tiên sống sót/Block hơn damage 2H. |

### Stat Tấn Công

Ưu tiên theo thứ tự thực dụng:

1. `+Rank` hoặc damage cho `Zenith` / Ultimate / Zealot Skills nếu có.
2. `Critical Strike Chance` tới mức rotation crit ổn định.
3. `Attack Speed`, nhất là nếu dùng `Sermon of Steel`.
4. `Critical Strike Damage`.
5. `Zealot Skill Damage`, `Physical Damage`, `Damage to Weakened/Vulnerable`.
6. `Cooldown Reduction` nếu giúp Zenith/Falling Star/Rally/Defiance vào đúng nhịp.
7. `Strength`.

### Stat Phòng Thủ

Không bỏ qua các stat này chỉ vì build có Fortify từ Fervor:

- Armor cap theo Torment đang chơi.
- All Resistance cap theo Torment đang chơi.
- Maximum Life.
- Damage Reduction / DR while Fortified / DR from Close.
- Fortify Generation.
- Block Chance / Block Damage Reduction nếu dùng shield.
- Movement Speed trên boots/amulet nếu thiếu tốc độ farm.

### Gems / Runes / Talisman

| Slot | Gợi ý |
|---|---|
| Weapon | Nếu damage chính đang là Physical, ưu tiên hướng gem tăng Physical/Zenith theo hệ gem hiện tại; kiểm tra tooltip in-game trước khi socket. |
| Armor | Maximum Life hoặc Strength tùy gem tier và điểm yếu hiện tại. |
| Jewelry | All Resistance cho tới khi cap; sau đó mới tối ưu damage/utility. |
| Rune | Ưu tiên rune giúp Critical Strike, Ultimate/skill rank, cooldown hoặc defensive proc. |
| Talisman/Charm | Ưu tiên set/Charm hỗ trợ Zealot, Fervor, Zenith/Ultimate, Critical Strike, Attack Speed, Movement Speed, Fortify/DR. |

## Paragon Tổng Quan

- Status: Community + Inference
- Checked: 2026-05-13

Hướng Paragon nên giải quyết 4 việc:

| Mục tiêu | Board/Glyph hướng tới |
|---|---|
| Scale Zenith/Physical/Zealot | Board/glyph có Zealot Skill Damage, Ultimate/Physical/Crit scaling |
| Tăng damage từ giáp/đứng gần | `Castle`/armor-scaling node nếu đang dùng theo community Zenith setup |
| Giữ Fervor/Crit | `Fervent` hoặc glyph/node tương đương nếu có trong planner hiện tại |
| Sống sót khi melee | Shield/Block/Fortify/Maximum Life/DR board như `Shield Bearer` hoặc node tương đương |

Không copy Paragon nếu gear chưa giống guide. Nếu chưa đủ crit/attack speed/cooldown, hãy ưu tiên node giúp rotation mượt trước node damage xa vời.

## Rotation Thực Chiến

### Pack Thường

1. Dùng `Rally` để lấy tốc độ và chuẩn bị Faith nếu cần.
2. `Falling Star` vào rìa pack, không đáp giữa ground effect.
3. Bật active `Fanaticism Aura` nếu pack dày hoặc có elite.
4. Dùng `Zeal` để giữ Fervor và dọn quái thường.
5. `Zenith` khi pack tụ hoặc có mục tiêu lớn cần xóa nhanh.
6. Chạy tiếp bằng `Rally`/`Falling Star`.

Pack thường không nên bắt bạn dùng đủ mọi cooldown. Nếu pack nhỏ vẫn cần Zenith mới chết, damage/weapon/difficulty đang chưa đúng.

### Pack Đông / Elite

1. Vào rìa pack bằng `Falling Star`.
2. Bật `Fanaticism Aura` để Weaken/debuff.
3. Nếu dùng bản farm, cast `Condemn` để kéo/stun.
4. Xả `Zenith`; nếu dùng `Sermon of Steel`, spam Zenith để giữ window.
5. `Zeal` vào mục tiêu còn sống để giữ Fervor và clear phần còn lại.
6. `Defiance Aura` chỉ dùng khi bị CC, sắp bị burst, hoặc cần Unstoppable để đứng đánh nốt.

### Boss

1. Không mở boss bằng cách xả hết cooldown nếu boss sắp nhảy/teleport.
2. Giữ Fervor bằng `Zeal`, giữ `Fanaticism Aura` cho damage window.
3. Bật `Rally` trước burst nếu thiếu Faith/tốc độ.
4. Dùng `Zenith` khi boss đứng yên, stagger, hoặc vừa hết phase nguy hiểm.
5. Nếu dùng `Sunder`, canh boss đứng trong rift/detonation.
6. Giữ `Defiance Aura` cho CC/burst; đừng dùng chỉ để tăng damage nếu boss có phase nguy hiểm ngay sau đó.

## Khi Nào Đổi Variant

| Triệu chứng | Đổi gì |
|---|---|
| Chết vì CC/burst | Giữ `Defiance Aura`, đổi `Falling Star -> Aegis`, dùng shield, thêm Life/DR/Resistance. |
| Pack tản, clear mất nhịp | Đổi `Defiance Aura -> Condemn` nếu đủ sống; thêm pull/CC support. |
| Boss chậm | Dùng `Zenith - Sunder`, thêm Vulnerable/Weaken uptime, tăng Crit Damage/Zealot/Physical, kiểm tra cooldown window. |
| Zenith downtime quá lâu | Dùng `Sermon of Steel`, thêm Attack Speed/CDR, dùng Aspect hỗ trợ Ultimate/cooldown, giảm reliance vào `Zeal`. |
| Hay cạn Faith | Ưu tiên Rally/resource affix; nếu vẫn khựng, tạm đổi `Falling Star -> Advance` để có Basic generator. |
| Farm thấy chậm | Dùng `Empyrean Edge` hoặc giữ `Falling Star`, thêm Movement Speed, giảm bớt defensive thừa ở content thấp. |

## Điều Kiện Build Hoạt Động Tốt

- `Fervor` không rơi mất quá thường xuyên trong chuỗi combat.
- `Zenith` có damage đủ để elite mất phần lớn máu trong một window.
- Pack thường chết bằng `Zeal` + 1 cast/1 window `Zenith`, không cần kéo lê.
- Bạn có ít nhất một nút sống sót thật: `Defiance Aura`, `Aegis`, shield, hoặc defensive gear.
- Crit/attack speed đủ để Zealot echo và `Sermon of Steel` có giá trị.

## Dấu Hiệu Nên Hạ Difficulty Hoặc Chỉnh Gear

| Dấu hiệu | Nghĩa |
|---|---|
| Phải uống potion mỗi pack | Thiếu defense hoặc đang lao vào sai vị trí. |
| Elite sống qua 2-3 Zenith window | Damage/crit/cooldown chưa đủ hoặc difficulty quá cao. |
| Boss kéo dài nhưng bạn không nguy hiểm | Có thể chấp nhận tạm, nhưng nên thêm boss variant trước khi push. |
| Chết khi `Defiance Aura` đang cooldown | Cần Aegis/shield/DR hoặc học lại timing, không tăng Torment vội. |
| `Zeal` đang gây phần lớn damage còn Zenith chỉ phụ | Build đang lệch sang Zeal; hoặc Zenith chưa đủ gear để làm trục chính. |

## Checklist Test Cho Voryn

Ghi vào [Testing Log](../notes/testing-log.md) sau 1-2 dungeon hoặc boss:

```md
### Zealot Zenith Fervor Test

- Date:
- Patch:
- Level / Paragon:
- Difficulty / Torment:
- Weapon setup: 1H+Shield / 2H
- Skill bar: Zeal / Zenith / Fanaticism / Defiance / Rally / Falling Star
- Zenith variant: Sermon of Steel / Sunder / Empyrean Edge
- Pack clear:
- Elite clear:
- Boss kill time:
- Fervor uptime: Good / Medium / Bad
- Faith issue: None / Mild / Bad
- Deaths / potion pressure:
- Biggest problem:
- Change for next run:
- Verdict: Keep / Adjust / Drop
```

## Khuyến Nghị Hiện Tại

- Status: Inference + Community
- Checked: 2026-05-13
- Impact on Voryn: Nên test làm build endgame chính nếu bạn bắt buộc muốn `Zenith` và thích Zealot tốc độ.

Chơi bản mặc định trước:

```text
Zeal / Zenith / Fanaticism Aura / Defiance Aura / Rally / Falling Star
```

Ưu tiên 1H + shield nếu đang học Torment hoặc boss. Sau khi không còn chết, test:

```text
Defiance Aura -> Condemn
```

Nếu clear nhanh hơn rõ mà không chết nhiều hơn, dùng bản `Condemn` để farm pack đông. Nếu chết, quay lại `Defiance Aura`; build melee tốt là build không làm bạn mất nhịp vì nằm sàn.
