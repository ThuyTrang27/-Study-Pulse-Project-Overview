# FEATURE 04: Learning Fun Zone – Khu vực học tập thú vị

## 1. Overview – Tổng quan

**Mục đích:**
Learning Fun Zone là khu vực giúp học sinh duy trì động lực học tập thông qua các yếu tố trò chơi hóa như chuỗi ngày học liên tiếp, thử thách hằng ngày, điểm kinh nghiệm, cấp độ, huy hiệu và bảng xếp hạng.

**Vấn đề cần giải quyết:**
- Học sinh dễ mất động lực khi học tập trong thời gian dài.
- Khó duy trì thói quen học tập đều đặn mỗi ngày.
- Thiếu sự ghi nhận khi hoàn thành nhiệm vụ học tập.
- Việc học có thể trở nên nhàm chán nếu chỉ tập trung vào bài học và bài kiểm tra.
- Học sinh chưa có mục tiêu nhỏ để tạo động lực học tập mỗi ngày.

**Đối tượng sử dụng:**
- Học sinh THCS và THPT.
- Phụ huynh có thể theo dõi thành tích học tập nếu hệ thống hỗ trợ.

**Giá trị mang lại:**
- Tạo động lực học tập thông qua các phần thưởng và thành tích.
- Hình thành thói quen học tập đều đặn.
- Khuyến khích học sinh hoàn thành các hoạt động học tập.
- Tăng tính tương tác và trải nghiệm thú vị khi sử dụng Study Pulse.
- Giúp học sinh theo dõi sự tiến bộ của bản thân.

## 2. Sub-features – Các chức năng nhỏ
| ID | Sub-feature | Mô tả |
|---|---|---|
| LFZ-01 | Learning Streak – Chuỗi ngày học liên tiếp | Theo dõi số ngày học liên tiếp của học sinh và khuyến khích duy trì thói quen học tập. |
| LFZ-02 | Achievement & Rewards – Thành tích và phần thưởng | Ghi nhận thành tích và trao huy hiệu hoặc phần thưởng khi học sinh đạt các cột mốc. |
| LFZ-03 | Daily Learning Challenge – Thử thách học tập hằng ngày | Cung cấp thử thách học tập mỗi ngày theo môn học hoặc chủ đề. |
| LFZ-04 | Gamified Learning – Trò chơi hóa học tập | Tích lũy XP, lên cấp và theo dõi tiến trình thành tích học tập. |
| LFZ-05 | Leaderboard – Bảng xếp hạng | Hiển thị thứ hạng học sinh dựa trên XP, thử thách hoặc thành tích học tập. |

## 3. User Flow – Luồng hoạt động
### 3.1 General User Flow
1. Học sinh mở Learning Fun Zone.
2. Hệ thống hiển thị Learning Streak, XP, Level, Achievement và Daily Challenge.
3. Học sinh lựa chọn thử thách hoặc tiếp tục hoạt động học tập.
4. Học sinh hoàn thành bài học, quiz, nhiệm vụ hoặc thử thách.
5. Hệ thống ghi nhận hoạt động học tập hợp lệ.
6. Hệ thống cập nhật Learning Streak, XP và tiến trình thành tích.
7. Nếu học sinh đạt điều kiện, hệ thống trao huy hiệu hoặc phần thưởng.
8. Hệ thống cập nhật Leaderboard.
9. Học sinh xem thành tích và tiếp tục học tập.

### 3.2 General Flow Diagram
Student opens Learning Fun Zone
              |
              v
View Streak / XP / Level / Achievement
              |
              v
Select Daily Learning Challenge
              |
              v
Complete Learning Activity
              |
              v
System validates completed activity
              |
              v
Update Streak + XP + Level
              |
              v
Check Achievement & Rewards
              |
              v
Update Leaderboard
              |
              v
Display Learning Progress

## 4. Functional Description – Mô tả chức năng
### LFZ-01: Learning Streak – Chuỗi ngày học liên tiếp
**Mô tả:**
- Theo dõi số ngày liên tiếp học sinh hoàn thành ít nhất một hoạt động học tập.
- Hiển thị số ngày học liên tiếp hiện tại.
- Hiển thị chuỗi ngày học dài nhất đã đạt được.
- Cập nhật streak dựa trên hoạt động học tập thực tế của học sinh.

**Input:**
- User ID.
- Ngày và thời gian hoàn thành hoạt động học tập.
- Trạng thái hoàn thành hoạt động.

