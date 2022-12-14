# 제목 (Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물고 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록 (두번 들여쓰기)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Link)

<a href="https://www.google.com">GOOGLE</a>

[GOOGLE](https://www.google.com)

<a href="https://www.google.com" title="구글로 이동!">GOOGLE</a>

[GOOGLE](https://www.google.com "구글로 이동!")

<a href="https://www.google.com" title="구글로 이동!" target="_blank">GOOGLE</a>

# 이미지(Image)
![]()
![HEROPY](https://heropy.blog/css/images/logo.png)

[![GOOGLE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://www.google.com)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2

# 인라인(inLine) 코드 강조

CSS에서 `background` 혹은 `background-image` (한번에 드래그해서 백틱기호 누르면 한번에 됨)  
속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.com"  target="_blank">GOOGLE</a>
```

```css
.list {
  position: relative;
  top: 40px;
}
```

```javascript
function () {
  var a ='aaa';
  return a;
}
```

```bash
$ git commit -m '마크다운 공부'
```

```plaintext
동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--: 
static | 기준없음 | 0
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://www.google.com"  target="_blank">GOOGLE</a>
___
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___