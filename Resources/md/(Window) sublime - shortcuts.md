# (Window) sublime - shortcuts

## 윈도우와 서브라임 단축키 중복(Shortcuts overlap)
Keypress | Win Command | Sublime Command
-------- | ----------- | ---------------
<kbd>Ctrl + Alt + 방향키</kbd> | 화면전환 | 멀티라인 커서

## 파일(Files)
Keypress | Command
-------- | -------
<kbd>Ctrl + Shift + N</kbd>  | 새로운 서브라임 창 열기
<kbd>Ctrl + Shift + W</kbd>  | 서브라임 종료
<kbd>Ctrl + W</kbd>          | 현재 파일 닫기

## 기본키(General)
Keypress | Command
-------- | -------
<kbd>Ctrl + `</kbd>            | 콘솔 보기(Show Console)
<kbd>Ctrl + Shift + P</kbd>    | 명령어 팔레트(Command Palette)
<kbd>F11</kbd>                 | 전체화면(Toggle fullscreen mode) 
<kbd>Shift + F11</kbd>         | 집중 편집모드(Distraction Free Mode)
<kbd>Ctrl + K, Ctrl + B</kbd>  | 사이드바 보이기/숨기기(Show/Hide Side Bar)

## 텍스트 조작(Text manipulation)
Keypress | Command
-------- | -------
<kbd>Ctrl + K, Ctrl + U</kbd>              | 대문자 변환(Transform to Uppercase)
<kbd>Ctrl + K, Ctrl + L</kbd>              | 소문자 변환(Transform to Lowercase)
<kbd>Edit / Convert Case / Swap Case</kbd> | 대문자는 소문자로, 소문자는 대문자로 변환(Swapcase)

## 편집(Editing)
Keypress | Command
-------- | -------
<kbd>Ctrl + K, Ctrl + V</kbd>      | 복사 히스토리(Past from History)
<kbd>Ctrl + /</kbd>                | 주석(Comment/un-comment current line)
<kbd>Ctrl + Shift + /</kbd>        | 여러블록 주석(Block comment current selection)
<kbd>Ctrl + ]</kbd> or <kbd>tab</kbd>         | 들여쓰기(Indent)
<kbd>Ctrl + [</kbd> or <kbd>Shift + tab</kbd> | 내어쓰기(Unindent)
<kbd>Ctrl + Shift + ↑</kbd>        | 위 라인과 교체(Swap Line Up)
<kbd>Ctrl + Shift + ↓</kbd>        | 아래 라인과 교체(Swap Line Down)
<kbd>Ctrl + Shift + D</kbd>        | 라인 복제(Duplicate Line)
<kbd>Ctrl + Shift + K</kbd>        | 라인 삭제(Delete Line)
<kbd>Ctrl + J</kbd>                | 라인 합치기(Join Lines)
<kbd>Ctrl + Enter</kbd>            | 아래에 행을 삽입(Insert line after)
<kbd>Ctrl + Shift + Enter</kbd>    | 위에 행을 삽입(Insert line before)
<kbd>Ctrl + Shift + [</kbd>        | 코드 접기(Fold)
<kbd>Ctrl + Shift + ]</kbd>        | 코드 펴기(Unfold)
<kbd>Ctrl + K, Ctrl + J</kbd>      | 코드 전체 펴기(Unfold All)
<kbd>Ctrl + K, Ctrl + 1</kbd>      | 코드 전체 접기(Fold All)
<kbd>Ctrl + K, Ctrl + [1,2,3,...,9]</kbd>  | 코드 레벨별 접기(Fold Level)

## 선택(Selection)
Keypress | Command
-------- | -------
<kbd>Ctrl + 👆</kbd>             | 멀티커서
<kbd>Ctrl + Alt + ↑</kbd>        | 멀티라인 커서 - 위의 라인에 커서 추가(Extra cursor on the line above)
<kbd>Ctrl + Alt + ↓</kbd>        | 멀티라인 커서 - 아래 라인에 커서 추가(Extra cursor on the line below)
<kbd>Ctrl + D</kbd>              | 단어 선택 후 다음 단어 선택 반복(Select word - Repeat to select next occurrence)
<kbd>Ctrl + L</kbd>              | 라인 선택 후 다음 행 선택 반복(Select line - Repeat to select next lines)
<kbd>Ctrl + A</kbd>              | 전체 선택(Select All)
<kbd>Ctrl + Shift + Space</kbd>  | 범위로 선택을 확장합니다(Expand Selection to scope)
<kbd>Ctrl + Shift + M</kbd>      | 괄호로 선택을 확장합니다(Expand Selection to brackets) - JS
<kbd>Ctrl + Shift + J</kbd>      | 들여 쓰기로 선택을 확장합니다(Expand Selection to indentation) - CSS
<kbd>Ctrl + Shift + A</kbd>      | 태그 선택을 확장합니다(Expand Selection to tag) - HTML

## 빠른이동(Navigation/Goto Anywhere)
Keypress | Command
-------- | -------
<kbd>Ctrl + P</kbd>            | 현재 프로젝트의 모든 폴더 탐색(Quick-open files by name), ※ "@"기호 사용시 단어탐색도 동시 사용 가능
<kbd>Ctrl + R</kbd>            | 현재 파일의 단어 탐색(Goto symbol / Goto word in current file)
<kbd>Ctrl + Shift + R</kbd>    | 현재 프로젝트에서 단어 탐색(Goto symbole in project)
<kbd>Ctrl + G</kbd>            | 현재 파일의 라인 이동(Goto line in current file)
<kbd>Ctrl + PageDown</kbd>     | 다음 파일(Next File)
<kbd>Ctrl + PageUp</kbd>       | 이전 파일(Previous FIle)
<kbd>Ctrl + Tab</kbd>          | 현재 레이아웃에서의 다음 파일, 즉 열린 순서를 기억하여 순차탭(Next File in Stack)
<kbd>Ctrl + Shift + Tab</kbd>  | 현재 레이아웃에서의 이전 파일, 즉 열린 순서를 기억하여 순차탭(Previous File in Stack)
<kbd>Alt + [1,2,3,...]</kbd>   | 현재 열려있는 파일의 번호를 순차적으로 붙여 해당 번호의 파일로 이동(Select Number File)
<kbd>Ctrl + K, Ctrl + C</kbd>  | 현재 커서(또는 선택) 위치로 스크롤 이동(Scroll to Selection)
<kbd>Ctrl + ↑</kbd>            | 현재 커서를 기점으로 페이지의 화면 스크롤 위로 이동(Line Up)
<kbd>Ctrl + ↓</kbd>            | 현재 커서를 기점으로 페이지의 화면 스크롤 아래로 이동(Line Down)
<kbd>Ctrl + M</kbd>            | 괄호 시작점과 끝점으로 이동(Jump to Matching Bracket)

## 찾기/바꾸기(Find/Replace)
Keypress | Command
-------- | -------
<kbd>Ctrl + F</kbd>            | 찾기(Find)
<kbd>F3</kbd>                  | 다음 찾기(Find Next)
<kbd>Shift + F3</kbd>          | 이전 찾기(Find Previous)
<kbd>Alt + Enter</kbd>         | "찾기 모드"에서 전체 찾기(Find All)
<kbd>Ctrl + I</kbd>            | 향상된 찾기(Incremental Find)
<kbd>Ctrl + H</kbd>            | 찾아 바꾸기(Replace)
<kbd>Ctrl + Shift + H</kbd>    | 다음 바꾸기(Replace Next), ※ 바꿀단어를 미리 정의해야 하므로 약간 비효율적임
<kbd>Ctrl + F3</kbd>           | 빠른 찾기(Quick Find)
<kbd>Alt + F3</kbd>            | 빠른 모두 찾기(Quick Find All)
<kbd>Ctrl + D</kbd>            | 다음 단어 탐색(Quick Add Next)
<kbd>Ctrl + K, Ctrl + D</kbd>  | 한 번 건너띈후 다음 단어 탐색(Quick Skip Next)
<kbd>Ctrl + Shift + F</kbd>    | 현재 프로젝트의 모든 파일에서 탐색(Find in Files)
<kbd>Ctrl + E</kbd>            | 찾기 선택자(Use Selection for Find)
<kbd>Ctrl + Shift + E</kbd>    | 대체 선택자(Use Selection for Replace)
<kbd>F4</kbd>                  | "파일 탐색 결과화면에서" 다음 찾기(Next Result)
<kbd>Shift + F4</kbd>          | "파일 탐색 결과화면에서" 이전 찾기(Previous Result)

## 탭 패널(Tabs Panels)
Keypress | Command
-------- | -------
<kbd>Alt + Shift + 1</kbd>       | 한개의 화면(Revert view to single column)
<kbd>Alt + Shift + 2</kbd>       | 2개의 화면(Split view into two columns)
<kbd>Alt + Shift + 3</kbd>       | 3개의 화면(Split view into three columns)
<kbd>Alt + Shift + 4</kbd>       | 4개의 화면(Split view into four columns)
<kbd>Alt + Shift + 5</kbd>       | 4개의그리드(Set view to gird 4 groups)
<kbd>Alt + Shift + 8</kbd>       | 가로 2개 화면(2 Rows)
<kbd>Alt + Shift + 9</kbd>       | 가로 3개 화면(3 Rows)
<kbd>Ctrl + Shift + Number</kbd> | 현재 파일을 원하는 화면의 그룹으로 이동
<kbd>Ctrl + Number</kbd>         | 해당 그룹으로 포커스 이동

## 북마크(Bookmarks)
Keypress | Command
-------- | -------
<kbd>Ctrl + F2</kbd>         | (Toggle bookmark)
<kbd>F2</kbd>                | (Next bookmark)
<kbd>Shift + F2</kbd>        | (Previous bookmark)
<kbd>Ctrl + Shift + F2</kbd> | (Clear bookmark)

## 프로젝트(Project)
Keypress | Command
-------- | -------
<kbd>Ctrl + Alt + P</kbd> | Quick Switch Project