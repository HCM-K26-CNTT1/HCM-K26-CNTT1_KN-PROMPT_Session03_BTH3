# **[Bài thực hành 3] Xây dựng kế hoạch học tập cá nhân**

## **1. Prompt theo khung CREATE**

```
[C - Context]
Bạn là chuyên gia tư vấn phương pháp học tập và quản lý thời gian cho sinh viên năm nhất.

[R - Request]
Hãy phân tích và xây dựng kế hoạch học tập cá nhân trong 7 ngày, từ thứ Hai đến Chủ nhật, giúp sinh viên cân bằng giữa học trên lớp, tự học và giải trí.

[E - Explanation]
Các ràng buộc cần tuân thủ:
- Học trên lớp từ thứ Hai đến thứ Sáu, 7h30–11h30.
- Thời gian tự học bố trí vào buổi chiều và buổi tối.
- Mỗi ngày có ít nhất 1 giờ giải trí.
- Không học quá 3 giờ liên tục.
- Có thời gian nghỉ ngơi, ăn uống và ngủ đủ giấc.
- Ưu tiên các môn có nhiều bài tập hoặc cần nhiều thời gian ôn luyện.

[A - Action]
1. Phân tích quỹ thời gian trong ngày.
2. Phân bổ thời gian học trên lớp, tự học, giải trí và nghỉ ngơi.
3. Ưu tiên thời gian cho các môn có nhiều bài tập.
4. Xây dựng lịch học cụ thể trong 7 ngày.
5. Kiểm tra kế hoạch để đảm bảo đáp ứng các ràng buộc.

[T - Tone]
Sử dụng tiếng Việt đơn giản, rõ ràng, thực tế và phù hợp với sinh viên năm nhất.

[E - Extras]
- Trả về bảng Markdown gồm 7 ngày.
- Bảng có 4 cột: Ngày, Thời gian, Hoạt động, Mục tiêu.
- Sau bảng, viết nhận xét ngắn về tính hợp lý của kế hoạch.
- Không trình bày dưới dạng đoạn văn dài.
```

## **2. Kết quả thực hiện**

### **Kế hoạch học tập trong 7 ngày**

