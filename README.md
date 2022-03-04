# 제목 (Header)

# 제목 1
## 제목 2
### 제목 3
<!-- #개수만큼 h1~h6 태그와 동일하게 동작 -->

# 문장(Paragraph)
줄바꿈을
했는데

# 줄바꿈(Line Break)
줄바꿈을  
두 번
<!-- 2번 띄어쓰기하고 엔터 누르거나 <br> 태그를 사용하면 된다 -->

# 강조(Emphasis)
_이탤릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
_**이텔릭 + 두껍게**_  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)
1. 순서가 필요한 목록
2. 순서가
      1. 어어어어 
      <!-- 2. 들여쓰기를 2번 해야 정상 작동 -->
3. 필요한데요

- 순서가 필요하지 않은 목록
- 하하
- ㅏ하하하
- ㅁㄴㅇ

# 링크
[google](google.com "구글로 이동!")

# 이미지
![HEROPY](https://heropy.blog/css/images/logo.png)
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)

# 인용문
> 인용문은 문장 앞에 '> '를 넣으면 된다.
> > 중첩도 할 수 있다.

# 인라인 코드 강조
코드에 해당하는 것만 `앞뒤`에 백틱 (`)을 넣거나 블록 한 다음 백틱을 누르면 된다.

# 블록 코드 강조
```html
<u>코드</u> 
```

```plaintext
그냥 쓰고 싶은 말도 코드처럼 강조 가능
```

# 표

값 | 의미 | 기본값
--|:--:|--
static | 기준 없음 | O
relative

각 열을 구분할 때는 |(shift+\)를 이용하고  
머리와 몸통 구분 시에는 -- | -- 을 사용한다.
가운데 정렬은 머리/몸통 구분하는 항목 앞뒤에 :, 오른쪽 정렬은 오른쪽에만 : 삽입


# 원시 HTML
마크다운 안에서 실제 HTML을 사용하는 것  
ex) 이미지에 width 속성을 설정해야 하는데 마크다운 문법으로는 할 수 없기 때문에, html에서 이용하는 img 태그를 그대로 사용하는 것

# 수평선
--- 혹은 *** 혹은 ___  

---
***
___

