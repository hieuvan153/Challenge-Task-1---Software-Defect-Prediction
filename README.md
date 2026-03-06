# Challenge-Task-1---Software-Defect-Prediction
Challenge task 1 of ISE Lab
Software Defect Prediction: Dự đoán lỗi phần mềm  
Là 1 task nhỏ trong SE, input là các dự án bao gồm source code repo, output: dự đoán lỗi có thể có ở các level khác nhau: function, method. 

Bài toán này hiện có 2 cách tiếp cận: 

- Chỉ dựa trên độ phức tạp mã nguồn (software metrics) 

- Dựa trên cả độ phức tạp mã nguồn + source code 

Phân loại theo scope: 

- Dự đoán trong 1 project: Dùng 1 version của source code để train, 1 version tiếp theo của source code để test của chính project đó. Benefit: thông thướng 2 version liên tiếp nhau thì sẽ có một số phần code chung, và các code change. Người ta dựa trên version trước đó để dự đoán lỗi version hiện tại thì rất hợp lý

- Dự đoán chéo project: Dùng 1 project A để train và test trên project B  
