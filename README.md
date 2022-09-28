# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

#제목1  : #과 글자를 붙여쓰면 제목스타일이 안된다

# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks) : 띄어쓰기 두번 또는 <br/>
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 살마 대한으로 길이 보전하세

# 강조(Emphasis)
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~ : 물결표시 두번으로 감싸기  
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록 : 숫자 1만 적어주면 자동으로 순서가 생성된다.
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록        
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
(글자)[링크 "타이틀"]  
<a href="https://google.com" title="구글로 이동">GOOGLE</a>  
[GOOGLE](https://google.com "구글로 이동")

# 이미지(Images) : 링크에서 앞에 ! 만 붙여주면 된다.
!(대체텍스트)[이미지경로]  
![HEROPY](https://heropy.blog/css/images/logo.png)

[![대체텍스트](이미지경로)](링크) : 이미지를 클릭하면 링크로 이동
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)


# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 이용문
>>> 중중첩된 이용문 1  
>>> 중중첩된 이용문 2  
>>> 중중첩된 이용문 3

# 인라인(inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조
```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
    .list>li{position:absolute;top:40px;}
```

```javascript
    function func(){
        var a = 'AAA';
        return a;
    }
```

```bash
$ git commit -m 'Study Markdown'
```
여기에서 $ 표시는 터미널에 입력한다는 표시이다. (실제로 입력 X)

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)
position 속성  
값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
- Markdown에서 실제 HTML 문법을 사용하는 것

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
<span style="text-decoration:underline">하느님</span>이 보우하사 우리나라 만세

<a href="https://google.com" target="_blank">GOOGLE</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horisontal Rule)
---
하이픈(-) 기호 3번
***
에스터리스크(*) 기호 3번
___
언더바(_) 기호 3번
