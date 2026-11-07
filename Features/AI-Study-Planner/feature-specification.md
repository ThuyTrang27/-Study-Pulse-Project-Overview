# TÀI LIỆU YÊU CẦU NGHIỆP VỤ

# KẾ HOẠCH HỌC TẬP AI – KẾ HOẠCH HỌC TẬP CÁ NHÂN HÓA BẰNG AI

## 1. Tổng quan

### 1.1. Mục đích

Kế hoạch học tập AI là tính năng cho phép học sinh xây dựng kế hoạch học tập cá nhân hóa dựa trên thông tin học tập, mục tiêu, thời gian ôn tập, sở thích học tập và tài liệu do người dùng cung cấp.

Hệ thống ứng dụng AI để phân tích tài liệu học tập, trích xuất kiến thức, phân loại các chủ đề và xây dựng danh sách nội dung cần học. Sau khi học sinh kiểm tra và xác nhận danh sách chủ đề, AI tiếp tục sử dụng các thông tin đầu vào để tạo kế hoạch học tập phù hợp với năng lực và thời gian của từng học sinh.

### 1.2. Vấn đề cần giải quyết

- Học sinh có nhiều tài liệu học tập ở các định dạng khác nhau nhưng chưa có công cụ tổng hợp và tổ chức kiến thức hiệu quả.
- Học sinh gặp khó khăn trong việc xác định những kiến thức cần ưu tiên ôn tập.
- Học sinh chưa biết cách phân bổ thời gian học tập hợp lý trước các kỳ thi.
- Mỗi học sinh có trình độ, mục tiêu và phương pháp học tập khác nhau, nhưng thường phải sử dụng một kế hoạch học tập chung.
- Học sinh mất nhiều thời gian đọc, phân loại và tổng hợp nội dung từ các tài liệu.
- Học sinh khó xác định những kiến thức còn yếu và cần tập trung cải thiện.

### 1.3. Đối tượng sử dụng

| Đối tượng | Discribe |
| --------- | ----- |
| Học sinh  | Học sinh THCS và THPT sử dụng hệ thống để thiết lập và quản lý kế hoạch học tập cá nhân. |
| Phụ huynh | Phụ huynh có thể theo dõi kế hoạch và tiến độ học tập nếu hệ thống hỗ trợ vai trò này. |

### 1.4. Giá trị mang lại

**Đối với học sinh:**

- Tiết kiệm thời gian tổng hợp và phân loại tài liệu học tập.
- Có kế hoạch học tập phù hợp với mục tiêu cá nhân.
- Xác định được những chủ đề cần ưu tiên.
- Chủ động kiểm soát thời gian ôn tập trước kỳ thi.
- Tiếp cận nội dung học tập phù hợp với sở thích và mức độ hiểu biết.

---

# 2. Các chức năng nhỏ

Kế hoạch học tập AI được phân rã thành 5 nhóm nghiệp vụ chính và 14 chức năng nhỏ.

## 2.1. Thiết lập thông tin học tập

| ID | Chức năng nhỏ | Discribe nghiệp vụ |
| --- | --- | --- |
| ASP-01 | Thu thập thông tin học tập | Thu thập thông tin học tập cá nhân của người dùng. |
| ASP-02 | Lựa chọn ngôn ngữ Output | Lựa chọn ngôn ngữ sử dụng khi AI tạo nội dung học tập. |
| ASP-03 | Thiết lập mục tiêu học tập | Thiết lập mục tiêu học tập và kết quả mong muốn. |
| ASP-04 | Thiết lập ngày thi và lịch học | Thiết lập ngày thi và thời gian có thể dành cho việc học. |
| ASP-05 | Lựa chọn phương thức học tập | Lựa chọn phương thức học tập yêu thích. |
| ASP-06 | Đánh giá mức độ hiểu biết | Đánh giá mức độ hiểu biết hiện tại đối với môn học hoặc tài liệu ôn thi. |

## 2.2. Quản lý tài liệu học tập

| ID | Chức năng nhỏ | Discribe nghiệp vụ |
| --- | --- | --- |
| ASP-07 | Tải lên tài liệu học tập | Cho phép người dùng tải một hoặc nhiều tài liệu học tập lên hệ thống. |
| ASP-08 | Kiểm tra tệp | Kiểm tra định dạng, dung lượng, tính toàn vẹn và khả năng đọc của tài liệu. |

## 2.3. Processing tài liệu bằng AI

| ID | Chức năng nhỏ | Discribe nghiệp vụ |
| --- | --- | --- |
| ASP-09 | Phân tích tài liệu bằng AI | AI đọc, trích xuất, phân tích và đánh giá khả năng sử dụng của tài liệu. |

## 2.4. Quản lý chủ đề kiến thức

| ID | Chức năng nhỏ | Discribe nghiệp vụ |
| --- | --- | --- |
| ASP-10 | Phân loại và tổ chức chủ đề | Phân loại, nhóm và sắp xếp các chủ đề kiến thức theo cấu trúc logic. |
| ASP-11 | Tạo và xem xét danh sách chủ đề | Tạo danh sách chủ đề, cho phép người dùng xem xét, chỉnh sửa và xác nhận. |
| ASP-12 | Lựa chọn trọng tâm học tập | Cho phép người dùng lựa chọn những chủ đề cần ưu tiên tập trung. |

## 2.5. Tạo kế hoạch học tập bằng AI

| ID | Chức năng nhỏ | Discribe nghiệp vụ |
| --- | --- | --- |
| ASP-13 | Tạo lịch học bằng AI | AI phân bổ các chủ đề vào lịch học dựa trên mục tiêu, ngày thi và thời gian rảnh. |
| ASP-14 | Xem xét và lưu kế hoạch học tập | Cho phép người dùng xem xét, điều chỉnh, xác nhận và lưu kế hoạch học tập. |

# 3. Luồng hoạt động

## 3.1. Luồng tổng quát

Quy trình bắt đầu khi học sinh truy cập Kế hoạch học tập AI và cung cấp các thông tin cần thiết.
Hệ thống tiếp nhận dữ liệu, Processing tài liệu bằng AI, tổ chức danh sách chủ đề và cuối cùng tạo kế hoạch học tập cá nhân hóa.

### Luồng chính

1. Học sinh truy cập Kế hoạch học tập AI.
2. Hệ thống hiển thị quy trình thiết lập học tập.
3. Học sinh cung cấp thông tin học tập cá nhân.
4. Học sinh chọn ngôn ngữ Output.
5. Học sinh thiết lập mục tiêu học tập và điểm số mục tiêu.
6. Học sinh cấu hình ngày thi và thời gian có thể học.
7. Học sinh chọn phương thức học tập ưa thích.
8. Học sinh tự đánh giá mức độ hiểu biết hiện tại.
9. Học sinh tải lên tài liệu học tập.
10. Hệ thống kiểm tra các tệp đã tải lên.
11. AI đọc và phân tích các tài liệu hợp lệ.
12. AI trích xuất văn bản và nhận diện cấu trúc kiến thức.
13. AI đánh giá khả năng sử dụng của tài liệu.
14. AI nhận diện, phân loại và tổ chức các chủ đề học tập.
15. Hệ thống tạo danh sách chủ đề có cấu trúc.
16. Học sinh xem xét và chỉnh sửa danh sách chủ đề đã tạo.
17. Học sinh chọn những chủ đề cần dành nhiều sự chú ý nhất.
18. Học sinh xác nhận danh sách chủ đề.
19. AI phân tích toàn bộ thông tin học tập đã được xác nhận.
20. AI tạo lịch học cá nhân hóa.
21. Học sinh xem xét kế hoạch học tập đã được tạo.
22. Học sinh điều chỉnh kế hoạch nếu cần.
23. Học sinh xác nhận kế hoạch học tập.
24. Hệ thống lưu kế hoạch học tập.
25. Hệ thống cung cấp kế hoạch đã lưu cho các hoạt động học tập tiếp theo.

## 3.2. Sơ đồ luồng người dùng

```mermaid
flowchart TD
    A([Bắt đầu Kế hoạch học tập AI]) --> B[Thiết lập thông tin học tập]

    B --> B1[Chọn ngôn ngữ Output]
    B1 --> B2[Thiết lập mục tiêu học tập]
    B2 --> B3[Thiết lập ngày thi và lịch học]
    B3 --> B4[Chọn phương thức học tập]
    B4 --> B5[Đánh giá mức độ hiểu biết hiện tại]

    B5 --> C[Tải lên tài liệu học tập]
    C --> D{Kiểm tra tệp}

    D -->|Không hợp lệ| E[Thông báo lỗi cho người dùng]
    E --> C

    D -->|Hợp lệ| F[AI phân tích tài liệu]
    F --> G[Trích xuất văn bản và cấu trúc tài liệu]
    G --> H[Đánh giá khả năng sử dụng của tài liệu]

    H --> I{Tài liệu có sử dụng được không?}
    I -->|Không| J[Thông báo người dùng và yêu cầu tài liệu khác]
    J --> C

    I -->|Có| K[Phân loại và tổ chức chủ đề]
    K --> L[Tạo danh sách chủ đề]
    L --> M[Xem xét và chỉnh sửa chủ đề]
    M --> N[Chọn mức ưu tiên học tập]
    N --> O[Xác nhận danh sách chủ đề]

    O --> P[AI tạo lịch học]
    P --> Q[Xem xét kế hoạch học tập]
    Q --> R{Hài lòng với kế hoạch?}

    R -->|Không| S[Điều chỉnh kế hoạch học tập]
    S --> Q

    R -->|Có| T[Xác nhận và lưu kế hoạch học tập]
    T --> U([Kết thúc])
```

