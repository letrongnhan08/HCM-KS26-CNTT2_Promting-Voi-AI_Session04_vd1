Vận dụng cơ bản 1: Sửa đổi prompt thiếu cấu trúc ràng buộc định dạng

**Bước 1: Phân tích lỗi:**

Chỉ ra 3 phần văn bản thừa thãi (như lời chào, lời kết) trong câu trả lời cũ của AI.

- Lời chào xã giao mở đầu: như (Chào bạn! Dưới đây là giải thích ngắn gọn về)
- Đoạn dẫn dắt/chuyển ý lặp lại:(Để khắc phục hoàn toàn tình trạng trên, chúng ta cần đưa)
- Lời kết chúc tụng, mở rộng cuối bài: (Hy vọng thông tin trên hữu ích cho bạn)  hoặc (Bạn có muốn tìm hiểu thêm gì nữa không?)

**Bước 2: Viết prompt tối ưu:**

Hãy đóng vai là một giảng viên CNTT đang dạy về Kỹ thuật Prompting vơi AI, Hãy giải thích ngắn gọn các nội dung của Chain-of-Thought, Prompt Chaining, xử lý đứt gãy (Continue generating)

RÀNG BUỘC ĐỊNH DẠNG & NỘI DUNG

- Không sử dụng những câu từ cảm xúc, chào hỏi,lời dẫn dắt thừa thãi như (Chào bạn,Dưới đây là,Hy vọng,Bạn có muốn tìm hiểu thêm) , chỉ tập trung nói vào nội dung chính
- Mỗi khái niệm trình bày tối đa từ 2 đến 4 câu hoặc dưới 50 từ.
- Bắt buộc sử dụng định dạng danh sách gạch đầu dòng (bullet points) cho từng khái niệm.

**Kết quả phản hồi của AI:**
- **Chain-of-Thought (CoT):** Kỹ thuật hướng dẫn AI chia nhỏ quá trình suy luận thành các bước logic tuần tự trước khi đưa ra kết quả cuối cùng, giúp tăng độ chính xác cho các bài toán phức tạp.
    
- **Prompt Chaining:** Kỹ thuật chia một nhiệm vụ lớn thành chuỗi các prompt nhỏ liên tiếp, trong đó đầu ra của prompt trước được dùng làm đầu vào cho prompt sau để kiểm soát luồng xử lý tốt hơn.
    
- **Xử lý đứt gãy (Continue generating):** Thao tác ra lệnh tiếp tục hoặc sử dụng tính năng bổ trợ khi câu trả lời của AI bị ngắt quãng giữa chừng do chạm giới hạn token đầu ra.
