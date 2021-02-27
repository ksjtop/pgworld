**개행 : 문장 맨 끝에서 스페이스 두번 누르면 줄바뀜.  
**띄어쓰기 : `&nbsp;` 를 넣어주면 그 수 만큼 띄어쓰기

#
**0.&nbsp;제목 (Header)**
==============
# 테스트 1
## 테스트 2
--------------
### 테스트 3
--------------
#### 테스트 4
--------------  
#  
# 
#    
**1.&nbsp;목록 (List)**  
==========================
1. 순서가 필요한 목록
2. 순서가 필요한 목록  
   - 순서가 필요하지 않은 목록(서브)  
   - 순서가 필요하지 않은 목록(서브)

3. 순서가 필요한 목록
   1. 순서가 필요한 목록(서브)
   2. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록  
   - 순서가 필요하지 않은 목록에 사용 가능한 기호
     - 대쉬(hyphen)
     * 별표(asterisks)
     + 더하기(plus sign)

**2.&nbsp;강조**
===========
0)&nbsp; 기본  
PostgreSQL  
1)&nbsp;이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.  
>`이텔릭체 : *PostgreSQL* 혹은 _PostgreSQL_  `  
>결과 : *PostgreSQL* 혹은 _PostgreSQL_  

2)&nbsp;두껍게는 별표(asterisks) 혹은 언더바(underscore)를 사용하세요.  
>`두껍게 : **PostgreSQL**`  
>결과 : **PostgreSQL**

3)&nbsp;이텔릭체와 두껍게를 같이 사용할 수 있습니다.  
>`두꺼운 이텔릭체 : **_PostgreSQL_** `   
>결과 : **_PostgreSQL_**

4)&nbsp;취소선은 물결표시(tilde)를 사용하세요.  
>`취소선 : ~~PostgreSQL~~`  
>결과 : ~~PostgreSQL~~  

5)밑줄은 <u></u>를 사용하세요
>`밑줄 : <u>PostgreSQL</u>`  
>결과 : <u>PostgreSQL</u>


1) 이텔릭체 + 두껍게 + 밑줄  
>`밑줄 : _**<u>PostgreSQL</u>**_`  
>결과 : _**<u>PostgreSQL</u>**_

#
#
#
**3.&nbsp;링크**
================
>`[GOOGLE](https://google.com)`  
결과 : [GOOGLE](https://google.com)  
#
>`[MyGitHub](https://github.com/ksjtop/pgworld)`  
결과 : [MyGitHub](https://github.com/ksjtop/pgworld)
#

#
#
#
**4.&nbsp;이미지(Images)**
===========================
![대체 텍스트(alternative text)를 입력하세요!](http://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요.")


![텍스트](./ccc.PNG)
![텍스트](./\00_락플레이스\98_GitHub\pgworld\image\aaa.PNG)


<img width="550" src="./\00_락플레이스\98_GitHub\pgworld\image\aaa.PNG" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">


<img width="550" src="./\00_락플레이스\98_GitHub\pgworld\aaa.PNG" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">

#
#
#
**5.&nbsp;표(Table)**
===========================
| 값 | 의미 | 기본값 |
|---|:---|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |


#
#
#
**6.&nbsp;인용문(BlockQuote)**
==============================
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

#
#
#
**7.&nbsp;원시 HTML(Raw HTML)**
=================================
<u>마크다운에서 지원하지 않는 기능</u>을 사용할 때 유용하며 대부분 잘 동작합니다.

<img width="150" src="http://www.gstatic.com/webp/gallery/4.jpg" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">

<img width="50" src="https://github.com/ksjtop/pgworld/tree/main/image/aaa.PNG" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">


![텍스트](./\00_락플레이스\98_GitHub\pgworld\image\aaa.PNG)

---
***
___