## 3.3. Luồng thay thế

- Học sinh bỏ qua thông tin tùy chọn: Hệ thống tiếp tục sử dụng các thông tin hiện có nếu đáp ứng yêu cầu tối thiểu.
- Học sinh tải lên nhiều tệp: Hệ thống kiểm tra và Processing từng tệp một cách độc lập.
- Một số tệp không hợp lệ: Hệ thống chỉ ra các tệp không hợp lệ và cho phép học sinh thay thế hoặc xóa.
- AI không thể trích xuất nội dung: Hệ thống báo lỗi và cho phép tải lại hoặc thử lại.
- Học sinh chỉnh sửa danh sách chủ đề: AI sử dụng danh sách đã cập nhật cho các bước tạo kế hoạch học tập tiếp theo.
- Học sinh thay đổi mức ưu tiên học tập: AI cập nhật việc phân bổ thời gian học tương ứng.
- Học sinh không hài lòng với kế hoạch đã tạo: Học sinh có thể chỉnh sửa kế hoạch hoặc yêu cầu tạo lại.
- Học sinh thoát trước khi lưu: Hệ thống nên lưu giữ tiến trình nếu được hỗ trợ.

---

# 4. Discribe chức năng

## ASP-01. Thu thập thông tin học tập

**Discribe:**

Cho phép học sinh cung cấp các thông tin cá nhân và thông tin học tập cơ bản để hệ thống xác định đối tượng, nhu cầu và bối cảnh học tập của người dùng.

**Input:**

- Cấp học, trình độ học vấn (THCS/THPT).
- Khối lớp.
- Thông tin môn học.
- Ngôn ngữ mẹ đẻ
- Khó khăn khi học


**Processing:**

1. Hệ thống truy xuất hồ sơ hiện có của người dùng.
2. Hệ thống hiển thị các trường thông tin học tập bắt buộc.
3. Học sinh cung cấp hoặc cập nhật thông tin.
4. Hệ thống kiểm tra tính hợp lệ của thông tin.
5. Hệ thống liên kết thông tin với tài khoản của người dùng.

**Output:**

- Hồ sơ học tập đã cập nhật.
- Cấp học.
- Khối lớp.
- Trạng thái thông tin học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Xác thực người dùng: Chỉ người dùng đã đăng nhập mới được thiết lập thông tin học tập. |
| BR02 | Cấp học: Cấp học phải thuộc phạm vi hệ thống hỗ trợ. |
| BR03 | Kiểm tra khối lớp: Khối lớp phải phù hợp với cấp học. |
| BR04 | Liên kết hồ sơ: Thông tin phải được liên kết với đúng tài khoản người dùng. |
| BR05 | Cập nhật hồ sơ: Người dùng có thể cập nhật thông tin học tập khi cần. |

**Processing ngoại lệ:**

- Thiếu thông tin bắt buộc: Hệ thống yêu cầu người dùng cung cấp thông tin còn thiếu.
- Cấp học không hợp lệ: Hệ thống hiển thị thông báo kiểm tra.
- Khối lớp không hợp lệ: Hệ thống yêu cầu người dùng chọn khối lớp hợp lệ.
- Lỗi truy xuất hồ sơ: Hệ thống hiển thị lỗi và cho phép thử lại.
- Lỗi lưu dữ liệu: Hệ thống giữ lại thông tin đã nhập nếu có thể và cho phép thử lại.

---

## ASP-02. Lựa chọn ngôn ngữ Output

**Discribe:**

Cho phép học sinh lựa chọn ngôn ngữ mà AI sẽ sử dụng để tạo nội dung học tập, giải thích kiến thức và các thông tin liên quan đến kế hoạch học tập.

**Input:**

- Ngôn ngữ Output được chọn.
- Mã người dùng.

**Processing:**

1. Hệ thống hiển thị các ngôn ngữ Output được hỗ trợ.
2. Học sinh chọn ngôn ngữ mong muốn.
3. Hệ thống kiểm tra tính hợp lệ của ngôn ngữ đã chọn.
4. Hệ thống lưu lựa chọn ngôn ngữ.
5. AI nhận thiết lập ngôn ngữ cho các lần tạo nội dung tiếp theo.

**Output:**

- Ngôn ngữ Output đã chọn.
- Tùy chọn ngôn ngữ đã cập nhật.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Chọn ngôn ngữ: Người dùng phải chọn một ngôn ngữ trong danh sách hệ thống hỗ trợ nếu trường này được cấu hình bắt buộc. |
| BR02 | Ngôn ngữ được hỗ trợ: Chỉ cho phép sử dụng ngôn ngữ được hệ thống hỗ trợ. |
| BR03 | Nhất quán ngôn ngữ: AI phải sử dụng ngôn ngữ đã chọn khi tạo nội dung. |
| BR04 | Cập nhật ngôn ngữ: Người dùng có thể thay đổi ngôn ngữ Output. |
| BR05 | Lưu trữ ngôn ngữ: Lựa chọn phải được lưu và sử dụng trong các bước tiếp theo. |

**Processing ngoại lệ:**

- Ngôn ngữ không được hỗ trợ: Hệ thống từ chối lựa chọn.
- Chưa chọn ngôn ngữ: Hệ thống yêu cầu người dùng chọn ngôn ngữ nếu bắt buộc.
- Lỗi lưu dữ liệu: Hệ thống thông báo cho người dùng và cho phép thử lại.

---

## ASP-03. Thiết lập mục tiêu học tập

**Discribe:**

Cho phép học sinh thiết lập mục tiêu học tập để AI hiểu được kết quả mà người dùng mong muốn đạt được và sử dụng thông tin đó để xây dựng kế hoạch phù hợp.

**Input:**

- Mục tiêu học tập.
- Điểm số mục tiêu (nếu có).
- Môn học.
- Discribe mục tiêu (nếu có).

**Processing:**

1. Hệ thống hiển thị các tùy chọn mục tiêu học tập có sẵn.
2. Học sinh chọn hoặc nhập mục tiêu học tập.
3. Học sinh cung cấp điểm số mục tiêu nếu áp dụng.
4. Hệ thống kiểm tra tính hợp lệ của thông tin.
5. Hệ thống lưu mục tiêu học tập.
6. AI nhận mục tiêu làm dữ liệu đầu vào cho việc tạo kế hoạch học tập.

**Output:**

- Mục tiêu học tập.
- Điểm số mục tiêu.
- Trạng thái mục tiêu học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Chọn mục tiêu: Người dùng phải xác định mục tiêu học tập theo hình thức mà hệ thống hỗ trợ. |
| BR02 | Nhiều mục tiêu: Hệ thống cho phép lựa chọn nhiều mục tiêu nếu nghiệp vụ cho phép. |
| BR03 | Khoảng điểm mục tiêu: Điểm số mục tiêu phải nằm trong thang điểm được hệ thống cấu hình. |
| BR04 | Liên kết mục tiêu: Mục tiêu phải được liên kết với môn học hoặc kế hoạch tương ứng. |
| BR05 | Cập nhật mục tiêu: Người dùng có thể cập nhật mục tiêu trước khi xác nhận kế hoạch học tập. |
| BR06 | Tích hợp mục tiêu vào AI: AI phải sử dụng mục tiêu làm dữ liệu tham khảo khi tạo kế hoạch. |

**Processing ngoại lệ:**

- Thiếu mục tiêu: Hệ thống yêu cầu người dùng cung cấp mục tiêu nếu bắt buộc.
- Điểm số mục tiêu không hợp lệ: Hệ thống hiển thị thông báo kiểm tra.
- Mục tiêu mâu thuẫn: Hệ thống yêu cầu làm rõ nếu các mục tiêu không thể đồng thời đạt được.
- Lỗi lưu dữ liệu: Hệ thống thông báo cho người dùng và cho phép thử lại.

---

## ASP-04. Thiết lập ngày thi và lịch học

**Discribe:**

Cho phép học sinh thiết lập ngày thi và thời gian có thể dành cho việc học để AI xác định khoảng thời gian ôn tập và phân bổ nội dung học tập hợp lý.

**Input:**

- Ngày thi.
- Các ngày có thể học.
- Thời gian có thể học.
- Thời gian học ưa thích.
- Thời lượng mỗi buổi học (nếu được hỗ trợ).
- Múi giờ.

**Processing:**

1. Hệ thống hiển thị phần cấu hình ngày thi và lịch học.
2. Học sinh chọn ngày thi.
3. Học sinh cấu hình các ngày có thể học.
4. Học sinh nhập số giờ hoặc khung giờ có thể học.
5. Hệ thống kiểm tra tính hợp lệ của lịch học.
6. Hệ thống tính toán khoảng thời gian ôn tập khả dụng.
7. Hệ thống lưu thông tin lịch học.

