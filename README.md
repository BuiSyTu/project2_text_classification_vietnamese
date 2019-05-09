# Vietnamese-Text-Classification
Vietnamese Text Classification

## Chương trình phân loại 
- Chạy chương trình phân loại 1 văn bản bất kì (model đã tồn tại trong train_model): 
```
python classification_file.py -i <filename document>
```
- Chạy chương trình phân loại 1 đoạn văn bản bất kì từ terminal:
```
python classification_text.py --text "text document"
```
------
## Build lại chương trình 

- Tạo thư mục dataset và features : 
```
./mkdir.sh
```
#### Xây dựng dữ liệu & Tiền xử lý
```
python preProcessData.py
```
- Dữ liệu tiền xử lý và lưu trong thư mục  processsed_data 
- Trích chọn đặc trưng đưa vào thư mục feature_extraction

### Chạy chương trình train : 
```
python main.py
```
- File model lưu trong thư mục trained_model
### Dữ liệu được lấy từ link:
```
https://github.com/duyvuleo/VNTC/tree/master/Data/10Topics/Ver1.1
```