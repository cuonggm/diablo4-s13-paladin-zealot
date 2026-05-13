# Paladin Build Doctrine

Checked: 2026-05-13

## Điều Hướng

- [README](../README.md)
- Liên quan: [Glossary](basic-terms-and-mechanics.md), [Current Character Checklist](current-character-checklist.md), [Zealot Zenith Leveling](../builds/zealot-zenith-leveling.md), [Zealot Zenith Fervor](../builds/zealot-zenith-fervor.md), [Testing Log](../notes/testing-log.md)

File này ghi quan điểm build riêng của dự án. Guide cộng đồng là dữ liệu đối chiếu; build cuối cùng phải phục vụ cách chơi thật: vào pack mượt, giết đúng mục tiêu, không chết vô lý, không đứng chờ resource, và vẫn giữ fantasy Paladin.

## Luật Gốc

| Luật | Ý nghĩa thực chiến |
|---|---|
| Vấn đề trước, tier list sau | Chỉ đổi build khi biết đang thiếu gì: damage pack, boss damage, sống sót, resource, cooldown, mobility hoặc cảm giác chơi. |
| Engine phải rõ | Mỗi build cần biết skill nào là damage engine, skill nào là setup, skill nào là nút cứu mạng. |
| Không bỏ defense để lấy damage mù | Melee build chết hoặc phải kite quá nhiều sẽ farm chậm dù damage sheet cao. |
| Resource loop là sức mạnh thật | Nếu Faith/cooldown khựng, mọi aspect damage đều mất giá trị. |
| Gear hiện có quan trọng hơn planner | Nếu chưa có item/affix guide yêu cầu, dùng bản thay thế hợp logic thay vì copy y nguyên. |
| Test ngắn nhưng có tiêu chí | Mỗi thay đổi nên có giả thuyết, pass/fail criteria và verdict trong Testing Log. |

## Khung Suy Luận 6 Trụ

| Trụ | Câu hỏi cần trả lời |
|---|---|
| Damage engine | Skill nào thật sự giết quái: `Zeal`, `Zenith`, Holy DoT, shield hit, hay burst window? |
| Delivery | Làm sao đưa damage vào đúng mục tiêu: pull, dash, CC, boss stagger, hoặc đứng gần? |
| Resource loop | Faith đến từ đâu, spender nào làm cạn, cooldown nào tạo downtime? |
| Defense latch | Khi bị CC/burst thì nút nào giữ mạng: `Defiance Aura`, `Aegis`, shield, Fortify, DR? |
| Tempo | Di chuyển pack-to-pack bằng gì: `Rally`, `Advance`, `Falling Star`, Movement Speed? |
| Evidence | Sau 15-30 phút, số lần chết, potion pressure, boss time và resource feel nói gì? |

## Kiến Trúc Zealot Zenith Riêng

Với hướng `Zealot + Zenith`, dự án không xem 6 slot là bất biến. Nên nhìn như một hệ module:

| Module | Mặc định | Vai trò | Có thể đổi khi |
|---|---|---|---|
| Oath engine | `Zealot` | Tạo `Fervor`, echo hit, Fortify khi giữ nhịp | Chỉ đổi nếu bỏ hẳn concept Zealot |
| Damage nền | `Zeal` | Giữ nhịp, clear pack nhỏ, duy trì Fervor | Chỉ đổi nếu chuyển sang Core khác như Blessed Shield/Hammer |
| Burst | `Zenith` | Xóa elite, pack dày, boss window | Không đổi trong hai build chính |
| Buff window | `Fanaticism Aura` | Attack Speed/Crit/debuff để bật damage window | Không nên bỏ trong Zealot Zenith |
| Tempo/resource | `Rally` hoặc `Advance` | Chạy map, giữ Faith, bám mục tiêu | Chọn theo giai đoạn leveling/endgame |
| Flex slot | `Defiance Aura`, `Condemn`, `Falling Star`, `Aegis`, `Consecration` | Giải quyết vấn đề hiện tại | Đổi theo test, không đổi theo tier list |

## Các Chế Độ Riêng Của Dự Án

| Chế độ | Skill bar mẫu | Dùng khi | Rủi ro |
|---|---|---|---|
| `Iron Pilgrim` | `Advance / Zeal / Fanaticism Aura / Defiance Aura / Rally / Zenith` | Leveling, gear thấp, cần sống và giữ Faith | Clear pack tản chậm hơn bản có pull |
| `Bellringer` | `Advance / Zeal / Fanaticism Aura / Condemn / Rally / Zenith` | Pack tản, cần kéo/stun để Zenith trúng nhiều mục tiêu | Mất defensive aura, dễ chết nếu Armor/Resistance thấp |
| `Star Pilgrim` | `Advance / Zeal / Fanaticism Aura / Falling Star / Rally / Zenith` | Content dễ, muốn speed farm và mobility cao | Lao sai vị trí dễ mất potion |
| `Zenith Sentinel` | `Zeal / Zenith / Fanaticism Aura / Defiance Aura / Rally / Falling Star` | Endgame mặc định, cân bằng burst, tốc độ và an toàn | Không có pull chủ động |
| `Condemn Harvester` | `Zeal / Zenith / Fanaticism Aura / Condemn / Rally / Falling Star` | Farm pack đông khi đã đủ sống | Chết vì CC/burst nếu bỏ defense quá sớm |
| `Aegis Bulwark` | `Zeal / Zenith / Fanaticism Aura / Defiance Aura / Rally / Aegis` | Push, boss lạ, Hardcore hoặc thiếu DR | Chậm hơn, ít mobility hơn |
| `Sunder Duelist` | Giữ skill bar an toàn, đổi `Zenith` sang `Sunder` | Boss/elite sống lâu, cần burst gọn | Kém tốc độ farm nếu pack thường đã dễ |

Tên chế độ chỉ để ghi log và ra quyết định nhanh. Nếu tooltip/gear thực tế nói khác, ưu tiên test trong game.

## Cách Khác Guide Truyền Thống

- Guide truyền thống thường bắt đầu từ planner hoàn chỉnh; dự án này bắt đầu từ vấn đề đang gặp.
- Guide thường tối ưu damage cuối game; dự án này tối ưu nhịp chơi hiện tại trước, rồi mới tăng damage.
- Guide thường coi slot skill là cố định; dự án này coi `Flex slot` là nơi giải quyết vấn đề.
- Guide thường chase item bắt buộc; dự án này dùng phương án thay thế cho tới khi item thật sự rơi.
- Guide thường đưa kết luận mạnh/yếu; dự án này ghi `Status`, giả thuyết và tiêu chí test.

## Tiêu Chí Pass/Fail

| Test | Pass | Fail |
|---|---|---|
| Pack clear | 3 pack đông liên tiếp không cần uống potion liên tục, Zenith trúng nhiều mục tiêu | Pack tản, Zenith hụt giá trị, phải chase quái lẻ quá lâu |
| Elite | Elite mất phần lớn máu trong 1-2 burst window | Elite sống quá lâu hoặc bạn phải chạy vòng chờ cooldown |
| Boss | Boss chết ổn định, không hết potion, có window rõ để dùng Zenith | Boss di chuyển làm hụt burst hoặc rotation cạn Faith liên tục |
| Defense | Có nút phản ứng khi bị CC/burst | Chết khi cooldown phòng thủ chưa kịp hồi |
| Resource | Ít khi phải đánh chay vì thiếu Faith | Rotation khựng quá thường xuyên |
| Fun | Muốn chơi tiếp thêm một run | Damage có thể ổn nhưng cảm giác điều khiển khó chịu |
