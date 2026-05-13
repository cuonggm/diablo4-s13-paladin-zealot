# Juggernaut Bastion Cuối Game - Paladin

Checked: 2026-05-13
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](../docs/thuat-ngu-va-co-che.md), [Nguyên Tắc Build Paladin](../docs/nguyen-tac-build-paladin.md), [Paladin: Faith, Oaths, Auras](../docs/co-che/paladin-faith-oaths-aura.md), [Juggernaut Bastion Lên Cấp](juggernaut-bastion-len-cap.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

Mục tiêu: endgame Paladin `Juggernaut Oath` dùng shield làm trung tâm, đủ cứng để push/Nightmare/Pit vừa, vẫn clear được pack bằng `Blessed Shield` và không phụ thuộc vào một burst window mỏng.

Triết lý: build này thắng bằng độ ổn định. Nếu Zealot là tốc độ và burst, Juggernaut là build cho người muốn cầm shield thật sự: đứng được, block được, rồi biến defense thành damage.

Dấu ấn riêng: endgame chia thành 3 mode nhỏ: `Bastion Sentinel` làm điểm xuất phát dễ đối chiếu, `Condemn Bulwark` để gom pack, `Aegis Warden` để push/boss lạ. Mỗi mode chỉ đổi 1 slot hoặc 1 package gear.

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Endgame nên giữ `Juggernaut Oath` nếu mục tiêu là shield/tank/push an toàn. | Verified + Inference | Đây là Oath có logic phòng thủ rõ nhất, hợp Hardcore và content chưa thuộc. |
| Skill bar mặc định nên là `Clash / Blessed Shield / Rally / Fanaticism Aura / Defiance Aura / Falling Star`, với `Blessed Shield` lấy `Shield of Retribution`. | Community | Đây là baseline Blessed Shield Juggernaut endgame của Icy Veins Season 13. |
| `Blessed Shield` cần variant `Shield of Retribution` để thành Juggernaut; nếu không, dùng `Shield Bash` hoặc đổi sang Judicator. | Community | Không nên gọi là Oath Juggernaut nếu damage chính không tương tác với Oath. |
| Build cần shield/Block package; nếu thiếu shield tốt, damage sẽ tụt dù skill đúng. | Community | Gear quyết định build này mạnh hay chỉ là tank chậm. |
| Có thể đổi `Falling Star -> Condemn` nếu pack tản hoặc `Falling Star -> Aegis` nếu cần nút thủ lớn. | Inference + Needs testing | Đổi theo vấn đề, không đổi cả bar cùng lúc. |
| Điểm yếu chính là boss đơn mục tiêu nếu shield path/pulse và Block scaling chưa đủ. | Community + Inference | Cần test boss riêng trước khi kết luận build yếu/mạnh. |

Sources:

- Blizzard - Diablo IV Patch Notes 3.0.2, 2026-05-13: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Blizzard - Paladin class overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Icy Veins - Blessed Shield Paladin Endgame, community guide Season 13: https://www.icy-veins.com/d4/guides/blessed-shield-paladin-build/
- Icy Veins - Paladin Skills, community guide Season 13: https://www.icy-veins.com/d4/guides/paladin-skills/

## Build Identity

Tên build: `Paladin - Juggernaut Bastion Cuối Game`

| Mục | Chọn |
|---|---|
| Use case | Endgame farm ổn định, Nightmare Dungeon, Pit vừa, boss lạ, Hardcore leaning |
| Oath | `Juggernaut` |
| Damage chính | `Blessed Shield - Shield of Retribution`, shield hit, Block/Resolve/Thorns scaling; `Shield Bash` fallback |
| Damage type chính | Kiểm tra tooltip variant; base `Blessed Shield` là Holy/Judicator, `Shield of Retribution` đổi tag sang Juggernaut |
| Phong cách | Vào rìa pack, gom/giữ vị trí, ném shield, dùng defensive button đúng lúc |
| Weapon đề xuất | 1H + shield |
| Mức gear | Trung bình trở lên; càng có shield/Block package càng tốt |

## Bảng Điều Khiển Mode

### `Bastion Sentinel` - Bản Mặc Định

```text
Clash / Blessed Shield / Rally / Fanaticism Aura / Defiance Aura / Falling Star
```

| Slot | Skill | Vai trò |
|---|---|---|
| Basic | `Clash` | Generate Faith, giữ nhịp shield/Resolve |
| Core | `Blessed Shield - Shield of Retribution` | Damage chính, đổi sang Juggernaut, scale shield/Block/Thorns package |
| Valor | `Rally` | Movement Speed, Faith, tempo |
| Aura 1 | `Fanaticism Aura` | Attack Speed/Crit/debuff window, tăng nhịp ném shield |
| Aura 2 | `Defiance Aura` | Armor/Resistance, active Unstoppable |
| Valor | `Falling Star` | Engage/reposition, chạy pack-to-pack |

Đây là bản nên dùng đầu tiên khi mới vào endgame vì cân bằng giữa tốc độ, defense và resource. Nếu chưa có hoặc không thích `Shield of Retribution`, dùng `Shield Bash` làm Core và xem đây là `Shield Bash Bastion` thay vì Blessed Shield.

### `Condemn Bulwark` - Bản Gom Pack

Đổi:

```text
Falling Star -> Condemn
```

Dùng khi:

- Pack tản làm shield path/pulse trúng ít mục tiêu.
- Bạn không cần thêm mobility trong dungeon đang farm.
- Elite cần bị Stun/Pull để đứng trong damage window.

Rollback nếu mất nhịp di chuyển hoặc Condemn không giúp shield trúng nhiều hơn.

### `Aegis Warden` - Bản Push/Boss Lạ

Đổi:

```text
Falling Star -> Aegis
```

Dùng khi:

- Boss/elite có burst khó đọc.
- Hardcore hoặc push làm potion pressure cao.
- Bạn chấp nhận mất một phần mobility để có Block/Unstoppable chủ động.

Rollback nếu clear chậm hơn mà số lần chết không giảm rõ.

### `Fortress Warden` - Panic Button Tình Huống

Đổi:

```text
Fanaticism Aura -> Fortress
```

Chỉ dùng khi boss/push cần nút thủ lớn hơn damage window. Đây là mode test, không phải mặc định farm.

## Luật Flex Của Bastion

`Bastion` không phải "đeo nhiều skill thủ nhất có thể". Lõi hợp lý là shield Core + Resolve/Block + một damage window + một defensive latch. Flex slot quyết định build đang thiên farm, push hay boss.

| Trục cần chỉnh | Skill ứng viên | Khi chọn | Vì sao hợp cơ chế |
|---|---|---|---|
| Damage window | `Fanaticism Aura` | Mặc định farm/endgame | Attack Speed/Crit/debuff giúp shield engine hit đều hơn |
| Defensive latch | `Aegis`, `Fortress` | Push, Hardcore, boss lạ | Cho Block/Unstoppable hoặc vùng thủ để đứng lại khi elite phản công |
| Delivery | `Falling Star`, `Condemn` | `Falling Star` cho tempo; `Condemn` cho pack tản | Một skill đưa bạn tới pack, skill kia đưa pack về đúng đường shield |
| Resource bridge | `Clash`, `Rally` | Giữ mặc định trừ khi gear quá mạnh | Shield Core tốn Faith; thiếu bridge sẽ làm mọi damage aspect mất giá trị |
| Sustain/holy pressure | `Holy Light Aura` | Farm pack đông, cần heal nhẹ hơn là burst | Thêm damage/sustain nền, nhưng không thay `Defiance` khi đang thiếu defense |

Nếu muốn tự sửa: đổi `Delivery` trước khi đổi damage. Rất nhiều lần shield build yếu không phải vì thiếu multiplier, mà vì đường bay/pulse chỉ trúng 1-2 mục tiêu. Khi `Condemn` làm shield trúng nhiều mục tiêu hơn, DPS thật tăng dù sheet không đổi.

## Gear Priority

### Power Package

| Package | Status | Vì sao |
|---|---|---|
| `Blessed Shield Engine` | Community | Tăng rank, damage, AoE hoặc hiệu ứng của `Blessed Shield - Shield of Retribution`. |
| `Shield Bash Fallback` | Community + Inference | Dùng khi chưa mở/không có variant Juggernaut cho Blessed Shield hoặc muốn melee bash rõ hơn. |
| `Block Conversion` | Community + Inference | Biến Block/Shield stat thành damage hoặc DR, đúng bản sắc Juggernaut. |
| `Resolve Engine` | Verified + Inference | Giữ stack/giá trị `Resolve` để skill Juggernaut có damage/size tốt hơn. |
| `Defensive Anchor` | Inference | Armor/Resistance/Life/DR để đứng được trong content endgame. |
| `Tempo Patch` | Inference | Movement Speed, CDR, Rally/Falling Star uptime để tank không bị ì. |

### Unique / Aspect Cần Theo Dõi

| Power | Status | Ghi chú |
|---|---|---|
| Unique hoặc Aspect tăng `Blessed Shield`/`Shield of Retribution` | Community | Ưu tiên cao nhất nếu roll không phá defense. |
| Unique hoặc Aspect tăng `Shield Bash` | Community + Inference | Ưu tiên nếu chuyển sang fallback đúng Juggernaut. |
| Shield Unique tốt | Community + Inference | Đáng test ngay vì build phụ thuộc shield hơn hầu hết hướng Paladin khác. |
| Aspect tăng Block/Resolve/Fortify | Inference | Giá trị thực cao khi vào Torment/Pit, nhất là Hardcore. |
| Aspect gom pack hoặc CC | Inference | Hợp `Condemn Bulwark`, nhưng không thay thế defense nền. |
| Mythic Unique | Needs testing | Không coi là điều kiện bắt buộc; chỉ dùng nếu không làm mất shield/Block package. |

### Stat Tấn Công

1. `+Rank Blessed Shield`, `+Rank Shield Bash` hoặc Core Skill theo damage engine đang dùng.
2. Block-related damage nếu tooltip/aspect dùng Block.
3. Critical Strike Chance.
4. Critical Strike Damage.
5. Holy/Core/Close damage.
6. Attack Speed nếu giúp ném shield và generate Faith mượt.
7. Cooldown Reduction nếu ảnh hưởng `Defiance Aura`, `Falling Star`, `Aegis` variant.

### Stat Phòng Thủ

1. Armor cap theo Torment.
2. All Resistance cap.
3. Maximum Life.
4. Block Chance / Block Damage Reduction.
5. DR Close / DR while Fortified / DR while Shielded nếu có.
6. Fortify Generation.
7. Movement Speed đủ để không bị kẹt nhịp farm.

## Tempering / Masterworking Priority

| Giai đoạn | Ưu tiên |
|---|---|
| Vừa vào endgame | Temper Life/Armor/Resistance/Block trước, rồi mới tối ưu damage. |
| Farm ổn định | Temper `Blessed Shield` damage/rank/size, resource, CDR. |
| Push | Masterwork shield, chest, pants, amulet trước nếu chúng giữ defensive breakpoint. |
| Bossing | Masterwork weapon/shield và affix tăng single-target trước khi đổi toàn build. |

## Paragon Tổng Quan

- Status: Community + Inference
- Checked: 2026-05-13

| Mục tiêu | Board/Glyph hướng tới |
|---|---|
| Scale shield/Core/Holy | Core Skill, Holy Damage, shield skill, damage to Close/CC |
| Scale Block | Block Chance, Block DR, damage after Block nếu có |
| Giữ sống | Armor, Resistance, Life, Fortify, DR |
| Resolve/Juggernaut | Node/glyph tăng Juggernaut Skill hoặc `Resolve` |
| Tempo | Movement, CDR, resource nếu board có |

Không copy Paragon nếu gear chưa giống planner. Với Juggernaut, mất breakpoint defense có thể làm build từ "cứng" thành "chậm mà vẫn chết".

## Rotation Thực Chiến

### Pack Thường

1. `Rally` để lấy Movement Speed và Faith.
2. `Falling Star` vào rìa pack nếu cần engage.
3. Bật `Fanaticism Aura` nếu pack dày hoặc có elite.
4. Ném `Blessed Shield - Shield of Retribution` xuyên qua cụm mục tiêu; nếu dùng fallback thì `Shield Bash` vào cụm dày nhất.
5. Dùng `Clash` khi Faith thấp hoặc pack còn ít mục tiêu.
6. Giữ `Defiance Aura` cho CC/burst; nếu đang ở `Aegis Warden`, giữ `Aegis` cho hit lớn.

### Pack Đông / Elite

1. Vào vị trí sao cho đường bay/pulse của shield đi qua nhiều mục tiêu.
2. Nếu dùng `Condemn Bulwark`, kéo/stun trước rồi ném shield.
3. Bật `Fanaticism Aura` trước shield window.
4. Bật `Defiance Aura` khi bị CC hoặc chuẩn bị ăn burst.
5. Nếu dùng `Aegis Warden`, bật `Aegis` sau khi elite bắt đầu đánh, tận dụng Block/DR window.
6. Dọn quái còn sót bằng `Blessed Shield` hoặc `Clash` để hồi Faith.

### Boss

1. Đừng đứng xa quá nếu shield cần hit/return hoặc cần Close DR.
2. Giữ `Fanaticism Aura` cho boss đứng yên hoặc stagger.
3. Dùng `Rally` để sửa Faith và reposition sau mechanic.
4. Dành `Defiance Aura` cho CC/burst; nếu dùng `Aegis Warden`, giữ `Aegis` cho hit lớn.
5. Nếu boss quá lâu, ghi log: thiếu damage, thiếu debuff, thiếu uptime hay phải chạy quá nhiều.
6. Nếu chết ít nhưng boss quá chậm, test mode damage trước khi hạ toàn bộ defense.

## Khi Nào Đổi Variant

| Triệu chứng | Hành động | Tiêu chí pass |
|---|---|---|
| Pack tản | `Falling Star -> Condemn` | Shield trúng nhiều mục tiêu hơn, clear nhanh hơn |
| Boss/burst nguy hiểm | `Falling Star -> Aegis` hoặc thêm defensive aspect | Ít chết hơn mà boss không quá lâu |
| Rotation cạn Faith | Giữ `Clash`, thêm resource, rollback nếu bỏ `Rally` làm khựng | Ít phải đánh chay |
| Farm ì ạch | Quay về `Falling Star`, thêm Movement Speed/CDR | Thời gian pack-to-pack giảm rõ |
| Damage thấp dù sống tốt | Thêm offensive package nhưng giữ shield/Block core; cân nhắc `Shield Bash` nếu variant Blessed Shield không đủ | Elite mất máu rõ trong 1-2 cycle |

## Checklist Test

| Test | Pass | Fail |
|---|---|---|
| Pack clear | Shield path/pulse hiệu quả, ít chase quái lẻ | Pack tản và phải đánh từng con |
| Elite | Không chết trong CC/burst, kill trong vài cycle | Elite quá lâu hoặc hết potion |
| Boss | Giữ uptime ổn, defensive button cứu được | Boss quá lâu hoặc chết khi cooldown lệch |
| Resource | `Clash`/`Rally` đủ giữ Faith | Đứng đánh chay thường xuyên |
| Push | Ít chết hơn Zealot ở cùng content | Chậm hơn nhưng vẫn chết, không đáng giữ |