**Processing:**
1. Hệ thống kiểm tra hoạt động học tập của học sinh.
2. Nếu học sinh hoàn thành ít nhất một hoạt động hợp lệ trong ngày, ngày đó được ghi nhận là ngày học.
3. Nếu học sinh học vào ngày tiếp theo liên tiếp, streak tăng lên 1.
4. Nếu học sinh bỏ lỡ một ngày, streak hiện tại bị reset.
5. Hệ thống cập nhật streak dài nhất nếu streak hiện tại vượt qua thành tích trước đó.

**Output:**
- Current Learning Streak.
- Longest Learning Streak.
- Trạng thái duy trì chuỗi ngày học.

**Business Rules:**
- Một ngày được tính là ngày học khi học sinh hoàn thành ít nhất một hoạt động học tập hợp lệ.
- Không tăng streak nhiều lần trong cùng một ngày.
- Nếu bỏ lỡ một ngày, streak hiện tại bị reset.
- Longest Streak không bị reset khi học sinh mất streak hiện tại.
- Streak được cập nhật dựa trên hoạt động học tập thực tế, không dựa trên việc mở ứng dụng.

**Exception Handling:**
- Nếu không có hoạt động học tập trong ngày, hệ thống không ghi nhận ngày học.
- Nếu dữ liệu hoạt động bị thiếu, hệ thống không tự động tăng streak.
- Nếu có lỗi cập nhật, hệ thống cần lưu lại trạng thái và thử cập nhật lại.

**AI sử dụng:**
- Không sử dụng AI.
- Sử dụng logic xử lý dữ liệu và điều kiện của hệ thống.

### LFZ-02: Achievement & Rewards – Thành tích và phần thưởng
**Mô tả:**
- Ghi nhận thành tích khi học sinh đạt các cột mốc học tập.
- Cung cấp huy hiệu hoặc phần thưởng để khuyến khích học sinh.
- Hiển thị danh sách huy hiệu đã đạt được.
- Hiển thị lịch sử phần thưởng.

**Input:**
- User ID.
- Learning Streak.
- Tổng số nhiệm vụ đã hoàn thành.
- Tổng XP.
- Trạng thái hoàn thành mục tiêu học tập.
- Achievement rules.

**Processing:**
1. Hệ thống nhận dữ liệu hoạt động học tập.
2. Kiểm tra điều kiện của từng achievement.
3. Nếu học sinh đạt điều kiện, hệ thống trao achievement hoặc reward.
4. Lưu achievement vào bộ sưu tập của học sinh.
5. Cập nhật lịch sử phần thưởng.

**Output:**
- Achievement unlocked.
- Reward notification.
- Achievement collection.
- Reward history.

**Business Rules:**
- Achievement được trao khi học sinh đáp ứng đầy đủ điều kiện.
- Điều kiện có thể dựa trên streak, số nhiệm vụ, XP hoặc mục tiêu học tập.
- Ví dụ: học liên tiếp 7 ngày, hoàn thành 10 nhiệm vụ hoặc đạt mục tiêu học tập tuần.
- Không trao cùng một achievement nhiều lần nếu achievement đó chỉ được nhận một lần.
- Hệ thống phải lưu lại thời điểm đạt thành tích.

**Exception Handling:**
- Nếu achievement chưa đạt điều kiện, hệ thống không trao phần thưởng.
- Nếu lỗi cập nhật achievement, hệ thống cần thử xử lý lại.
- Nếu dữ liệu thành tích không đầy đủ, hệ thống không tự động trao thưởng.

**AI sử dụng:**
- Không sử dụng AI.
- Sử dụng rule-based system để kiểm tra điều kiện và trao thưởng.

### LFZ-03: Daily Learning Challenge – Thử thách học tập hằng ngày
**Mô tả:**
- Cung cấp thử thách học tập hằng ngày cho học sinh.
- Thử thách có thể liên quan đến môn học hoặc chủ đề cụ thể.
- Các thử thách có thể bao gồm trả lời câu hỏi, giải bài tập hoặc ôn tập kiến thức.
- Theo dõi trạng thái hoàn thành thử thách.
- Có thể đề xuất thử thách dựa trên trình độ và tiến độ học tập của học sinh.

**Input:**
- User ID.
- Môn học.
- Chủ đề học tập.
- Trình độ học sinh.
- Learning Progress.
- Challenge History.

