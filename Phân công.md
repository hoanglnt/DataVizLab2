Hướng dẫn:
- Trước khi làm phần của mình thì 
    - git checkout master
    - git pull
- Tạo branch mới theo cú pháp git checkout branch <tên mình>/<tên phần>, ví dụ Hoang/preprocess, Nguyen/explore
- Chỉ code trong branch của mình, đừng đá qua master
- Code xong thì push lên rồi báo t, đừng merge lung tung, mấy cái lz notebook merge nó bị conflict nhiều lắm
- Đọc dữ liệu để explore từ file `datasets/weather_cleaned.csv`

- Collect: Hòa
- Explore:
    - Phân bố trong từng cột: Nghĩa
    - Phân bố giữa các cột: 
        - Giữa các cột numerical với nhau: Hòa
        - Giữa cột thời gian với: min, max, rain, humidity, wind, cloud, pressure: Hiển
        - Giữa province với: min, max, rain, cloud, humidity, wind: Nguyên
        - Cột hướng gió với vùng miền và thời gian: Hoàng
        - Cột province, numerical và thời gian: Hoàng

Lưu ý khi gõ đề mục markdown: Không cần gõ số đề mục, chỉ cần chú ý số lượng dấu "#", ví dụ có mục `1. Tiền xử lí` và `1.1. Missing values` thì:

- Không nên làm như này:
```
# 1. Tiền xử lí
## 1.1. Missing values
```

- Mà nên làm như này
```
# Tiền xử lí
## Missing values
```

Làm vậy thì lúc export pdf nó sẽ tự đánh số, không cần phải đánh số nữa