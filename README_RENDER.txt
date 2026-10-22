HƯỚNG DẪN ĐƯA LÊN RENDER (Static Site) — QDON.ENLITE
1. Đưa TOÀN BỘ file trong thư mục này (index.html nằm ở thư mục gốc) lên GitHub.
2. Render > New > Static Site > chọn repo.
3. Build Command: để trống (hoặc echo "static")   |   Publish Directory: .
   (Hoặc dùng sẵn render.yaml: New > Blueprint.)
4. Deploy xong mở link. Lần đầu tải dữ liệu ~6MB, các file export chỉ tải khi bấm tải mod.
Lưu ý: giữ nguyên tên các file .gz / .bin / assets.zip / thư mục runtime & category-icons.
Trang đã tự xử lý trường hợp server tự giải nén .gz nên chạy ổn trên Render.
