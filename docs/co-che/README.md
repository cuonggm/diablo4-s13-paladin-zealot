# Cơ Chế Game Đang Hỗ Trợ Ở Season 13

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Trang Chủ](../../README.md)
- Liên quan: [Tổng Quan Mùa 13](../../research/tong-quan-mua-13.md), [Trạng Thái Paladin](../../research/trang-thai-paladin.md), [Thuật Ngữ](../thuat-ngu-va-co-che.md), [Lộ Trình Chơi](../lo-trinh-choi.md)

Thư mục này tách từng cơ chế thành file riêng để đọc nhanh khi đang chơi. Mỗi file dùng cùng một chuẩn:

- `Verified`: đã kiểm bằng Blizzard hoặc tooltip trong game.
- `Community`: đến từ Wowhead, Icy Veins, Mobalytics, Maxroll hoặc cộng đồng.
- `Inference`: suy luận của dự án từ cơ chế đã xác minh.
- `Needs testing`: cần test trực tiếp trước khi coi là khuyến nghị ổn định.

## Bản Đồ Cơ Chế

| Cơ chế | File | Trạng thái hỗ trợ Season 13 |
|---|---|---|
| Realm, Season Rank, Season Blessings | [Realm Và Season Rank](realm-season-rank.md) | Seasonal Realm có reward mùa; Eternal vẫn dùng hệ thống nền. |
| Skill Tree rework và Skill Variants | [Skill Tree Và Skill Variants](skill-tree-va-skill-variants.md) | Cập nhật nền cho toàn game từ 3.0.0. |
| Paladin, Faith, Oaths, Auras | [Paladin: Faith, Oaths, Auras](paladin-faith-oaths-aura.md) | Paladin là class chính thức nếu có Lord of Hatred. |
| Combat, rotation, defense | [Combat Và Defense](combat-defense-rotation.md) | Áp dụng mọi build; Paladin melee cần đặc biệt chú ý. |
| Level cap, difficulty, Torment | [Leveling Và Difficulty](leveling-difficulty-torment.md) | Level cap 70, Torment mở tới 12. |
| Gear, Affix, Aspect, Unique, Tempering, Masterworking | [Itemization, Tempering, Masterworking](itemization-tempering-masterworking.md) | Hệ item được đổi lớn ở 3.0.0. |
| Talisman, Seal, Charm, set bonus | [Talisman, Seal, Charm](talisman-seal-charm.md) | Hệ thống mới của Lord of Hatred. |
| Horadric Cube và crafting | [Horadric Cube](horadric-cube-crafting.md) | Crafting station mới ở Temis sau campaign. |
| Gems, Runes, socketables | [Gems, Runes, Socketables](gems-runes-socketables.md) | Weapon gems mạnh hơn; có tier Horadric qua Cube. |
| Paragon và Glyph | [Paragon Và Glyph](paragon-glyph.md) | Vẫn là power dài hạn, Season Rank có thêm Paragon Points. |
| War Plans và endgame loop | [War Plans Và Endgame Loop](war-plans-endgame-loop.md) | Endgame playlist mới sau Lord of Hatred campaign. |
| Activity, boss farming, push | [Activities Và Boss Farming](activities-boss-farming.md) | NMD, Helltide, Undercity, Lair Bosses, Pit, Hordes, Tower. |
| Loot Filter | [Loot Filter](loot-filter.md) | Có rule, condition, show/hide/recolor, import/export. |
| Map Overlay, Pathfinder, QoL | [Map Overlay, Pathfinder, QoL](map-overlay-pathfinder-qol.md) | Có cho toàn game từ 3.0.0. |
| Fishing và Echoing Hatred | [Fishing Và Echoing Hatred](fishing-echoing-hatred.md) | Fishing là hoạt động phụ; Echoing Hatred là thử thách hiếm. |

## Nên Đọc Theo Mục Tiêu Nào

| Mục tiêu | Đọc theo thứ tự |
|---|---|
| Tạo Paladin mới | [Realm](realm-season-rank.md) -> [Skill Tree](skill-tree-va-skill-variants.md) -> [Paladin](paladin-faith-oaths-aura.md) -> [Leveling](leveling-difficulty-torment.md) |
| Leveling 1-70 | [Combat](combat-defense-rotation.md) -> [Leveling](leveling-difficulty-torment.md) -> [Loot Filter](loot-filter.md) -> [Itemization](itemization-tempering-masterworking.md) |
| Vào endgame | [War Plans](war-plans-endgame-loop.md) -> [Activities](activities-boss-farming.md) -> [Paragon](paragon-glyph.md) -> [Talisman](talisman-seal-charm.md) |
| Sửa gear/build | [Itemization](itemization-tempering-masterworking.md) -> [Horadric Cube](horadric-cube-crafting.md) -> [Gems/Runes](gems-runes-socketables.md) -> [Loot Filter](loot-filter.md) |
| Push hoặc Hardcore | [Combat](combat-defense-rotation.md) -> [Paladin](paladin-faith-oaths-aura.md) -> [Leveling/Difficulty](leveling-difficulty-torment.md) -> [Activities](activities-boss-farming.md) |

## Phân Biệt Quyền Truy Cập

| Nhóm | Status | Ý nghĩa thực tế |
|---|---|---|
| `Permanent updates` | Verified | Skill Tree updates, level cap 70, itemization updates, Loot Filter, Map Overlay, Pathfinder, Pit overhaul, Torment tiers áp dụng toàn game theo Blizzard. |
| `Lord of Hatred expansion` | Verified | Paladin, Warlock, Skovos, War Plans, Echoing Hatred, Horadric Cube, Talisman, Fishing cần expansion. |
| `Season of Reckoning content` | Verified | Season Rank objectives/rewards, Season Blessings, Battle Pass/Reliquary và Tower/Leaderboards Beta là nội dung mùa. |

## Quy Tắc Sử Dụng Bộ Cơ Chế

- Không đổi build chỉ vì thấy cơ chế mới. Xác định vấn đề trước: damage pack, boss damage, defense, resource, cooldown, mobility, hay cảm giác chơi.
- Mỗi lần test chỉ đổi một trục lớn: skill, gear, Talisman, Paragon, difficulty hoặc activity.
- Với Paladin, luôn kiểm tra `Faith` và defensive layer trước khi chase damage.
- Với Season 13, đừng tìm borrowed power riêng của mùa. Sức mạnh chính đến từ hệ thống nền: Skill Tree, itemization, Talisman, Cube, War Plans, Paragon/Glyph và gear.

## Nguồn Chính

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Paladin overview: https://news.blizzard.com/en-us/article/24244399/wield-divine-might-as-the-paladin
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Wowhead - Season 13 community overview: https://www.wowhead.com/diablo-4/guide/gameplay/season-13-overview
