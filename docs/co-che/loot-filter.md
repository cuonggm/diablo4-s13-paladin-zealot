# Loot Filter

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Itemization](itemization-tempering-masterworking.md), [Talisman](talisman-seal-charm.md), [War Plans](war-plans-endgame-loop.md), [Checklist Nhân Vật](../checklist-nhan-vat-hien-tai.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Loot Filter có thể hide, show hoặc recolor gear item ở drop, inventory, stash và vendor. | Verified | Giảm thời gian nhìn rác, tăng thời gian chơi. |
| Loot Filter không ảnh hưởng non-gear items như Temper manuals, reagents, gems hoặc currency. | Verified | Đừng kỳ vọng filter tự xử lý material/gem. |
| Một filter có 1-25 rules, rules chạy từ trên xuống. | Verified | Rule quan trọng phải đặt cao hơn rule hide rộng. |
| Conditions gồm Item Power, rarity, Ancestral, Codex upgrade, GA, item type, required/optional affixes, specific Unique, Talisman Set Bonus. | Verified | Có thể tạo filter rất cụ thể cho Paladin/Zealot. |
| Có hotkey toggle filter và import/export. | Verified | Luôn biết cách tắt filter khi nghi bị ẩn đồ tốt. |
| Patch 3.0.1a từng sửa lỗi filter với Aspect roll cao hơn Codex. | Verified | Nếu nghi ngờ, toggle off để kiểm tra pile đồ. |

## Nguyên Tắc Rule

| Rule type | Dùng để | Ví dụ |
|---|---|---|
| `Show` | Ghi đè rule hide ở dưới | Show shield/flail có affix cần. |
| `Recolor` | Làm nổi item cần kiểm | Recolor Unique, GA, Talisman set. |
| `Hide Text Label/Hide All` | Giấu item không muốn nhặt | Hide rarity thấp khi không dùng base. |

Rule chạy từ trên xuống. Đặt rule giữ đồ quan trọng trước rule hide rộng.

## Filter Leveling

| Rule | Action | Lý do |
|---|---|---|
| Unique/Mythic Unique | Recolor | Luôn kiểm. |
| Legendary có Codex upgrade | Recolor/Show | Nâng Aspect/Codex. |
| Weapon/offhand/shield item power cao | Show/Recolor | Leveling damage phụ thuộc weapon. |
| Item có GA | Recolor | Có thể là base tốt. |
| Rarity thấp quá cũ | Hide | Chỉ hide khi không dùng làm Cube base. |

## Filter Endgame Paladin

| Nhóm | Rule nên có |
|---|---|
| Slot chính | Flail, sword, shield, gloves, ring, amulet, boots. |
| Offense | Skill rank, Core/Ultimate damage, crit, attack speed, damage type đúng. |
| Defense | Armor, All Resistances, Life, DR, Block/Fortify nếu có. |
| Resource | Resource generation, cost reduction, cooldown, Faith support nếu có. |
| Talisman | Set bonus đúng build, Seal nhiều slot, Charm affix đúng. |
| Unique target | Specific Unique cho Zeal/Blessed Shield/Blessed Hammer/Disciple/shield. |

## Filter Theo Buổi Farm

| Buổi chơi | Nên bật filter |
|---|---|
| Leveling | Rộng, ưu tiên item power/Aspect/GA. |
| Gear session | Rộng vừa, show slot đang thiếu và affix chính. |
| Boss target | Specific Unique + slot liên quan. |
| Talisman session | Talisman Set Bonus + Seal/Charm affix. |
| Material session | Có thể hide ít hơn nếu cần salvage/crafting base. |
| Push session | Chỉ highlight upgrade thật, tránh dừng quá nhiều. |

## Lỗi Thường Gặp

| Lỗi | Cách sửa |
|---|---|
| Hide rarity thấp quá sớm | Nhớ Season 13 dùng Common/Magic/Rare làm Cube base; hide sau khi đã hiểu mình cần base gì. |
| Rule Show đặt dưới Hide | Kéo Show/Recolor quan trọng lên trên. |
| Filter quá chi tiết khi leveling | Leveling thay đồ nhanh, filter quá hẹp dễ bỏ upgrade. |
| Không biết filter có hoạt động không | Dùng hotkey toggle off để xem pile đồ. |
| Import filter của người khác | Kiểm tra class-specific Unique/Talisman rule có đúng Paladin không. |

## Nguồn

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
