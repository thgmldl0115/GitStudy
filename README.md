"Hello Git!" 

# Markdown 이란?
markdown은 텍스트를 서식 있는 문서로 쉽게 변환할 수 있는 마크업 언어. 2004년에 개발 되었으며, 문서를 작성하는데 사용되는 간단한 형식으로, HTML로 변환하기 쉽게 설계되었다.
markdown의 주 목적은 사람들이 읽기 쉽고 쓰기 쉬운 서식 문서를 만드는 것.

# 마크업 언어란?
마크업 언어는 텍스트에 태그를 사용하여 문서의 구조와 서식을 정의하는 언어.
컴퓨터가 텍스트를 처리하는 데 도움이 되며, 문서를 체계적으로 작성하고 읽을 수 있도록 함.
마크업 언어의 예로는 HTML, XML... 등이 있음.

# HTML 이란?
웹 페이지를 작성하는데 사용되는 표준 마크업 언어.
웹 페이지의 구조를 정의하며, 텍스트, 이미지, 링크, 표, 폼 등을 웹 브라우저에서 표시할 수 있도록 함.


1.**헤더(Headers)** :
```
   백틱(`) <-- 3개 코드라인 markdown
   문법이 적용안됨.
   # 헤더1
   ## 헤더2
   ### 헤더3
```
## 헤더2
### 헤더3


2.굵게
``` **굵게** ```

**굵게**


3.기울임
``` *기울임* ```
*기울임*


4.목록
#### 순서가 있는
```
1. 첫 번째
2. 두 반째
```
#### 순서가 없는
```
- 첫 번째
- 두 번째
```
- 첫 번째
- 두 번째


5.링크
```
   [링크 텍스트](https://naver.com)
```
[네이버로 가기](https://naver.com)


6.이미지
```
 ![이미지 설명](http:~)
```
![포스터](https://)

![사진](https://s.pstatic.net/dthumb.phinf/?src=%22http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDA3MjJfNDkg%2FMDAxNzIxNjUyNTc1NjA1.sMM6Fj67Y9Jt4e2xJ5Wp8JBqlQdstiNHzgIkjse9r7cg.2SscZOdcTrWOCjWbOh56g5f7Gal2DcYLwDjkLU-U4tAg.JPEG%2Foutput_243443898.jpg%22&amp;type=nf308_200&amp;service=navermain)


7.인용구

```
   > 이것은 인용구입니다.
   >> 중첩된 인용구입니다.
```
> 이것은 인용구 입니다.
>> 이것은 중첩 인용구 입니다.


8.특정 언어의 코드 블록
``` markdown
    ```python
        print("hello^^")
    ```
```


```python
    print("hello")
```


9.구분선

```---```
---


10.체크박스

``` - [] 할일 - [x] 완료한 일 ```
- [] 할일
- [x] 완료한 일



11.테이블
``` | 제목1 | 제목2 |
    |-------| -----|
    |내용 1 | 내용2 |
```
| 제목1 | 제목2 |
|-------| -----|
|내용 1 | 내용2 |


12.이모지 추가하기

[이모지 검색 및 다운로드](https://emojipedia.org/)

- 오늘의 날씨는? ☔
- 나는 오늘 👧💻 열심히 해서 💯


13.배지 추가

[배지 달기(언어, 기술, 개발 도구, 자격)](https://simpleicons.org)
