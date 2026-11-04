# LiveGame - bản phát hành

Kho này **chỉ chứa file cài đặt và bản cập nhật** của ứng dụng LiveGame cho Windows. Không có mã nguồn ở đây.

**LiveGame** là ứng dụng Windows giúp streamer TikTok LIVE chạy game tương tác với người xem (Đấu Trí, Đoán Từ, ...): người xem trả lời bằng bình luận, bảng xếp hạng và bục vinh danh hiện ngay trên màn hình livestream.

Trang chủ: **https://livegame.vn**

## Tải về

Vào mục [Releases](../../releases/latest) và tải `LiveGame-Setup-<phiên bản>.exe`. Yêu cầu Windows 10 trở lên (64-bit). Ứng dụng tự kiểm tra và tải bản mới; bạn chọn lúc khởi động lại để cập nhật.

### Cảnh báo SmartScreen

Bản cài đặt hiện chưa được ký số, nên Windows SmartScreen có thể báo "Windows protected your PC". Chọn **More info** rồi **Run anyway** để tiếp tục. Bạn có thể đối chiếu mã SHA-512 của file trong `latest.yml` đi kèm mỗi bản phát hành.

## Giấy phép bên thứ ba

- Ứng dụng dùng thư viện [TikTok-Live-Connector](https://github.com/zerodytrash/TikTok-Live-Connector) (zerodytrash và cộng đồng đóng góp), phát hành theo **GNU AGPL-3.0** kèm các quyền bổ sung (mục 18 và 19). Mã nguồn và nội dung giấy phép nằm ở liên kết trên. LiveGame dùng thư viện nguyên bản, không sửa đổi.
- Các thành phần giấy phép MIT (React, Zod, ws, electron-updater) và phông chữ Nunito, Baloo 2 (SIL OFL 1.1): xem `third-party-notices.txt` trong thư mục `resources` của ứng dụng đã cài; Electron và Chromium có `LICENSE.electron.txt` và `LICENSES.chromium.html` cạnh file chạy.
- LiveGame không liên kết với TikTok.
