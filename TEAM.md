# TEAM — Ngày 12

Mã bộ ảnh: **G12** · Hình thức: **cá nhân** (review chéo với một bạn cùng mã G12)

| Họ tên | MSSV | Đã gán đủ 22 ảnh? | Review chéo với (peer diff) | Số dòng disagreement đã xử lý |
|---|---|---|---|---|
| Nguyễn Xuân Việt | 2A202604045 | có | Bùi Văn Thịnh (2A202604040) | xem `disagreement_log.csv` (86 dòng, trong đó 11 dòng đã sửa theo bạn Thịnh) |
| Bùi Văn Thịnh | 2A202604040 | | Nguyễn Xuân Việt (2A202604045) | |

Ca hai bạn vẫn không thống nhất / chưa kết luận (ghi tên ảnh + đối tượng):

- Không còn ca lệch về box. S07 và S08: ghế `rear_right` là người lớn, Việt đã đổi `child_seat` thành `person` theo bạn Thịnh. S08_ir: bạn Thịnh vẽ hai `face` trùng nhau, Việt giữ một `face`.
- `seatbelt` ở S07, S08: Việt `unknown`, Thịnh `not_worn`; Việt giữ nguyên.
- `eye_left`, `eye_right`, `glasses`, `gaze_zone` và các cờ `occluded`/`outside` của `face13` (D01–D06, S01, S07, S08): khó xác định, hai bên đều có thể đúng, tạm giữ nguyên.

## Cá nhân

### Nguyễn Xuân Việt - 2A202604045
- Phần mình làm (ngoài 22 ảnh của mình, ví dụ ai review ai, ai tổng hợp ca hỏi coach): review chéo bản export của Bùi Văn Thịnh bằng `cabin_check diff`; sửa 3 ca mình sai (seatbelt D04, D06; on_wheel D05) và thêm face còn thiếu ở S07, S08 và đổi child_seat thành person ở ghế rear_right của S07, S08; export lại `export_final_v2.zip`.
- Điều mình học được hôm nay: …