**Output:**

- Ngày thi.
- Các ngày có thể học.
- Thời gian có thể học.
- Tổng thời gian ôn tập khả dụng.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Kiểm tra ngày thi: Ngày thi phải phù hợp với quy định thời gian của hệ thống. |
| BR02 | Thời gian khả dụng: Người dùng cần cung cấp thời gian có thể học nếu đây là thông tin bắt buộc. |
| BR03 | Kiểm tra thời gian: Thời gian bắt đầu phải trước thời gian kết thúc. |
| BR04 | Nhất quán lịch học: Lịch học không được chứa các khoảng thời gian mâu thuẫn nếu hệ thống không hỗ trợ lịch chồng lấn. |
| BR05 | Lịch học không được chứa các khoảng thời gian mâu thuẫn nếu hệ thống không hỗ trợ lịch chồng lấn. |
| BR06 | Cập nhật lịch học: Người dùng có thể cập nhật lịch học và ngày thi. |
| BR07 | Tích hợp lịch học vào AI: AI phải sử dụng thời gian khả dụng khi phân bổ nội dung học tập. |

**Processing ngoại lệ:**

- Ngày thi không hợp lệ: Hệ thống yêu cầu nhập ngày hợp lệ.
- Ngày thi đã qua: Hệ thống hiển thị cảnh báo hoặc ngăn xác nhận tùy theo chính sách được cấu hình.
- Không có thời gian học khả dụng: Hệ thống yêu cầu người dùng cấu hình thời gian rảnh.
- Khung giờ xung đột: Hệ thống chỉ ra và yêu cầu chỉnh sửa.
- Không đủ thời gian chuẩn bị: Hệ thống thông báo cho người dùng rằng khoảng thời gian khả dụng có thể không đủ cho tất cả các chủ đề đã chọn.

---

## ASP-05. Lựa chọn phương thức học tập

**Discribe:**

Cho phép học sinh lựa chọn các phương thức học tập yêu thích để AI có thể đề xuất và cá nhân hóa hình thức nội dung học tập phù hợp.

**Input:**

- Phương thức học tập:
  - Học qua đọc.
  - Học qua nghe (podcast).
  - Học qua xem.
  - Học qua thực hành.

**Processing:**

1. Hệ thống hiển thị các phương thức học tập được hỗ trợ.
2. Học sinh chọn một hoặc nhiều phương thức.
3. Hệ thống ghi nhận các lựa chọn.
4. Hệ thống kiểm tra tính hợp lệ của lựa chọn.
5. Hệ thống lưu các phương thức học tập.
6. AI nhận các phương thức này để đề xuất nội dung cá nhân hóa.

**Output:**

- Các phương thức học tập đã chọn.
- Trạng thái phương thức học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Hiển thị phương thức: Hệ thống hiển thị các phương thức học tập được hỗ trợ. |
| BR02 | Chọn nhiều phương thức: Người dùng có thể chọn nhiều phương thức học tập. |
| BR03 | Kiểm tra lựa chọn: Lựa chọn phải thuộc danh sách phương thức được hệ thống hỗ trợ. |
| BR04 | Lưu lựa chọn: Hệ thống phải lưu các phương thức học đã chọn. |
| BR05 | Cập nhật lựa chọn: Người dùng có thể thay đổi lựa chọn. |
| BR06 | Cá nhân hóa bằng AI: AI sử dụng sở thích học tập để đề xuất hình thức nội dung phù hợp. |

**Processing ngoại lệ:**

- Chưa chọn phương thức nào: Hệ thống yêu cầu chọn nếu bắt buộc.
- Phương thức không được hỗ trợ: Hệ thống từ chối lựa chọn.
- Lỗi lưu dữ liệu: Hệ thống thông báo cho người dùng và cho phép thử lại.

---

## ASP-06. Đánh giá mức độ hiểu biết

**Discribe:**

Cho phép học sinh tự đánh giá mức độ hiểu biết hiện tại đối với tài liệu ôn thi hoặc các chủ đề kiến thức thuộc môn học đã chọn.

Hệ thống sử dụng dữ liệu này để AI xác định mức độ ưu tiên và điều chỉnh nội dung học tập phù hợp với khả năng hiện tại của học sinh.

**Input:**

- Môn học.
- Chủ đề hoặc tài liệu được chọn.
- Mức độ quen thuộc với kiến thức.

**Các mức độ được hỗ trợ:**

| Level | Discribe |
| --- | ----- |
| 1 | Nội dung này hoàn toàn mới với tôi. |
| 2 | Tôi đã từng nghe qua. |
| 3 | Tôi nắm được kiến thức cơ bản. |
| 4 | Tôi hiểu rõ nội dung này. |
| 5 | Tôi tự tin với nội dung này. |

**Processing:**

1. Hệ thống hiển thị câu hỏi về mức độ quen thuộc với kiến thức.
2. Hệ thống hiển thị năm mức độ hiểu biết.
3. Học sinh chọn mức độ Discribe đúng nhất hiểu biết hiện tại của mình.
4. Hệ thống ghi nhận mức độ đã chọn.
5. Hệ thống liên kết mức độ với môn học, tài liệu hoặc chủ đề tương ứng.
6. AI nhận thông tin đánh giá để cá nhân hóa.

**Output:**

- Mức độ quen thuộc với kiến thức.
- Đánh giá kiến thức theo từng chủ đề (nếu đánh giá theo từng chủ đề).
- Trạng thái đánh giá học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Các mức lựa chọn: Hệ thống phải cung cấp năm mức độ hiểu biết. |
| BR02 | Chọn một mức: Người dùng chọn một mức độ cho mỗi đối tượng được đánh giá tại một thời điểm. |
| BR03 | Ánh xạ mức độ: Mỗi lựa chọn tương ứng với một giá trị từ 1 đến 5. |
| BR04 | Liên kết đánh giá: Mức độ đánh giá phải gắn với môn học hoặc chủ đề tương ứng. |
| BR05 | Cập nhật đánh giá: Người dùng có thể cập nhật mức độ hiểu biết. |
| BR06 | Tích hợp vào AI: AI sử dụng mức độ hiểu biết làm dữ liệu tham khảo để điều chỉnh kế hoạch. |

**Processing ngoại lệ:**

- Chưa chọn mức độ: Hệ thống yêu cầu chọn nếu bắt buộc.
- Không thể lưu dữ liệu đánh giá: Hệ thống thông báo cho người dùng và cho phép thử lại.
- Chủ đề không khả dụng: Hệ thống yêu cầu người dùng chọn chủ đề hợp lệ.

---

## ASP-07. Tải lên tài liệu học tập

**Discribe:**

Cho phép học sinh tải lên một hoặc nhiều tài liệu học tập để hệ thống sử dụng làm nguồn dữ liệu đầu vào cho quá trình AI phân tích và xây dựng danh sách chủ đề kiến thức.

**Input:**

- Các tệp đã tải lên.
- Tên tệp.
- Loại tệp.
- Dung lượng tệp.
- Môn học đã chọn.

**Các loại tệp được hỗ trợ:**

- PDF.
- DOC/DOCX.
- PPT/PPTX.
- JPG/JPEG.
- PNG.

**Processing:**

1. Hệ thống hiển thị giao diện tải lên tài liệu.
2. Học sinh chọn một hoặc nhiều tệp.
3. Hệ thống tiếp nhận các tệp đã tải lên.
4. Hệ thống kiểm tra định dạng và dung lượng tệp.
5. Hệ thống thực hiện kiểm tra tệp ban đầu.
6. Hệ thống tải các tệp hợp lệ lên kho lưu trữ.
7. Hệ thống liên kết tài liệu đã tải lên với tài khoản của người dùng.
8. Hệ thống cập nhật trạng thái tải lên.

**Output:**

- Danh sách tài liệu đã tải lên.
- Siêu dữ liệu của tệp.
- Trạng thái tải lên.
- Mã tài liệu.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Định dạng được hỗ trợ: Chỉ chấp nhận định dạng tài liệu được hệ thống hỗ trợ. |
| BR02 | Giới hạn dung lượng: Dung lượng mỗi tệp không được vượt quá giới hạn cấu hình. |
| BR03 | Tải lên nhiều tệp: Hệ thống hỗ trợ tải nhiều tài liệu nếu tính năng được bật. |
| BR04 | Liên kết tệp: Tài liệu phải được liên kết với tài khoản người dùng. |
| BR05 | Trạng thái tải lên: Mỗi tài liệu phải có trạng thái tải lên rõ ràng. |
| BR06 | Quản lý tài liệu: Người dùng có thể xem hoặc xóa tài liệu đã tải lên trước khi Processing. |
| BR07 | Hoàn tất tải lên: Chỉ những tài liệu tải lên thành công mới được chuyển sang bước Processing tiếp theo. |

**Processing ngoại lệ:**

