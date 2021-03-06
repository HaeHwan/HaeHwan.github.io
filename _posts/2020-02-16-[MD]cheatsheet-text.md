---
title: <i class="fab fa-markdown"> Text and Typography</i>
date: 2020-02-16 17:46:00 +0800
categories: [Markdown, Tutorial]
tags: [github pages, markdown, tutorial]
toc: true
comments: true
seo:
  date_modified: 2020-05-18 16:44:33 +0900
sitemap:
  changefreq: daily
  priority: 1.0
---

본 글에서는 자주 쓰지만, 쉽게 외워지지 않는 마크다운 사용법들을 적어놨습니다. 많은 분들에게 도움이 되면 좋을 것 같습니다.  

## 키보드 표시
+ <kbd>키보드</kbd>에 있는 자판처럼 보이고 싶다면, `<kbd>`를 사용하면 됩니다.  

***

## image
### github에 저장한 이미지 불러오기
![image1](/assets/img/sample/round_avatar.png)
```
![image1](/assets/img/sample/image.png)
```
### image address 활용하기
![재규어](https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Jaguar_%28Panthera_onca_palustris%29_female_Piquiri_River.JPG/375px-Jaguar_%28Panthera_onca_palustris%29_female_Piquiri_River.JPG)
```
![재규어](https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Jaguar_%28Panthera_onca_palustris%29_female_Piquiri_River.JPG/375px-Jaguar_%28Panthera_onca_palustris%29_female_Piquiri_River.JPG)
```

<br>

## Link
링크가 걸릴 부분을 <kbd>[...]</kbd>안에 넣어주고 바로 이어서 이동할 URL 주소를 <kbd>(...)</kbd>안에 넣어주면 됩니다. 
+ 마크다운 설명과 관련하여서는 이곳에서 더 자세히 [사용법](https://hgmin1159.github.io/technique/2020/02/17/post2.html)을 배울 수 있습니다.

```
[사용법](https://hgmin1159.github.io/technique/2020/02/17/post2.html)  
```

### 이미지로 링크 연결하기
이미지 첨부와 링크 연결을 순차적으로 대입하면 됩니다. 아래의 이미지를 클릭하면 저의 깃헙 블로그로 새로고침됩니다.  
[![](/assets/img/sample/round_avatar72.png)](https://haehwan.github.io/)
```
[![image3](/assets/img/sample/round_avatar72.png)](https://haehwan.github.io/)
```

***

## footnote
각주 사용법은 링크와 유사합니다. 각주로 처리할 단어 앞에 caret[^caret]을 넣어주면 됩니다.  

이 때에 한글로 각주를 불러오려고 하면 에러가 나는 경우가 있습니다. 되도록이면 위와 같이 영어로 각주(caret)를 달 것을 추천드립니다.
  
[^caret]: caret의 뜻이 궁금하다면? [**caret**](https://en.wikipedia.org/wiki/Caret)  

```
[^caret]: caret의 뜻이 궁금하다면? [**caret**](https://en.wikipedia.org/wiki/Caret)  
```

### Reverse Footnote
Footnote는 마크다운에서 글을 쓰는 순서와 상관없이 항상 글 가장 마지막에 주석내용이 등장합니다. 각주를 달고 싶은 내용이 생각나면, 바로 밑에 그 내용을 적더라도 알아서 가장 마지막에 해당 내용이 순서대로 나타나기 때문에 글을 편하게 쓸 수 있게 됩니다.  

각주에 해당하는 단어를 똑같이 입력해주고 : 뒤에 내용을 적어주면 됩니다. 이 때 괄호 안에 단어를 영어만 인식하는 경우가 있습니다. 예를 들어 아래에 제가 footnote가 아니라 `[^각주]` 이렇게 하면 뜨지가 않는 경우가 있습니다.
```
[^footnote]: ...
```
> <kbd>:</kbd> 을 빼먹을 때가 많으므로 유의해야합니다.

본 글에서는 각주내용에 링크와 bold체를 추가했습니다.  

```
[^caret]: [**caret**](https://en.wikipedia.org/wiki/Caret)이란?
```

<br>  

***
***
# 각주 및 추천자료

## 각주