# Cắt video thành các phần — tải từ TikTok & cắt

Web chạy ngay trong trình duyệt, không tải video lên server nào.

## Cách dùng

1. Mở web: dán link TikTok để tải video về (không watermark), hoặc chọn file video có sẵn trên máy.
2. Chọn cách chia:
   - Chia đều N phần
   - Theo độ dài tối đa mỗi phần (preset 10 giây — đúng giới hạn nạp video của Flow, video 30 giây thành đúng 3 phần)
   - Tuỳ chỉnh: tự đặt điểm cắt trên timeline
3. Tuỳ chọn tắt tiếng các đoạn, chọn chế độ cắt Nhanh hoặc Chính xác.
4. Bấm **Cắt & tải tất cả** — các phần được tải về với tên `ten-video_phan-01.mp4`, `phan-02`, ... theo đúng thứ tự để nạp vào các node VIDEO ĐẦU VÀO của workflow Motion Control.

Mọi xử lý (tải, cắt) chạy bằng ffmpeg.wasm ngay trên máy của người dùng.
