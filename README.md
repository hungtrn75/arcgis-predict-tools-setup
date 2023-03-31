## Các bước để cài đặt toolbox "DA Tools" vào ArcGisPro v3.1.0

### Bước 1: Cài đặt `môi trường` trong ArcGisPro để chạy được `Toolbox`

- Tên mặc định là predict-image. Bạn có thể tự đổi tên môi trường

  ```
  conda create --name predict-image --file D:\python\THung\arcgis_predict.txt
  ```
- Nếu bạn đang sử dụng phiên bản conda của ArcGisPro thì sao khi tạo môi trường bạn sẽ thấy sẽ có môi trường được tạo ở trong phần "Package Manager"

  <img src="images/1.png" alt="1" width="400"/>

  <img src="images/5.png" alt="5" width="800"/>

  > Bạn chỉ cần active môi trường này lên để sử dụng là được

- Trường hợp bạn sử dụng phiên bản conda cài đặt trên máy tính của mình thì bạn cần tìm được đường dẫn chứa môi trường bạn vừa tạo ở trên. Nó sẽ nằm trong folder "envs"

  > Để thực hiện import một môi trường ngoài vào ArcGisPro. Bạn thực hiện lần lượt các bước 1 -> 2

  <img src="images/2.png" alt="2" width="800"/>

  > Sau khi import xong thì sẽ tồn tại môi trường và bạn chỉ cần active môi trường này lên. Giống bước trên

### Bước 2: Thêm mới `Toolbox` trong ArcGisPro

- Sau khi cài đặt môi trường để chạy được môi trường thành công

- Để thêm `Toolbox`, click chuột phải và chọn `Add Toolbox`

  <img src="images/3.png" alt="3" width="800"/>

- Sau đó chọn `DA Tools.pyt` để import 

  <img src="images/4.png" alt="4" width="800"/>

### Bước 3: Sử dụng `Toolbox` trong ArcGisPro

- Sau khi thêm được Toolbox thành công, để sử dụng bạn chuột phải vào `DA Predict Tool` chọn `Open` để bắt đầu

  <img src="images/6.png" alt="6" width="400"/>

- Các tham số đầu vào cho Tool

  <img src="images/7.png" alt="7" width="400"/>

  > Bước 1: Chọn `model` để predict

  > Bước 2: Chọn đường dẫn đến file ảnh cần predict

  > Bước 3: Chọn nơi lưu trữ đầu ra

  > Bước 4: Sau khi cấu hình, chọn `Run` để chạy `Tool`

- Sau khi hoàn thành tiến trình, kết quả sẽ được hiển thị lên giao diện map hiện tại

  <img src="images/8.png" alt="8" width="1200"/>