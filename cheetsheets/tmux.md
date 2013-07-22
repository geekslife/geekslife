Tmux Cheet Sheet
================

[tmux 입문자님들을 위해](http://bit.ly/132BDQi) 시리즈 참고

## Session

* 세션 생성
    * tmux
* 세션 삭제
    * ctrl + d
* 세션 조회
    * tmux ls
* 세션 attach / detach
    * ctrl + b , d (detach)
    * tmux attach -t 1 (attach)
* 세션간 이동
    * ctrl + b , l
* 세션 이름 변경
    * ctrl + b , $

## Window

* 윈도 생성
    * ctrl + b , c
* 윈도 삭제
    * ctrl + d
* 윈도 이동
    * ctrl + 번호
    * ctrl + n / p (next/previous)

## Pane

* 행 생성
    * ctrl + b , %
* 열 생성
    * ctrl + b , "
* 이동
    * ctrl + b , 방향키
    * ctrl + b , q , 번호
* 삭제
    * ctrl + d
* 크기 변경
    * ctrl + b , ctrl+방향키

## Buffer

* Copy
    1. ctrl + b , [ (copy mode 시작)
    1. space        (복사 시작)
    1. enter        (복사 끝)
* Paste
    * ctrl + b , = (paste 목록 표시)
        * enter     (선택된 목록 붙여넣기)
        * q         (취소)
   
