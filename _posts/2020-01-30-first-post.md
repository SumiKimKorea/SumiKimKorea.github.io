---
title: "[TIL+일기] 2020. 01. 29(수) - 시작이 어렵다"
excerpt: "아직도 모르겠다. 이거 시작했다고 할 수 있나?"

date: 2020-01-29  08:26:28 -0400
categories:
 - TIL
tags:
 - TIL
last_modified_at: 2020-01-30T08:06:00-05:00
---

일하는데 있어서 목표가 없었다. 그냥 살다보니 대학을 가고 입사를 하고, 어라? 하다보니 훌쩍 시간이 흘렀다. 심지어 이제는 20대 막바지에 도달했다. 
 
  "20대 때 나는 무엇을 했을까?"

정말 뭘 했지? 숨이 턱 막힌다. 5년이라는 정말 긴 시간동안 내내 정체되어 있었다. 새로운 것을 배우려고 노력하지 않았고, 내 일에 관심을 주지 않았다. 나이가 주는 두려움, 5년이라는 시간이 주는 막막함이 한순간에 휘몰아쳤다. 

새해가 벌써 한달이 지나버린 시점에, 드디어 Github 블로그를 개설했다. 습관 어디 가지 않았다... 이번에도 여러 블로그들 참고하면서 후루루 만들어봤다. ruby가 뭔지 jekyll이 뭔지 이 많은 코드들은 뭔지 모르겠지만, 우선 시작하는데 의의를 두려고 한다. 진짜 시작이 너무 어렵다!
  
새해를 맞이해서 개설한 첫 블로그, 처음 쓰는 글인만큼 몇가지 다짐들을 적어본다. 
1. 윈도우 프로그래밍 공부한 내용 블로그에 정리하기  
2. 궁금한 점, 추가 공부한 내용, 유용한 자료들도 정리하기  

많이는 못 적겠지만, 우선 윈도우 프로그래밍 자유자재로 뚝딱 만들수있게 공부해야겠다. 개발이 너무 신나서 이것도 만들고 저것도 만들겠다고 자신있게 말할 수 있는 개발자가 되고 싶다. 이전에 직업이 뭐냐고 묻는 말에, 개발자입니다! 당당하게 말할수있기를 그런 사람이 되기를 꿈꾼다. 
(후, 오늘은 MFC에서 엑셀시트를 참조 작업하느라 애먹었다..정말 ㅠㅠ)

GitHub Blog 서비스인 github.io 블로그 시작하기로 했다.
GitHub Blog 서비스의 이름은 Pages이다.

Pages가 다른 블로그 플랫폼 보다 편한 것 같아서 마음에 든다.
다른 사람들도 같이 많이 사용했으면 좋겠다는 생각이 든다.

YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.
이 글의 제목은 {{ page.title }}이고
마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.

## 참고 사이트 정리
[지킬, 루비 설치](https://dataitgirls2.github.io/tutorial/Tutorial_180709_StaticBlogging_JekyllandRuby.html)  
[지킬, 루비 설치]
(http://error404.co.kr/dev/2018/04/13/jekyll-for-windows/)  
[github 블로그 시작하기](https://devinlife.com/howto%20github%20pages/first-post/)  
<https://zoomkoding.github.io/gitblog/2019/08/18/git-blog-2.html>

## 주의할점
로컬에서 수정사항을 확인한 후에 최종 git push를 보내도록 하자. 
해당 폴더에서 cmd 창 실행하여 bundle exec jekyll serve 하면 서버 연동됨

## 충격
_config.yml 파일을 수정하고 나니 szinfo? 어쩌구 에러가 났다. 왜 났는지 몰라서 한참을 쩔쩔 매다가 결국에는 매우 간단한 문제였음을... timezone 설정을 Asia/Seoul로 했는데 이게 문제였다.? 뭐지? 내일 확인해봐야지