- Định dạng tệp không được hỗ trợ: Hệ thống từ chối tệp và hiển thị các định dạng được hỗ trợ.
- Tệp vượt quá giới hạn dung lượng: Hệ thống thông báo cho người dùng và yêu cầu chọn tệp khác.
- Gián đoạn khi tải lên: Hệ thống đánh dấu việc tải lên là thất bại và cho phép thử lại.
- Lỗi kho lưu trữ: Hệ thống thông báo cho người dùng.
- Tệp trùng lặp: Hệ thống cảnh báo người dùng và áp dụng chính sách Processing trùng lặp đã cấu hình.
- Chưa tải tệp nào: Hệ thống yêu cầu ít nhất một tài liệu nếu việc tải lên là bắt buộc.

---

## ASP-08. Kiểm tra tệp

**Discribe:**

Kiểm tra định dạng, dung lượng, tính toàn vẹn và khả năng đọc của tài liệu đã tải lên trước khi chuyển tài liệu sang quy trình Processing bằng AI.

**Input:**

- Danh sách tài liệu đã tải lên.
- Định dạng tệp.
- Dung lượng tệp.
- Nội dung tệp.
- Siêu dữ liệu của tệp.

**Processing:**

**A. Kiểm tra định dạng**

1. Xác định phần mở rộng và loại tệp thực tế.
2. So sánh loại tệp với các định dạng được hỗ trợ.
3. Từ chối các định dạng không được hỗ trợ.

**B. Kiểm tra dung lượng**

1. Lấy dung lượng tệp.
2. So sánh dung lượng tệp với giới hạn hệ thống đã cấu hình.
3. Từ chối các tệp quá dung lượng.

**C. Kiểm tra tính toàn vẹn của tệp**

1. Kiểm tra tệp có bị hỏng hoặc lỗi hay không.
2. Kiểm tra tệp có thể truy cập được hay không.
3. Xác định các tệp không đọc được hoặc không hợp lệ.

**D. Kiểm tra nội dung**

1. Kiểm tra tài liệu có chứa nội dung đọc được hay không.
2. Phát hiện tài liệu rỗng hoặc trống.
3. Xác định các tệp có nội dung không đủ.
4. Phát hiện các tệp có khả năng trùng lặp.

**Output:**

- Kết quả kiểm tra tệp.
- Danh sách tài liệu hợp lệ.
- Danh sách tài liệu không hợp lệ.
- Danh sách cảnh báo tài liệu.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Kiểm tra định dạng: Tệp phải thuộc định dạng được hỗ trợ. |
| BR02 | Kiểm tra dung lượng: Tệp phải đáp ứng giới hạn dung lượng. |
| BR03 | Kiểm tra tính toàn vẹn: Tệp phải có khả năng truy cập và không bị hỏng. |
| BR04 | Phát hiện nội dung rỗng: Hệ thống phải phát hiện tài liệu không chứa nội dung có thể đọc được. |
| BR05 | Phát hiện trùng lặp: Hệ thống có thể phát hiện các tài liệu trùng lặp. |
| BR06 | Kiểm tra độc lập: Hệ thống kiểm tra từng tệp độc lập khi người dùng tải nhiều tệp. |
| BR07 | Phân loại kết quả kiểm tra: Tài liệu được phân loại thành Hợp lệ, Không hợp lệ hoặc Cần xem xét. |
| BR08 | Hạn chế Processing: Chỉ tài liệu đáp ứng điều kiện Processing mới được chuyển sang bước Processing tài liệu bằng AI. |
| BR09 | Thông báo người dùng: Hệ thống phải thông báo kết quả kiểm tra cho người dùng. |

**Processing ngoại lệ:**

- Tệp bị hỏng: Hệ thống đánh dấu tệp là Không hợp lệ.
- Tài liệu rỗng: Hệ thống thông báo cho người dùng rằng không tìm thấy nội dung đọc được.
- Tài liệu được bảo vệ bằng mật khẩu: Hệ thống yêu cầu phiên bản có thể truy cập hoặc mật khẩu nếu được hỗ trợ.
- Tệp chỉ đọc được một phần: Hệ thống đánh dấu tệp là Cần xem xét.
- Tài liệu trùng lặp: Hệ thống cảnh báo người dùng và cho phép họ giữ hoặc xóa bản trùng lặp.
- Lỗi dịch vụ kiểm tra: Hệ thống báo lỗi và cho phép Processing lại.

---

## F09. Phân tích tài liệu bằng AI

**Discribe:**

Sử dụng AI để đọc, trích xuất và phân tích nội dung từ các tài liệu hợp lệ do học sinh tải lên. Hệ thống chuyển đổi nội dung tài liệu thành dữ liệu có cấu trúc để phục vụ quá trình nhận diện và tổ chức chủ đề kiến thức.

**Input:**

- Danh sách tài liệu hợp lệ.
- Nội dung tệp.
- Siêu dữ liệu của tệp.
- Môn học đã chọn.
- Ngôn ngữ Output.

**Processing:**

**A. Đọc tài liệu**

1. AI nhận danh sách tài liệu đã được kiểm tra.
2. AI xác định định dạng tài liệu.
3. AI đọc các tài liệu PDF, Word, PowerPoint và tài liệu dạng hình ảnh.
4. AI xác định các tài liệu không đọc được.
5. Hệ thống cập nhật trạng thái Processing tài liệu.

**B. Trích xuất văn bản và OCR**

1. Trích xuất văn bản từ các tài liệu được hỗ trợ.
2. Áp dụng OCR cho tài liệu dạng hình ảnh hoặc các trang scan.
3. Trích xuất cấu trúc tài liệu.
4. Nhận diện các tiêu đề và tiêu đề phụ.
5. Trích xuất các chương, phần và nội dung chính.
6. Trích xuất các bảng và danh sách liên quan nếu được hỗ trợ.
7. Kiểm tra mức độ đầy đủ của việc trích xuất.

**C. Phân tích nội dung**

1. Phân tích nội dung đã trích xuất.
2. Xác định chủ đề chính và kiến thức liên quan.
3. Xác định nội dung không liên quan hoặc không đủ.
4. Xác định nội dung lặp lại.
5. Đánh giá thông tin đã trích xuất có phù hợp cho bước phân loại chủ đề tiếp theo hay không.

**D. Xem xét kết quả trích xuất**

1. Lưu nội dung đã trích xuất.
2. Hiển thị kết quả trích xuất nếu hỗ trợ người dùng xem xét.
3. Xác định các lỗi trích xuất.
4. Cho phép Processing lại các tài liệu bị lỗi nếu được hỗ trợ.

**Output:**

- Nội dung văn bản đã trích xuất.
- Nội dung tài liệu có cấu trúc.
- Các chương và phần đã nhận diện.
- Kết quả phân tích tài liệu.
- Trạng thái trích xuất.
- Trạng thái khả năng sử dụng của tài liệu.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Yêu cầu tài liệu hợp lệ: Chỉ Processing tài liệu đã vượt qua điều kiện kiểm tra đầu vào. |
| BR02 | Hỗ trợ định dạng: AI chỉ đọc các định dạng được hệ thống hỗ trợ. |
| BR03 | Processing OCR: Hệ thống sử dụng OCR đối với tài liệu chứa hình ảnh hoặc nội dung scan khi cần thiết. |
| BR04 | Nhận diện cấu trúc: AI cần nhận diện cấu trúc tài liệu nếu dữ liệu cho phép. |
| BR05 | Trích xuất nội dung: Nội dung trích xuất phải được lưu dưới dạng dữ liệu có thể Processing tiếp. |
| BR06 | Mức độ liên quan đến môn học: AI cần đánh giá mức độ liên quan của nội dung với môn học đã chọn. |
| BR07 | Mức độ đầy đủ của trích xuất: Hệ thống phải xác định trường hợp trích xuất thất bại hoặc thiếu nội dung đáng kể. |
| BR08 | Trạng thái tài liệu: Tài liệu phải có trạng thái Processing tương ứng. |
| BR09 | Thông báo lỗi: Người dùng phải được thông báo khi tài liệu không thể đọc hoặc phân tích. |
| BR10 | Truy vết dữ liệu: Nội dung trích xuất cần duy trì liên kết với tài liệu nguồn. |

**Processing ngoại lệ:**

- Định dạng tài liệu không được hỗ trợ: Hệ thống dừng Processing và báo lỗi.
- Lỗi OCR: Hệ thống đánh dấu việc trích xuất là thất bại hoặc chưa đầy đủ.
- Tài liệu không đọc được: Hệ thống thông báo cho người dùng.
- Kết quả trích xuất rỗng: Hệ thống xác định tài liệu không có nội dung trích xuất sử dụng được.
- Trích xuất một phần: Hệ thống đánh dấu kết quả là chưa đầy đủ và chỉ ra tài liệu bị ảnh hưởng.
- Lỗi Processing của AI: Hệ thống cho phép thử lại việc phân tích.
- Nội dung không liên quan: Hệ thống cảnh báo người dùng rằng tài liệu có thể không phù hợp với môn học đã chọn.
- Dịch vụ AI không khả dụng: Hệ thống thông báo cho người dùng và giữ lại các tài liệu đã tải lên.

---

## F10. Phân loại và tổ chức chủ đề

**Discribe:**

Sử dụng AI để phân loại và tổ chức các kiến thức được trích xuất thành những chủ đề có cấu trúc logic, dựa trên môn học, chương, nội dung và mối quan hệ giữa các kiến thức.

**Input:**

