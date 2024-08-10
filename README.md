# NER_BERT_VN

## Introduction
Dự án này thử nghiệm các mô hình BERT xây dựng mô hình cho tác vụ nhận diện thực thể (NER)

## Data
Data có dạng:
| Word  | POS | Chunk | NER  |
|-------|-----|-------|------|
| Dương | Np  | B-NP  | B-PER|
| là    | V   | B-VP  | O    |
| một   | M   | B-NP  | O    |
| chủ   | N   | B-NP  | O    |
| cửa   | N   | B-NP  | O    |
| hàng  | N   | I-NP  | O    |
| lâu   | A   | B-AP  | O    |
| năm   | N   | B-NP  | O    |
| ở     | E   | B-PP  | O    |
| Hà    | Np  | B-NP  | B-LOC|
| Nội   | Np  | I-NP  | I-LOC|
| .     | CH  | O     | O    |
