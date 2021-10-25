# 마크다운 
마크다운(markdown)은 일반 텍스트 기반의 경량 마크업 언어다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다. HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다.
***

## 목차
0. [줄바꿈](#0-줄바꿈)
1. [제목](#1-header-제목)
2. [강조](#2-강조)
3. [리스트](#3-리스트)
4. [링크](#4-링크)
5. [인용문](#5-인용문)
6. [이미지 삽입](#6-이미지-삽입)
7. [코드 삽입](#7-코드-삽입)
8. [테이블 만들기](#8-테이블-만들기)
9. [수평선 넣기](#9-수평선-넣기)
10. [참고자료](#10-참고자료)

# 0. 줄바꿈
- `<br>` 사용
- 엔터 두번
## 사용방법
```
엔터 두번을 하면

줄바꿈이 된다.

br을 사용하면<br>
줄바꿈이 된다.
```
## 실행결과
엔터 두번을 하면

줄바꿈이 된다.

br을 사용하면<br>
줄바꿈이 된다.

# 1. HEADER 제목
- `#`으로 시작하는 텍스트
- `#` 1 ~ 6개로 나타냄
- h1은 `===`로 나타낼 수 있다.
- h2는 `---`로 나타낼 수 있다. 
## 사용법
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
h1===
===
h2---
---
```
## 실행결과
# h1
## h2
### h3
#### h4
##### h5
###### h6
h1===
===
h2---
---

# 2. 강조
## 사용방법
```
*기울이기*
_기울이기_
**강조**
__강조__
**_기울이기와 강조를 같이사용_**
~~취소선~~
<u>밑줄</u>
<mark>형광팬</mark>
```
## 실행결과
*기울이기*<br>
_기울이기_<br>
**강조**<br>
__강조__<br>
**_기울이기와 강조를 같이사용_**<br>
~~취소선~~<br>
<u>밑줄</u><br>
<mark>형광팬</mark>

# 3. 리스트
## 사용방법
```
1. 순서있는 목록
2. 출력하는 방법
5. 순서가 달라도 순서대로반영

+ 순서없는 목록 `+`
    + 출력하는 방법
        + hi
* 순서없는 목록 `*`
    * 출력하는 방법
        * hi
- 순서없는 목록 `-`
    - 출력하는 방법
        - hi
+ 순서없는 목록 `+, -, *`
    * 출력하는 방법
        - hi
```
## 실행결과
1. 순서있는 목록
2. 출력하는 방법
5. 순서가 달라도 순서대로반영

+ 순서없는 목록 `+`
    + 출력하는 방법
        + hi
* 순서없는 목록 `*`
    * 출력하는 방법
        * hi
- 순서없는 목록 `-`
    - 출력하는 방법
        - hi
+ 순서없는 목록 `+, -, *`
    * 출력하는 방법
        - hi

# 4. 링크
## 사용방법
```
구글 www.google.com
[Naver](www.naver.com)
[Github](http://www.github.com "깃허브")
email <aaa@aaaa.com>
[1. 제목](#1-제목)
<!-- 내부 연결 링크는 띄어쓰기는 `-`로 연결, 영어는 소문자 -->
[README](../README.md)

```
## 실행결과
구글 www.google.com<br>
[Naver](www.naver.com)<br>
[Github](http://www.github.com "깃허브")<br>
email <aaa@aaaa.com><br>
[1. 제목](#1-header-제목)<br>
[README](../README.md)

# 5. 인용문
## 사용방법
```
As Kanye West said:

> We're living the future so
>> the present is our past.
```
## 실행결과
As Kanye West said:

> We're living the future so
>> the present is our past.


# 6. 이미지 삽입
## 사용방법
```
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
```
## 실행결과
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

# 7. 코드 삽입
## 사용방법

```` 
```
Look! You can see my backticks.
```
~~~
~ 도 가능.
~~~
````

## 실행결과
```
Look! You can see my backticks.
```
~~~
~ 도 가능.
~~~

# 8. 테이블 만들기
## 사용방법
```
생성
헤더1|헤더2|헤더3
---|---|---
셀1|셀2|셀3
셀4|셀5|셀6
셀7|셀8|셀9

정렬
왼쪽정렬|가운데정렬|오른쪽정렬
:---|:---:|---:
셀|셀|셀
셀|셀|셀
셀|셀|셀
```
## 실행결과
생성
헤더1|헤더2|헤더3
---|---|---
셀1|셀2|셀3
셀4|셀5|셀6
셀7|셀8|셀9

정렬
왼쪽정렬|가운데정렬|오른쪽정렬
:---|:---:|---:
셀|셀|셀
셀|셀|셀
셀|셀|셀

# 9. 수평선 넣기
## 사용방법
```
* * *
***
*****
- - -
------------
```
## 실행결과
* * *
***
*****
- - -
------------


# 10. 참고자료
[Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#mentioning-people-and-teams)<br>
[code blocks](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks#syntax-highlighting)<br>
[ 마크다운 마스터하기](https://guides.github.com/features/mastering-markdown/)<br>
<https://daringfireball.net/projects/markdown/><br>
<https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4>
https://bskyvision.com/1140
