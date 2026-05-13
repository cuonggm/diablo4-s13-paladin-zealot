# Skill Tree Và Skill Variants

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Paladin](paladin-faith-oaths-aura.md), [Combat](combat-defense-rotation.md), [Itemization](itemization-tempering-masterworking.md), [Zealot Zenith Lên Cấp](../../builds/zealot-zenith-len-cap.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Skill Tree được redesign cho tất cả class ở 3.0.0. | Verified | Không dùng planner mùa cũ nếu chưa cập nhật Skill Variants. |
| Active Skills có nhiều branch modifier hơn, mở dần theo level. | Verified | Leveling cần đọc tooltip từng mốc, không chỉ lấy skill base. |
| Passive/Key Passive cũ không còn nằm nguyên trong Skill Tree; nhiều phần chuyển sang Aspect/Unique. | Verified | Gear và Skill Tree phải đọc cùng nhau. |
| Bonus Skill Variants có thể đổi tính chất/tag skill và tạo build-defining property. | Verified | Cơ chế này ảnh hưởng Affix, Paragon, Talisman, Aspect và Oath. |
| Người có Lord of Hatred mở toàn bộ 3 Bonus Skill Variants; không có expansion chỉ truy cập 2/3 theo Blizzard. | Verified | Nếu guide dùng variant bị khóa, cần phương án thay thế. |

## Cách Đọc Một Skill Trong Season 13

Mỗi skill nên đọc theo 5 lớp:

| Lớp | Câu hỏi |
|---|---|
| Base skill | Skill làm gì, tốn resource/cooldown không, đánh single-target hay AoE? |
| Branch 1 | Modifier nền giải quyết damage, resource, range, utility hay defense? |
| Branch 2 | Có thêm điều kiện nào cần setup không: crit, target bị CC, shield, aura, mark? |
| Bonus Skill Variant | Có đổi gameplay, skill tag, damage type hoặc vai trò skill không? |
| Scaling ngoài tree | Aspect/Unique/Talisman/Paragon nào thật sự scale skill này? |

## Khung Chọn Skill Bar

| Slot vai trò | Cần có gì | Lỗi thường gặp |
|---|---|---|
| Damage chính | 1 Core/engine rõ ràng | Nâng quá nhiều spender làm thiếu resource. |
| Generator/resource | Basic hoặc skill generate ổn | Bỏ generator quá sớm rồi rotation khựng. |
| Mobility | Dash/leap/charge/move speed | Farm chậm vì đi bộ giữa pack. |
| Defensive | DR, Block, Barrier, Unstoppable, immune hoặc heal | Dồn hết slot vào damage rồi chết khi bị CC/burst. |
| Utility/AoE | Pull, stun, knockdown, Weaken, Vulnerable, pack control | Pack tản khiến burst hụt giá trị. |
| Burst/Ultimate | Skill dùng cho elite, boss, pack dày hoặc panic button | Dùng Ultimate theo cooldown thay vì dùng đúng window. |

## Recommend Cho Paladin

| Mục tiêu | Gợi ý cơ chế | Status |
|---|---|---|
| Leveling mượt | Chọn một Core như `Zeal`, `Blessed Hammer`, `Blessed Shield`, `Divine Lance` hoặc `Shield Bash`; đừng đổi engine liên tục. | Inference |
| Giữ Faith | Dùng Basic/`Rally`/modifier resource trước khi chase damage. | Inference |
| Đúng fantasy Paladin | Ưu tiên shield, Aura, Holy/Light skill, `Aegis`, `Fortress`, `Consecration` nếu gameplay vẫn đủ nhanh. | Inference |
| Zealot Zenith | Giữ `Zeal`, `Fanaticism Aura`, `Rally`, `Zenith`; flex slot giải quyết defense hoặc grouping. | Inference + Needs testing |
| Bossing | Cần single-target variant hoặc debuff window, không chỉ AoE clear. | Needs testing |

## Khi Nào Nên Đổi Skill Variant

| Dấu hiệu | Hành động |
|---|---|
| Pack clear ổn nhưng boss quá lâu | Test variant single-target hoặc Oath/gear hỗ trợ boss. |
| Boss ổn nhưng map chậm | Test variant AoE/mobility hoặc thêm pull/stun. |
| Hết Faith liên tục | Đổi modifier resource/cost trước khi đổi toàn build. |
| Chết vì CC/burst | Đổi một slot sang defensive/Unstoppable trước khi giảm toàn bộ damage. |
| Talisman/Paragon không khớp tag | Kiểm tra Bonus Skill Variant có đổi tag/damage type không. |

## Quy Tắc Test

| Test | Pass | Fail |
|---|---|---|
| Variant mới | Sau 15-30 phút, clear/boss/defense tốt hơn mà rotation không khựng | Không rõ cải thiện gì hoặc làm mất resource/defense |
| Skill point mới | Giải quyết đúng vấn đề đã ghi trước test | Chỉ tăng số đẹp nhưng cảm giác chơi tệ hơn |
| Skill tag mới | Gear/Paragon/Talisman cùng scale đúng tag | Có item mạnh nhưng không tương tác với skill thật |

## Nguồn

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
