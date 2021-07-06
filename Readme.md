# CSS코드 규칙

1. selector 작성(tag 지정) - property 작성(value값 작성)
2. CSS는 위에서부터 아래 순서로 적용되기 때문에 만약 한개의 태그에 다른 밸류값을 지정하면  
가장 마지막에 지정한 value값이 적용된다.
3. block: div, header, section, main, footer, article 등등은 옆에 어떤것도 들어가지 않는다.
4. inline(in the same line)은 같은 줄 옆에 다른 요소가 추가될 수 있다
5. block 이 아닌 것들: span, a, image
6. 어떤 요소를 inline으로 설정할 경우 그 요소는 높이와 너비를 가질 수 없다.


## box의 요소
1. margin : box의 border(경계)의 바깥에 있는 공간이다.
(1) margin 값을 설정할 때 margin: 20px 15px과 같은 경우로 설정할 경우 첫번째 값인 20px은 수직 margin 값을, 두번째 값인 15px은 수평 margin값이다.  
(2) margin 값을 설정할 때 margin: 20px 5px 12px 9px 과 같은 경우로 설정하면 위, 오른쪽, 아래, 왼쪽(시계방향)으로 값이 설정된다.  
(3) collapsing margin: block과 block의 경계가 같을 때 두 block의 위 아래의 margin은 같이 취급된다.

2. padding: box의 경계로부터 '안쪽'에 있는 공간
(1) 값의 개수에 따라 적용되는 방향은 위의 margin과 동일하다
(2) 여러 div를 생성했을 때 id를 이용하여 div들을 구분할 수 있고, 각각 다른 속성을 적용시킬 수 있다.
(3) id에 속성을 적용 시킬 때는 #id {}로 표기
