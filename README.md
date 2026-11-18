Đề bài / Yêu cầu

Lập kế hoạch tài chính cá nhân bằng Chain-of-Thought

1. Mục tiêu

Luyện tập tư duy suy luận logic phức tạp của AI bằng kỹ thuật Chain-of-Thought (CoT).

Biết cách kiểm soát các bước lập luận trung gian để hạn chế sai sót tính toán số học của LLM.

Cấu trúc kết quả đầu ra trực quan gồm cả phần phân tích logic và bảng tổng hợp số liệu.

2. Bối cảnh bài toán

Một cá nhân có thu nhập biến động mỗi tháng và đang có một số khoản nợ cần thanh toán. Họ cần một trợ lý AI thông minh lập kế hoạch tài chính chi tiết, tối ưu hóa dòng tiền và đưa ra đề xuất phân bổ ngân sách chi tiêu hợp lý.

Do bài toán liên quan đến nhiều phép tính số học và ràng buộc tài chính (tiết kiệm tối thiểu 20%, trả nợ đúng hạn, quỹ dự phòng), nếu để AI trả lời ngay đáp án sẽ rất dễ bị sai lệch số liệu.

3. Yêu cầu

Thiết kế prompt yêu cầu AI lập kế hoạch tài chính hàng tháng từ dữ liệu đầu vào gồm: Thu nhập, Chi phí cố định, Các khoản nợ, Mục tiêu tiết kiệm.

Yêu cầu AI thực hiện suy luận từng bước (Chain-of-Thought) để tính toán ngân sách trước khi xuất kết quả cuối cùng.

4. Quy tắc xử lý

Kích hoạt Chain-of-Thought bằng chỉ thị tường minh: 'Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định'.

Vạch ra quy trình lập luận gồm các bước:

Bước 1: Tính toán tổng thu nhập khả dụng sau khi trừ thuế và chi phí cố định bắt buộc.

Bước 2: Phân bổ khoản tiền trả nợ tối thiểu.

Bước 3: Trích lập quỹ tiết kiệm theo tỷ lệ cam kết.

Bước 4: Chia phần còn lại cho chi tiêu linh hoạt theo quy tắc 50/30/20 cải tiến.

5. Yêu cầu xử lý dữ liệu

Trình bày kết quả lập luận thành hai phần rõ rệt:

Phần 1: Nhật ký suy luận logic (Reasoning Steps) chỉ ra công thức tính toán và số liệu trung gian.

Bước 1. Tính toán tổng thu nhập khả dụng sau khi trừ thuế và chi phí cố định bắt buộc.

Thu nhập sau thuế: 16,000,000 – 1,000,000 = 15,000,000 VNĐ (cố định làm mốc 100%)

Thu nhập khả dụng: 15,000,000 – 4,500,000 = 10,500,000 VNĐ (chi phí cố định)

Tỷ lệ chi phí cố định: (4,500,000 : 15,000,000) x 100% = 30%

Bước 2. Phân bổ khoản tiền trả nợ tối thiểu.

Tổng nợ tối thiểu: 1,500,000 (trả góp) + 750,000 (thể tín dụng) = 2,250,000 VNĐ

Số dư sau nợ: 10,500,000 – 2,250,000 = 8,250,000 VNĐ

Tỷ lệ trả nợ: (2,250,000 : 15,000,000) x 100% = 15%

Bước 3: Trích lập quỹ tiết kiệm theo tỷ lệ cam kết.

Tiền tiết kiệm: 15,000,000 x 20% = 3,000,000 VNĐ (chiếm 20% thu nhập sau thuế).

Số dư chi tiêu còn lại: 8,250,000 – 3,000,000 = 5,250,000 VNĐ (Còn lại 35% ngân sách). 

Bước 4: Chia chi tiêu linh hoạt theo quy tắc 60/20/20 cải tiến (từ số dư 5,250,000 VNĐ)

Sinh hoạt thiết yếu biến đổi (60%  số dư): 5,250,000 x 50% = 2,625,000 VNĐ → (1,575,000 : 15,000,000) x 100% = 10,5%

Cá nhân và Giải trí (30% số dư): 5,250,000 x 30% = 1,575,000 VNĐ → (1,575,000 : 15,000,000) x 100% = 17,5% 

Quỹ dự phòng thu nhập biến động (20% số dư ): 5,250,000 x 20% = 1,050,000 VNĐ →(1,050,000 : 15,000,000) x 100% = 7%

Đối soát tổng hợp: 30% + 15% + 20% + 17,5% + 10,5% + 7% = 100% (khớp chính xác 15,000,000 VNĐ) 

Phần 2: Bảng phân bổ ngân sách cuối cùng bằng Markdown Table với các cột: Hạng mục, Số tiền, Tỷ lệ %, Ghi chú.

Hạng mục	Số tiền	Tỷ lệ %	Ghi chú

Chi phí cố định bắt buộc	4,500,000 VNĐ	30%	Tiền phòng trọ, điện, nước, internet.

Sinh hoạt thiết yếu biến đổi	2,625,000 VNĐ	17,5%	Ăn uống, xăng xe, đi lại hàng ngày.

Thanh toán nợ tối thiểu	2,250,000 VNĐ	15%	Trả góp và thanh toán tối thiểu thẻ tín dụng đúng hạn.

Quỹ tiết kiệm cam kết	3,000,000 VNĐ	20%	Khóa cứng ngay khi nhận lương để đảm bảo kỷ luật.

Chi tiêu cá nhân và Giải trí	1,575,000 VNĐ	10,5%	Mua sắm, cà phê, giải trí cuối tuần.

Quỹ dự phòng linh hoạt	1,050,000 VNĐ	7%	Bù đắp dòng tiền cho những tháng thu nhập sụt giảm.

TỔNG CỘNG	15,000,000 VNĐ	100%	Tính trên tổng thu nhập thực nhận sau thuế.

6. Ràng buộc kỹ thuật

Bắt buộc hiển thị đầy đủ phép tính cộng trừ nhân chia trung gian, không nhảy cóc ra kết quả.

Đảm bảo tổng tỷ lệ phần trăm phân bổ ngân sách phải bằng chính xác 100%.

Không dùng Pydantic hay code Python, thực hiện hoàn toàn bằng kỹ năng Prompting logic.
