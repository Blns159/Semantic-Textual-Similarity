# STSb Multi MT

## Giới thiệu
STS là một dự án nghiên cứu về đo lường độ tương đồng văn bản đa ngôn ngữ. Chúng tôi tập trung vào việc phát triển các phương pháp và mô hình để đo lường sự tương đồng giữa các cặp câu văn bản trong nhiều ngôn ngữ khác nhau.

## Thông tin bộ dữ liệu
Sử dụng
```
from datasets import load_dataset
ds = load_dataset("PhilipMay/stsb_multi_mt", "en")
```

Thông tin trích dẫn
```
@InProceedings{huggingface:dataset:stsb_multi_mt,
title = {Machine translated multilingual STS benchmark dataset.},
author={Philip May},
year={2021},
url={https://github.com/PhilipMay/stsb-multi-mt}
}
```

## Mục tiêu
Sử dụng bộ dữ liệu STSb Multi M với ngôn ngữ tiếng anh.
Nghiên cứu và so sánh các phương pháp đo lường độ tương đồng văn bản.
Hiểu rõ hơn về tính đa dạng của các ngôn ngữ và cách chúng ảnh hưởng đến đo lường độ tương đồng.
Cách sử dụng
Bạn có thể sử dụng bộ dữ liệu này để:

Huấn luyện mô hình học máy để tính toán độ tương đồng văn bản.
Nghiên cứu về xử lý ngôn ngữ tự nhiên đa ngôn ngữ.
Đánh giá hiệu suất của các mô hình trên tập dữ liệu STSb Multi MT.
## Cài đặt
Clone kho lưu trữ:
```
git clone https://github.com/Blns159/Semantic-Textual-Similarity.git
```

Cài đặt các thư viện cần thiết:
```
pip install -r requirements.txt
```