**Processing:**
1. Hệ thống xác định môn học hoặc chủ đề phù hợp.
2. Hệ thống lấy thử thách có sẵn hoặc tạo thử thách mới khi cần.
3. Nếu cần tạo thử thách bằng AI, hệ thống gửi thông tin môn học, chủ đề và trình độ đến Gemini Flash API.
4. AI tạo thử thách phù hợp với học sinh.
5. Hệ thống hiển thị thử thách.
6. Học sinh thực hiện thử thách.
7. Hệ thống kiểm tra và cập nhật trạng thái hoàn thành.

**Output:**
- Daily Learning Challenge.
- Challenge details.
- Challenge completion status.
- Challenge reward nếu có.

**Business Rules:**
- Thử thách cần phù hợp với môn học và trình độ học sinh.
- Mỗi thử thách phải có nội dung và điều kiện hoàn thành rõ ràng.
- Trạng thái thử thách được cập nhật khi học sinh hoàn thành.
- Phần thưởng được trao theo điều kiện của thử thách.
- AI chỉ được sử dụng khi cần tạo hoặc cá nhân hóa thử thách.

**Exception Handling:**
- Nếu AI không tạo được thử thách, hệ thống sử dụng thử thách có sẵn nếu có.
- Nếu không có thử thách phù hợp, hệ thống hiển thị thông báo.
- Nếu kết nối AI thất bại, học sinh có thể thử lại sau.
- Nếu thử thách chưa hoàn thành, hệ thống giữ trạng thái chưa hoàn thành.

**AI sử dụng:**
- Gemini Flash API.
- Sử dụng AI để tạo hoặc cá nhân hóa thử thách học tập dựa trên môn học, chủ đề và trình độ học sinh.

### LFZ-04: Gamified Learning – Trò chơi hóa học tập
**Mô tả:**
- Tạo hệ thống XP để ghi nhận hoạt động học tập.
- Học sinh nhận XP khi hoàn thành bài học, quiz hoặc nhiệm vụ.
- Sử dụng XP để xác định Level của học sinh.
- Hiển thị tiến trình lên cấp và thành tích học tập.

**Input:**
- User ID.
- Completed Learning Activities.
- XP Rules.
- Total XP.
- Level Thresholds.

**Processing:**
1. Học sinh hoàn thành hoạt động học tập.
2. Hệ thống kiểm tra hoạt động có hợp lệ hay không.
3. Hệ thống xác định lượng XP được nhận.
4. Cộng XP vào tổng XP của học sinh.
5. Kiểm tra điều kiện lên Level.
6. Nếu đạt điều kiện, hệ thống cập nhật Level.
7. Hiển thị XP và tiến trình Level mới.

**Output:**
- XP earned.
- Total XP.
- Current Level.
- Level progress.
- Level-up notification nếu có.

**Business Rules:**
- XP chỉ được trao cho hoạt động học tập hợp lệ đã hoàn thành.
- Mỗi hoạt động chỉ được nhận XP theo quy định của hệ thống.
- Không cộng XP nhiều lần cho cùng một hoạt động nếu không được cho phép.
- Level được xác định dựa trên tổng XP và ngưỡng XP đã thiết lập.
- XP và Level được cập nhật sau khi hoạt động được xác nhận hoàn thành.

**Exception Handling:**
- Nếu hoạt động chưa hoàn thành, hệ thống không trao XP.
- Nếu xảy ra lỗi cập nhật XP, hệ thống cần thử cập nhật lại.
- Nếu dữ liệu XP không hợp lệ, hệ thống không cập nhật Level.

**AI sử dụng:**
- Không sử dụng AI.
- Sử dụng logic xử lý XP và Level của hệ thống.

### LFZ-05: Leaderboard – Bảng xếp hạng
**Mô tả:**
- Hiển thị bảng xếp hạng học sinh dựa trên thành tích học tập.
- Xếp hạng dựa trên XP, số thử thách hoàn thành hoặc thành tích học tập.
- Cập nhật thứ hạng khi dữ liệu học tập thay đổi.
- Hỗ trợ bảng xếp hạng theo tuần hoặc tháng.

**Input:**
- User ID.
- Total XP.
- Completed Challenges.
- Learning Achievements.
- Ranking Period.

**Processing:**
1. Hệ thống thu thập dữ liệu thành tích của học sinh.
2. Xác định tiêu chí xếp hạng.
3. Tổng hợp dữ liệu theo tuần hoặc tháng.
4. Sắp xếp học sinh theo tiêu chí.
5. Cập nhật thứ hạng.
6. Hiển thị bảng xếp hạng.

