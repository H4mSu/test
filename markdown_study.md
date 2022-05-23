# 마크다운 문법 정리

 ## 헤더 사용
 # H1
 ## H2
 ### H3
 #### H4
 ##### H5
 ###### H6
 ####### H7은 없음
 ```
 # H1
 ## H2
 ### H3
 #### H4
 ##### H5
 ###### H6
 ####### H7은 없음
 ```
 <hr>

 ## 목록 사용
 ### 순서가 있는 목록 사용
 예시)
 1. 첫번째
 1. 두번째
 1. 세번째<Br>

 코드 
```
1. 첫번째
1. 두번째
1. 세번째 
 ```
앞에 숫자와 상관없이 내림차순으로 정리가 된다.

### 순서가 없는 목록 사용
예시)
* 빨강
    * 녹색
        * 파랑

+ 빨강
    + 녹색
        + 파랑
-  빨강
    - 녹색
        - 파랑

* 빨강
    + 녹색
        - 파랑

```
* 빨강
    * 녹색
        * 파랑

+ 빨강
    + 녹색
        + 파랑
-  빨강
    - 녹색
        - 파랑

* 빨강
    + 녹색
        - 파랑
```
혼합해서 사용하는 것도 가능하다.
## 강조 
*이텔릭체*<Br>
_밑줄 사용_<br>
**굵게 하는법**<br>
__밑줄 과 굵게__<br>
~~취소선~~

```
*이텔릭체*
_밑줄 사용_
**굵게 하는법**
__밑줄 과 굵게__
~~취소선~~
```
문장 중간에 사용 할 경우 **띄어쓰기** 를 하는 것이 좋다<br>
```문장 중간에 사용 할 경우 **띄어쓰기** 를 하는 것이 좋다```
## 인용구사용
```
인용구사용은 ```~~ ```입니다.
```
```한줄에 사용도 가능하다```


## 테이블 사용
이름|나이|학교
--|--|--|
방준하| 24 |계명대 |
```
이름|나이|학교
--|--|--|
방준하| 24 |계명대 |
```

## 들여쓰기
    - 탭은 한번만 누를것
        - 두번누르면 안되는듯? -> 가능
        - 하이폰 스페이스바 생활화 할것

## html 한번에 나오는 커맨드
```
! + tab 사용하면 head, body 가 바로 나온다
```

##  이미지 업로드
![이미지 이름](https://mblogthumb-phinf.pstatic.net/MjAxODAzMjZfMTU3/MDAxNTIyMDQ5NTgwMDMy.GwbG30bbo5Ie7Ph6hdqzqFmZgnJIHvOT3PwmylbISvcg.AsqC0vlRZTILTYZVkQEh_jV7aOIw-BIA7ngrKJFI1Lkg.PNG.canonkoreacamera/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C-1.png?type=w800)<br><br>

<img src = "https://mblogthumb-phinf.pstatic.net/MjAxODAzMjZfMTU3/MDAxNTIyMDQ5NTgwMDMy.GwbG30bbo5Ie7Ph6hdqzqFmZgnJIHvOT3PwmylbISvcg.AsqC0vlRZTILTYZVkQEh_jV7aOIw-BIA7ngrKJFI1Lkg.PNG.canonkoreacamera/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C-1.png?type=w800"  width="100px" height="100px"/>

```
![이미지 이름](링크 주소) width="픽셀크기", height="픽셀크기"로 줄일수도 있다.
```
## 이미지 정렬
<p align = "center">
<img src = "https://mblogthumb-phinf.pstatic.net/MjAxODAzMjZfMTU3/MDAxNTIyMDQ5NTgwMDMy.GwbG30bbo5Ie7Ph6hdqzqFmZgnJIHvOT3PwmylbISvcg.AsqC0vlRZTILTYZVkQEh_jV7aOIw-BIA7ngrKJFI1Lkg.PNG.canonkoreacamera/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C-1.png?type=w800"  width="100px" height="100px"/>
</p>

```
<p align="center,right"><img src="image_src"></p>
가운데, 오른쪽 정렬, 왼쪽 정렬은 기본값
```

## 꺽새(>) 활용(블럭 인용)
>한줄평 : ~~~
>> 꺽새 두개를 쓰면 한번더 들어간다
>>> 여러개도 가능하다   

## 링크 
- 참조 링크

Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
```
코드
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
```
- 외부 링크

링크 : [google](https://www.google.com)
```
코드
[google](https://www.google.com)
```

- 자동 연결
일반적인 url 혹은 이메일 주소인 경우 적절한 형식으로 링크를 형성한다.<br>
- 외부링크 : <http://www.naver.com>
- 이메일 링크 : <ginam21@naver.com>

```
코드

- 외부링크 : <http://www.naver.com>
- 이메일 링크 : <ginam21@naver.com>
```

## 기타)html 한번에 나오는 커맨드
```
! + tab 사용하면 head, body 가 바로 나온다
```

## 중복으로 추가할때 
li.클래스네임*갯수
