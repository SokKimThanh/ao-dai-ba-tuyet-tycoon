🎮 Cơ chế gameplay: Người chơi vào vai nhân vật phụ
🧍‍♀️ Nhân vật Phượng – Nhân viên hậu sự kiện
Vai trò người chơi: Hỗ trợ bà chủ, tránh gây lỗi.

Nhiệm vụ:

Không làm gãy kim, hư máy may.

Học kỹ năng mới qua mini-game (ví dụ: sửa máy may, phục vụ khách).

Thưởng: Nếu Phượng làm tốt → tăng uy tín, giảm nguy cơ nổi điên của bà chủ.

🚚 Cơ chế Gacha nhập hàng – Shipper chuẩn “Anh Liêm”
Thành phần	Mô tả
Shipper VIP	“Anh Liêm” – giao hàng đúng, lịch sự, hàng xịn
Cách chọn	Tung xí ngầu hoặc chơi mini-game (ví dụ: đoán đúng hộp hàng, phản xạ nhanh)
Phần thưởng	Nhận hàng chất lượng cao, tăng điểm uy tín
Rủi ro	Nếu chọn nhầm shipper gian → bà chủ nổi điên, thua cuộc
➡️ Đây là cơ chế gacha nhập hàng, tạo cảm giác hồi hộp và chiến lược.

🧘‍♀️ Nhóm tập thể dục – Chuyển cảnh tự động
Thời điểm: 4h sáng mỗi ngày

Cơ chế: Dùng cutscene đơn giản để chuyển cảnh → giảm tải lập trình

Tác động: Tăng điểm tâm lý cho bà chủ nếu nhóm đoàn kết

🧍‍♀️ Nhân vật Diệp – Kẻ gây rối trong nhóm thể dục
Cơ chế	Mô tả
Tác động	Gây chia rẽ phe phái trong nhóm thể dục → ảnh hưởng đến lượng khách
Mini-game	“Tìm kẻ nói dối” – người chơi phải điều tra, đối thoại, chọn đúng người
Kết quả:
Chọn đúng → giữ đoàn kết, tăng khách

Chọn sai → mất khách từ một phe, tăng nguy cơ thua

➡️ Đây là cơ chế chơi người người, tạo chiều sâu xã hội và tương tác.

🧠 Cơ chế chống thua cuộc mặc định
Nhân vật phụ	Cách chống thua
Phượng	Làm tốt công việc, học kỹ năng
Shipper	Chọn đúng qua gacha hoặc mini-game
Nhóm thể dục	Giữ đoàn kết, chọn phe hoặc trung lập
Diệp	Phát hiện và xử lý kẻ gây rối đúng cách
🧩 Gợi ý cấu trúc lập trình
Module	Chức năng
SubCharacterController	Quản lý hành vi nhân vật phụ
GachaSystem	Tung xí ngầu, chọn shipper VIP
MiniGameManager	Điều khiển trò chơi nhỏ (sửa máy, tìm kẻ nói dối…)
CutsceneEngine	Tự động chuyển cảnh nhóm thể dục
FactionImpactSystem	Tính toán ảnh hưởng phe phái đến khách hàng
EmotionRiskMeter	Hiển thị nguy cơ nổi điên của bà chủ theo hành vi người chơi
