# 013 - Công cụ Magic Wand, Quick Selection, Feather và Anti-Alias  

### Magic Wand Tool (W)
* click vào 1 điểm nó sẽ tạo 1 vùng chọn dựa trên tính toán vùng chọn có màu giống điềm ảnh mình chọn.  
	![Imgur](https://i.imgur.com/htIk49N.png)    
* trị số Tolerance thể hiện phạm vi lấy rộng hay hẹp (mặc định là 32)  
	![Imgur](https://i.imgur.com/5TSkPgc.png)  
* chỉ có 1 phạm vi màu giống với điểm ảnh của ta chọn được chọn vì nó bị ngăn cách bởi các ranh giới màu khác để cộng thêm vùng chọn ta giữ phím shift để chọn thêm.  
	![Imgur](https://i.imgur.com/goFv32Y.png)  

* để chọn hết các vùng chọn có phạm vi màu giống với điểm ảnh mà ta đã chọn mà không cần mất công ấn giữ shift và chọn nhiều lần, ta tích bỏ thuộc tính Contiguous đi và chỉ cần ấn chọn là nó sẽ chọn tất cả các vùng có màu đó.  

	![Imgur](https://i.imgur.com/xquhd0X.png)  

	![Imgur](https://i.imgur.com/BJcSQze.png)    

* Khi đang chọn được vào background thì ta chỉ thao tác được những gì trên vùng chọn đó (như tô màu,dịch chuyển, xóa...) nếu muốn chuyển vùng chọn về những vùng chọn chưa được chọn ta dùng nghịch chuyển vùng chọn (ctrt + shift + i)  (nên để chọn 1 vùng chọn gián tiếp ta có thể chọn vào background rồi nghịch chuyển lại).
	![Imgur](https://i.imgur.com/VA0cKaA.png)  
	
### Quick Selection Tool (W)

* tạo vùng chọn bằng cách vẽ rê lên hình ảnh chọn nó sẽ tạo vùng chọn theo các vùng ta vừa vẽ lên (do các vùng chọn được photoshop tự tính toán nên sẽ có sai xót nên ta có thể giữ phím alt để trừ vùng chọn sai đi).  
	
	![Imgur](https://i.imgur.com/7n3ZtAz.png)    

* dùng phím tắt "[" hoặc "]" để phóng to thu nhỏ nét vẽ, Hoặc dùng ctrl + alt kết hợp với click phải chuột rê qua phải để tăng nét vẽ, rê qua trái để giảm (tăng giảm size nét cọ) còn rê lên xuống để tăng giảm độ mờ nhòe (Hardness) của nét cọ.

	![Imgur](https://i.imgur.com/CbJ0zIm.png)  
* click vào option Auto-Enhance thì khi rê chuột tạo vùng chọn thì Photoshop sẽ tự động chỉnh lại đường nét cho nó vô đúng với vùng chọn vừa vẽ ra, sẽ đẹp hơn.

	![Imgur](https://i.imgur.com/FXd1tCw.png)  

###  Feather và Anti-Alias

![Imgur](https://i.imgur.com/Ici0PP6.png)   

phím tắt tô màu nhanh vào vùng chọn:   
Alt + delete: tô màu của Foreground color lên cho vùng chọn.  
ctrl + delete: tô màu của Background color lên cho vùng chọn

![Imgur](https://i.imgur.com/ef59xAP.png)    

* khi normal (click bỏ Anti-alias và feather = 0px): Biên vùng chọn sẽ có dạng răng cưa.  
 
	![Imgur](https://i.imgur.com/hoXVKby.png)  

* Khi click vào Anti-alias (feather = 0px): Biên vùng chọn sẽ có nét mượt viền hơi bị blur một chút.

	![Imgur](https://i.imgur.com/eETPNl0.png)  

* Khi tăng feather lên (có tích anti-alias, feather = 30px): biên vùng chọn bị nhòe (làm nhòe đường biên) (từ đường kiến bò nhòe ra ngoài 30px, nhòe vào trong 30px, Nên khi nhập feather là 30px ta sẽ có tổng cộng 60px mờ) độ mờ này càng cao hình sẽ càng bị nhòe

	![Imgur](https://i.imgur.com/6Ds59Pj.png)   

	* với thông số feather trên thanh option bắt buộc phải nhập trước khi vẽ vùng chọn nếu vẽ xong mới chọn feather thì sẽ không nhận.
	* Còn nếu đã vẽ vùng chọn mà quên tạo feather thì ta vào Feather selection (shift + f6) để đặt lại nó mới nhận.  
	![Imgur](https://i.imgur.com/wGrvYSE.png)    
	![Imgur](https://i.imgur.com/3ORJjGh.png)  
	* Cách nhanh nhất ta click chuột phải vào vùng chọn rồi chọn Feather selection thì nó cũng ra tương tự khi ta truy cập vào thanh select.  
	![Imgur](https://i.imgur.com/QXcdg1d.png)  


* Chúng ta có thể save vùng chọn lại để dùng lại bằng cách vào select để save, save rồi có thể bỏ vùng chọn, nếu cần lấy lại thì vào select để load vùng chọn ra, select được lưu này sẽ có mặt ở trong bảng channels. Nếu lưu file là psd thì cái channel này sẽ được lưu trữ lại dùng cho lần sau mở lên, còn nếu file lưu là jpeg, png,... thì sẽ không lưu chữ được channel này.

![Imgur](https://i.imgur.com/6v7bPKd.png)    

![Imgur](https://i.imgur.com/0WX8Jtf.png)  

![Imgur](https://i.imgur.com/DX2DKhI.png)    

![Imgur](https://i.imgur.com/9qEYg87.png)  

![Imgur](https://i.imgur.com/qNA1nae.png)  