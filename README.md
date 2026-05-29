# MockAI Interview - Premium Job Support Platform

Nền tảng hỗ trợ việc làm toàn diện tích hợp Trí tuệ Nhân tạo (AI), giúp ứng viên tối ưu hóa CV, rèn luyện kỹ năng phỏng vấn thực chiến và kết nối hiệu quả với nhà tuyển dụng.

---

## Thành viên nhóm (Team Members)

| STT | Họ và Tên           |
| :-: | :------------------ |
|  1  | Lê Nhã Phương       |
|  2  | Nguyễn Tam Quân     |
|  3  | Trần Nguyễn Gia Huy |
|  4  | Nguyễn Đông Triều   |
|  5  | Phạm Quang Sáng     |

---

## Tổng quan Dự án (Business Value)

**MockAI Interview** không chỉ là một công cụ tạo CV mà là một hệ sinh thái hỗ trợ ứng viên toàn diện:

- **CV Parser & Analyzer**: Hệ thống tự động đọc hiểu CV (PDF/Docx), đánh giá điểm mạnh/yếu và trích xuất kỹ năng lõi.
- **AI Realtime Interview**: Mô phỏng phỏng vấn 1-1 với AI qua giọng nói (Voice-to-Text & Text-to-Voice), tạo áp lực và môi trường như thật.
- **Competency Assessment**: Trực quan hóa năng lực ứng viên qua Radar Chart đa chiều, so sánh với yêu cầu thực tế của thị trường.
- **HR Dashboard**: Cung cấp công cụ quản lý ứng viên tinh gọn, bảo mật cao và đánh giá ứng viên khách quan dựa trên dữ liệu AI cung cấp.

---

## Hàm lượng Nghiên cứu (Research & Technical Depth)

Dự án này không chỉ dừng lại ở các thao tác CRUD cơ bản mà đi sâu vào việc giải quyết các bài toán phức tạp trong kỹ thuật phần mềm và AI:

### 1. Nghiên cứu Thuật toán & Trí tuệ Nhân tạo (Algorithms & AI)

- **Natural Language Processing (NLP)**: Nghiên cứu và áp dụng các thuật toán trích xuất thực thể (Named Entity Recognition) để bóc tách dữ liệu phi cấu trúc từ CV thành dữ liệu có cấu trúc.
- **Audio Processing (WebRTC & Socket)**: Xử lý luồng âm thanh thời gian thực (Realtime audio streaming) với độ trễ thấp, kết nối mượt mà giữa Speech-to-Text và Text-to-Speech models.
- **Scoring Algorithm**: Phát triển thuật toán chấm điểm đa biến dựa trên từ khóa, độ lưu loát của giọng nói và ngữ cảnh câu trả lời để vẽ biểu đồ năng lực (Radar Chart).

### 2. Công nghệ Lập trình (Advanced Technologies)

- **Modern Frontend (React 19 & Vite)**: Tối ưu hóa bundle size và tốc độ render bằng kiến trúc React mới nhất.
- **Premium Visuals & Motion**: Sử dụng **Tailwind CSS v4**, **Framer Motion** và **Three.js** để tạo ra các tương tác UI/UX sang trọng (Glassmorphism), animations mượt mà, mang tính chất tâm lý học UX (Psychology-driven design).
- **State Management Separation**: Tách biệt hoàn toàn Server State (**TanStack Query** - cho caching, deduping) và Client State (**Zustand** - cho UI interactions), khắc phục điểm yếu của Redux truyền thống.
- **Robust Backend**: Node.js kết hợp Express và **Knex.js** (Query Builder) cùng PostgreSQL để đảm bảo hiệu năng truy vấn và tính toàn vẹn của dữ liệu phức tạp.

### 3. Kiến trúc Thiết kế Hệ thống (System Architecture)

- **Secure Authentication & RBAC**: Xây dựng luồng bảo mật tiêu chuẩn công nghiệp với JWT (JSON Web Token), Refresh Token rotation, kết hợp Bcryptjs và Axios Interceptors. Mọi endpoint đều được bảo vệ bởi Middleware và `<ProtectedRoute>` ở Frontend.
- **Micro-interaction & Modular Design**: Hệ thống chia nhỏ thành các module độc lập (CV Module, Interview Module, Assessment Module) giúp dễ dàng scale và maintain theo chuẩn Software Factory.
- **Realtime Infrastructure**: Thiết kế kiến trúc Event-driven qua WebSockets để xử lý song song các tác vụ nặng (như generate AI response) mà không chặn luồng chính (Main thread) của ứng dụng.

### 4. Quản lý dự án (Jira)

- **Phân công thành viên**:
- **Link Jira**: [Group6 Team Jira](https://nhaphuong220905.atlassian.net/?continue=https%3A%2F%2Fnhaphuong220905.atlassian.net%2Fwelcome%2Fsoftware%3FprojectId%3D10002&atlOrigin=eyJpIjoiZTRiZmMwZjQyYTgwNDZlNGIyOWUzZDg2MTVjOTYyYzMiLCJwIjoiamlyYS1zb2Zmd2FyZSJ9)
