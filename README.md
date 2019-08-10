# Markdown

## 1. Cách thức hoạt động của gitub
----
> Markdown là ngôn ngữ đánh dấu văn bản được tạo ra bởi John Gruber, sử dụng cú pháp khá đơn giản và dễ hiểu, dễ nhớ. Nếu nắm vững các cú pháp của Markdown bạn có thể trình bày bài viết của mình một cách mạch lạc, ấn tượng mà không mất nhiều thời gian.

> - Markdown thường dùng để định dạng email, viết các bài đăng trên diễn đàn, tự tạo nên các danh sách việc làm, viết wiki cá nhân ...

## 2. Các cú pháp thường gặp
----
### Tiêu Đề

 - Tương tự như thẻ h1 tới h6 của html
 
 > ```#h1```
 
 > ```##h2```
 
 > ```###h3```
 
 > ```####h4```
 
 > ```#####h5```
 
 > ```######h6```

![Heading](https://i.stack.imgur.com/5f2uf.jpg)

----

### Nhấn mạnh

 - kẹp một từ ở đầu và cuối bằng 1 ký tự `*` để in nghiêng, 2 ký tự `**` để bôi đậm, và 3 ký tự `***` để vừa in nghiêng vừa bôi đậm.in

`*in nghiêng*`

`**Bôi đậm  **`

`***vừa in nghiêng vừa bôi đậm***`

---

> *in nghiêng*

> **Bôi đậm**

> ***vừa in nghiêng vừa bôi đậm***

----

### Inline code

- Sử dụng cặp nháy ngược

``` `inline code` ```


> ```inline code```

---

### highlight block code

- Sử dụng 3 dấu nháy ngược

` ```echo "anything";``` `

> ```echo "anything";```

----

### Link, Image

- Chèn link và chèn ảnh
 - Chèn link

 `[title](http://~)`
 - Chèn ảnh

 `![alt](http://~)`

![markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

----

### List

* Viết ký tự `*` ở đầu dòng để bắt đầu cho list

`*List1`

`*List2`

`*List3`

> * List1

> * List2

> * List3

---

### Horizonal rules

* Sử dụng `***` để tạo Horizonal rules

`***`

Horizonal rules

---

### Blockquotes

* Sử dụng `>` để tạo Blockquotes

`> Blockquotes`

> Blockquotes

---

### Escape markdown

* Sử dụng ký tự `\` để phân biệt ký tự thường với ký tự markdown

`\*text*`

> \*text*

---

### Tạo bảng

* Sử dụng dấu `|` để tạo bảng.

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
```

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
