# BÁO CÁO PHÂN TÍCH VÀ LỰA CHỌN MÔ HÌNH SDLC
**Dự án:** RikkeiExpress App  
**Đơn vị:** RikkeiExpress Logistics  
**Ngày lập:** 10/09/2026  

---

## 1. PHẦN 1: BẢNG SO SÁNH MÔ HÌNH WATERFALL VÀ AGILE/SCRUM

Dựa trên 4 tiêu chí chuẩn trong phân tích & thiết kế hệ thống, dưới đây là bảng so sánh giữa hai mô hình phát triển phần mềm:

| Tiêu chí đánh giá | Mô hình Thác nước (Waterfall) | Phương pháp Linh hoạt (Agile/Scrum) |
| :--- | :--- | :--- |
| **1. Yêu cầu ban đầu** | **Cố định 100%**: Yêu cầu tài liệu hóa toàn bộ trước khi lập trình. Cấm hoặc hạn chế tối đa thay đổi trong quá trình phát triển (6 tháng). | **Linh hoạt & Thay đổi**: Yêu cầu được chia nhỏ (Backlog) và có thể thích ứng, điều chỉnh linh hoạt theo phản hồi thực tế sau mỗi chu kỳ (Sprint 1-2 tuần). |
| **2. Thời gian có bản Demo** | **Muộn (Sau 6 tháng)**: Sản phẩm chỉ được bàn giao và nhìn thấy hoàn chỉnh ở giai đoạn cuối của dự án. | **Sớm (Mỗi 2 tuần)**: Bản Demo/Increment chạy được được bàn giao liên tục sau mỗi Sprint 2 tuần để chạy thử nghiệm thị trường. |
| **3. Mức độ rủi ro** | **Rất cao (Waterfall Rigidity Trap)**: Rủi ro xây sai nhu cầu tài xế/thị trường. Nếu sản phẩm bị lạc hậu sau 6 tháng, toàn bộ ngân sách đã giải ngân hết và rất khó sửa chữa. | **Thấp**: Rủi ro được chia nhỏ và kiểm soát theo từng Sprint. Phát hiện lỗi hoặc lệch hướng nhu cầu thị trường sớm để điều chỉnh kịp thời, tránh lãng phí ngân sách lớn. |
| **4. Mức độ tham gia của KH / Người dùng** | **Thấp**: Khách hàng/Ban Giám đốc chỉ tham gia chính ở giai đoạn lấy yêu cầu ban đầu và nghiệm thu cuối cùng. | **Rất cao**: Khách hàng, Ban Giám đốc và người dùng tham gia liên tục (Review/Feedback sau mỗi 2 tuần) để định hình phát triển sản phẩm. |

---

## 2. PHẦN 2: ĐỀ XUẤT MÔ HÌNH & BẢN LẬP LUẬN THUYẾT PHỤC BAN GIÁM ĐỐC & CFO

### Đề xuất mô hình tối ưu: **Mô hình Agile/Scrum**

---

### Bản lập luận thuyết phục CFO & Ban Giám đốc (3-4 câu sắc bén):

1. **Tối ưu hóa dòng tiền & Kiểm soát rủi ro tài chính:**  
   Thay vì giải ngân 100% ngân sách cho 6 tháng phát triển rủi ro cao theo Waterfall, việc cấp ngân sách theo từng chu kỳ Sprint (1-2 tuần) giúp CFO chủ động kiểm soát chi phí theo giá trị thực tế nhận được (Pay-as-you-go) và dừng/điều chỉnh dự án kịp thời nếu không đạt ROI kỳ vọng.

2. **Rút ngắn Time-to-Market & Chiếm lĩnh thị trường sớm:**  
   Với mô hình Agile/Scrum, RikkeiExpress App sẽ sở hữu phiên bản thử nghiệm có thể chạy được (MVP) chỉ sau 2-4 tuần đầu tiên, giúp doanh nghiệp đưa sản phẩm ra thị trường sớm thay vì phải chờ đợi 6 tháng như mô hình Thác nước.

3. **Loại bỏ "Bẫy cứng nhắc" (Waterfall Rigidity Trap) & Đảm bảo đúng nhu cầu người dùng:**  
   Việc thu nhận phản hồi trực tiếp từ Khách hàng và Tài xế sau mỗi bản Demo 2 tuần giúp sản phẩm liên tục hoàn thiện theo đúng thực tế thị trường, loại bỏ hoàn toàn rủi ro đầu tư hàng tỷ đồng để tạo ra một ứng dụng lạc hậu hay không thể sử dụng sau 6 tháng.
