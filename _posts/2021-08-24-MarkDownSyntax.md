---
layout: single
title: "마크다운 문법"
---


#마크다운 문법
##(GFM: Github Flavored Markdown)
---

##1. 헤딩
#Heading1
##Heading2
###Heading3
####Heading4
#####Heading5
######Heading6

---
##2. 텍스트 꾸미기
**굵은 글씨**
*이텔릭체*, _Italic?_
~~취소문자~~ (가운데 선 그어짐)
<u>밑줄 긋기</u>

---
##3. 인용문
> In the words of Abraham Lincoln:
> Pardon my French

---
##4. 코드인용 및 코드펜스
####- 원하는 프로그래밍 언어 이름을 backtick 시작 부분에 입력

```javascript
function hello(){
    console.log("hello");
}
```
---
##5. 링크
[Google](https://www.google.com)
[네이버로 접속](https://www.naver.com "마우스를 올려놓으면 말풍선이 나옵니다.") 
<https://www.naver.com>  
[2. 텍스트 꾸미기 이동]("#2.-텍스트-꾸미기")  : 문서 내부 링크로 이동하기

---

##6. 참조링크

[Naver][gg] 링크입니다.

[gg]: https://www.Naver.com

---
##7. 이미지 링크
![keyboard cat](https://media.giphy.com/media/LHZyixOnHwDDy/giphy.gif)

---
##8. 리스트
- 리스트1
- 리스트2
 * 공백 인덴트를 이용해 네스팅
    1. 네스팅1
    2. 네스팅2
- 리스트3
1. 순서 있는 리스트1
2. 순서 있는 리스트2

+ 순서 없는 리스트
 - 리스트1
    * 리스트
        + 리스트
---
##9. 이모지 사용
[Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
:+1:, :a:, :accept:, :baby:, :car:, :kiss:, :kr:

---

##10. 라인 구분선

```
--------
````

---
##11. 표 만들기
|제목1|제목2|
|:---:|---:|
|1234556내용|123123123내용2|
|내용3|내용4|


`:` 위치에 따라서 정렬이 가능하다.

---
##12. Escape

마크 다운 문법 \*강조\* 최소하기

---
마크다운 포스트 문서 작성시 파일 명: 포스트 제목(소문자)-일련번호

[참고 블로그1] https://theorydb.github.io/envops/2019/05/22/envops-blog-how-to-use-md/
<br>
[참고 블로그2]https://tutorialpost.apptilus.com/code/posts/tools/markdown01-syntax/
