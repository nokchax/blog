---
title: vim shortcut
date: 2020-07-27 19:40:54
categories:
- vim

tags: 
- vim
- 단축키
---
# Vim에서 사용하는 단축키를 알아보자
vim에서 자주 사용하는 단축키에 대해서 알아봅시다

## Vim에 존재하는 모드에 대해서
put image here

### 일반모드 명령 (Normal mode / Command mode)
- 가장 기본적인 모드
- 다른 모드에서 **ESC** 를 누르면 전환 된다.
- 혹은 **Ctrl + [** 를 눌러도 전환 된다.

### 비주얼 모드

### ex 모드


## w와 W에 대해
w는 단어
W는 **공백** 으로 나누어지는 것을 하나의 단어로 인식합니다.

## inner word
### ciw (change inner word)
커서 기준으로 한 단어를 삭제하고 입력 상태로 변경합니다
![change inner word](./vim-shortcut/ciw.gif)
---
### diw (delete inner word)
커서 기준으로 한 단어를 삭제합니다.
![delete inner word](./vim-shortcut/diw.gif)
---
### ciW / diW
커서를 기준으로 빈 공백 사이의 문자들을 삭제합니다.
![delete inner word](./vim-shortcut/ciwUpper.gif)
![delete inner word](./vim-shortcut/diwUpper.gif)


## 복사 / 붙여넣기
맥 OS의 경우에는 command + c, v 를 이용해서 복사 붙여넣기가 가능하기 때문에 상관 없지만, 윈도우 환경에서는 단축기가 충돌난다.
이떄 ctrl + ins / shift + ins 로 대체할 수 있다.

## K
open man page (manual page?)