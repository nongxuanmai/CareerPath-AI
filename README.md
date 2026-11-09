CareerPath AI
Hệ thống hỗ trợ khám phá và gợi ý định hướng nghề nghiệp bằng Machine Learning
Trạng thái: Đang lập kế hoạch (Planning)
Hình thức: Dự án cá nhân kết hợp Business Analysis (BA) và Artificial Intelligence (AI)
Thời gian dự kiến: 09/11/2026 – 06/02/2027
Phiên bản mục tiêu: MVP v1.0

1. Giới thiệu
CareerPath AI là dự án ứng dụng web nhằm hỗ trợ sinh viên khám phá các nhóm nghề nghiệp dựa trên những thông tin có thể thu thập hợp lý, chẳng hạn như sở thích, kỹ năng và năng lực tự đánh giá. Hệ thống dự kiến ứng dụng mô hình học máy để tạo gợi ý và trình bày các yếu tố liên quan đến kết quả.

Dự án đồng thời là môi trường thực hành trọn vẹn quy trình phân tích nghiệp vụ → chuẩn bị dữ liệu → xây dựng và đánh giá mô hình → phát triển sản phẩm → kiểm thử và trình bày kết quả.

Lưu ý: Kết quả gợi ý chỉ mang tính tham khảo, không phải đánh giá năng lực chính thức hay bảo đảm về mức độ phù hợp với một nghề nghiệp.
2. Bài toán và mục tiêu
2.1. Bài toán cần xác minh
Sinh viên có thể gặp khó khăn khi tìm hiểu lựa chọn nghề nghiệp, nhận diện kỹ năng của bản thân và kết nối thông tin cá nhân với yêu cầu nghề nghiệp. Đây là giả thuyết ban đầu, cần được kiểm chứng thông qua khảo sát hoặc phỏng vấn người dùng ở giai đoạn BA.
2.2. Mục tiêu dự án
- Phân tích nhu cầu người dùng và xác định yêu cầu nghiệp vụ rõ ràng, có thể kiểm thử.
- Đánh giá tính khả thi của dữ liệu cho bài toán phân loại/gợi ý nghề nghiệp.
- Xây dựng mô hình baseline, so sánh các phương pháp phù hợp và báo cáo kết quả bằng các chỉ số có ý nghĩa.
- Phát triển MVP web đơn giản, kết nối được giao diện với API dự đoán.
- Tài liệu hóa giả định, giới hạn, rủi ro và các quyết định kỹ thuật.
- Hoàn thiện sản phẩm có thể trình diễn cùng hồ sơ BA và AI phục vụ portfolio.
3. Đối tượng và các bên liên quan
Nhóm	Vai trò dự kiến	Điều cần xác minh
Sinh viên	Người dùng chính	Nhu cầu, cách trả lời câu hỏi, mức độ hiểu kết quả
Người tư vấn hướng nghiệp	Bên liên quan chuyên môn	Tính hợp lý của thông tin và cách diễn giải
Người phát triển dự án	BA, AI, phát triển và kiểm thử	Tính khả thi, chất lượng và phạm vi MVP


Danh sách stakeholder sẽ được cập nhật sau khi phân tích thực tế.
4. Phạm vi MVP dự kiến
4.1. Chức năng trong phạm vi
1. Nhập thông tin và trả lời bộ câu hỏi đánh giá nghề nghiệp.
2. Kiểm tra hợp lệ và tiền xử lý dữ liệu đầu vào.
3. Sử dụng mô hình Machine Learning để dự đoán nhóm nghề nghiệp.
4. Hiển thị tối đa ba gợi ý nghề nghiệp nếu mô hình hỗ trợ xếp hạng có cơ sở.
5. Trình bày các yếu tố có liên quan đến dự đoán bằng phương pháp giải thích phù hợp.
6. Đề xuất kỹ năng cần tìm hiểu hoặc phát triển dựa trên nguồn hồ sơ nghề nghiệp được kiểm chứng, không tự suy diễn từ mô hình phân loại.
4.2. Ngoài phạm vi MVP
- Chatbot sử dụng mô hình ngôn ngữ lớn (LLM).
- Đăng ký, đăng nhập và hệ thống quản trị phức tạp.
- Ứng dụng di động.
- Tích hợp dữ liệu tuyển dụng thời gian thực.
- Tuyên bố đánh giá tâm lý, năng lực hoặc mức độ phù hợp nghề nghiệp mang tính chính thức.
Điều kiện quan trọng: Bộ câu hỏi và các trường đầu vào chỉ được chốt sau khi kiểm tra tập dữ liệu. Đặc trưng suy luận phải tương thích với đặc trưng huấn luyện. Không tự đặt câu hỏi rồi giả định có thể đưa trực tiếp vào mô hình.

