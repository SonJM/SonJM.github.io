---
title:  "2021-01-18 TIL"
author: Blisle
date:   2021-01-18 11:49:23 +0900
categories: [TIL]
tags: [TIL, 2021년 1월]
--- 

1월 15일날 미쳐 끝내지 못한 tags와 categories에 대한 문제를 해결하려한다.

해결과정
  카테고리와 태그를 그냥 바꾸고 깃헙에 push해보고 결과 값 보기
.ext파일에 대해 구글링 해보기 (한 번 찾아봤지만 딱히 얻은건 없었음 ㅠ)
.md파일로 글 작성 후 git push 해보기

중간 결과
  2021-01-15일 파일은 그대로 페이지에서 인식하고 결과가 깔끔하게 나왔다
심지어 15일 당시에는 안되던 tags와 categories도 깔끔하게 변경이 되었다,,,
원인이 무엇인지는 아직 모르겠지만 18일도 이와 똑같이 된다면 좋겠다,,,

해결  
  .ext파일에 대해 구글링해본 결과 리눅스에서 사용 하는 파일 확장자라는 것을 알게되었다,,
단순 마크다운 기본설명서를 새로 구글링해서 포스팅해놓았다 내일부터는 이런 칙칙한 디자인보다 
마크다운의 여러 문법들을 사용해가며 이쁘장하게 포스팅해봐야겠다,,!!
  
  
  
  
  
## TIL  

### Kotlin 언어공부  
<img src="{{ site.baseurl }}/images/../../../images/2021-01-18.png" width="250" height="350">
1. 오리엔테이션
   + kotlin 강의 진행에 있어서 필요한 정보들을 알려주는 시간이였다.
2. 1단원 : 코틀린의 기본을 익혀요!
   + 수업은 zulu에서 jdk 8버전을 다운받아서 진행하고 있고 intellij 개발 툴을 사용하여 수업이 진행된다.

``` java
// Decompile된 소스
public final class HelloKotlinKt {
   public static final void main() {
      String var0 = "Hello Kotlin!";
      System.out.println(var0);
   }

   // $FF: synthetic method
   public static void main(String[] var0) {
      main();
   }
}
```