- Nội dung văn bản đã trích xuất.
- Nội dung tài liệu có cấu trúc.
- Các chương và phần đã nhận diện.
- Môn học đã chọn.
- Ngôn ngữ Output.

**Processing:**

1. AI nhận nội dung đã trích xuất.
2. AI xác định các chủ đề kiến thức.
3. AI xác định chủ đề chính và chủ đề con.
4. AI xác định mỗi chủ đề thuộc chương nào.
5. AI nhóm các kiến thức có liên quan.
6. AI phân biệt các chủ đề khác nhau.
7. AI xác định mối quan hệ giữa các chủ đề.
8. AI xác định kiến thức tiên quyết khi áp dụng.
9. AI xác định trình tự học hợp lý.
10. AI phát hiện các chủ đề trùng lặp hoặc chồng chéo.
11. AI tổ chức các chủ đề thành cấu trúc phân cấp.

**Output:**

- Danh sách chủ đề đã phân loại.
- Các chủ đề chính.
- Các chủ đề con.
- Cấu trúc chủ đề theo chương.
- Mối quan hệ giữa các chủ đề.
- Quan hệ tiên quyết.
- Trình tự học đề xuất.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Yêu cầu nguồn: Chỉ phân loại nội dung đã được trích xuất thành công hoặc đủ điều kiện sử dụng. |
| BR02 | Phân loại theo môn học: Chủ đề phải được liên kết với môn học phù hợp. |
| BR03 | Phân loại theo chương: AI cần phân loại chủ đề theo chương nếu tài liệu cung cấp cấu trúc chương. |
| BR04 | Nhóm chủ đề: Các kiến thức có liên quan cần được nhóm thành những chủ đề phù hợp. |
| BR05 | Phân biệt chủ đề: Các chủ đề khác nhau phải được phân biệt rõ ràng. |
| BR06 | Xác định mối quan hệ: AI cần xác định mối quan hệ giữa các chủ đề khi có đủ dữ liệu. |
| BR07 | Xác định kiến thức tiên quyết: AI cần xác định kiến thức tiên quyết khi có mối quan hệ phụ thuộc. |
| BR08 | Processing chủ đề trùng lặp: Các chủ đề trùng lặp cần được đánh dấu hoặc hợp nhất theo quy tắc hệ thống. |
| BR09 | Cấu trúc phân cấp: Danh sách kiến thức phải hỗ trợ cấu trúc chủ đề chính và chủ đề con. |
| BR10 | Trình tự học: Thứ tự học được đề xuất dựa trên cấu trúc kiến thức và quan hệ tiên quyết. |

**Processing ngoại lệ:**

- Nội dung trích xuất không đủ: Hệ thống yêu cầu bổ sung tài liệu.
- Chủ đề không nhận diện được: Hệ thống đánh dấu nội dung để xem xét.
- Cấu trúc chương không rõ ràng: AI tổ chức chủ đề dựa trên nội dung hiện có và đánh dấu các phân loại chưa chắc chắn.
- Chủ đề trùng lặp: Hệ thống xác định các chủ đề có khả năng trùng lặp để xem xét.
- Không phát hiện quan hệ tiên quyết: Hệ thống giữ các chủ đề độc lập.
- Lỗi phân loại của AI: Hệ thống cho phép Processing lại.

---

## F11. Tạo và xem xét danh sách chủ đề

**Discribe:**

Tạo danh sách chủ đề học tập từ kết quả phân loại của AI và cho phép học sinh kiểm tra, chỉnh sửa, bổ sung hoặc xóa các chủ đề trước khi xác nhận danh sách cuối cùng.

**Input:**

- Danh sách chủ đề đã phân loại.
- Các chủ đề chính.
- Các chủ đề con.
- Thông tin chương.
- Discribe chủ đề.
- Hướng dẫn học tập (tùy chọn).

**Processing:**

**A. Tạo danh sách chủ đề**

1. Hệ thống nhận các chủ đề đã phân loại.
2. Hệ thống tạo danh sách chủ đề có cấu trúc.
3. Hệ thống nhóm chủ đề theo môn học và chương.
4. Hệ thống tạo Discribe ngắn cho từng chủ đề.
5. Hệ thống hiển thị danh sách chủ đề cho học sinh.

**B. Xem xét chủ đề**

1. Học sinh xem xét danh sách chủ đề đã tạo.
2. Học sinh xem chi tiết chủ đề.
3. Học sinh xác định các chủ đề còn thiếu hoặc không cần thiết.

**C. Chỉnh sửa chủ đề**

1. Học sinh thêm chủ đề mới.
2. Học sinh chỉnh sửa tên chủ đề.
3. Học sinh chỉnh sửa Discribe chủ đề.
4. Học sinh thêm hướng dẫn học tập.
5. Học sinh xóa các chủ đề không cần thiết.
6. Học sinh sắp xếp lại các chủ đề nếu được hỗ trợ.

**D. Xác nhận chủ đề**

1. Hệ thống kiểm tra tính hợp lệ của danh sách chủ đề đã chỉnh sửa.
2. Học sinh xác nhận danh sách chủ đề cuối cùng.
3. Hệ thống lưu các chủ đề đã xác nhận.

**Output:**

- Danh sách chủ đề đã tạo.
- Danh sách chủ đề đã cập nhật.
- Danh sách chủ đề đã xác nhận.
- Trạng thái xác nhận danh sách chủ đề.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Tạo chủ đề: Danh sách chủ đề phải được tạo từ kết quả phân loại kiến thức. |
| BR02 | Cấu trúc chủ đề: Chủ đề cần được hiển thị theo môn học và chương nếu có dữ liệu tương ứng. |
| BR03 | Discribe chủ đề: Mỗi chủ đề nên có Discribe ngắn để người dùng hiểu nội dung cần học. |
| BR04 | Thêm chủ đề: Người dùng được phép bổ sung chủ đề mới. |
| BR05 | Sửa chủ đề: Người dùng được phép chỉnh sửa tên và Discribe chủ đề. |
| BR06 | Hướng dẫn học tập: Người dùng có thể bổ sung hướng dẫn học tập cho từng chủ đề nếu chức năng được hỗ trợ. |
| BR07 | Xóa chủ đề: Người dùng được phép xóa chủ đề không cần thiết. |
| BR08 | Kiểm tra chủ đề: Hệ thống cần kiểm tra tính hợp lệ của danh sách sau khi chỉnh sửa. |
| BR09 | Xác nhận chủ đề: Chỉ danh sách đã được người dùng xác nhận mới được chuyển sang bước tạo kế hoạch học tập. |
| BR10 | Lưu chủ đề: Danh sách đã xác nhận phải được lưu để phục vụ các bước tiếp theo. |

**Processing ngoại lệ:**

- Danh sách chủ đề rỗng: Hệ thống yêu cầu bổ sung nội dung hoặc tạo chủ đề thủ công.
- Thêm chủ đề trùng lặp: Hệ thống cảnh báo người dùng về chủ đề trùng lặp.
- Thông tin chủ đề không hợp lệ: Hệ thống yêu cầu chỉnh sửa.
- Xóa chủ đề: Hệ thống yêu cầu xác nhận trước khi xóa nếu cần thiết.
- Lỗi lưu dữ liệu: Hệ thống giữ lại các chỉnh sửa mới nhất nếu có thể và cho phép thử lại.
- Danh sách chủ đề do AI tạo chưa đầy đủ: Học sinh có thể thêm các chủ đề còn thiếu theo cách thủ công.

---

## F12. Lựa chọn trọng tâm học tập

**Discribe:**

Cho phép học sinh lựa chọn các chủ đề cần tập trung nhiều nhất trong quá trình ôn tập. Hệ thống sử dụng lựa chọn này để điều chỉnh mức độ ưu tiên và phân bổ thời gian học trong kế hoạch do AI tạo ra.

**Input:**

- Danh sách chủ đề đã xác nhận.
- Các chủ đề ưu tiên đã chọn.
- Mức độ ưu tiên học tập.
- Mục tiêu học tập của học sinh.

**Processing:**

1. Hệ thống hiển thị danh sách chủ đề đã xác nhận.
2. Học sinh chọn các chủ đề cần dành nhiều sự chú ý hơn.
3. Học sinh gán mức độ ưu tiên nếu được hỗ trợ.
4. Hệ thống ghi nhận các mức ưu tiên đã chọn.
5. Hệ thống liên kết mức ưu tiên với các chủ đề tương ứng.
6. AI nhận thông tin ưu tiên.

**Output:**

- Các chủ đề ưu tiên đã chọn.
- Mức độ ưu tiên của chủ đề.
- Tùy chọn trọng tâm học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Chọn chủ đề: Người dùng chỉ được lựa chọn các chủ đề thuộc danh sách đã xác nhận. |
| BR02 | Chọn nhiều chủ đề ưu tiên: Người dùng có thể chọn nhiều chủ đề cần ưu tiên. |
| BR03 | Phân loại ưu tiên: Hệ thống có thể cung cấp các mức Cao, Trung bình và Thấp. |
| BR04 | Liên kết mức ưu tiên: Mức độ ưu tiên phải được liên kết với từng chủ đề tương ứng. |
| BR05 | Cập nhật mức ưu tiên: Người dùng có thể thay đổi mức độ ưu tiên trước khi tạo hoặc xác nhận kế hoạch. |
| BR06 | Tích hợp mức ưu tiên vào AI: AI phải sử dụng mức độ ưu tiên khi phân bổ thời gian học. |

