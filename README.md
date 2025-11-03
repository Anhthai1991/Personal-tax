# Vietnam Personal Income Tax Calculator 2026 🇻🇳

Công cụ tính thuế thu nhập cá nhân (TNCN) Việt Nam năm 2026 - So sánh hệ thống thuế hiện tại và đề xuất mới.

## 🌟 Tính năng chính

- ✅ Tính thuế TNCN theo 3 hệ thống:
  - Hệ thống hiện tại 2025 (7 bậc thuế)
  - Đề xuất 2026 Phương án 1 (5 bậc thuế)
  - Đề xuất 2026 Phương án 2 - Được khuyến nghị (5 bậc thuế)
  
- 📊 So sánh chi tiết giữa các hệ thống
- 💰 Tính toán chính xác:
  - Bảo hiểm bắt buộc (10.5%)
  - Giảm trừ gia cảnh
  - Thu nhập tính thuế
  - Thuế TNCN phải nộp
  - Lương ròng (take-home)

- 📱 Giao diện thân thiện, responsive
- 🎯 Kịch bản mẫu với các mức lương phổ biến
- 🖨️ In và xuất kết quả

## 🆕 Thay đổi chính trong năm 2026

1. **Giảm số bậc thuế**: Từ 7 bậc xuống còn 5 bậc
2. **Tăng giảm trừ bản thân**: 11 triệu → 15.5 triệu VNĐ/tháng (+40.9%)
3. **Tăng giảm trừ người phụ thuộc**: 4.4 triệu → 6.2 triệu VNĐ/tháng (+40.9%)
4. **Mở rộng khoảng thu nhập**: Giảm tình trạng "bị nhảy bậc thuế" khi lương tăng nhẹ

## 📋 So sánh bậc thuế

### Hệ thống hiện tại 2025 (7 bậc)
| Bậc | Thu nhập tính thuế/tháng (triệu VNĐ) | Thuế suất |
|-----|--------------------------------------|-----------|
| 1   | Đến 5                                | 5%        |
| 2   | Trên 5 - 10                          | 10%       |
| 3   | Trên 10 - 18                         | 15%       |
| 4   | Trên 18 - 32                         | 20%       |
| 5   | Trên 32 - 52                         | 25%       |
| 6   | Trên 52 - 80                         | 30%       |
| 7   | Trên 80                              | 35%       |

### Đề xuất 2026 - Phương án 1 (5 bậc)
| Bậc | Thu nhập tính thuế/tháng (triệu VNĐ) | Thuế suất |
|-----|--------------------------------------|-----------|
| 1   | Đến 10                               | 5%        |
| 2   | Trên 10 - 30                         | 15%       |
| 3   | Trên 30 - 50                         | 25%       |
| 4   | Trên 50 - 80                         | 30%       |
| 5   | Trên 80                              | 35%       |

### Đề xuất 2026 - Phương án 2 (5 bậc) ⭐ KHUYẾN NGHỊ
| Bậc | Thu nhập tính thuế/tháng (triệu VNĐ) | Thuế suất |
|-----|--------------------------------------|-----------|
| 1   | Đến 10                               | 5%        |
| 2   | Trên 10 - 30                         | 15%       |
| 3   | Trên 30 - 60                         | 25%       |
| 4   | Trên 60 - 100                        | 30%       |
| 5   | Trên 100                             | 35%       |

## 💡 Ví dụ tác động

| Lương (triệu VNĐ) | Người phụ thuộc | Thuế 2025 | Thuế 2026 (PA2) | Tiết kiệm |
|-------------------|-----------------|-----------|-----------------|-----------|
| 20                | 1               | 125,000   | 0               | 100%      |
| 25                | 1               | 448,000   | 34,000          | 92%       |
| 30                | 2               | 968,000   | 258,000         | 73%       |
| 50                | 2               | 4,508,000 | 2,898,000       | 36%       |

## 🚀 Cách sử dụng

