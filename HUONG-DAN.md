# THPT English AI — cách cài lên điện thoại

## Cách 1: Cài ngay như app (PWA, không cần APK) — nhanh nhất
1. Đưa thư mục `www` lên một hosting miễn phí có HTTPS (Netlify Drop: kéo thả thư mục tại app.netlify.com/drop, hoặc GitHub Pages / Vercel).
2. Mở link bằng Chrome trên Android → menu ⋮ → "Cài đặt ứng dụng" / "Thêm vào màn hình chính".
3. App chạy offline, có micro và giọng đọc đầy đủ.

## Cách 2: Ra file APK thật (GitHub tự build, miễn phí)
1. Tạo repo mới trên github.com, upload TOÀN BỘ nội dung thư mục này (kể cả thư mục `.github`).
2. Vào tab **Actions** → "Build APK" → **Run workflow**. Đợi 3–5 phút.
3. Mở lần chạy xong → mục **Artifacts** → tải `THPT-English-AI-apk` → giải nén ra `app-debug.apk`.
4. Chép sang điện thoại, bật "Cài từ nguồn không xác định" và cài.

## Bật AI chấm điểm
Mở app → ⚙️ → dán khoá Gemini API (miễn phí: aistudio.google.com/apikey).
Không có khoá, app vẫn chấm bằng thuật toán trên máy.
