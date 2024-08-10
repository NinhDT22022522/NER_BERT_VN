# NER_BERT_VN

## Introduction
Dự án này thử nghiệm các mô hình BERT xây dựng mô hình cho tác vụ nhận diện thực thể (NER)

Dự án sử dụng Kaggle notebook để thực hiện

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

## Model

Bạn có thể thử nghiệm các mô hình sau khi tôi huấn luyện:
1. PhoBERT: DrRinS/NER-PhoBERT
2. PhoBERTv2: DrRinS/NER-PhoBERTv2
3. Multilingual BERT: DrRinS/NER_MultilingualBERT