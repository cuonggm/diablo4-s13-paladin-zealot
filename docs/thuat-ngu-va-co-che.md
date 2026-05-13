# Thuật Ngữ Và Cơ Chế

Checked: 2026-05-13

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Tổng Quan Mùa 13](../research/tong-quan-mua-13.md), [Trạng Thái Paladin](../research/trang-thai-paladin.md), [Cơ Chế Game Season 13](co-che/README.md), [Nguyên Tắc Build Paladin](nguyen-tac-build-paladin.md), [Lộ Trình Chơi](lo-trinh-choi.md), [Checklist Nhân Vật Hiện Tại](checklist-nhan-vat-hien-tai.md), [Zealot Zenith Lên Cấp](../builds/zealot-zenith-len-cap.md), [Zealot Zenith Cuối Game](../builds/zealot-zenith-endgame.md)

File này là glossary trung tâm. Thuật ngữ game giữ bằng tiếng Anh để khớp UI, patch note và guide cộng đồng; phần ghi chú giải thích ngắn bằng tiếng Việt.

## Tra Nhanh

| Muốn hiểu | Đọc phần |
|---|---|
| `Verified`, `Community`, `Inference`, `Needs testing` | [Trạng thái nguồn](#source-status) |
| `Seasonal Realm`, `Eternal Realm`, `Level Cap`, `Season Rank` | [Nhân vật, Realm, Progression](#character-progression) |
| `Faith`, `Oath`, `Fervor`, `Zealot`, `Judgement`, `Resolve`, `Arbiter` | [Paladin](#paladin) |
| `Basic`, `Core`, `Aura`, `Valor`, `Justice`, `Ultimate`, `Rotation`, `CC` | [Skill và Combat](#skill-combat) |
| `Armor`, `Resistance`, `Fortify`, `Barrier`, `Block`, `Unstoppable` | [Defense](#defense) |
| `Aspect`, `Unique`, `Mythic Unique`, `GA`, `Tempering`, `Masterworking` | [Gear và Itemization](#gear-itemization) |
| `War Plans`, `Talisman`, `Horadric Cube`, `Loot Filter`, `Map Overlay` | [Season 13 Systems](#season-13-systems) |
| `Helltide`, `Whispers`, `Nightmare Dungeon`, `The Pit`, `Lair Bosses` | [Activities](#activities) |

Nếu cần hướng dẫn thực hành chi tiết theo từng hệ thống, đọc [Cơ Chế Game Season 13](co-che/README.md). File hiện tại giữ vai trò glossary ngắn.

<a id="source-status"></a>
## Trạng Thái Nguồn

| Status | Nghĩa |
|---|---|
| `Verified` | Đã kiểm bằng nguồn chính thức như Blizzard news/patch notes hoặc tooltip trong game. |
| `Community` | Đến từ guide/cộng đồng như Icy Veins, Wowhead, Maxroll, Mobalytics, Reddit, Discord. Dùng để tham khảo và so sánh, không phải khuôn bắt buộc. |
| `Inference` | Suy luận từ dữ kiện đã có để áp dụng cho Paladin. Cần ghi rõ cơ chế liên quan, kỳ vọng và rủi ro; đây không phải xác nhận chính thức. |
| `Needs testing` | Cần test trực tiếp trong game trước khi coi là khuyến nghị ổn định. Nên có tiêu chí pass/fail cụ thể. |

<a id="character-progression"></a>
## Nhân Vật, Realm, Progression

| Term | Ghi chú tiếng Việt |
|---|---|
| `Class` | Lớp nhân vật: Barbarian, Druid, Necromancer, Rogue, Sorcerer, Spiritborn, Paladin, Warlock. |
| `Build` | Cách phối skill, gear, Aspect, Paragon, Talisman để tạo lối chơi. |
| `Seasonal Realm` | Realm mùa; reset nhân vật theo mùa, có Season Rank/Blessings/reward mùa. |
| `Eternal Realm` | Realm vĩnh viễn; nhân vật không reset theo mùa. |
| `Hardcore` | Chết là mất nhân vật; ưu tiên defense hơn damage sheet. |
| `Campaign` | Cốt truyện chính. Có thể skip nếu account đã mở điều kiện skip. |
| `Level Cap` | Cấp tối đa; Season 13 tăng lên 70. |
| `Skill Point` | Điểm dùng để nâng Active Skill và modifier trong Skill Tree. |
| `Paragon Point` | Điểm sau leveling dùng cho Paragon Board/Glyph, tăng sức mạnh dài hạn. |
| `Season Rank` | Objective mùa, cho reward như Skill Points, Paragon Points, material, cache. |
| `Season Blessing` | Buff mùa mua bằng Smoldering Ashes. |

<a id="paladin"></a>
## Paladin

| Term | Ghi chú tiếng Việt |
|---|---|
| `Paladin` | Class chính thức trong Lord of Hatred. Xem trạng thái tại [Trạng Thái Paladin](../research/trang-thai-paladin.md). |
| `Project Scope` | Bộ ghi chú này ưu tiên Paladin thật nếu account có Lord of Hatred. |
| `Faith` | Resource của Paladin theo nguồn chính thức, guide cộng đồng và tooltip skill. Nếu thiếu Faith, rotation sẽ bị khựng. |
| `Oath` | Class mechanic của Paladin; chọn một hướng chơi như `Zealot`, `Juggernaut`, `Judicator`, `Disciple`. |
| `Zealot` | Oath đánh nhanh, tạo `Fervor`, hợp `Zeal`/`Zenith` và crit. |
| `Fervor` | Stack từ Zealot; giúp Critical Strike echo thêm hit và cho Fortify khi gain ở max stack. |
| `Juggernaut` | Oath thiên về tank, shield, `Resolve`, size/damage cho skill phòng thủ. |
| `Resolve` | Stack phòng thủ/tank của Juggernaut, thường đi với shield/Block/DR. |
| `Judicator` | Oath gắn `Judgement` lên mục tiêu rồi detonate bằng Core Judicator Skills. |
| `Judgement` | Debuff/mark của Judicator; dùng cho lối đánh mark-and-burst. |
| `Disciple` | Oath thiên về Arbiter/angelic form, cooldown và Holy fantasy. |
| `Arbiter` | Trạng thái/biến hình thiên thần của Disciple, tăng mobility và damage theo nguồn chính thức. |
| `Zenith` | Ultimate/Burst skill trọng tâm của hướng Paladin hiện tại. |
| `Zeal` | Core Skill đánh nhanh, làm damage nền và giữ nhịp Fervor cho build Zealot. |

<a id="skill-combat"></a>
## Skill Và Combat

| Term | Ghi chú tiếng Việt |
|---|---|
| `Basic Skill` | Skill thường dùng để generate resource hoặc đánh khi hết resource. |
| `Core Skill` | Skill gây damage chính, thường tốn resource. |
| `Cooldown` | Thời gian hồi chiêu. Build tốt không bị lệ thuộc quá nhiều vào cooldown dài. |
| `Resource` | Năng lượng class dùng để cast skill; Paladin dùng `Faith`. |
| `Rotation` | Thứ tự/ưu tiên dùng skill trong combat. Thực tế nên nghĩ là priority, không phải combo cứng. |
| `Engage` | Cách mở combat, ví dụ lao vào bằng Mobility hoặc gom quái bằng CC. |
| `Crowd Control` / `CC` | Khống chế: Stun, Daze, Slow, Immobilize, Knock Down, Pull. |
| `Unstoppable` | Trạng thái chống/thoát CC; cực quan trọng khi push hoặc Hardcore. |
| `Vulnerable` | Debuff khiến mục tiêu nhận thêm damage theo hệ thống hiện tại. |
| `Weaken` | Debuff giảm sức mạnh/hiệu quả địch; kiểm tra tooltip skill cụ thể. |
| `Fortify` | Lớp phòng thủ liên quan Maximum Life; thường hợp build bền. |
| `Barrier` | Lớp khiên tạm thời hấp thụ damage. |
| `Taunt` | Khiến địch tập trung đánh bạn; tốt cho tank/party nhưng nguy hiểm nếu thiếu defense. |
| `Lucky Hit` | Cơ hội kích hoạt hiệu ứng “on hit”; không giống Critical Strike. |
| `Critical Strike` / `Crit` | Đòn chí mạng, thường cần Crit Chance và Crit Damage. |
| `Overpower` | Cơ chế hit lớn dựa trên Life/Fortify tùy build. |
| `Damage over Time` / `DoT` | Damage theo thời gian, không phải hit trực tiếp. |
| `Thorns` | Damage phản lại khi bị đánh; hợp fantasy tank nhưng cần build riêng. |

<a id="defense"></a>
## Defense

| Term | Ghi chú tiếng Việt |
|---|---|
| `Armor` | Giảm Physical damage; càng lên difficulty càng cần kiểm tra lại. |
| `Resistance` / `All Resistances` | Giảm elemental/non-physical damage; đừng bỏ qua khi vào Torment. |
| `Damage Reduction` / `DR` | Giảm damage nhận vào; thường giá trị hơn tăng máu thuần khi push. |
| `Maximum Life` | Máu tối đa; giúp chống burst và scale một số cơ chế. |
| `Dodge` | Né đòn. Không nên là defense duy nhất. |
| `Block` | Chặn bằng shield hoặc cơ chế block; rất hợp Paladin. |
| `Potion` | Bình máu; nếu uống liên tục trong pack thường là dấu hiệu thiếu defense hoặc đứng sai vị trí. |

<a id="gear-itemization"></a>
## Gear Và Itemization

| Term | Ghi chú tiếng Việt |
|---|---|
| `Item Power` | Cấp sức mạnh item; leveling thường ưu tiên weapon item power cao. |
| `Affix` | Dòng chỉ số trên item. |
| `Greater Affix` / `GA` | Affix roll cao nổi bật; rất đáng giữ nếu đúng stat build. |
| `Legendary Aspect` | Power có thể nằm trên Legendary hoặc trong Codex. |
| `Codex of Power` | Kho Aspect đã học/nâng; salvage Legendary để cập nhật Aspect tốt hơn. |
| `Unique` | Item có power riêng, thường định hình build. Season 13 Unique có thay đổi lớn. |
| `Mythic Unique` | Unique hiếm và rất mạnh; không nên coi là điều kiện bắt buộc cho bản leveling. |
| `Ancestral` | Item tier cao hơn ở endgame/Torment; thường đáng kiểm tra kỹ. |
| `Tempering` | Thêm affix qua Blacksmith; Season 13 Unique cũng có thể Temper theo nguồn chính thức. |
| `Masterworking` | Nâng cấp gear endgame bằng material như Obducite. |
| `Socket` | Ô gắn Gem/Rune. |
| `Gem` | Đá gắn vào gear; Season 13 weapon gem effect đã đổi mạnh theo damage type. |
| `Rune` / `Runeword` | Hệ thống rune tạo hiệu ứng khi gắn đúng điều kiện. |
| `Loot Filter` | Bộ lọc đồ; dùng để ẩn rác, highlight item có affix/GA/Unique cần săn. |
| `Elixir` / `Incense` | Consumable cũ. Theo Wowhead, Season 13 Seasonal Realm đã giảm/loại phần lớn vai trò của Elixir/Incense; kiểm tra lại trong game trước khi ghi vào build. |

<a id="season-13-systems"></a>
## Season 13 Systems

| Term | Ghi chú tiếng Việt |
|---|---|
| [`War Plans`](co-che/war-plans.md) | Endgame playlist tại Temis, nối nhiều activity để farm có kế hoạch. |
| [`Command Table`](co-che/command-table.md) | Bàn ở Temis để tạo War Plan. |
| [`Activity Points`](co-che/activity-points.md) | Điểm mở cây nâng cấp activity trong War Plans. |
| [`War Chest`](co-che/war-chest.md) | Reward sau khi hoàn tất War Plan. |
| [`Talisman`](co-che/talisman.md) | Hệ thống mới dùng Seal và Charm để thêm affix/power/set bonus. |
| [`Seal`](co-che/seal.md) | Mở slot Charm và quyết định khung Talisman. |
| [`Charm`](co-che/charm.md) | Mảnh gắn vào Talisman, cho affix hoặc set bonus. |
| [`Horadric Cube`](co-che/horadric-cube.md) | Crafting station ở Temis để transmute/reroll/create gear, charm, gem, rune. |
| [`Echoing Hatred`](co-che/echoing-hatred.md) | Endgame challenge hiếm, dùng Trace of Echoes để vào. |
| [`Fishing`](co-che/fishing.md) | Hoạt động thư giãn/collection trong Skovos và nơi có nước. |
| [`Map Overlay`](co-che/map-overlay.md) | Bản đồ phủ lên màn hình để di chuyển dễ hơn. |
| [`Pathfinder`](co-che/pathfinder.md) | Hỗ trợ chỉ đường. |

<a id="activities"></a>
## Activities

| Activity | Dùng khi nào |
|---|---|
| [`Helltide`](co-che/helltide.md) | Farm gear, material, density tốt, dễ kết hợp leveling. |
| [`Whispers`](co-che/whispers.md) | Làm objective nhanh, nhận cache, gold/material, có thể chồng với activity khác trong War Plans. |
| [`Nightmare Dungeon`](co-che/nightmare-dungeon.md) / `NMD` | Farm dungeon có độ khó, material/Glyph tùy hệ thống hiện tại. |
| [`The Pit`](co-che/the-pit.md) | Push sức mạnh, nâng tiến trình endgame/Glyph tùy patch. |
| [`Lair Bosses`](co-che/lair-bosses.md) | Target farm Unique/boss drop. |
| [`Infernal Hordes`](co-che/infernal-hordes.md) | Activity wave-based, farm reward nếu build clear tốt. |
| [`The Undercity`](co-che/the-undercity.md) | Activity từ Vessel of Hatred, dùng khi cần reward mục tiêu nếu có expansion. |
| [`Artificer's Tower`](co-che/artificers-tower.md) | Tower/leaderboard beta, dùng để thử sức và nhận reward theo mùa. |

<a id="read-build-guide"></a>
## Cách Đọc Một Build Guide

1. Xem guide cập nhật cho patch nào.
2. Xem build dùng để làm gì: leveling, speed farm, bossing, push, Hardcore.
3. Tìm `required items`. Nếu chưa có item bắt buộc, đừng copy y nguyên.
4. Tách phần nào là dữ liệu quan sát được, phần nào là kết luận của tác giả guide.
5. Xem rotation và defensive layer trước khi xem damage number.
6. Xem stat priority, rồi tạo Loot Filter theo stat đó.
7. Test 15-30 phút và ghi lại: damage pack, damage boss, độ sống sót, resource, độ vui.

<a id="reason-about-builds"></a>
## Cách Tự Suy Luận Build

Không cần chờ một guide có sẵn nếu tooltip và cơ chế đã cho đủ manh mối. Dùng khung này để tạo phương án `Inference` rồi đem test:

1. Chọn mục tiêu: leveling, speed farm, bossing, push, Hardcore, hoặc giữ fantasy.
2. Chọn damage engine: skill nào giết quái chính, skill nào chỉ để setup/burst.
3. Kiểm tra resource loop: generate Faith bằng gì, spender nào làm cạn Faith, cooldown nào gây downtime.
4. Ghép cơ chế: ví dụ Attack Speed + nhiều hit + Crit giúp giữ `Fervor`; shield + Block + DR giúp melee sống lâu hơn.
5. Đảm bảo đủ defense và mobility trước khi thêm damage tham lam.
6. Chọn gear/stat theo vấn đề đang gặp, không chỉ theo bảng stat của guide.
7. Ghi giả thuyết test: đổi gì, kỳ vọng cải thiện gì, dấu hiệu nào cho thấy thất bại.
8. Sau test, chuyển trạng thái thành `Keep`, `Change` hoặc `Retest` trong [Nhật Ký Test](../notes/nhat-ky-test.md).
