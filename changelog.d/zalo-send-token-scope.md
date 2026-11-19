---
bump: minor
title: API token that can only send to a Zalo group
---
## vi
### Thêm mới
- **Token API chỉ gửi được vào nhóm Zalo.** Thêm mức quyền `zalo-send` khi tạo token: token này chỉ gọi được đúng một đường (gửi một tin vào một nhóm Zalo), không đọc được dữ liệu và không điều khiển được Javis. Website lớp học dùng nó để gửi bản ghi cho học viên vắng mà không cần token toàn quyền.

## en
### Added
- **An API token that can only send to a Zalo group.** A new `zalo-send` scope when creating a token: it can call exactly one route (send one text to one Zalo group), cannot read data and cannot drive Javis. The class website uses it to send the recording to absent students without a full-access token.
