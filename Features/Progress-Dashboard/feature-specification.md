# FEATURE 03: Progress Dashboard – Bảng theo dõi tiến độ học tập

## 1. Overview – Tổng quan
### Mục đích:
Cung cấp một bảng theo dõi tiến độ học tập giúp học sinh quản lý, đánh giá và theo dõi quá trình học tập thông qua các dữ liệu như thời gian học, nhiệm vụ đã hoàn thành, kết quả học tập và hiệu suất theo từng môn.

### Vấn đề cần giải quyết:
- Học sinh khó theo dõi tiến độ học tập và mức độ hoàn thành mục tiêu.
- Học sinh không biết mình đã dành bao nhiêu thời gian cho từng môn học.
- Học sinh khó đánh giá mức độ hoàn thành các nhiệm vụ học tập.
- Học sinh chưa nhận biết rõ môn học nào đang tiến bộ và môn học nào cần cải thiện.
- Phụ huynh gặp khó khăn khi muốn nắm bắt tình hình học tập của con.
### Đối tượng sử dụng:
- Học sinh trung học cơ sở.
- Học sinh trung học phổ thông.
- Phụ huynh muốn theo dõi tình hình học tập của con.
### Giá trị mang lại:
- Giúp học sinh theo dõi tiến độ học tập một cách trực quan.
- Hỗ trợ học sinh đánh giá mức độ hoàn thành mục tiêu.
- Giúp học sinh quản lý thời gian học tập hiệu quả hơn.
- Xác định điểm mạnh và những môn học cần cải thiện.
- Cung cấp báo cáo học tập để học sinh và phụ huynh nắm bắt tình hình học tập.
- Hỗ trợ AI đưa ra nhận xét và gợi ý học tập dựa trên dữ liệu thực tế.
## 2. Sub-features – Các chức năng nhỏ
Progress Dashboard gồm 5 chức năng nhỏ:
 ID | Sub-feature | Mô tả
|---|---|---|
PD-01 | Overall Learning Progress | Theo dõi tổng quan tiến độ học tập
PD-02 | Study Time Tracking | Theo dõi thời gian học tập
PD-03 | Task Completion |	Theo dõi nhiệm vụ học tập đã hoàn thành
PD-04 | Learning Report |	Tổng hợp và tạo báo cáo học tập
PD-05 | Subject Performance Analysis | Phân tích kết quả học tập theo môn

## 3. User Flow – Luồng hoạt động
Luồng tổng quát:
1. Học sinh truy cập tính năng Progress Dashboard.
2. Hệ thống truy xuất dữ liệu học tập đã được ghi nhận.
3. Hệ thống hiển thị tổng quan tiến độ học tập.
4. Học sinh xem thời gian học tập theo môn hoặc theo khoảng thời gian.
5. Học sinh xem trạng thái và tỷ lệ hoàn thành nhiệm vụ.
6. Học sinh lựa chọn khoảng thời gian muốn xem báo cáo.
7. Hệ thống tổng hợp dữ liệu học tập tương ứng.
8. AI phân tích dữ liệu và tạo nhận xét học tập nếu có đủ dữ liệu.
9. Hệ thống hiển thị báo cáo học tập và kết quả phân tích theo môn.
10. Học sinh sử dụng thông tin để đánh giá và điều chỉnh kế hoạch học tập.
### Sơ đồ luồng tổng quát:
Access Progress Dashboard
          ↓
Retrieve Learning Data
          ↓
Overall Learning Progress
          ↓
Study Time Tracking
          ↓
Task Completion
          ↓
Select Time Period
          ↓
Generate Learning Report
          ↓
AI analyzes learning data
          ↓
Subject Performance Analysis
          ↓
Display Learning Insights

## 4. Functional Description – Mô tả chức năng
### PD-01: Overall Learning Progress – Theo dõi tổng quan tiến độ học tập
#### Mô tả:
Cho phép học sinh theo dõi tiến độ học tập tổng thể theo ngày, tuần hoặc tháng. Hệ thống tổng hợp dữ liệu từ các nhiệm vụ, hoạt động học tập và mục tiêu đã được ghi nhận.

