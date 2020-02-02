---
title: "[참고] 마크다운 문법"
excerpt: "포스트 작성 참고 자료"
toc: true
toc_label: 페이지 주요 목차
toc_sticky: true
date: 2020-02-01  08:26:28 -0400
categories:
 - Markdown
tags:
 - Markdown
---
## READMEs 작성법
### README 파일이란?
- 프로젝트에 대해 설명 하는 파일이다.
- 코드에 대한 이해를 돕느다.
- 프로젝트에 접근하는 사람들에게 사용 및 관리에 용이함을 준다.

Link : [Google][googlelink]
[googlelink]: http://browserify.org/#install "Go Install Browserify"

### 마크다운이란? 
- HTML 과 같은 코드 포맷 없이도 구조적으로 웹문서를 빠르게 작성할 수 있다.
- 마크다운으로 쓰여진 문서는 .md 라는 확장자를 사용한다.
- 마크다운 사용 프로그램 : WordPress, Github, Reddit, Trello, Stack Overflow 등..

### 마크다운 문법 정리
**1. 헤더 (Header)**
#의 개수로 헤더를 표기할 수 있다. # 뒤는 한칸 뛰어야 한다.
```
# 카테고리
## 대분류
### 소분류
```
# 카테고리
## 대분류
### 소분류

**2. 인용문**
```
>의 개수로 인용문을 표기할 수 있다.
> Dictionary go ahead
>> verb To proceed; to begin
>>> related go sson, go rather
```
>의 개수로 인용문을 표기할 수 있다.
> Dictionary go ahead
>> verb To proceed; to begin
>>> related go sson, go rather

**3. 순서가 있는 목록**
1,2,3 등의 숫자로 순서를 표기할 수 있다.

**4. 순서가 없는 목록**
*, +, - 등으로 목록을 표기할 수 있다.
```
* 목록1
* 목록2
    * 내용
    * 예시
```
* 목록1
* 목록2
    * 내용
    * 예시  
    
**5. 링크**
[링크연결]
```
[링크연결](https://github.com/SumiKimKorea/SumiKimKorea.github.io/)
<(https://github.com/SumiKimKorea/SumiKimKorea.github.io/)>
```
[링크연결](https://github.com/SumiKimKorea/SumiKimKorea.github.io/)   
<https://github.com/SumiKimKorea/SumiKimKorea.github.io/>

**6. 강조**
```
두껍게 **두껍게** 혹은 __두껍게__
이텔릭체 *이텔릭체* 혹은 _이텔릭체_
두껍게+이텔릭체 **_두껍게 이텔릭체_ __*두껍게 이텔릭체*
취소선 ~~취소선~~
```
두껍게 **두껍게** 혹은 __두껍게__
이텔릭체 *이텔릭체* 혹은 _이텔릭체_
두껍게+이텔릭체 **_두껍게 이텔릭체_ __*두껍게 이텔릭체*
취소선 ~~취소선~~

**7. 이미지 삽입**  
```
![이미지 이름](이미지 URL)
```
![Dog](/assets/images/Cute.jpg){:align-center}

**8. 표**  
```
SUN | MON | TUE | WED | THU | FRI | SAT  
----|----|----|----|----|----|---- 
|  |  |  | 1 | 2 | 3 | 4   
|  |  |  | O | O | O | O
```
  
SUN | MON | TUE | WED | THU | FRI | SAT  
----|----|----|----|----|----|---- 
|  |  |  | 1 | 2 | 3 | 4   
|  |  |  | O | O | O | O   