**Processing ngoại lệ:**

- Chưa chọn chủ đề ưu tiên: Hệ thống áp dụng chính sách ưu tiên mặc định hoặc yêu cầu chọn, tùy theo cấu hình.
- Mức ưu tiên không hợp lệ: Hệ thống yêu cầu chọn lại cho hợp lệ.
- Chủ đề không còn tồn tại: Hệ thống loại bỏ hoặc yêu cầu chọn lại chủ đề không khả dụng.

---

## F13. Tạo lịch học bằng AI

**Discribe:**

Sử dụng AI để xây dựng lịch học tập cá nhân hóa bằng cách phân bổ các chủ đề đã xác nhận vào những khoảng thời gian học phù hợp, dựa trên mục tiêu, ngày thi, thời gian rảnh, mức độ hiểu biết và mức độ ưu tiên của học sinh.

Đây là bước chuyển đổi danh sách chủ đề kiến thức thành một kế hoạch học tập có thời gian và thứ tự thực hiện cụ thể.

**Input:**

- Danh sách chủ đề đã xác nhận.
- Mục tiêu học tập.
- Điểm số mục tiêu.
- Ngày thi.
- Lịch học khả dụng.
- Phương thức học tập ưa thích.
- Mức độ quen thuộc với kiến thức.
- Các chủ đề ưu tiên đã chọn.
- Quan hệ tiên quyết.
- Ngôn ngữ Output.

**Processing:**

**A. Phân tích dữ liệu học tập**

1. AI nhận toàn bộ thông tin học tập đã xác nhận.
2. AI phân tích mục tiêu học tập và điểm số mục tiêu.
3. AI tính toán khoảng thời gian ôn tập khả dụng.
4. AI phân tích số lượng chủ đề và khối lượng học tập ước tính.
5. AI đánh giá mức độ ưu tiên và mức độ hiểu biết đối với từng chủ đề.
6. AI xác định các quan hệ tiên quyết.

**B. Phân bổ thời gian học**

1. AI xác định các buổi học khả dụng.
2. AI ước tính thời gian cần thiết cho từng chủ đề.
3. AI ưu tiên các chủ đề cần dành nhiều sự chú ý hơn.
4. AI phân bổ các chủ đề vào các buổi học khả dụng.
5. AI sắp xếp các chủ đề theo mối quan hệ phụ thuộc trong học tập.
6. AI dành thời gian ôn tập hoặc thực hành khi phù hợp.
7. AI kiểm tra xung đột lịch.

**C. Tạo kế hoạch học tập**

1. AI tạo lịch học.
2. AI tổ chức các hoạt động theo ngày và buổi học.
3. AI liên kết mỗi buổi học với các chủ đề học tập tương ứng.
4. AI đề xuất phương thức học dựa trên sở thích của học sinh.
5. AI tạo mục tiêu học tập dự kiến cho từng buổi học.
6. Hệ thống hiển thị kế hoạch học tập đã tạo.

**Output:**

- Kế hoạch học tập cá nhân hóa.
- Lịch học theo ngày hoặc theo tuần.
- Phân bổ chủ đề.
- Thông tin buổi học.
- Các hoạt động học tập đề xuất.
- Thời lượng học ước tính.
- Mục tiêu học tập.
- Trạng thái tạo kế hoạch.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Đầy đủ dữ liệu Input: AI chỉ tạo kế hoạch khi có đủ các dữ liệu bắt buộc theo cấu hình hệ thống. |
| BR02 | Chủ đề đã xác nhận: AI chỉ sử dụng danh sách chủ đề đã được xác nhận. |
| BR03 | Hạn chót ngày thi: Kế hoạch phải xem xét ngày thi và khoảng thời gian ôn tập còn lại. |
| BR04 | Thời gian khả dụng: Thời gian học được phân bổ phải nằm trong khoảng thời gian người dùng đã cung cấp. |
| BR05 | Ưu tiên chủ đề: Các chủ đề có mức độ ưu tiên cao cần được xem xét phân bổ thời gian phù hợp. |
| BR06 | Mức độ hiểu biết: AI cần xem xét mức độ hiểu biết của học sinh khi ước lượng thời gian và độ khó. |
| BR07 | Thứ tự tiên quyết: Các chủ đề có quan hệ tiên quyết cần được sắp xếp theo thứ tự học phù hợp. |
| BR08 | Sở thích học tập: AI cần xem xét sở thích học tập khi đề xuất hoạt động học. |
| BR09 | Phân bổ khối lượng: AI cần phân bổ khối lượng học tập hợp lý trong khoảng thời gian khả dụng. |
| BR10 | Xung đột lịch: Các buổi học không được xung đột với lịch đã được xác định. |
| BR11 | Tính đầy đủ của kế hoạch: Kế hoạch cần bao phủ các chủ đề được xác nhận hoặc thông báo rõ những chủ đề chưa được phân bổ. |
| BR12 | Minh bạch khi tạo kế hoạch: Hệ thống cần hiển thị thông tin về lịch học và nội dung được đề xuất. |
| BR13 | Tạo lại: Người dùng có thể yêu cầu AI tạo lại kế hoạch khi điều chỉnh các dữ liệu đầu vào. |

**Processing ngoại lệ:**

- Không đủ thời gian học: AI thông báo cho học sinh rằng thời gian khả dụng có thể không đủ để bao phủ tất cả các chủ đề.
- Ngày thi quá gần: AI tạo kế hoạch rút gọn nếu khả thi và thông báo cho học sinh về hạn chế.
- Lịch học xung đột: Hệ thống xác định các khung giờ không khả dụng hoặc chồng lấn.
- Quá nhiều chủ đề học tập: AI ưu tiên các chủ đề và xác định những chủ đề không thể xếp lịch.
- Thiếu thông tin chủ đề: Hệ thống yêu cầu học sinh hoàn thiện danh sách chủ đề.
- Lỗi tạo kế hoạch của AI: Hệ thống giữ lại thông tin đầu vào và cho phép thử lại.
- Không có lịch khả thi: Hệ thống giải thích xung đột và yêu cầu học sinh điều chỉnh thời gian học khả dụng hoặc mục tiêu học tập.
- Quan hệ tiên quyết không nhất quán: AI đánh dấu các quan hệ chưa chắc chắn để xem xét thay vì ép một trình tự sai.

---

## F14. Xem xét và lưu kế hoạch học tập

**Discribe:**

Cho phép học sinh xem xét, điều chỉnh, xác nhận và lưu kế hoạch học tập do AI tạo ra. Sau khi xác nhận, kế hoạch được lưu vào hệ thống để phục vụ các hoạt động học tập tiếp theo.

**Input:**

- Kế hoạch học tập đã tạo.
- Lịch học.
- Các buổi học.
- Các hoạt động học tập.
- Các điều chỉnh của học sinh.
- Trạng thái xác nhận.

**Processing:**

**A. Xem xét kế hoạch học tập**

1. Hệ thống hiển thị kế hoạch học tập đã tạo.
2. Học sinh xem lịch học theo ngày hoặc theo tuần.
3. Học sinh xem xét các chủ đề và hoạt động học tập được phân bổ.
4. Học sinh kiểm tra thời gian học và mục tiêu học tập.

**B. Tùy chỉnh kế hoạch học tập**

1. Học sinh thay đổi ngày hoặc giờ của các buổi học.
2. Học sinh thay đổi phân bổ chủ đề.
3. Học sinh điều chỉnh thời lượng học.
4. Học sinh thêm hoặc xóa các hoạt động học tập nếu được hỗ trợ.
5. Hệ thống kiểm tra tính hợp lệ của kế hoạch đã cập nhật.

**C. Xác nhận kế hoạch học tập**

1. Học sinh xác nhận kế hoạch học tập cuối cùng.
2. Hệ thống kiểm tra tính hợp lệ của kế hoạch.
3. Hệ thống lưu kế hoạch đã xác nhận.
4. Hệ thống liên kết kế hoạch với tài khoản của người dùng.
5. Hệ thống cung cấp kế hoạch cho các hoạt động học tập tiếp theo.

**Output:**

- Kế hoạch học tập đã cập nhật.
- Kế hoạch học tập đã xác nhận.
- Mã kế hoạch học tập đã lưu.
- Trạng thái kế hoạch học tập.

**Business rule:**