Thông tin được hiển thị dưới dạng tỷ lệ hoàn thành, số nhiệm vụ đã hoàn thành và biểu đồ tiến độ, giúp học sinh dễ dàng đánh giá tình hình học tập của mình.

#### Input:
- Dữ liệu nhiệm vụ học tập.
- Dữ liệu hoạt động học tập.
- Mục tiêu học tập.
- Khoảng thời gian cần theo dõi: ngày, tuần hoặc tháng.
#### Processing:
1. Hệ thống truy xuất dữ liệu học tập từ database.
2. Lọc dữ liệu theo khoảng thời gian người dùng lựa chọn.
3. Tổng hợp số nhiệm vụ đã hoàn thành và tổng số nhiệm vụ.
4. Tính toán tỷ lệ hoàn thành tiến độ học tập.
5. Tổng hợp dữ liệu theo ngày, tuần hoặc tháng.
6. Hiển thị kết quả bằng biểu đồ hoặc thanh tiến độ.
#### Output:
- Tổng quan tiến độ học tập.
- Tỷ lệ hoàn thành mục tiêu.
- Số nhiệm vụ đã hoàn thành.
- Biểu đồ tiến độ học tập.
- Tiến độ theo ngày, tuần hoặc tháng.
#### Business Rules:
- Chỉ sử dụng dữ liệu học tập đã được ghi nhận trong hệ thống.
- Dữ liệu phải thuộc khoảng thời gian người dùng lựa chọn.
- Tỷ lệ tiến độ được tính dựa trên dữ liệu hợp lệ.
- Nếu không có dữ liệu, hệ thống không hiển thị tỷ lệ tiến độ giả định.
- Tiến độ được cập nhật khi người dùng hoàn thành nhiệm vụ hoặc ghi nhận hoạt động học tập mới.
#### Exception Handling:
- Không có dữ liệu học tập → hiển thị thông báo “Chưa có dữ liệu học tập”.
- Lỗi truy xuất dữ liệu → hiển thị thông báo lỗi và cho phép tải lại.
- Dữ liệu không hợp lệ → loại bỏ dữ liệu lỗi khỏi quá trình tính toán.
AI sử dụng: Backend + Database + Progress Calculation Logic
### PD-02: Study Time Tracking – Theo dõi thời gian học tập
#### Mô tả:
Cho phép học sinh theo dõi thời gian dành cho việc học theo từng môn học và khoảng thời gian cụ thể.

Hệ thống tổng hợp thời gian học đã ghi nhận, giúp học sinh biết mình đã dành bao nhiêu thời gian cho từng môn và có phân bổ thời gian học tập hợp lý hay không.

#### Input:
- Môn học.
- Thời gian bắt đầu học.
- Thời gian kết thúc học.
- Thời lượng học.
- Khoảng thời gian cần xem.
#### Processing:
1. Hệ thống ghi nhận thời gian bắt đầu và kết thúc của phiên học.
2. Tính toán tổng thời lượng học tập.
3. Lưu dữ liệu thời gian học vào database.
4. Tổng hợp thời gian học theo từng môn.
5. Tổng hợp thời gian theo ngày, tuần hoặc tháng.
6. Hiển thị dữ liệu dưới dạng bảng hoặc biểu đồ.
#### Output:
- Tổng thời gian học tập.
- Thời gian học theo từng môn.
- Thời gian học theo ngày, tuần hoặc tháng.
- Biểu đồ phân bổ thời gian học tập.
#### Business Rules:
- Thời gian học phải được ghi nhận hợp lệ.
- Thời gian kết thúc không được nhỏ hơn thời gian bắt đầu.
- Không ghi nhận thời lượng học âm.
- Thời gian học được phân loại theo môn học tương ứng.
- Chỉ tổng hợp các phiên học có dữ liệu hợp lệ.
#### Exception Handling:
- Chưa có dữ liệu thời gian học → hiển thị thông báo chưa có dữ liệu.
- Phiên học chưa kết thúc → chưa tính thời lượng hoàn chỉnh.
- Thời gian không hợp lệ → yêu cầu người dùng kiểm tra lại.
- Lỗi truy xuất dữ liệu → hiển thị thông báo và cho phép tải lại.
AI sử dụng: Backend + Database + Time Tracking Logic
### PD-03: Task Completion – Theo dõi nhiệm vụ học tập đã hoàn thành
#### Mô tả:
Cho phép học sinh theo dõi trạng thái của các nhiệm vụ học tập như bài tập, mục tiêu hoặc hoạt động được tạo từ AI Study Planner.

