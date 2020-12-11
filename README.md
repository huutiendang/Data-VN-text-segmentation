# Data-VN-text-segmentation
* Vietnamese wiki data for text segmentation 
 * [Data](https://drive.google.com/open?id=1AifvA7VKipLsYLfcAkit8QNtOzvD-JUB)
 * [PDF](https://huutiendang.github.io/files/Textseg.pdf)
# Data construction 
  * number of docs : 66050
  * train = 39584 ratio 0.6
  * dev  =  13253 ratio 0.2
  * test =  13213 ratio 0.2
  * number of sentence = 6520892
  * avg len sentence = 22.18
# Data anotation 
  * Each document contains several segments. There is a line between two segments starts with “========”, which denotes the point of changing topic. That line also contains the index of the segment and name of the topic refered from Wikipedia.
  * example 
    *  ========,1,preface.
      * USS "Colhoun" (DD-85/APD-2) là một tàu khu trục thuộc lớp "Wickes" của Hải quân Hoa Kỳ trong giai đoạn Chiến tranh Thế giới thứ nhất, và tiếp tục phục vụ như một tàu vận chuyển cao tốc với ký hiệu lườn APD-2 trong Chiến tranh Thế giới thứ hai.
Nó là chiếc tàu chiến đầu tiên của Hải quân Hoa Kỳ được đặt tên theo Chuẩn đô đốc Edmund Colhoun.
    * ========,2,Thiết kế và chế tạo.
     * "Colhoun" được đặt lườn tại xưởng đóng tàu của hãng Fore River Shipbuilding Company ở Quincy, Massachusetts vào ngày 19 tháng 9 năm 1917.
Nó được hạ thủy vào ngày 21 tháng 2 năm 1918; được đỡ đầu bởi cô A. Colhoun, được đưa ra hoạt động vào ngày 13 tháng 6 năm 1918 dưới quyền chỉ huy của hạm trưởng, Trung tá Hải quân B. Wygant, và trình diện để hoạt động cùng Hạm đội Đại Tây Dương Hoa Kỳ.