| ID   | Business rule |
| ---- | ----------------- |
| BR01 | Xem kế hoạch: Người dùng phải có khả năng xem kế hoạch do AI tạo ra. |
| BR02 | Tùy chỉnh kế hoạch: Người dùng được phép điều chỉnh kế hoạch trong phạm vi hệ thống hỗ trợ. |
| BR03 | Kiểm tra lịch: Những thay đổi về thời gian phải được kiểm tra tính hợp lệ. |
| BR04 | Xác nhận kế hoạch: Kế hoạch chỉ được lưu thành kế hoạch chính thức sau khi người dùng xác nhận. |
| BR05 | Liên kết kế hoạch: Kế hoạch phải được liên kết với đúng tài khoản người dùng. |
| BR06 | Lưu kế hoạch: Kế hoạch đã xác nhận phải được lưu trữ. |
| BR07 | Trạng thái kế hoạch: Hệ thống phải quản lý trạng thái kế hoạch, ví dụ Nháp, Đã xác nhận, Đang áp dụng. |
| BR08 | Cập nhật kế hoạch: Người dùng có thể cập nhật kế hoạch sau khi lưu nếu hệ thống hỗ trợ. |
| BR09 | Tích hợp hạ nguồn: Kế hoạch đã lưu có thể được sử dụng bởi các tính năng quản lý nhiệm vụ và theo dõi tiến độ học tập. |

**Processing ngoại lệ:**

- Kế hoạch học tập rỗng: Hệ thống ngăn việc xác nhận và yêu cầu tạo lại.
- Điều chỉnh lịch không hợp lệ: Hệ thống hiển thị thông báo kiểm tra.
- Khung giờ xung đột: Hệ thống xác định các buổi học bị xung đột.
- Lỗi lưu dữ liệu: Hệ thống giữ lại kế hoạch đã tạo và cho phép thử lại.
- Xác nhận trùng lặp: Hệ thống ngăn việc vô tình tạo kế hoạch trùng lặp.
- Người dùng thoát trước khi xác nhận: Hệ thống giữ kế hoạch ở trạng thái Nháp nếu được hỗ trợ.

---

# 5. Tiêu chí nghiệm thu

Tiêu chí nghiệm thu được xây dựng để xác định tính năng Kế hoạch học tập AI hoạt động đúng với các yêu cầu nghiệp vụ.

| ID   | Cho trước (Given) | Khi (When) | Thì (Then) |
| ---- | ----------------- | ---------- | ---------- |
| AC01 | Học sinh đã đăng nhập | Học sinh truy cập Kế hoạch học tập AI | Hệ thống hiển thị quy trình thiết lập học tập. |
| AC02 | Học sinh đang cấu hình thông tin học tập | Học sinh gửi thông tin hợp lệ | Hệ thống lưu hồ sơ học tập. |
| AC03 | Học sinh chọn ngôn ngữ Output | Học sinh xác nhận lựa chọn | Hệ thống lưu tùy chọn ngôn ngữ. |
| AC04 | Học sinh nhập mục tiêu học tập | Học sinh gửi mục tiêu | Hệ thống ghi nhận mục tiêu học tập. |
| AC05 | Học sinh cấu hình ngày thi và lịch học | Học sinh gửi lịch học | Hệ thống kiểm tra và lưu lịch học. |
| AC06 | Học sinh chọn phương thức học tập | Học sinh xác nhận các lựa chọn | Hệ thống lưu các phương thức học tập đã chọn. |
| AC07 | Học sinh đánh giá mức độ hiểu biết | Học sinh chọn một mức độ | Hệ thống ghi nhận mức độ tương ứng. |
| AC08 | Học sinh tải lên một tệp được hỗ trợ | Việc tải lên hoàn tất thành công | Hệ thống lưu tệp và cập nhật trạng thái của tệp. |
| AC09 | Học sinh tải lên một tệp không được hỗ trợ | Hệ thống kiểm tra tệp | Hệ thống từ chối tệp và hiển thị lỗi. |
| AC10 | Học sinh tải lên một tệp vượt quá dung lượng | Hệ thống kiểm tra tệp | Hệ thống từ chối tệp và hiển thị giới hạn dung lượng. |
| AC11 | Học sinh tải lên một tệp bị hỏng | Hệ thống kiểm tra tính toàn vẹn | Hệ thống đánh dấu tệp là Không hợp lệ. |
| AC12 | Học sinh tải lên một tài liệu hợp lệ | AI bắt đầu Processing | Hệ thống trích xuất nội dung đọc được. |
| AC13 | Học sinh tải lên một tài liệu scan | AI Processing tài liệu | Hệ thống áp dụng OCR nếu được hỗ trợ. |
| AC14 | AI trích xuất nội dung tài liệu | Quá trình phân tích hoàn tất | Hệ thống cung cấp nội dung có cấu trúc cho bước phân loại chủ đề. |
| AC15 | Đã có nội dung được trích xuất | AI phân loại nội dung | Hệ thống tạo ra cấu trúc chủ đề có tổ chức. |
| AC16 | Đã có các chủ đề được phân loại | AI tạo danh sách chủ đề | Hệ thống hiển thị các chủ đề được nhóm theo môn học và chương nếu có thể. |
| AC17 | Học sinh xem xét danh sách chủ đề | Học sinh chỉnh sửa một chủ đề | Hệ thống cập nhật thông tin chủ đề tương ứng. |
| AC18 | Học sinh chọn mức ưu tiên học tập | Học sinh xác nhận lựa chọn | Hệ thống lưu thông tin ưu tiên. |
| AC19 | Danh sách chủ đề đã được xác nhận | AI tạo lịch học | Hệ thống tạo kế hoạch học tập cá nhân hóa dựa trên các dữ liệu đầu vào hiện có. |
| AC20 | AI đã tạo một kế hoạch học tập | Học sinh xem xét kế hoạch | Hệ thống hiển thị lịch học và các chủ đề học tập được phân bổ. |
| AC21 | Học sinh thay đổi một buổi học | Học sinh lưu điều chỉnh | Hệ thống kiểm tra và cập nhật kế hoạch. |
| AC22 | Học sinh hài lòng với kế hoạch | Học sinh xác nhận kế hoạch | Hệ thống lưu kế hoạch học tập đã xác nhận. |
| AC23 | Kế hoạch học tập đã được lưu | Học sinh truy cập khu vực quản lý học tập | Hệ thống hiển thị kế hoạch đã lưu. |
| AC24 | Quá trình Processing của AI thất bại | Không thể hoàn tất Processing | Hệ thống thông báo cho người dùng và giữ lại dữ liệu đầu vào hiện có. |
| AC25 | Thời gian học không đủ | AI không thể phân bổ tất cả các chủ đề | Hệ thống thông báo cho học sinh và chỉ ra các chủ đề chưa được phân bổ. |

---

# 6. Giao diện tham khảo

## 6.1. Thiết lập thông tin học tập

**Discribe màn hình dự kiến:**

- Giao diện thu thập thông tin học tập.
- Cho phép chọn cấp học và khối lớp.
- Cho phép chọn môn học.
- Thiết lập mục tiêu và điểm số mong muốn.
- Thiết lập ngày thi và thời gian học.
- Hiển thị tiến trình thiết lập.

**Thành phần giao diện:**

- Danh sách thả xuống / Thẻ lựa chọn.
- Trường nhập liệu.
- Bộ chọn ngày.
- Bộ chọn giờ.
- Thanh tiến trình.
- Nút Tiếp theo / Quay lại.

## 6.2. Lựa chọn phương thức học tập

**Discribe màn hình dự kiến:**

Hiển thị câu hỏi "Bạn thích học theo cách nào?" và các lựa chọn phương thức học tập.

**Thành phần giao diện:**

- Thẻ lựa chọn Đọc.
- Thẻ lựa chọn Nghe.
- Thẻ lựa chọn Xem.
- Thẻ lựa chọn Thực hành.
- Chọn nhiều.
- Nút Tiếp tục.

## 6.3. Đánh giá mức độ hiểu biết

**Discribe màn hình dự kiến:**

Hiển thị câu hỏi về mức độ hiểu biết của học sinh đối với tài liệu hoặc môn học.

**Thành phần giao diện:**

- Câu hỏi đánh giá.
- Lựa chọn năm mức độ.
- Trạng thái đã chọn.
- Nút Tiếp tục.

## 6.4. Tải lên tài liệu học tập

**Discribe màn hình dự kiến:**

- Khu vực tải tài liệu.
- Hiển thị định dạng được hỗ trợ.
- Hiển thị giới hạn dung lượng.
- Danh sách tài liệu đã tải lên.
- Trạng thái Processing từng tệp.

**Thành phần giao diện:**

- Khu vực tải lên.
- Chọn tệp.
- Danh sách tệp.
- Tiến trình tải lên.
- Trạng thái kiểm tra.
- Nút Xóa tệp.

## 6.5. Processing phân tích tài liệu

**Discribe màn hình dự kiến:**

Hiển thị trạng thái AI đang đọc, trích xuất và phân tích tài liệu.

**Thành phần giao diện:**

- Chỉ báo đang Processing.
- Trạng thái Processing tài liệu.
- Kết quả Processing tệp.
- Thông báo lỗi.
- Thao tác thử lại.

Các trạng thái tham khảo:

- Đang tải lên.
- Đang kiểm tra.
- Đang đọc.
- Đang trích xuất.
- Đang phân tích.
- Hoàn tất.
- Thất bại.
- Cần xem xét.

## 6.6. Phân loại và tổ chức chủ đề

**Discribe màn hình dự kiến:**

Hiển thị danh sách kiến thức được AI phân loại theo môn học và chương.

**Thành phần giao diện:**

- Tab môn học.
- Các phần theo chương.
- Danh sách chủ đề.
- Danh sách chủ đề con.
- Mở rộng / Thu gọn.
- Chi tiết chủ đề.

