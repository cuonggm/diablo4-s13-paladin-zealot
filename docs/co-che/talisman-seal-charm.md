# Talisman, Seal, Charm

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Itemization](itemization-tempering-masterworking.md), [Horadric Cube](horadric-cube-crafting.md), [Loot Filter](loot-filter.md), [Paladin](paladin-faith-oaths-aura.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Talisman là hệ item mới dùng `Seal` và `Charm` để thêm affix, power và set bonus. | Verified | Đây là một lớp build mới ngang gear/Paragon, không phải trang trí phụ. |
| Seal mở tối đa 6 Charm slots; Seal mạnh hơn cho nhiều affix/slot hơn. | Verified | Seal tốt là nền; Charm tốt không phát huy nếu Seal thiếu slot. |
| Charms có thể thay đổi tự do trong slot mở. | Verified | Dùng để swap theo farm/boss/push mà không đổi toàn gear. |
| Nhiều non-Unique Charms cùng affix có thể stack bonus. | Verified | Có thể dùng charm lặp để sửa thiếu stat cụ thể. |
| Set Charms có partial/full set bonus, gồm class-specific và all-class. | Verified | Paladin nên chọn set theo Oath/skill engine, không chỉ theo rarity. |
| Patch 3.0.2 sửa nhiều lỗi Talisman/set bonus/charm equip. | Verified | Sau patch cần test lại setup charm nếu trước đó thấy bonus rơi mất. |

## Thành Phần

| Thành phần | Vai trò | Nên đọc |
|---|---|---|
| `Seal` | Mảnh trung tâm, quyết định slot Charm và affix nền. | Số slot, affix, rarity, có đúng build không. |
| `Charm` | Mảnh ngoài, thêm affix/power. | Affix có sửa vấn đề hiện tại không. |
| `Set Charm` | Charm có set bonus partial/full. | Set bonus có scale skill/Oath thật không. |
| `Unique Charm` | Charm có unique power. | Có đáng đổi khỏi stat/set hiện tại không. |

## Lộ Trình Dùng Talisman

| Giai đoạn | Recommend |
|---|---|
| Leveling | Dùng Seal nhiều slot nhất có thể, ưu tiên affix sống sót/resource/damage rõ. |
| 50-70 | Bắt đầu giữ Charms theo tag build: Core, Holy, Zealot, shield, crit, resource, defense. |
| Endgame sớm | Chọn một set bonus hợp build, không chase perfect roll ngay. |
| Endgame giữa | Dùng Loot Filter để highlight Seal/Charm đúng set, đúng affix, đúng slot. |
| Push/min-max | Tối ưu Seal nhiều slot + set bonus + Unique Charm, nhưng giữ rollback setup cũ. |

## Recommend Cho Paladin

| Build/nhu cầu | Charm/Seal nên tìm |
|---|---|
| Zealot Zenith | Crit, Attack Speed, Core/Ultimate damage, Zealot Skill support, Faith/resource, Fortify. |
| Shield fantasy | Block, Armor, All Resistances, DR, Shield Bash/Blessed Shield support. |
| Bossing | Single-target, Judgement/Judicator, Core damage, debuff uptime. |
| Hardcore/push | DR, Life, Resist, Fortify/Barrier, Unstoppable/CDR support. |
| Speed farm | Movement Speed, cooldown, resource sustain, AoE/pack clear support. |

## Lỗi Thường Gặp

| Lỗi | Hậu quả | Cách sửa |
|---|---|---|
| Chỉ nhìn rarity | Đeo charm không khớp build | Đọc affix và set bonus trước. |
| Thay toàn bộ charm cùng lúc | Không biết power tăng/giảm từ đâu | Đổi 1-2 charm rồi test. |
| Bỏ defense để lấy damage | Push/Torment cao chết nhiều hơn | Giữ một nhóm charm defense cố định. |
| Không dùng Loot Filter | Bỏ sót Seal/Charm đúng set | Tạo rule Talisman Set Bonus và affix. |
| Không ghi rollback | Setup mới tệ nhưng không nhớ setup cũ | Ghi Seal, set, số slot, charm chính vào nhật ký. |

## Test Pass/Fail

| Test | Pass | Fail |
|---|---|---|
| Đổi Seal | Thêm slot/affix giúp clear hoặc sống rõ ràng | Mất set/defense làm chết nhiều hơn |
| Đổi set bonus | Cải thiện đúng mục tiêu build | Damage sheet tăng nhưng rotation tệ hơn |
| Thêm Unique Charm | Power mới tạo tương tác rõ | Mất quá nhiều affix nền |

## Nguồn

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes
- Wowhead - Talisman community guide: https://www.wowhead.com/diablo-4/guide/systems/talisman