Hệ thống phân loại nhiệm vụ theo trạng thái đã hoàn thành, đang thực hiện và chưa hoàn thành. Từ đó, học sinh có thể biết được mức độ hoàn thành kế hoạch học tập của mình.

#### Input:
- Danh sách nhiệm vụ học tập.
- Tên nhiệm vụ.
- Môn học.
- Hạn hoàn thành.
- Trạng thái nhiệm vụ.
- Dữ liệu nhiệm vụ từ AI Study Planner hoặc các hoạt động học tập.
#### Processing:
1. Hệ thống truy xuất danh sách nhiệm vụ học tập.
2. Lọc nhiệm vụ theo khoảng thời gian.
3. Phân loại nhiệm vụ theo trạng thái.
4. Tính số nhiệm vụ đã hoàn thành.
5. Tính tỷ lệ hoàn thành nhiệm vụ.
6. Hiển thị danh sách nhiệm vụ và trạng thái tương ứng.
#### Output:
- Danh sách nhiệm vụ học tập.
- Trạng thái từng nhiệm vụ.
- Số nhiệm vụ đã hoàn thành.
- Số nhiệm vụ đang thực hiện.
- Số nhiệm vụ chưa hoàn thành.
- Tỷ lệ hoàn thành nhiệm vụ.
#### Business Rules:
- Mỗi nhiệm vụ phải có trạng thái hợp lệ.
- Trạng thái nhiệm vụ được cập nhật khi người dùng hoàn thành nhiệm vụ.
- Tỷ lệ hoàn thành được tính dựa trên số nhiệm vụ hoàn thành và tổng số nhiệm vụ.
- Chỉ tính các nhiệm vụ thuộc khoảng thời gian được chọn.
- Nhiệm vụ không có trạng thái hợp lệ sẽ không được tính vào kết quả.
#### Exception Handling:
- Không có nhiệm vụ → hiển thị thông báo chưa có nhiệm vụ học tập.
- Nhiệm vụ thiếu thông tin → không sử dụng dữ liệu không hợp lệ.
- Lỗi cập nhật trạng thái → thông báo cho người dùng và cho phép thử lại.
- Lỗi truy xuất danh sách → hiển thị thông báo lỗi và cho phép tải lại.
AI sử dụng: Backend + Database + Task Management Logic
### PD-04: Learning Report – Tổng hợp và tạo báo cáo học tập
#### Mô tả:
Cho phép hệ thống tổng hợp dữ liệu học tập của học sinh theo ngày, tuần hoặc tháng để tạo báo cáo học tập.

Báo cáo bao gồm thời gian học, nhiệm vụ đã hoàn thành, kết quả học tập và tiến độ đạt mục tiêu. AI phân tích dữ liệu để tạo nhận xét về điểm mạnh, những vấn đề cần cải thiện và gợi ý học tập phù hợp.

Báo cáo giúp học sinh nhìn lại quá trình học tập và giúp phụ huynh hiểu rõ hơn về tình hình học tập của con.

