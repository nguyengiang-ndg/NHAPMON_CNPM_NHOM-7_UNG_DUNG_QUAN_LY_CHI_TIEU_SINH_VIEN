# Ứng dụng Quản lý Chi tiêu Sinh viên

## Tầm nhìn sản phẩm

Công cụ giúp người dùng ghi chép thu chi hàng ngày và trực quan hóa thời quen tài chính.

## Thành viên nhóm

| STT | Họ và tên             | MSSV       | GitHub                                       | Phụ trách           |
| --- | --------------------- | ---------- | -------------------------------------------- | ------------------- |
| 1   | Nguyễn Đan Giang      | 25S1020025 | <https://github.com/thanhhuyen270107-source> | Scrum Master        |
| 2   | Nguyễn Khánh Linh     | 25S1020060 | <https://github.com/khanhlinhtl07-dotcom>    | (Phụ trách)         |
| 3   | Huỳnh Thị Thanh Huyên | 25S1020047 | <https://github.com/thanhhuyen270107-source> | Form nhập giao dịch |
| 4   | Nguyễn Ngọc Anh       | *(MSSV)*   | <https://github.com/ngocanh131027-stack>     | *(Phụ trách)*       |

## Công nghệ dự kiến

- Ngôn ngữ / Framework: *(điền sau khi nhóm chốt)*
- Cơ sở dữ liệu: *(điền sau khi nhóm chốt)*

## Cấu trúc dự án

```
.
├── README.md
├── .gitignore
└── (các thư mục mã nguồn)
```

## Quy trình làm việc nhóm

Nhóm làm việc theo **Feature Branch Workflow**:

1. `main` luôn chứa phiên bản ổn định nhất.
2. Mỗi công việc mới tạo nhánh riêng từ `main`: `feature/ten-tinh-nang`, `fix/ten-loi`.
3. Commit, push nhánh lên GitHub và tạo **Pull Request**.
4. Thành viên khác (ưu tiên Scrum Master) review và **Approve**.
5. Merge vào `main`, sau đó **Delete branch**.

Trước khi bắt đầu việc mới, luôn cập nhật code mới nhất:

```bash
git checkout main
git pull origin main
```