**Output:**
- Leaderboard.
- Student ranking.
- Ranking period.
- Student position.

**Business Rules:**
- Thứ hạng được xác định dựa trên tiêu chí đã thiết lập.
- Bảng xếp hạng có thể được phân chia theo tuần hoặc tháng.
- Thứ hạng được cập nhật khi dữ liệu thành tích thay đổi hoặc theo lịch hệ thống.
- Nếu nhiều học sinh có cùng điểm, hệ thống cần có quy tắc xử lý đồng hạng.
- Chỉ sử dụng dữ liệu học tập hợp lệ để tính thứ hạng.

**Exception Handling:**
- Nếu không có dữ liệu xếp hạng, hệ thống hiển thị thông báo phù hợp.
- Nếu dữ liệu chưa được cập nhật, hệ thống hiển thị thứ hạng gần nhất.
- Nếu lỗi truy xuất dữ liệu, hệ thống thông báo và cho phép thử lại.

**AI sử dụng:**
- Không sử dụng AI.
- Sử dụng thuật toán sắp xếp và xử lý dữ liệu.

## 5. Acceptance Criteria – Tiêu chí nghiệm thu
| ID | Acceptance Criteria |
|---|---|
| AC-01 | Hệ thống ghi nhận Learning Streak khi học sinh hoàn thành ít nhất một hoạt động học tập hợp lệ trong ngày. |
| AC-02 | Hệ thống cập nhật Current Streak và Longest Streak chính xác. |
| AC-03 | Hệ thống reset Current Streak khi học sinh bỏ lỡ một ngày học. |
| AC-04 | Hệ thống kiểm tra điều kiện Achievement trước khi trao phần thưởng. |
| AC-05 | Hệ thống lưu Achievement và Reward History của học sinh. |
| AC-06 | Hệ thống hiển thị Daily Learning Challenge phù hợp với môn học hoặc chủ đề. |
| AC-07 | Hệ thống cập nhật trạng thái thử thách khi học sinh hoàn thành. |
| AC-08 | Hệ thống có thể sử dụng Gemini Flash API để tạo thử thách khi cần. |
| AC-09 | Hệ thống cộng XP khi học sinh hoàn thành hoạt động học tập hợp lệ. |
| AC-10 | Hệ thống cập nhật Level khi học sinh đạt đủ XP theo quy định. |
| AC-11 | Hệ thống không cộng XP nhiều lần cho cùng một hoạt động nếu không được phép. |
| AC-12 | Hệ thống hiển thị Leaderboard theo tiêu chí và khoảng thời gian đã thiết lập. |
| AC-13 | Hệ thống cập nhật thứ hạng khi dữ liệu thành tích thay đổi. |

## 6. UI/UX Reference – Giao diện tham khảo
### Learning Fun Zone Main Screen
Giao diện chính có thể bao gồm:
- Current Learning Streak.
- Total XP.
- Current Level.
- Daily Learning Challenge.
- Achievement Collection.
- Leaderboard.
- Progress to Next Level.

### Suggested Layout
------------------------------------------------
              LEARNING FUN ZONE
------------------------------------------------
 Learning Streak       Level       Total XP
      7 Days             3           450 XP
------------------------------------------------
              DAILY CHALLENGE
       Complete today's learning task
------------------------------------------------
              ACHIEVEMENTS
       [Badge 1] [Badge 2] [Badge 3]
------------------------------------------------
              LEADERBOARD
       1. Student A       850 XP
       2. Student B       720 XP
       3. Student C       650 XP
------------------------------------------------

## 7. Priority – Mức độ ưu tiên
| Sub-feature | Priority | Reason |
|---|---|---|
| Learning Streak | High | Giúp hình thành thói quen học tập đều đặn. |
| Achievement & Rewards | Medium | Tạo động lực thông qua thành tích và phần thưởng. |
| Daily Learning Challenge | High | Khuyến khích học sinh tham gia hoạt động học tập mỗi ngày. |
| Gamified Learning | High | Tạo hệ thống XP và Level để tăng động lực. |
| Leaderboard | Medium | Tăng tính cạnh tranh và tương tác giữa học sinh. |

### Suggested MVP Implementation Order
1. Gamified Learning – XP và Level.
2. Learning Streak – Theo dõi chuỗi ngày học.
3. Achievement & Rewards – Ghi nhận thành tích.
4. Daily Learning Challenge – Thử thách học tập.
5. Leaderboard – Bảng xếp hạng.