#### Input:
- Dữ liệu thời gian học tập.
- Trạng thái nhiệm vụ.
- Kết quả quiz hoặc bài kiểm tra.
- Tiến độ học tập.
- Mục tiêu học tập.
- Khoảng thời gian tạo báo cáo.
#### Processing:
1. Người dùng lựa chọn khoảng thời gian muốn xem báo cáo.
2. Hệ thống truy xuất dữ liệu học tập tương ứng.
3. Tổng hợp thời gian học, nhiệm vụ hoàn thành và kết quả học tập.
4. Kiểm tra tính hợp lệ và mức độ đầy đủ của dữ liệu.
5. Gửi dữ liệu tổng hợp đến Gemini Flash API.
6. AI phân tích dữ liệu học tập.
7. AI tạo nhận xét về tiến độ, điểm mạnh và những nội dung cần cải thiện.
8. Hệ thống hiển thị báo cáo học tập cho người dùng.
#### Output:
- Báo cáo học tập theo ngày, tuần hoặc tháng.
- Tổng thời gian học tập.
- Tỷ lệ hoàn thành nhiệm vụ.
- Kết quả học tập theo môn.
- Nhận xét về điểm mạnh.
- Những nội dung cần cải thiện.
- Gợi ý học tập dựa trên dữ liệu.
#### Business Rules:
- Báo cáo phải được tạo dựa trên dữ liệu học tập đã ghi nhận.
- Người dùng phải chọn khoảng thời gian hợp lệ.
- AI chỉ phân tích dữ liệu được cung cấp.
- AI không được tự tạo điểm số hoặc hoạt động học tập không tồn tại.
- Nếu dữ liệu không đủ, hệ thống cần thông báo rõ rằng báo cáo chưa thể đưa ra nhận xét đầy đủ.
- Phải phân biệt dữ liệu thực tế và nhận xét do AI tạo ra.
#### Exception Handling:
- Không có dữ liệu học tập → hiển thị thông báo chưa có dữ liệu để tạo báo cáo.
- Dữ liệu không đầy đủ → hiển thị báo cáo với dữ liệu hiện có và thông báo giới hạn.
- AI không phản hồi → hiển thị dữ liệu thống kê cơ bản và thông báo phần nhận xét AI tạm thời không khả dụng.
- Lỗi truy xuất dữ liệu → hiển thị thông báo lỗi và cho phép thử lại.
AI sử dụng: Backend + Database + Gemini Flash API
### PD-05: Subject Performance Analysis – Phân tích kết quả học tập theo môn
#### Mô tả:
Cho phép học sinh theo dõi và phân tích kết quả học tập theo từng môn dựa trên điểm quiz, bài kiểm tra và kết quả luyện tập.

Hệ thống tổng hợp kết quả của từng môn để tính điểm trung bình hoặc các chỉ số liên quan. AI phân tích dữ liệu nhằm xác định môn học có kết quả tốt, môn học cần cải thiện và đưa ra nhận xét hoặc gợi ý học tập phù hợp.

