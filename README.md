# **Markdown là gì?**

``` Markdown là ngôn ngữ đánh dấu văn bản được tạo ra bởi John Gruber. Markdown sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản và văn bản được viết bằng Markdown sẽ có thể được chuyển đổi sang HTML. Ngược lại các văn bản được viết bằng HTML cũng có thể được chuyển đổi sang Markdown. ``` 

# **Các cú pháp thường gặp** 

###*Ngoài ra còn rất nhiều cú pháp khác* 

####**1. Thẻ tiêu đề (headers)**

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề (có thể dùng từ 1 kí tự # đến 6 kí tự ######) 

Ví dụ: 
#Tiêu đề cấp 1
##Tiêu đề cấp 2
###Tiêu đề cấp 3
####Tiêu đề cấp 4
#####Tiêu đề cấp 5
######Tiêu đề cấp 6 


####**2. Chèn link, ảnh**

- Để chèn hyoerlink bạn chỉ cần dán link đó vào file .md

"https://github.com/blackdot88.md" 
KQ: https://github.com/blackdot88 


- Hoặc cũng có thể rút ngắn với cú pháp sau:

"[blackdot88](https://github.com/hellsins)"
KQ: [blackdot88](https://github.com/hellsins) 

- Để chèn ảnh bạn có thể chèn trực tiếp hoặc qua link:

< img src="link_anh" >

<img src="http://65.media.tumblr.com/tumblr_m70kuclAea1rsskhm.gif" >

Hình ảnh bạn có thể lấy bất cứ đâu trên internet, có thể bạn up lên để lấy link

- Bạn cũng có thể chèn ảnh như sau:
 
 ![chú_thích] (/đường_dẫn ) 

<img src="https://i.ytimg.com/vi/m0Xb9BhfVjY/maxresdefault.jpg"> 

###**3. In đậm, In nghiêng**
- Để in đậm một đoạn text bạn sử dụng cú pháp:
"**Từ cần in đậm**" hoặc:" __Từ cần in đậm__" 
KQ: **Từ cần in đậm** 

- Để in nghiêng một đoạn text bạn sử dụng cú pháp: 
"*Từ cần in nghiêng*"
KQ: *Từ cần in nghiêng* 

###**4. Gạch đầu dòng, danh sách**

Để gạch đầu dòng hoặc có thể như 1 danh sách bạn có thể dùng: 
- Gạch đầu dòng thứ nhất 
<ul> <li> Thụt đầu dòng thứ 1.1
</li> <li> Thụt đầu dòng thứ 1.2
- Gạch đầu dòng thứ hai 
<ul> <li> Thụt đầu dòng thứ 2.1
</li> <li> Thụt đầu dòng thứ 2.2
 
hoặc có thể dùng Enter và Tab để tạo như sau:
- Gạch đầu dòng thứ nhất 
- Thụt đầu dòng thứ 1.1
- Thụt đầu dòng thứ 1.2 
- Gạch đầu dòng thứ hai 
- Thụt đầu dòng thứ 2.1 
- Thụt đầu dòng thứ 2.2 
Kết quả: Gạch đầu dòng thứ nhất 
Thụt đầu dòng thứ 1.1 
Thụt đầu dòng thứ 1.2 
Gạch đầu dòng thứ hai
Thụt đầu dòng thứ 2.1 
Thụt đầu dòng thứ 2.2 

###**5. Chú thích cuối trang** 

Chú thích[^1], chú thích[^1]:

Chú thích 1 [^1]: 

Chú thích 2 [^2]:


###**6. Chèn code**

print("This is synktax on python 3.5"); 

KQ: ```print("This is synktax on python 3.5");```

###**7. Trích dẫn** 

- Có thể sử dụng cặp dấu "" hoặc để tạo trích dẫn 

###**Cài đặt Sublime Text và tìm kiếm, cài đặt các công cụ hỗ trợ Markdown (export HTML, markdown preview,...):**

http://www.sublimetextcom/3
