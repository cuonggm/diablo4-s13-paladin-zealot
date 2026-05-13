# Nguyên Tắc Build Paladin

Checked: 2026-05-13

## Điều Hướng

- [Trang Chủ](../README.md)
- Liên quan: [Thuật Ngữ](thuat-ngu-va-co-che.md), [Checklist Nhân Vật Hiện Tại](checklist-nhan-vat-hien-tai.md), [Zealot Zenith Lên Cấp](../builds/zealot-zenith-len-cap.md), [Zealot Zenith Cuối Game](../builds/zealot-zenith-endgame.md), [Juggernaut Bastion](../builds/juggernaut-bastion-len-cap.md), [Judicator Hammer](../builds/judicator-hammer-len-cap.md), [Disciple Arbiter](../builds/disciple-arbiter-len-cap.md), [Nhật Ký Test](../notes/nhat-ky-test.md)

File này ghi quan điểm build riêng của dự án. Guide cộng đồng là dữ liệu đối chiếu; build cuối cùng phải phục vụ cách chơi thật: vào pack mượt, giết đúng mục tiêu, không chết vô lý, không đứng chờ resource, và vẫn giữ fantasy Paladin.

## Luật Gốc

| Luật | Ý nghĩa thực chiến |
|---|---|
| Vấn đề trước, tier list sau | Chỉ đổi build khi biết đang thiếu gì: damage pack, boss damage, sống sót, resource, cooldown, mobility hoặc cảm giác chơi. |
| Engine phải rõ | Mỗi build cần biết skill nào là damage engine, skill nào là setup, skill nào là nút cứu mạng. |
| Không bỏ defense để lấy damage mù | Melee build chết hoặc phải kite quá nhiều sẽ farm chậm dù damage sheet cao. |
| Resource loop là sức mạnh thật | Nếu Faith/cooldown khựng, mọi aspect damage đều mất giá trị. |
| Gear hiện có quan trọng hơn planner | Nếu chưa có item/affix guide yêu cầu, dùng bản thay thế hợp logic thay vì copy y nguyên. |
| Test ngắn nhưng có tiêu chí | Mỗi thay đổi nên có giả thuyết, pass/fail criteria và verdict trong Nhật Ký Test. |

## Khung Suy Luận 6 Trụ

| Trụ | Câu hỏi cần trả lời |
|---|---|
| Damage engine | Skill nào thật sự giết quái: `Zeal`, `Zenith`, Holy DoT, shield hit, hay burst window? |
| Delivery | Làm sao đưa damage vào đúng mục tiêu: pull, dash, CC, boss stagger, hoặc đứng gần? |
| Resource loop | Faith đến từ đâu, spender nào làm cạn, cooldown nào tạo downtime? |
| Defense latch | Khi bị CC/burst thì nút nào giữ mạng: `Defiance Aura`, `Aegis`, shield, Fortify, DR? |
| Tempo | Di chuyển pack-to-pack bằng gì: `Rally`, `Advance`, `Falling Star`, Movement Speed? |
| Evidence | Sau 15-30 phút, số lần chết, potion pressure, boss time và resource feel nói gì? |

## Khung Flex Theo Oath

Mỗi Oath nên có một lõi không đổi và 1-2 slot flex. Nếu phải đổi 3 slot trở lên để build chạy được, thường đó là dấu hiệu đang chuyển sang build khác, không còn là variant nhỏ.

| Oath | Lõi nên giữ | Slot flex thật sự | Câu hỏi trước khi đổi |
|---|---|---|---|
| `Zealot` | `Zealot Oath`, `Zeal`, `Zenith`, `Fanaticism Aura`, một nguồn Faith/tempo | `Defiance Aura`, `Condemn`, `Falling Star`, `Aegis`, variant `Zenith` | Đang thiếu sống, thiếu gom pack, thiếu boss burst hay thiếu tốc độ? |
| `Juggernaut` | `Juggernaut Oath`, một Core shield đúng tag, shield/Block package, `Defiance Aura`, một nguồn Faith | `Aegis`, `Falling Star`, `Condemn`, `Fanaticism Aura`, `Holy Light Aura`, `Fortress` | Damage chưa vào mục tiêu hay đã vào nhưng số quá thấp? Chết do thiếu DR hay do đứng sai? |
| `Judicator` | `Judicator Oath`, `Blessed Hammer` hoặc Core Judicator, một nguồn `Judgement`, một công cụ giữ enemy trong vùng hit | `Holy Bolt`, `Holy Light Aura`, `Condemn`, `Purify`, `Fanaticism Aura`, `Defiance Aura` | Vấn đề là thiếu mark, hammer quay hụt, cạn Faith hay thiếu sống? |
| `Disciple` | `Disciple Oath`, một skill cooldown để vào `Arbiter`, Holy/aura package, một nút thoát CC/burst | `Advance`, `Rally`, `Aegis`, `Condemn`, `Holy Light Aura`, `Arbiter of Justice` | Window có đủ uptime không, hay bạn chết/khựng ngoài window? |

Nguyên tắc suy luận: slot flex phải giải quyết một nút nghẽn cụ thể. `Condemn` không phải "thêm damage"; nó là cách ép enemy đứng đúng chỗ. `Aegis` không phải "một nút thủ nữa"; nó là quyền đứng lại trong burst window. `Rally` không chỉ là chạy nhanh; nó là bridge cho Faith và tempo. Nếu không mô tả được skill flex giải quyết vấn đề nào, chưa nên đổi.

## Bảng Đổi Skill Theo Triệu Chứng