#### Input:
- Danh sách môn học.
- Điểm quiz.
- Điểm bài kiểm tra.
- Kết quả luyện tập.
- Khoảng thời gian phân tích.
#### Processing:
1. Hệ thống truy xuất dữ liệu kết quả học tập.
2. Phân loại dữ liệu theo môn học.
3. Lọc dữ liệu theo khoảng thời gian được chọn.
4. Tính điểm trung bình hoặc các chỉ số kết quả học tập.
5. Tổng hợp dữ liệu theo từng môn.
6. Gửi dữ liệu tổng hợp đến Gemini Flash API.
7. AI phân tích kết quả và xác định môn học có điểm mạnh hoặc cần cải thiện.
8. AI tạo nhận xét và gợi ý học tập dựa trên dữ liệu.
9. Hệ thống hiển thị kết quả phân tích dưới dạng bảng hoặc biểu đồ.
#### Output:
- Kết quả học tập theo từng môn.
- Điểm trung bình hoặc thống kê kết quả theo môn.
- Biểu đồ so sánh kết quả học tập.
- Nhận xét về môn học có kết quả tốt.
- Nhận xét về môn học cần cải thiện.
- Gợi ý học tập dựa trên kết quả phân tích.
#### Business Rules:
- Chỉ sử dụng điểm số và kết quả học tập hợp lệ.
- Dữ liệu phải thuộc khoảng thời gian được chọn.
- Chỉ so sánh các môn có dữ liệu học tập.
- Không đưa ra đánh giá khi dữ liệu không đủ.
- AI không được tự tạo điểm số hoặc kết quả học tập.
- Nhận xét của AI phải dựa trên dữ liệu được cung cấp.
#### Exception Handling:
- Không có điểm số → hiển thị thông báo chưa có dữ liệu để phân tích.
- Điểm số không hợp lệ → loại bỏ dữ liệu lỗi khỏi quá trình tính toán.
- AI không phản hồi → hiển thị thống kê cơ bản và thông báo AI tạm thời không khả dụng.
- Lỗi truy xuất dữ liệu → hiển thị thông báo lỗi và cho phép tải lại.
AI sử dụng: Backend + Database + Data Analytics Logic + Gemini Flash API
## 5. Acceptance Criteria – Tiêu chí nghiệm thu
ID |	Tiêu chí nghiệm thu
AC-01 | 	Học sinh có thể truy cập Progress Dashboard và xem tổng quan tiến độ học tập.
AC-02 | 	Học sinh có thể chọn ngày, tuần hoặc tháng để xem tiến độ học tập.
AC-03 | 	Hệ thống tính toán và hiển thị tỷ lệ hoàn thành tiến độ dựa trên dữ liệu hợp lệ.
AC-04 | 	Hệ thống ghi nhận và hiển thị thời gian học tập theo từng môn.
AC-05 | 	Học sinh có thể xem thời gian học theo ngày, tuần hoặc tháng.
AC-06 | 	Hệ thống hiển thị danh sách nhiệm vụ và trạng thái hoàn thành.
AC-07 | 	Hệ thống tính toán và hiển thị tỷ lệ hoàn thành nhiệm vụ.
AC-08 | 	Học sinh có thể tạo báo cáo học tập theo khoảng thời gian đã chọn.
AC-09 | 	AI tạo nhận xét báo cáo dựa trên dữ liệu học tập được cung cấp.
AC-10 | 	Hệ thống hiển thị kết quả học tập theo từng môn.
AC-11 | 	AI phân tích kết quả theo môn khi có đủ dữ liệu.
AC-12 | 	Hệ thống thông báo khi dữ liệu học tập không đủ để phân tích.
AC-13 | 	Dashboard cập nhật khi người dùng ghi nhận hoạt động học tập mới.

## 6. UI/UX Reference – Giao diện tham khảo
### Mô tả màn hình dự kiến:
- Progress Dashboard Home: Hiển thị tổng quan tiến độ học tập.
- Overall Learning Progress: Hiển thị tỷ lệ hoàn thành và biểu đồ tiến độ.
- Study Time Tracking: Hiển thị tổng thời gian học và thời gian theo từng môn.
- Task Completion: Hiển thị nhiệm vụ đã hoàn thành, đang thực hiện và chưa hoàn thành.
- Learning Report: Hiển thị báo cáo học tập theo ngày, tuần hoặc tháng.
- Subject Performance Analysis: Hiển thị kết quả học tập theo từng môn và nhận xét AI.
--> Giao diện nên ưu tiên sự đơn giản, trực quan và dễ sử dụng trên điện thoại. Các thông tin quan trọng như tiến độ, thời gian học và nhiệm vụ hoàn thành cần được đặt ở vị trí dễ nhìn.
## 7. Priority – Mức độ ưu tiên
### Mức độ ưu tiên: High
#### Lý do:
Progress Dashboard là một tính năng cốt lõi của Study Pulse, giúp học sinh theo dõi hiệu quả học tập, đánh giá mức độ hoàn thành mục tiêu và nhận biết những môn học cần cải thiện.

Tính năng này cũng cung cấp dữ liệu quan trọng cho việc tạo báo cáo học tập và phân tích kết quả bằng AI, đồng thời hỗ trợ phụ huynh nắm bắt tình hình học tập của con.