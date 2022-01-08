# CSS

# HTML의 한계
\<font>\</font> 태그<br>
\<font color="색"><br>
```
<font color="red">
  \<font color="red">
  </font><br>
```
정보를 나타내는 태그가 아닌 디자인을 나타내는 태그.<br>
만약, 모든 \<a> 태그가 붙어있는 코드에 대해 color을 변경해야 한다면 일일히 변경을 해주어야 한다.
# CSS의 등장
## \<style> 태그
\<style> 태그 안쪽의 내용은 CSS로 간주한다. HTML과 CSS가 완전히 다른 언어이기 때문에 구분이 필요하다.<br>
  ```
  <head>
<style>
  a {
    color:red;
    text-decoration: none;
  }
</style>
  </head>
  ```
모든 a 태그에 대해 폰트 색깔을 red로 변경<br>
  장식 제거(ex) 밑줄)<br>
  a {} => 선택자<br>
  {} 내부 => 효과, 선언(declaration)
  디자인과 관련된 코드와 본문의 코드를 완벽하게 분리 가능
  # CSS
  모든 태그가 아닌 특정한 부분에 CSS를 적용하고 싶을때<br>
  style 속성을 이용한다
  ```
  <a href="2.html" style="color:red">CSS</a>
  ```
  1. style 태그
  2. style 속성
  
# CSS
선택자 Selector<br>
선언 declaration == 효과
color 속성 property
값 property value
```
a {
  color:red;
}
```
```
color
font-size
text-align
text-decoration
```
class HTML 속성을 지정해서 변경<br>
```
<a href="1.html" class="saw active"></a>
```
선택자는 class명 앞에 .를 붙여서 지정<br>
id 애트리뷰트
id 선택자는 #로시작.
id 선택자 > class 선택자 > 태그 선택자, 마지막에 기술한 것 먼저 적용
id는 단 한번 등장
[css 선택자](https://www.w3schools.com/cssref/css_selectors.asp)

화면 전체를 사용하는 태그 = block level element/ 자신의 크기만 갖는 것 inline element
주석 \/\* \*\/
displaying:inline
displaying:block
