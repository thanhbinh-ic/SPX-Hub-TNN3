# SPX Hub Thái Nguyên — Bảng tuyến và luật đẩy hàng

Hub: Tổ dân phố số 5, Phường Tích Lương, TP Thái Nguyên — 21.5439521, 105.8440779.
Phụ trách: Tân Lập, Phú Xá, Tích Lương.

## Luật ưu tiên

1. Mốc địa danh trước, rồi tổ + phường, rồi số nhà + ngõ + đường.
2. Trùm Quế (Tích Lương) luôn chuyển cho LÊ TUẤN ANH [139148].
3. Mốc 666: ĐH Kỹ thuật Công nghiệp ở 666 Đ. 3/2, Tích Lương. Số nhà ≤ 666 tại Tổ 8 về
   LÊ THANH HÀ [16338]; số 666–1016 tại Tổ 2 về DƯƠNG TIỀN PHÚ [157243].
4. Cây xăng Mạnh Hùng: mốc cuối tuyến LÊ THANH HÀ, mã JQR7+7C5, xã Vô Tranh.
   Vị trí ghim trên bản đồ chỉ là khu vực xã Vô Tranh, cần xác nhận điểm chính xác
   trên Google Maps trước khi dùng làm mốc tọa độ.
5. Quy tắc dự phòng CHỈ áp khi ảnh nhiệm vụ KHÔNG có chữ "hoàn hàng", "trả tiền"
   hay "trả hàng": Phú Xá → ĐẶNG TIẾN TRUNG [79629]; Tân Lập / Tích Lương →
   LÊ TUẤN ANH [139148]. "Người gửi trả phí" không tính là một trong ba chữ này.
6. Tổ 17 → tính là Phú Xá.
7. Tổ không có trong bảng (ví dụ Tổ 19) → hệ thống báo chưa xác định được,
   không tự đoán rider.
8. TRẦN ĐĂNG YÊN [162125] đã nghỉ làm tại Hub nên không chia tuyến nữa.

## Bảng tuyến (từ file chia tuyến huynh gửi)

### Tích Lương

- [53634] BÙI VĂN TUẤN: cổng A1 đến Tổ 6
- [16338] LÊ THANH HÀ: cổng chính ĐH Công nghiệp đến cây xăng Mạnh Hùng;
  từ 666 trở ngược về số nhỏ, Tổ 8
- [100332] LƯỜNG THỊ ĐẦM: Tổ 11, 12, 13, 14, 15
- [157243] DƯƠNG TIỀN PHÚ: Tổ 9, Tổ 10; từ 666 đến 1016, Tổ 2
- [38286] DƯƠNG VĂN SƠN: Tổ 4, Tổ 5 (trừ Trùm Quế)

### Phú Xá

- [36689] NGUYỄN HỮU HIỆN: số nhà 210 đến 58 chẵn; Tổ 2 mặt đường Việt Bắc,
  ngõ 167 đến nhà 57B lẻ
- [55666] NGUYỄN THỊ THU: Tổ 4, mặt lẻ đường 3/2 đến 1149
- [58352] NGUYỄN ĐỨC CHUNG: mặt lẻ Tổ 1 Phú Xá, Tổ 1 Cách mạng Tháng 8
- [79629] ĐẶNG TIẾN TRUNG: 1151 đến 1477, ngõ 67, ngõ 210; Tổ 7, ngõ 711
- [164091] HÀ NGỌC MAI: Tổ 8, Tổ 10, Tổ 11
- [123498] ĐỖ THỊ NHUNG: cổng GOLICC đến hết đường ga; đường Việt Bắc đến
  đèn xanh đèn đỏ; Ga Lưu Xá (Tích Lương cũ)

### Tân Lập

- [161388] NGUYỄN HOÀNG ANH: 502 đến Ốc Hương, lẻ đường 3/2; 8xx
- [79621] PHẠM TRUNG KIÊN: Tổ 1, Tổ 2, GO, đường Việt Bắc
- [69333] NGUYỄN MẠNH ĐỨC: chẵn Tân Lập, từ ngõ 272 đến số to trung cấp nghề
- [44207] NGUYỄN XUÂN THẮNG: từ 272 đến số nhỏ, trường nội trú
- [52224] PHẠM THỊ HIÊN: từ 505 đến số nhỏ
- [139148] LÊ TUẤN ANH: lấy hàng seller, NS tại Tân Lập

## Deploy lên Vercel

Trang là web tĩnh, không cần build. Trên Vercel chọn Import repo này,
framework để Other / Static, không cần lệnh build, file chạy là `index.html`.
