# Charm

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Talisman](talisman.md), [Seal](seal.md), [Horadric Cube](horadric-cube.md), [Loot Filter](loot-filter.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Charm gắn vào slot do Seal mở và có thể thay đổi tự do. | Verified | Dùng Charm để swap mode farm/boss/push mà không đổi toàn bộ gear. |
| Nhiều non-Unique Charms cùng affix có thể stack bonus. | Verified | Có thể sửa thiếu stat cụ thể, nhưng cần tránh mất cân bằng. |
| Set Charms có partial/full set bonus; có set class-specific và all-class. | Verified | Set bonus phải khớp Oath/skill engine thật của Paladin. |
| Unique Charms là mục tiêu craft/farm riêng qua Talisman/Cube route. | Verified | Đáng test như một build enabler, không chỉ là stat stick. |

## Phân Loại Charm

| Loại | Dùng để |
|---|---|
| Non-Unique Charm | Stack affix, sửa thiếu stat hoặc làm nền leveling/endgame sớm. |
| Set Charm | Mở partial/full set bonus, định hình mode build. |
| Unique Charm | Thêm power riêng, có thể đổi cách vận hành build. |
| Class-specific Charm | Tập trung vào class/Oath/skill cụ thể. |
| All-class Charm | Linh hoạt, dùng khi bonus tốt hơn set class hiện có. |

## Charm Cho Paladin Nên Tìm

| Nhu cầu | Affix/bonus đáng giữ |
|---|---|
| Zealot Zenith | Crit, Attack Speed, Core/Ultimate, Fervor, resource, Holy/Physical tùy tooltip. |
| Shield/tank | Block, DR, Life, Armor, Resist, Fortify/Barrier. |
| Bossing | Single-target, debuff, cooldown window, Judgement/Judicator. |
| Speed farm | Movement, cooldown, AoE, pickup/session comfort. |
| Hardcore | Defensive affix có điều kiện dễ duy trì. |

## Quy Tắc Đổi Charm

1. Đổi charm theo câu hỏi cụ thể: thiếu gì trong combat?
2. Nếu cần stack affix, stack vừa đủ để sửa vấn đề, không làm rỗng defense.
3. Nếu dùng set, ưu tiên đủ breakpoint set bonus trước khi chase roll hoàn hảo.
4. Giữ một bộ charm phòng thủ để rollback khi push hoặc Hardcore.
5. Tạo Loot Filter cho Talisman Set Bonus và affix Paladin cần.

## Rủi Ro Cần Test

| Rủi ro | Status | Pass/Fail |
|---|---|---|
| Stack quá nhiều damage charm. | Inference | Pass nếu clear nhanh hơn mà không chết; fail nếu potion/death tăng. |
| Đổi sang set bonus mới. | Needs testing | Pass nếu rotation mượt hơn; fail nếu damage chỉ tăng ở window hiếm. |
| Unique Charm làm mất affix nền. | Needs testing | Pass nếu power riêng bù rõ; fail nếu resource/defense tụt. |

## Nguồn

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Wowhead - Talisman community guide: https://www.wowhead.com/diablo-4/guide/systems/talisman

