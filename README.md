# Hướng dẫn sử dụng

## Giới thiệu 
Nội dung của repo gồm các file latex dùng để viết báo cáo Luận văn Tốt nghiệp trong trường Đại học Bách Khoa, Đại học Quốc gia thành phố Hồ Chí Minh.
Gồm các file: 
- Thư mục `images`: chứa các file ảnh sẽ có trong báo cáo.
- Thư mục `sections`: chứa các phần sẽ có trong một báo cáo: 
    - File .tex từ `c1` đến `c7`: file chứa dàn bài cho các chương trong báo cáo.
    - `chapter_summary.tex`: chương "Tóm tắt chương".
    - `guarantee.tex`: chương "Lời cam đoan".
    - `summary.tex`: chương "Tóm tắt đề tài".
    - `thanks.tex`: chương "Lời cảm ơn".
    - `title_page.tex`: trang đầu tiên của báo cáo.
- `main.tex` : file chính chưa mọi config của báo cáo.
- `references.bib`: file chứa thông tin về tài liệu tham khảo.

Các config đã được thiết lập sẵn, chỉ cần viết nội dung vào các phần đã chú thích. Nếu bạn mong muốn viết nội dung của báo cáo, hướng dẫn sử dụng phía dưới sẽ phù hợp với bạn.
## Cách sử dụng đoạn code latex
Tải đoạn code này lên [Overleaf](https://www.overleaf.com/) và sử dụng
## Cách viết báo cáo
### Trang đầu tiên của báo cáo (`title_page.tex`)
- Chỉnh sửa khoa phù hợp.
- Thay thế chữ "TIÊU ĐỀ" bằng tên đề tài của nhóm bạn trong câu lệnh `\textbf{TIÊU ĐỀ}`
- Thay đổi ngành học của mình
- Điền các thông tin về tên của Hội đồng, GVHD, GVPB, danh sách các thành viên trong nhóm.
- Thay đổi thông tin ngày tháng nộp luận văn trong `\large{TP. HỒ CHÍ MINH, THÁNG }`
### Cách thêm hình ảnh
Hình được được thêm vào bằng câu lệnh: 

<pre><code>
\begin{figure}[H]
    \centering
    \includegraphics[width=0.3\textwidth,frame]{images/landing_page.png}
    \caption{Giao diện}
    \label{fig:mobile_introduction}
\end{figure}</code></pre>

Trong đó:
- `includegraphics`: câu lệnh để thêm hình ảnh vào báo cáo, với đường dẫn nằm trong dấu ngoặc nhọn. Các option tự chọn có thể sử dụng là:
    - `with`: chiều rộng của hình ảnh
    - `frame`: thêm khung cho hình ảnh
- `caption`: Mô tả hình ảnh. Mô tả này sẽ được tự động thêm vào phần "Danh mục hình ảnh"
- `label`: dùng trong việc tham khảo đến hình ảnh. Đối với một tấm hình, phần tham khảo sẽ theo định dạng là **fig:<*Tên tham khảo viết liền*>**
### Cách thêm bảng
#### Bảng nằm trong một trang
#### Bảng dài qua nhiều trang
### Cách thêm tài liệu tham khảo

## Thông tin liên hệ
Nếu có thắc mắc về source code này, bạn có thể liên hệ qua email: trung.nguyen.trong2855@gmail.com
