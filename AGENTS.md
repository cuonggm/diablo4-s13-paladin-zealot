# AGENTS.md

## Mục tiêu

Dự án này dùng để nghiên cứu cách chơi, lối chơi và hướng xây dựng nhân vật Paladin trong Diablo 4 Season 13, với trọng tâm là class/concept **Paladin**.

Mục tiêu của agent là tổng hợp thông tin đáng tin cậy, chuyển hóa thành ghi chú build rõ ràng, và giúp người chơi ra quyết định thực chiến về kỹ năng, trang bị, Paragon, rotation, ưu/nhược điểm và hướng farm.

## Nguyên tắc nghiên cứu

- Luôn kiểm chứng thông tin Season 13 bằng nguồn mới và có ngày cập nhật rõ ràng.
- Ưu tiên nguồn chính thức: Blizzard news, patch notes, campfire chat, forum/thông báo của Diablo 4.
- Có thể tham khảo nguồn cộng đồng như Maxroll, Icy Veins, Mobalytics, Wowhead, YouTube creator, Discord/community post, nhưng phải ghi rõ đây là phân tích của cộng đồng.
- Không giả định Paladin là class chính thức nếu chưa có xác nhận. Nếu Paladin chỉ là concept, mod, tên roleplay, hoặc build fantasy, phải ghi rõ trong tài liệu.
- Tách bạch giữa dữ liệu đã xác minh, suy luận, và đề xuất thử nghiệm.
- Không sao chép nguyên văn build guide dài; hãy tóm tắt, dẫn nguồn, và biến thông tin thành checklist/thực hành riêng cho dự án.

## Phạm vi cần nghiên cứu

### 1. Tình trạng Season 13

- Ngày bắt đầu/kết thúc Season 13.
- Chủ đề mùa, seasonal mechanic, item/affix/borrowed power mới.
- Patch thay đổi class, item, rune, aspect, unique, tempering, masterworking, boss ladder, endgame.
- Những thay đổi ảnh hưởng đến lối chơi melee, shield, holy/light, thorns, aura, support hoặc crusader/paladin fantasy.

### 2. Định nghĩa Paladin

Nếu Diablo 4 Season 13 có Paladin chính thức:

- Xác định class mechanic, skill tree, resource, weapon restrictions.
- Xác định các archetype: tank, holy caster, shield melee, aura support, thorns, smite/hammer/crusader-style.
- Ghi rõ build nào mạnh cho leveling, speed farm, bossing, Pit/Nightmare Dungeon và hardcore.

Nếu Paladin không phải class chính thức:

- Định nghĩa Paladin là hướng roleplay/build fantasy của dự án này.
- Tìm class gần nhất có thể thể hiện fantasy này.
- Đánh giá các lựa chọn thay thế như shield/tank Barbarian, holy-themed Spiritborn nếu có, defensive melee, thorns, bleed/fortify, shout/aura-like gameplay.

### 3. Lối chơi

Cần mô tả lối chơi theo ngôn ngữ thực chiến:

- Cách vào combat.
- Rotation/cơ chế ưu tiên skill.
- Cách sống sót khi bị burst damage.
- Cách gom quái và clear pack.
- Cách đánh boss.
- Điểm cần chú ý khi resource cạn, cooldown bị lệch, hoặc thiếu key item.
- Lối chơi trên tay cầm và bàn phím/chuột nếu có khác biệt đáng kể.

### 4. Build và trang bị

Mỗi build nên có cấu trúc:

- Tên build.
- Mục đích: leveling, endgame, bossing, speed farm, push, hardcore.
- Core skill hoặc skill gây sát thương chính.
- Defensive layers.
- Mobility.
- Key passive.
- Aspects/uniques/mythic uniques quan trọng.
- Stat priority.
- Tempering và masterworking priority.
- Gems, runes, elixirs/incense nếu liên quan.
- Paragon boards/glyphs ở mức tổng quan.
- Điều kiện để build hoạt động tốt.
- Phương án thay thế khi chưa có đồ hiếm.

## Định dạng tài liệu nên tạo

Khi tạo file nghiên cứu hoặc build guide, ưu tiên các file Markdown ngắn gọn, có thể cập nhật dần:

- `research/season-13-overview.md`: tổng quan Season 13 và nguồn tham khảo.
- `research/paladin-status.md`: Paladin là class chính thức, concept, hay roleplay build.
- `builds/zealot-zenith-leveling.md`: build leveling chính, bắt buộc giữ lại.
- `builds/zealot-zenith-fervor.md`: build endgame chính, bắt buộc giữ lại.
- Tránh tạo thêm file build phụ nếu nội dung có thể đặt gọn vào 2 file build chính.
- `notes/testing-log.md`: kết quả test trong game, cập nhật theo patch.

## Tiêu chuẩn đầu ra

Mỗi kết luận quan trọng phải có:

- Trạng thái: `Verified`, `Community`, `Inference`, hoặc `Needs testing`.
- Ngày kiểm tra thông tin.
- Nguồn tham khảo nếu có.
- Tác động đến Paladin: nên dùng, nên tránh, hay cần test thêm.

Ví dụ:

```md
### Shield Thorns Paladin Fantasy

- Status: Inference
- Checked: 2026-05-12
- Sources: Patch notes + community build discussions
- Use case: Hardcore leveling / defensive endgame
- Notes: Phù hợp fantasy Paladin nếu Season 13 không có Paladin chính thức. Cần test tốc độ clear pack và damage boss.
```

## Checklist trước khi đưa khuyến nghị

- Đã kiểm tra patch mới nhất của Diablo 4 Season 13.
- Đã xác định Paladin có phải class chính thức trong Season 13 hay không.
- Đã ghi rõ mục tiêu build: leveling, endgame, bossing, speed farm, hardcore.
- Đã nêu điều kiện cần có để build hoạt động.
- Đã có phương án thay thế khi thiếu unique/aspect.
- Đã tách riêng thông tin đã xác minh và suy luận.
- Đã ghi ngày cập nhật.

## Phong cách viết

- Luôn trả lời và viết tài liệu bằng tiếng Việt có dấu, rõ ràng, thực dụng.
- Thuật ngữ trong game nên giữ bằng tiếng Anh để đúng với UI/guide cộng đồng; khi thuật ngữ quan trọng hoặc dễ gây nhầm lẫn, thêm ghi chú tiếng Việt bên cạnh.
- Ưu tiên bảng, checklist và ghi chú ngắn.
- Tránh nói chung chung như "build này rất mạnh" nếu không có bối cảnh.
- Khi có rủi ro bị nerf/buff, ghi rõ phiên bản patch hoặc ngày tham chiếu.
- Tập trung vào cách chơi thật sự trong game, không chỉ liệt kê item.
