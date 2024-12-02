# MARKDOWN_20241202
MARKDOWN_20241202

### 10. 체크리스트
`- [ ] 또는 - [X]를 사용하여 체크박스를 만든다.`  
- [ ] : 미완료된 작업  
- [X] : 완료된 작업

### 9. 표
`|와 -를 사용하여 테이블을 작성한다.`  
| 헤더1 | 헤더2 | 헤더3 |
|:----------------:|:----------------|--------------------------:|
| 데이터1009090909090 | 데이터29909090909090 | 데이터389898989898 |
| 데이터4 | 데이터5 | 데이터6 |
| 데이터7 | 데이터8 | 데이터9 |

### 8. 이미지
`이미지는 ![이미지 텍스트](이미지 URL)`  
![balsa](https://github.com/codingpgw/MARKDOWN_20241202/blob/main/balsa.JPG)


### 7. 강조(Emphasis)
- 굵게(Bold) : **텍스트** 또는 __text__
- Italic : *텍스트* 또는 _text_
- Bold + Italic : ***텍스트*** 또는 ___text___


### 6.링크(Link)
`[링크 텍스트](URL) 형태로 작성한다.`
<a href="https://cafe.daum.net/pcwk">test</a>  
[PCWK Daum](https://cafe.daum.net/pcwk)
**같은 페이지 내 하이퍼 링크**  
[여기](#4-코드블록)

### 5. 목록
**순서 있는 리스트**  
---
1. 아이템1
2. 아이템2  
   2.1. 1단계 하위 아이템  
   2.2. 2단계 하위 아이템  
3. 아이템3
4. 아이템4
***

**순서 없는 리스트**  
- 아이템1  
+ 아이템2
  -  1단계 하위 아이템
       * 2단계 하위 아이템
* 아이템3  


### 4. 코드 블록
**인라인 코드**
`System.out.println("Hello, World!");`

<b>코드 블록</b>
```
public class Hello {	
	public static void main(String []args){
		//console : "Hello, world!" 메세지 출력
		System.out.println("Hello, World!");
	}	
}
```

### 3. 인용 상자
>여기에 인용할 내용을 넣으면 됩니다.  
>빈 줄이 없으면 자동으로 인용 상자에 포함된다.  
식사 맛나게 하셨나요?<BR>

인용이 끝났습니다.

### 2. 제목(Header)
>제목은 # 기호를 사용하여 작성한다. #의 개수로 제목의 수준(1~6)을 나타낸다.<br>

# H1 제목
## H2 제목
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목

### 1. 문단 구분을 위한 개행
겨울 바다를 걸어 보아요.<br>
(개행 : SPACE 2개)  
첫 눈이 왔어요.<br>
(#4-코드블록)