## 6.7. Xem xét và chỉnh sửa danh sách chủ đề

**Discribe màn hình dự kiến:**

Cho phép học sinh xem xét và chỉnh sửa danh sách chủ đề do AI tạo ra.

**Thành phần giao diện:**

- Thẻ chủ đề.
- Nút Thêm chủ đề.
- Sửa chủ đề.
- Xóa chủ đề.
- Trường Discribe.
- Hướng dẫn học tập.
- Nút Xác nhận danh sách chủ đề.

## 6.8. Lựa chọn trọng tâm học tập

**Discribe màn hình dự kiến:**

Hiển thị câu hỏi "Chúng ta nên tập trung nhiều nhất vào đâu?" để học sinh lựa chọn các chủ đề cần ưu tiên.

**Thành phần giao diện:**

- Chọn chủ đề.
- Mức độ ưu tiên.
- Ưu tiên Cao / Trung bình / Thấp.
- Các chủ đề đã chọn.
- Nút Tiếp tục.

## 6.9. Tạo kế hoạch học tập bằng AI

**Discribe màn hình dự kiến:**

Hiển thị trạng thái AI đang xây dựng kế hoạch học tập dựa trên thông tin đã xác nhận.

**Thành phần giao diện:**

- Chỉ báo AI đang Processing.
- Tiến trình tạo kế hoạch.
- Tóm tắt kế hoạch học tập.
- Trạng thái hoàn thành dự kiến.

## 6.10. Xem xét và lưu kế hoạch học tập

**Discribe màn hình dự kiến:**

Hiển thị kế hoạch học tập dưới dạng lịch theo ngày hoặc tuần. Người dùng có thể xem, điều chỉnh và xác nhận kế hoạch.

**Thành phần giao diện:**

- Chế độ xem lịch.
- Lịch học theo tuần.
- Các buổi học theo ngày.
- Phân bổ chủ đề.
- Thời lượng học.
- Chỉnh sửa lịch.
- Tạo lại kế hoạch.
- Nút Xác nhận và lưu.

---

# 7. Mức độ ưu tiên

## 7.1. Mức độ ưu tiên theo nhóm tính năng

| Nhóm tính năng | Mức ưu tiên | Lý do |
| -------------- | ----------- | ----- |
| Thiết lập thông tin học tập | Cao | Cung cấp dữ liệu đầu vào cho quá trình cá nhân hóa. |
| Quản lý tài liệu học tập | Cao | Tiếp nhận và đảm bảo chất lượng tài liệu. |
| Processing tài liệu bằng AI | Cao | Chuyển đổi tài liệu thành dữ liệu kiến thức có cấu trúc. |
| Quản lý chủ đề kiến thức | Cao | Xác định và xác nhận các nội dung cần học. |
| Tạo kế hoạch học tập bằng AI | Cao | Tạo kế hoạch học tập cá nhân hóa. |

## 7.2. Mức độ ưu tiên theo chức năng nhỏ

| ID | Chức năng nhỏ | Mức ưu tiên |
| --- | --- | --- |
| ASP-01 | Thu thập thông tin học tập | Cao |
| ASP-02 | Lựa chọn ngôn ngữ Output | Trung bình |
| ASP-03 | Thiết lập mục tiêu học tập | Cao |
| ASP-04 | Thiết lập ngày thi và lịch học | Cao |
| ASP-05 | Lựa chọn phương thức học tập | Trung bình |
| ASP-06 | Đánh giá mức độ hiểu biết | Cao |
| ASP-07 | Tải lên tài liệu học tập | Cao |
| F08 | Kiểm tra tệp | Cao |
| F09 | Phân tích tài liệu bằng AI | Cao |
| F10 | Phân loại và tổ chức chủ đề | Cao |
| F11 | Tạo và xem xét danh sách chủ đề | Cao |
| F12 | Lựa chọn trọng tâm học tập | Trung bình |
| F13 | Tạo lịch học bằng AI | Cao |
| F14 | Xem xét và lưu kế hoạch học tập | Cao |

---

# 8. Các nghiệp vụ cần xem xét bổ sung

Những nội dung sau không nhất thiết phải đưa vào phiên bản MVP, nhưng nên được xem xét trong quá trình phát triển Kế hoạch học tập AI.

## 8.1. Tạo lại kế hoạch học tập

Cho phép học sinh yêu cầu AI tạo lại kế hoạch khi:

- Thay đổi mục tiêu học tập.
- Thay đổi ngày thi.
- Thay đổi thời gian có thể học.
- Bổ sung hoặc xóa tài liệu.
- Thay đổi danh sách chủ đề.
- Thay đổi mức độ ưu tiên.

## 8.2. Điều chỉnh kế hoạch học tập

Cho phép kế hoạch được điều chỉnh khi học sinh không hoàn thành đúng lịch.

Ví dụ:

- Học sinh bỏ lỡ một buổi học.
- Học sinh cần thêm thời gian cho một chủ đề.
- Học sinh hoàn thành chủ đề sớm hơn dự kiến.
- Học sinh có lịch học mới.

AI có thể đề xuất cập nhật lịch học còn lại dựa trên trạng thái mới.

## 8.3. Quản lý phiên bản kế hoạch học tập

Hệ thống có thể lưu các phiên bản kế hoạch khi người dùng yêu cầu AI tạo lại hoặc chỉnh sửa kế hoạch.

Các thông tin cần lưu:

- Mã kế hoạch.
- Số phiên bản.
- Ngày tạo.
- Ngày cập nhật.
- Kế hoạch trước đó.
- Trạng thái kế hoạch hiện tại.

## 8.4. Tích hợp tiến độ kế hoạch học tập

Kế hoạch đã lưu có thể liên kết với hệ thống theo dõi tiến độ học tập.

Ví dụ:

- Chưa bắt đầu.
- Đang thực hiện.
- Đã hoàn thành.
- Quá hạn.

Dữ liệu tiến độ có thể được sử dụng để đề xuất điều chỉnh kế hoạch trong tương lai.

---

# 9. Các giả định và vấn đề cần xác nhận

Các quy tắc dưới đây cần được Chủ sản phẩm (Product Owner) hoặc nhóm xác nhận trước khi xem là yêu cầu chính thức.

| ID | Câu hỏi | Tại sao quan trọng |
| --- | --- | --- |
| Q01 | Người dùng có bắt buộc tải tài liệu lên không? | Xác định AI có thể tạo kế hoạch chỉ từ thông tin nhập tay hay không. |
| Q02 | Một kế hoạch có thể chứa nhiều môn học không? | Ảnh hưởng đến cấu trúc dữ liệu và cách phân bổ thời gian. |
| Q03 | Người dùng có thể thiết lập nhiều ngày thi cho nhiều môn không? | Ảnh hưởng đến việc ưu tiên môn học và hạn chót. |
| Q04 | Có giới hạn số lượng tệp, dung lượng và số trang không? | Xác định quy tắc tải lên và Processing tài liệu. |
| Q05 | AI có tự đánh giá mức độ hiểu biết qua bài kiểm tra (Quiz) không? | Phân biệt tự đánh giá và đánh giá dựa trên kết quả thực tế. |
| Q06 | Người dùng có bắt buộc chọn phương thức học tập không? | Xác định điều kiện hoàn thành thiết lập. |
| Q07 | AI có tự đề xuất mức độ ưu tiên học tập hay chỉ ghi nhận lựa chọn của học sinh? | Xác định trách nhiệm của AI và người dùng. |
| Q08 | Người dùng có thể chỉnh sửa lịch học sau khi xác nhận không? | Xác định nghiệp vụ cập nhật kế hoạch. |
| Q09 | Khi lịch học không đủ để hoàn thành tất cả chủ đề, AI Processing như thế nào? | Xác định quy tắc ưu tiên và thông báo. |
| Q10 | Kế hoạch học tập sau khi lưu có tự động tạo các Nhiệm vụ chính (Main Tasks) không? | Xác định mối liên kết với module Quản lý nhiệm vụ. |

---

# 10. Kết quả cuối cùng

Sau khi hoàn thành Kế hoạch học tập AI, học sinh nhận được:

1. Một hồ sơ học tập được thiết lập theo nhu cầu cá nhân.
2. Danh sách tài liệu đã được tải lên và kiểm tra.
3. Nội dung tài liệu đã được AI đọc và phân tích.
4. Danh sách chủ đề kiến thức được phân loại theo môn học và chương.
5. Danh sách chủ đề đã được học sinh kiểm tra và xác nhận.
6. Các chủ đề được đánh dấu theo mức độ ưu tiên.
7. Một kế hoạch học tập cá nhân hóa theo ngày hoặc tuần.
8. Các hoạt động học tập và thời lượng dự kiến cho từng buổi.
9. Một kế hoạch học tập đã được xác nhận và lưu vào tài khoản người dùng.

**Giá trị nghiệp vụ cuối cùng:**

Kế hoạch học tập AI giúp chuyển đổi tài liệu học tập rời rạc và thông tin cá nhân của học sinh thành một kế hoạch học tập có cấu trúc, có thời gian, có thứ tự ưu tiên và phù hợp với mục tiêu của từng người học.