5. Định hướng BA
Các sản phẩm BA dự kiến:
- Problem Statement và Project Charter.
- Stakeholder Register, kế hoạch/phương án khảo sát.
- Business Requirements và phạm vi MVP.
- Functional Requirements (FR), Non-functional Requirements (NFR).
- Use Case Diagram, đặc tả Use Case và Business Rules.
- BPMN AS-IS/TO-BE khi có quy trình nghiệp vụ phù hợp.
- User Stories, Acceptance Criteria.
- Wireframe và luồng người dùng.
- Requirements Traceability Matrix (RTM).
- Test Cases, UAT và Defect Log.
Yêu cầu phải rõ ràng, nhất quán, khả thi, truy vết được và có thể kiểm thử.
6. Định hướng AI
Quy trình thực nghiệm dự kiến:
    1. Dataset audit: kiểm tra nguồn, giấy phép, kích thước, nhãn, phân bố lớp, dữ liệu thiếu và rủi ro thiên lệch.
    2. Feature/target review: xác minh biến mục tiêu, đặc trưng có thể thu thập khi sử dụng thật và nguy cơ data leakage.
    3. Data split: tách train/validation/test phù hợp; cố định random seed và lưu cấu hình.
    4. Baseline: bắt đầu bằng DummyClassifier, sau đó thử Logistic Regression và các mô hình phù hợp với kiểu dữ liệu.
    5. Model comparison: so sánh với Random Forest hoặc phương pháp khác nếu có cơ sở.
    6. Evaluation: ưu tiên macro-F1, precision/recall/F1 theo lớp, confusion matrix; cân nhắc calibration và top-k nếu cần.
    7. Explainability: thử permutation importance hoặc SHAP khi thích hợp; phân biệt giải thích hành vi mô hình với quan hệ nhân quả.
    8. Deployment: đóng gói toàn bộ pipeline tiền xử lý và mô hình để suy luận nhất quán.
    Không đặt ngưỡng accuracy tùy tiện. Không sử dụng tập test để lựa chọn mô hình hoặc tuning. Nếu dữ liệu không phù hợp, cần điều chỉnh phạm vi hoặc thay nguồn dữ liệu trước khi tiếp tục.
    7. Công nghệ dự kiến
    Thành phần	Công nghệ đề xuất	Trạng thái
    Tài liệu BA	Markdown, diagrams.net hoặc công cụ tương đương	Dự kiến
    Phân tích dữ liệu	Python, Pandas, NumPy	Dự kiến
    Machine Learning	scikit-learn	Dự kiến
    Trực quan và đánh giá	Matplotlib, Seaborn (tùy nhu cầu)	Dự kiến
    API	FastAPI	Dự kiến
    Giao diện web	Streamlit hoặc React/Next.js (chốt sau)	Chưa quyết định
    Quản lý phiên bản	Git, GitHub	Dự kiến


    Ưu tiên công nghệ đơn giản, phù hợp với 1 giờ/ngày. Chỉ bổ sung độ phức tạp khi có lý do nghiệp vụ hoặc kỹ thuật.
    8. Cấu trúc thư mục ban đầu
    careerpath-ai/
    ├── README.md
    ├── docs/
    │   ├── 01_problem_statement.md
    │   ├── 02_stakeholders.md
    │   ├── 03_data_feasibility.md
    │   ├── 04_mvp_scope.md
    │   └── 05_project_charter.md
    ├── assessments/
    │   └── baseline_week1.md
    └── reviews/
        └── week01_review.md
    Khi bước sang giai đoạn triển khai, có thể bổ sung data/, src/, notebooks/, tests/, app/, configs/ và results/. Không đưa dữ liệu nhạy cảm, khóa bí mật hoặc tập dữ liệu không được phép phân phối lên GitHub.
    9. Lộ trình
    Tuần	Thời gian	Trọng tâm	Đầu ra chính
    1	09–15/11/2026	Khởi động, xác định vấn đề, khảo sát dữ liệu	Project Charter v1, Data Feasibility Note, Baseline Assessment
    2	16–22/11/2026	Khảo sát người dùng và dữ liệu	Stakeholder Register, Interview Guide, Dataset Audit
    3	23–29/11/2026	Đặc tả yêu cầu và chọn đặc trưng	BRD v1, Use Case Diagram, Feature Mapping
    4	30/11–06/12/2026	Mô hình hóa nghiệp vụ và EDA	BPMN, Acceptance Criteria, EDA Report
    5	07–13/12/2026	Thiết kế giải pháp và tiền xử lý	SRS v1, Wireframe, Preprocessing Pipeline
    6	14–20/12/2026	Chốt yêu cầu, xây baseline	RTM, Baseline Results
    7	21–27/12/2026	Phát triển và so sánh mô hình	Model Comparison Report
    8	28/12–03/01/2027	Tối ưu, phân tích lỗi	Error Analysis, Model v1
    9	04–10/01/2027	Giải thích mô hình	Explainability Report, Explanation Design
    10	11–17/01/2027	Thiết kế và phát triển API	API cục bộ, API Tests
    11	18–24/01/2027	Phát triển và tích hợp giao diện	Web MVP end-to-end
    12	25–31/01/2027	Kiểm thử và hoàn thiện	Test Report, MVP Release Candidate
    13	01–06/02/2027	Portfolio, demo, tổng kết	Portfolio, Demo, Final Review


    Các mốc nghiệm thu
    - Cuối tuần 3: Bài toán, đặc trưng đầu vào và dữ liệu tương thích.
    - Cuối tuần 6: Baseline chạy được và kết quả tái lập được.
    - Cuối tuần 9: Mô hình được đánh giá nghiêm túc, có báo cáo giới hạn.
    - Cuối tuần 12: MVP chạy end-to-end và qua các kiểm thử quan trọng.
    - Cuối tuần 13: Trình diễn và tự bảo vệ các lựa chọn BA/AI.
    10. Kế hoạch từng ngày


    11. Sáu trụ cột phát triển cá nhân
    Trụ cột	Cách thực hành	Minh chứng
    Chuyên môn sâu	Phân tích nghiệp vụ, xây dựng và đánh giá ML	Tài liệu BA, mã nguồn, mô hình
    Tri thức rộng & phản biện	Đọc tài liệu, kiểm tra giả định, phân tích bằng chứng	Decision Log
    Giao tiếp	Trình bày yêu cầu, giải thích kết quả, demo	Bài nói, video hoặc ghi chú
    Bản lĩnh & độc lập	Tự đưa ra quyết định và bảo vệ bằng lý lẽ	Decision Journal
    Kỷ luật & tự quản	Học 60 phút/ngày, review hằng tuần	Nhật ký tiến độ
    Tinh tế & đời sống tinh thần	Đọc, viết, cảm nhận nghệ thuật và phản tư	Reflection Journal


    Các trụ cột được lồng ghép vào công việc hằng ngày, không bắt buộc tạo sáu nhiệm vụ riêng biệt mỗi ngày.
    12. Nguyên tắc thực hiện
    - Tự làm trước, nhận phản biện sau: sử dụng AI như người hướng dẫn và reviewer, không thay thế hoàn toàn việc tự suy nghĩ.
    - Không bịa dữ liệu: mọi nguồn, chỉ số và kết quả thực nghiệm phải được kiểm chứng.
    - Ưu tiên khả thi: giữ MVP nhỏ và hoàn thiện trước khi mở rộng.
    - Tài liệu và code nhất quán: thay đổi yêu cầu cần được phản ánh trong thiết kế và kiểm thử.
    - Theo dõi tiến độ: mỗi ngày ghi nội dung đã làm, khó khăn, quyết định và bước tiếp theo.
    - Đánh giá bằng minh chứng: không xem việc hoàn thành checklist là bằng chứng đủ về chất lượng.
    - Tôn trọng giới hạn của AI: không diễn giải dự đoán như kết luận chắc chắn về tương lai nghề nghiệp.
    13. Trạng thái triển khai
    Hạng mục	Trạng thái
    Xác định ý tưởng và phạm vi sơ bộ	Đã lập kế hoạch
    Phân tích người dùng và đặc tả	Chưa thực hiện
    Xác minh dữ liệu	Chưa thực hiện
    Huấn luyện và đánh giá mô hình	Chưa thực hiện
    API và giao diện web	Chưa thực hiện
    Kiểm thử và portfolio	Chưa thực hiện


    Các trạng thái trên cần được cập nhật theo tiến độ thực tế.