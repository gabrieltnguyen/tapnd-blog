---
# Title show in socical post share
title: "Hello World"
date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["about-me"]
author: "TapND"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
# Description also display in the post share
description: "Đây là bài post đầu tiên của tôi và tôi rất vui khi được chia sẻ với các bạn. Trong bài post này, tôi sẽ giới thiệu về câu lệnh 'Hello world' - một trong những câu lệnh đầu tiên mà mọi lập trình viên đều biết và tôi cũng sẽ lưu lại những cú pháp mà tôi sẽ sử dụng trong trang blog của mình."
canonicalURL: "https://tapnd.com/blog/first-post"
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true # false neu muon show het h1 h2 h3 h4
summary: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book."
cover:
    image: "cover.png" # image path/url
    alt: "First post alt text" # alt text
    caption: "First post caption" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/gabrielacme/tapnd-home/content/postes/first-post"
    Text: "Suggest Changes" # edit text
    appendFilePath: false # to append file path to Edit link
---
Đây là bài post đầu tiên của tôi và tôi rất vui khi được chia sẻ với các bạn. Trong bài post này, tôi sẽ giới thiệu về câu lệnh "Hello world" - một trong những câu lệnh đầu tiên mà mọi lập trình viên đều biết và tôi cũng sẽ lưu lại những cú pháp mà tôi sẽ sử dụng trong trang blog của mình.

## Câu lệnh "Hello World"

Câu lệnh "Hello world" là một trong những câu lệnh đầu tiên mà mọi lập trình viên đều biết và sử dụng. Câu lệnh này được sử dụng để in ra dòng chữ "Hello world" trên màn hình. Với ngôn ngữ lập trình Python, câu lệnh "Hello world" rất đơn giản và có thể được viết như sau:

```
print("Hello world")

```

Câu lệnh này sẽ in ra dòng chữ "Hello world" trên màn hình.

## Cú pháp trong trang blog của tôi

Trang blog của tôi sử dụng ngôn ngữ đánh dấu Markdown để định dạng nội dung. Đây là một ngôn ngữ đơn giản và rất phổ biến trong cộng đồng lập trình viên. Một số cú pháp mà tôi sẽ sử dụng trong trang blog của mình như sau:

- Để tạo tiêu đề, tôi sử dụng ký tự #.
- Để tạo đoạn văn bản mới, tôi sử dụng ký tự xuống dòng.
- Để tạo in đậm, tôi sử dụng ký tự * hoặc **.
- Để tạo in nghiêng, tôi sử dụng ký tự *.

## Kết luận

Như vậy, đó là bài post đầu tiên của tôi về câu lệnh "Hello world" và những cú pháp đơn giản mà tôi sẽ sử dụng trong trang blog của mình. Cảm ơn các bạn đã đọc và hẹn gặp lại ở các bài post tiếp theo!

{{< figure align=center src="cover.png" >}}
*Picture center*

![Picture Here](cover.png "Cover picture")
*Picture left*

## Header 2

### Header 3

#### Header 4

> Text one

`code simple`

```html
<!DOCTYPE html>
<html>
<body>

<h2>Use JavaScript to Change Text</h2>
<p>This example writes "Hello JavaScript!" into an HTML element with id="demo":</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script> 

</body>
</html>
```

```php
<?php

// Show all information, defaults to INFO_ALL
phpinfo();

// Show just the module information.
// phpinfo(8) yields identical results.
phpinfo(INFO_MODULES);
?>
```

```sql
-- Reference: customer_city (table: customer)
ALTER TABLE customer ADD CONSTRAINT customer_city
    FOREIGN KEY (city_id)
    REFERENCES city (id);
-- insert values
INSERT INTO call_outcome (outcome_text) VALUES ('call started');
INSERT INTO call_outcome (outcome_text) VALUES ('finished - successfully');
INSERT INTO call_outcome (outcome_text) VALUES ('finished - unsuccessfully');
```

{{< youtube adLGHcj_fmA >}}