### Sử dụng trực tuyến
Truy cập: [anhthai1991.github.io/Personal-tax/])

### Chạy local
```bash
# Clone repository
git clone https://github.com/anhthai1991/Personal-tax.git

# Mở file index.html trong trình duyệt
# Không cần cài đặt gì thêm!
```

### Deploy lên GitHub Pages
1. Fork repository này
2. Vào Settings → Pages
3. Chọn branch `main` và folder `root`
4. Lưu và truy cập qua URL được cung cấp

## 📚 Cơ sở pháp lý

- **Luật Thuế Thu nhập cá nhân 2007** (sửa đổi 2012, 2014)
- **Nghị định 65/2013/NĐ-CP** - Hướng dẫn chi tiết
- **Thông tư 111/2013/TT-BTC** (sửa đổi bởi Thông tư 92/2015/TT-BTC)
- **Nghị quyết UBTVQH** ngày 17/10/2025 - Điều chỉnh giảm trừ gia cảnh
- **Dự thảo Luật Thuế TNCN 2026** - Công bố tháng 8/2025

## 📅 Lộ trình thực hiện

- **17/10/2025**: UBTVQH thông qua điều chỉnh giảm trừ gia cảnh
- **Tháng 10/2025**: Dự kiến trình Quốc hội dự thảo luật mới
- **01/01/2026**: Giảm trừ gia cảnh mới có hiệu lực (15.5M/6.2M)
- **Tháng 7/2026**: Dự kiến bậc thuế mới có hiệu lực
- **Q1/2027**: Khai báo thuế năm 2026 theo chế độ mới

## 🔧 Công thức tính thuế

```
1. Trừ bảo hiểm bắt buộc:
   Thu nhập sau bảo hiểm = Lương gốc × (100% - 10.5%)

2. Trừ giảm trừ gia cảnh:
   Thu nhập tính thuế = Thu nhập sau BHXH - Giảm trừ bản thân - (Số người phụ thuộc × Giảm trừ/người)

3. Áp dụng biểu thuế lũy tiến từng phần:
   Thuế TNCN = Σ(Thu nhập trong bậc × Thuế suất bậc đó)

4. Tính lương ròng:
   Lương ròng = Lương gốc - BHXH - Thuế TNCN
```

## 📊 Tỷ lệ bảo hiểm (2025-2026)

| Loại bảo hiểm | Người lao động | Người sử dụng lao động |
|---------------|----------------|------------------------|
| BHXH          | 8%             | 17.5%                  |
| BHYT          | 1.5%           | 3%                     |
| BHTN          | 1%             | 1%                     |
| **Tổng**      | **10.5%**      | **21.5%**              |

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Vui lòng:

1. Fork repository
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## ⚠️ Lưu ý quan trọng

- Đây là công cụ tham khảo, không thay thế tư vấn thuế chuyên nghiệp
- Dự thảo luật có thể thay đổi trước khi được thông qua chính thức
- Luôn kiểm tra thông tin mới nhất từ Tổng cục Thuế
- Các trường hợp đặc biệt cần tư vấn riêng

## 📞 Liên hệ & Hỗ trợ

- **Issues**: [GitHub Issues](https://github.com/anhthai1991/vietnam-pit-2026/issues)
- **Email**: Anhthai.nhs@gmail.com
- **Website**: [Vietnam Tax Portal](https://gdt.gov.vn)

## 📄 License

MIT License - Xem file [LICENSE](LICENSE) để biết thêm chi tiết

## 🙏 Tài liệu tham khảo

- [Tổng cục Thuế Việt Nam](https://gdt.gov.vn)
- [Bộ Tài chính](https://mof.gov.vn)
- [Cổng thông tin điện tử Chính phủ](https://chinhphu.vn)
- [Văn phòng Chính phủ](https://vpcp.chinhphu.vn)

---

**Cập nhật lần cuối**: Tháng 11/2025  
**Phiên bản**: 1.0.0

⭐ Nếu công cụ này hữu ích, hãy cho một star nhé!