| Triệu chứng | Skill nên thử | Lý do cơ chế | Dấu hiệu rollback |
|---|---|---|---|
| Pack tản, burst hụt | `Condemn` | Pull/Stun giúp Core/Ultimate/aura hit nhiều mục tiêu hơn | Vẫn phải chase quái lẻ hoặc chết vì mất defensive slot |
| Chết vì CC/burst | `Defiance Aura`, `Aegis`, `Fortress` | Unstoppable, Block, DR hoặc immune window cho phép đứng đánh tiếp | Clear chậm hơn nhưng số lần chết không giảm |
| Cạn Faith | `Clash`, `Holy Bolt`, `Advance`, `Rally` | Basic/Rally là cầu nối giữa spender và cooldown | Damage tụt rõ mà resource vẫn khựng |
| Boss di chuyển làm hụt damage | Basic/Core ổn định hơn, `Purify`, variant single-target | Giảm phụ thuộc vào pack/AoE và canh window boss | Pack clear mất quá nhiều tốc độ |
| Farm chậm nhưng không chết | `Falling Star`, `Rally`, bớt một slot thủ | Giảm thời gian pack-to-pack, tăng uptime combat | Potion pressure tăng hoặc chết vì lao sai |
| Damage thấp nhưng rotation mượt | `Fanaticism Aura`, debuff, rank/Aspect đúng tag | Tăng throughput cho engine đang hoạt động | Damage tăng không rõ sau 15-30 phút test |

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

## Nguyên Tắc Chuyển Mode Mượt

Mục tiêu là đổi ít nhất có thể để cảm giác tay, gear và rotation không bị vỡ. Khi cần đổi, chỉ đổi 1 trục trong một lần test: skill slot, `Zenith` variant, gear package hoặc difficulty.

| Lõi giữ nguyên | Vì sao giữ |
|---|---|
| `Zealot Oath` | Giữ toàn bộ logic `Fervor`, crit echo và Fortify. |
| `Zeal` | Giữ damage nền và nhịp Fervor khi `Zenith` chưa vào window. |
| `Zenith` | Giữ fantasy và burst engine chính của hai build. |
| `Fanaticism Aura` | Giữ Attack Speed/Crit/debuff window ổn định. |
| `Rally` | Giữ tempo, Faith support và cảm giác chạy map. |
| `Fervor Engine` gear package | Giúp mọi mode dùng chung một nền stat/Aspect. |

| Từ mode | Sang mode | Đổi ít nhất | Khi dùng |
|---|---|---|---|
| `Iron Pilgrim` | `Bellringer` | `Defiance Aura -> Condemn` | Leveling bị pack tản, đã đủ sống. |
| `Iron Pilgrim` | `Star Pilgrim` | `Defiance Aura -> Falling Star` | Leveling content dễ, muốn chạy nhanh hơn. |
| `Iron Pilgrim` | `Aegis Pilgrim` | Giữ bar chính, thêm `Aegis` ở slot tạm/flex nếu đang có | Leveling đau, cần shield/Block/Unstoppable hơn tốc độ. |
| `Iron Pilgrim` | `Zenith Sentinel` | `Advance -> Falling Star` | Sang endgame khi Faith và mobility đã đủ. |
| `Zenith Sentinel` | `Condemn Harvester` | `Defiance Aura -> Condemn` | Farm pack đông, cần pull/stun. |
| `Zenith Sentinel` | `Aegis Bulwark` | `Falling Star -> Aegis` | Push, boss lạ, Hardcore, hoặc chết vì burst. |
| `Zenith Sentinel` | `Sunder Duelist` | Chỉ đổi `Zenith` variant sang `Sunder` | Boss/elite là nút nghẽn, không muốn đảo skill bar. |
| `Condemn Harvester` | `Zenith Sentinel` | `Condemn -> Defiance Aura` | Rollback an toàn nếu chết hoặc bị CC. |
| `Aegis Bulwark` | `Zenith Sentinel` | `Aegis -> Falling Star` | Quay lại farm khi đã sống ổn. |

Quy tắc rollback: trước khi test mode mới, ghi mode cũ, skill bị đổi và lý do đổi. Nếu mode mới làm chết nhiều hơn, cạn Faith hơn hoặc clear không nhanh hơn sau 15-30 phút, quay lại mode cũ thay vì tiếp tục sửa thêm nhiều thứ cùng lúc.

## Loadout Chung Dễ Chuyển

Để chuyển mode tiện, ưu tiên giữ một bộ gear nền dùng được cho nhiều tình huống:

| Nhóm | Nên giữ chung | Chỉ đổi khi cần |
|---|---|---|
| Weapon | Item power cao, damage type khớp `Zeal`/`Zenith`, crit/attack speed nếu có | 2H cho farm dễ, 1H + shield khi cần sống. |
| Jewelry | Resistance đủ cap, CDR/resource/crit nếu roll tốt | Gem/rune thiên damage khi đã đủ defense. |
| Aspects | `Fervor Engine`, Zealot/Fervor/Zenith support, một defensive aspect ổn định | Pull/CC aspect cho `Harvester`, shield/Block aspect cho `Bulwark`. |
| Tempering | Crit, Attack Speed, resource, CDR, Life/Armor/Resistance nền | Chỉ min-max theo mode sau khi đã xác nhận mode đáng giữ. |
| Paragon | Node/glyph giúp crit, Zealot, Physical/Ultimate và survival nền | Không respec sâu chỉ để test một mode ngắn. |

Nguyên tắc tiện lợi: skill slot là công tắc nhanh, gear là nền ổn định. Đừng đổi cả skill bar, gear, Paragon và difficulty trong cùng một lần test vì sẽ không biết thứ nào thật sự hiệu quả.

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
