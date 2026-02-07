# NCKH 2023–2024: Xây dựng Package Lý thuyết Đồ thị trên Maple

## Giới thiệu

Đề tài nghiên cứu khoa học năm 2023–2024: **Xây dựng gói lệnh (Package) giải các bài toán Lý thuyết Đồ thị trên phần mềm Maple**.

Package cung cấp các hàm và thủ tục để:
- Khởi tạo đồ thị (đỉnh, cạnh, đồ thị có hướng/vô hướng)
- Thực hiện các thuật toán trên đồ thị (duyệt, tìm đường đi ngắn nhất, cây khung, ...)
- Trực quan hóa đồ thị trong môi trường Maple

## Cấu trúc thư mục

```
nckh_2324/
├── BaoCaoNCKH2024.pdf          # Báo cáo nghiên cứu khoa học (PDF)
├── BaoCaoNCKH2024.ppt          # Slide báo cáo
├── README.md
└── Package/
    ├── GRAPH_THEORY.m           # Source code package chính
    ├── GRAPH_THEORY.mw          # Worksheet Maple chính
    ├── TEST.mw                  # Worksheet kiểm thử
    ├── testGRAPH_THEORY.mw      # Worksheet test bổ sung
    ├── Detoan/                  # Các bài toán mẫu
    │   ├── Bai0.txt → Bai4.txt
    └── data/                    # Dữ liệu định nghĩa
        ├── GRAPH.txt            # Định nghĩa đồ thị
        ├── EDGE.txt             # Định nghĩa cạnh
        ├── FUNCTIONS.txt        # Danh sách hàm
        ├── OPERATORS.txt        # Toán tử
        ├── OBJECTS.txt          # Đối tượng
        ├── RELATIONS.txt        # Quan hệ
        └── RULES.txt            # Luật suy diễn
```

## Hướng dẫn sử dụng

### Yêu cầu
- **Maple** (phiên bản 2020 trở lên được khuyến nghị)

### Cách chạy

1. Mở **Maple**
2. Mở file `Package/GRAPH_THEORY.mw` hoặc `Package/TEST.mw`
3. Chạy các lệnh trong worksheet để sử dụng package

### Ví dụ bài toán

Các bài toán mẫu nằm trong thư mục `Package/Detoan/` (Bai0.txt → Bai4.txt). Mỗi file chứa dữ liệu đầu vào cho một bài toán đồ thị cụ thể.

## Tài liệu tham khảo

- Xem chi tiết trong file `BaoCaoNCKH2024.pdf`
- Slide trình bày: `BaoCaoNCKH2024.ppt`