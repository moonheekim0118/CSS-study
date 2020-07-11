# CSS box-sizing 
- 박스의 크기를 화면에 표시하는 방식을 변경하는 속성
- width와 height는 엘리먼트의 컨텐츠의 크기를 지정함. 따라서 테두리가 있는 경우 테두리의 두께로 인해서 원하는 크기를 찾기가 어려움
- box-sizing 속성을 border-box로 지정하면 테두리를 포함한 크기를 지정할 수 있음
- 모든 엘리먼트에 box-sizing을 border-box로 지정하면 간편함 

```css
 *{
      box-sizing: border-box;
  }
```