| Ngày     | Thời gian   | Hoạt động                     | Mục tiêu                  |
| -------- | ----------- | ----------------------------- | ------------------------- |
| Thứ Hai  | 6h30–7h30   | Ăn sáng, chuẩn bị đi học      | Bắt đầu ngày mới          |
|          | 7h30–11h30  | Học trên lớp                  | Tiếp thu kiến thức        |
|          | 11h30–13h30 | Ăn trưa, nghỉ ngơi            | Phục hồi năng lượng       |
|          | 14h00–16h00 | Tự học môn Đại số tuyến tính  | Làm bài tập, ôn lý thuyết |
|          | 16h00–17h00 | Giải trí, vận động            | Thư giãn                  |
|          | 19h00–20h30 | Học môn Tin học cơ sở         | Thực hành bài tập         |
|          | 20h30–22h00 | Nghỉ ngơi, chuẩn bị ngủ       | Thư giãn                  |
| Thứ Ba   | 7h30–11h30  | Học trên lớp                  | Tiếp thu kiến thức        |
|          | 11h30–13h30 | Ăn trưa, nghỉ ngơi            | Phục hồi năng lượng       |
|          | 14h00–16h00 | Tự học môn Mạng máy tính      | Ôn tập và ghi chú         |
|          | 16h00–17h00 | Giải trí                      | Giảm căng thẳng           |
|          | 19h00–20h30 | Làm bài tập Đại số            | Củng cố kiến thức         |
|          | 20h30–22h00 | Nghỉ ngơi                     | Chuẩn bị ngủ              |
| Thứ Tư   | 7h30–11h30  | Học trên lớp                  | Tiếp thu kiến thức        |
|          | 11h30–13h30 | Ăn trưa, nghỉ ngơi            | Phục hồi năng lượng       |
|          | 14h00–16h00 | Tự học Tin học cơ sở          | Luyện tập lập trình       |
|          | 16h00–17h00 | Giải trí, vận động            | Thư giãn                  |
|          | 19h00–20h30 | Ôn tập Đại số                 | Hoàn thành bài tập        |
|          | 20h30–22h00 | Nghỉ ngơi                     | Chuẩn bị ngủ              |
| Thứ Năm  | 7h30–11h30  | Học trên lớp                  | Tiếp thu kiến thức        |
|          | 11h30–13h30 | Ăn trưa, nghỉ ngơi            | Phục hồi năng lượng       |
|          | 14h00–16h00 | Tự học Mạng máy tính          | Hệ thống hóa kiến thức    |
|          | 16h00–17h00 | Giải trí                      | Thư giãn                  |
|          | 19h00–20h30 | Làm bài tập Tin học cơ sở     | Rèn luyện kỹ năng         |
|          | 20h30–22h00 | Nghỉ ngơi                     | Chuẩn bị ngủ              |
| Thứ Sáu  | 7h30–11h30  | Học trên lớp                  | Tiếp thu kiến thức        |
|          | 11h30–13h30 | Ăn trưa, nghỉ ngơi            | Phục hồi năng lượng       |
|          | 14h00–16h00 | Tổng hợp kiến thức trong tuần | Kiểm tra nội dung đã học  |
|          | 16h00–17h00 | Giải trí                      | Giảm căng thẳng           |
|          | 19h00–20h30 | Hoàn thành bài tập còn thiếu  | Tránh tồn đọng bài tập    |
|          | 20h30–22h00 | Nghỉ ngơi                     | Thư giãn                  |
| Thứ Bảy  | 7h30–8h30   | Ăn sáng, vận động             | Khởi động ngày mới        |
|          | 8h30–10h30  | Ôn tập Đại số                 | Giải các bài tập khó      |
|          | 10h30–11h30 | Nghỉ ngơi                     | Phục hồi năng lượng       |
|          | 14h00–16h00 | Thực hành lập trình           | Cải thiện kỹ năng         |
|          | 16h00–18h00 | Giải trí, gặp gỡ bạn bè       | Cân bằng cuộc sống        |
|          | 19h00–20h00 | Ôn lại kiến thức trong tuần   | Ghi nhớ nội dung          |
|          | 20h00–22h00 | Nghỉ ngơi, giải trí           | Thư giãn                  |
| Chủ nhật | 7h30–8h30   | Ăn sáng, thư giãn             | Khởi đầu nhẹ nhàng        |
|          | 8h30–10h00  | Xem lại bài học còn chưa hiểu | Bổ sung kiến thức         |
|          | 10h00–11h30 | Nghỉ ngơi                     | Thư giãn                  |
|          | 14h00–15h30 | Chuẩn bị bài cho tuần mới     | Chủ động học tập          |
|          | 15h30–17h30 | Giải trí, hoạt động cá nhân   | Nghỉ ngơi                 |
|          | 19h00–20h00 | Lập kế hoạch tuần tiếp theo   | Quản lý thời gian         |
|          | 20h00–22h00 | Nghỉ ngơi, chuẩn bị ngủ       | Sẵn sàng cho tuần mới     |

### **3. Nhận xét về tính hợp lý của kế hoạch**

- **Đảm bảo thời gian học:** Từ thứ Hai đến thứ Sáu có lịch học trên lớp đúng khung giờ 7h30–11h30.
- **Ưu tiên môn học khó:** Đại số và Tin học cơ sở được bố trí nhiều buổi tự học để giải quyết bài tập.
- **Cân bằng nghỉ ngơi:** Mỗi ngày đều có ít nhất 1 giờ giải trí và thời gian nghỉ giữa các buổi học.
- **Tránh quá tải:** Các buổi tự học được chia thành từng khoảng 1,5–2 giờ, không học quá 3 giờ liên tục.

**Kết luận:** Kế hoạch giúp sinh viên chủ động quản lý thời gian, hạn chế trì hoãn, hoàn thành bài tập đúng hạn và duy trì sự cân bằng giữa học tập với cuộc sống cá nhân.
