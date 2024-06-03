# 240528 

## .md파일을 작성하기 위한 .md 파일의 문법 정리

### What's .md?

>.md는 markdown 의 약자
>
>markdown이란
>일반 텍스트 문서에 서식 요소를 추가할 수 있는 언어
>
>쓰는 이유?
>보기가 좋잖아요!


### 제목

    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6

또는

    Heading 1
    =========

    Heading 2
    ---------

주의 사항

'#'과 내용사이에는 공백이 있어야 제목으로 인식
줄 바꿈을 할때는 엔터 2번 해야함

(엔터를 기준으로 단락을 구분)

Heading 1은 문서당 한개만 존재해야함.

### 강조

    **bold**
    __bold__

### 이탤릭

    *Italic*
    _Italic_

언더 스코어(_) 는 문장 가운데 쓰는걸 허용 하지 않음.

### 인용

    > 인용문구
    > 
    > 여러 단락도 가능

    > 인용문구
    >
    >> 안에 중첩 인용도 가능
    > 인용 문 내에서 개행을 할경우 > 한번 입력후
    >
    > 개행을 한다.


### 목록

#### 순서있는 목록 (ol)
    
    1. First Item
    2. Second Item
    3. Third Item
    4. Fourth Item
        1. Indented Item
        2. Indented Item
    5. Fifth Item


#### 순서 없는 목록 (ul)

    - First Item
    - Second Item
    - Third Item
    - Fourth Item
        - Indented Item
        - Indented Item
    - Fifth Item

    - 대신 * + 기호 사용가능
    대신 섞어서 쓰면 안됨.

### Code

    코드 작성시 탭1개(공백4개) 들여쓰기로 시작

### 수평선

    ***
    ---

### 하이퍼링크
    [링크설명](https://url.주소)"hover할경우 설명"

### 이미지연결
    ![이미지설명](/assets/images/이미지 경로)"hover할경우 설명"


## Ref
https://www.markdownguide.org/
