# Fishing

Checked: 2026-05-13  
Patch tham chiếu: Diablo IV 3.0.2 Build #71886

## Điều Hướng

- [Cơ Chế](README.md)
- Liên quan: [Fishing Và Echoing Hatred](fishing-echoing-hatred.md), [War Plans](war-plans.md), [Lộ Trình Chơi](../lo-trinh-choi.md)

## Kết Luận Nhanh

| Kết luận | Status | Impact on Paladin |
|---|---|---|
| Fishing là hoạt động phụ trong Skovos và các nơi có nước. | Verified | Dùng để nghỉ nhịp/collection, không phải power farm chính. |
| Có thể trade fish với người chơi khác để hoàn thiện collection. | Verified | Hợp mục tiêu sưu tầm, không nên tính vào build power. |
| Patch 3.0.2 sửa lỗi quest liên quan `Fish of Dreams`. | Verified | Nếu từng bị kẹt quest Fishing, nên thử lại sau patch. |

## Dùng Fishing Khi Nào

| Nên dùng khi | Không nên dùng khi |
|---|---|
| Muốn nghỉ sau push hoặc farm dài. | Đang cần gear/material gấp. |
| Muốn collection/trade fish. | Đang đo DPS, defense hoặc clear/hour. |
| Chơi session ngắn ít căng thẳng. | Đang thiếu power để vào Torment. |
| Muốn khám phá Skovos. | Đang cố tối ưu XP/hour. |

## Cách Ghi Trong Dự Án

Fishing không nên trộn vào log test build, vì nó không đo combat. Nếu cần ghi, ghi thành mục riêng:

| Mục | Nên ghi |
|---|---|
| Địa điểm | Khu vực/nơi có nước. |
| Mục tiêu | Collection, trade, quest, nghỉ nhịp. |
| Reward đáng chú ý | Fish hiếm, collection progress, quest progress. |
| Tác động build | Thường là `None`; nếu có material/power thì cần xác minh. |

## Paladin Note

Fishing có giá trị tinh thần/session hơn giá trị power. Với dự án Paladin, nên coi Fishing là hoạt động nghỉ giữa các block War Plans, đặc biệt sau khi test push hoặc Echoing Hatred.

## Rủi Ro Cần Test

| Rủi ro | Status | Cách kiểm |
|---|---|---|
| Tưởng Fishing là route power farm. | Inference | So reward/hour với War Plans hoặc Whispers; nếu kém thì chỉ dùng chill. |
| Quest/collection bị lỗi. | Needs testing | Đối chiếu patch 3.0.2 và thử lại trong game. |
| Tốn thời gian trong season ngắn. | Inference | Chỉ fishing sau khi đã hoàn thành mục tiêu farm/build chính. |

## Nguồn

- Blizzard - Lord of Hatred / Season of Reckoning overview: https://news.blizzard.com/en-us/article/24267729/prepare-for-the-reckoning-lord-of-hatred-draws-near
- Blizzard - Diablo IV Patch Notes 3.0.2: https://news.blizzard.com/en-us/article/24271857/diablo-iv-patch-notes

