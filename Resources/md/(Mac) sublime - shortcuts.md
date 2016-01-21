# (Mac) sublime - shortcuts

<kbd>⌘</kbd> : Command, 
<kbd>⇧</kbd> : Shift, 
<kbd>⌃</kbd> : Control, 
<kbd>⌥</kbd> : Alt(option), 
<kbd>⇥</kbd> : Tab

## 맥과 서브라임 단축키 중복(Shortcuts overlap)
Keypress | MAC Command | Sublime Command
-------- | ----------- | ---------------
<kbd>⌃ + ↑</kbd> | Mission Control       | 멀티라인 커서
<kbd>⌃ + ↓</kbd> | 응용 프로그램 윈도우  | 멀티라인 커서
<kbd>⌃ + 1</kbd> | 데스크탑 1로 전환     | 그룹 포커싱
<kbd>⌃ + 2</kbd> | 데스크탑 2로 전환     | 그룹 포커싱

## 파일(Files)
Keypress | Command
-------- | -------
<kbd>⌘ + ⇧ + N</kbd> | 새로운 서브라임 창 열기
<kbd>⌘ + Q</kbd>     | 서브라임 종료
<kbd>⌘ + W</kbd>     | 현재 파일 닫기

## 기본키(General)
Keypress | Command
-------- | -------
<kbd>⌃ + `</kbd>         | 콘솔 보기(Show Console)
<kbd>⌘ + ⇧ + P</kbd>     | 명령어 팔레트(Command Palette)
<kbd>⌃ + ⌘ + F</kbd>     | 전체화면(Toggle fullscreen mode) 
<kbd>⌘ + K, ⌘ + B</kbd>  | 사이드바 보이기/숨기기(Show/Hide Side Bar)

## 텍스트 조작(Text manipulation)
Keypress | Command
-------- | -------
<kbd>⌘ + K, ⌘ + U</kbd>                | 대문자 변환(Transform to Uppercase)
<kbd>⌘ + K, ⌘ + L</kbd>                | 소문자 변환(Transform to Lowercase)
<kbd>Edit/Convert Case/Swap Case</kbd> | 대문자는 소문자로, 소문자는 대문자로 변환(Swapcase)

## 편집(Editing)
Keypress | Command
-------- | -------
<kbd>⌘ + ⌥ + V</kbd>                   | 복사 히스토리(Past from History)
<kbd>⌘ + /</kbd>                       | 주석(Comment/un-comment current line)
<kbd>⌘ + ⌥ + /</kbd>                   | 여러블록 주석(Block comment current selection)
<kbd>⌘ + ]</kbd> or <kbd>tab</kbd>     | 들여쓰기(Indent)
<kbd>⌘ + [</kbd> or <kbd>⇧ + tab</kbd> | 내어쓰기(Unindent)
<kbd>⌘ + ⌃ + ↑</kbd>                   | 위 라인과 교체(Swap Line Up)
<kbd>⌘ + ⌃ + ↓</kbd>                   | 아래 라인과 교체(Swap Line Down)
<kbd>⌘ + ⇧ + D</kbd>                   | 라인 복제(Duplicate Line)
<kbd>⌃ + ⇧ + K</kbd>                   | 라인 삭제(Delete Line)
<kbd>⌘ + J</kbd>                       | 라인 합치기(Join Lines)
<kbd>⌘ + ↩</kbd>                       | 아래에 행을 삽입(Insert line after)
<kbd>⌘ + ⇧ + ↩</kbd>                   | 위에 행을 삽입(Insert line before)
<kbd>⌘ + ⌥ + [</kbd>                   | 코드 접기(Fold)
<kbd>⌘ + ⌥ + ]</kbd>                   | 코드 펴기(Unfold)
<kbd>⌘ + K, ⌘ + J</kbd>                | 코드 전체 펴기(Unfold All)
<kbd>⌘ + K, ⌘ + 1</kbd>                | 코드 전체 접기(Fold All)
<kbd>⌘ + K, ⌘ + [1,2,3,...,9]</kbd>    | 코드 레벨별 접기(Fold Level)

## 선택(Selection)
Keypress | Command
-------- | -------
<kbd>⌘ + 👆</kbd>    | 멀티커서
<kbd>⌃ + ⇧ + ↑</kbd> | 멀티라인 커서 - 위의 라인에 커서 추가(Extra cursor on the line above)
<kbd>⌃ + ⇧ + ↓</kbd> | 멀티라인 커서 - 아래 라인에 커서 추가(Extra cursor on the line below)
<kbd>⌘ + A</kbd>     | 전체 선택(Select All)
<kbd>⌘ + D</kbd>     | 단어 선택 후 다음 단어 선택 반복(Select word - Repeat to select next occurrence)
<kbd>⌘ + L</kbd>     | 라인 선택 후 다음 행 선택 반복(Select line - Repeat to select next lines)
<kbd>⌘ + ⇧ + L</kbd> | 다중 선택과 배치 편집(선택을 분할하는 데 사용되며, 각 라인은 동시에 편집 가능) (Make batch edits with Multiple Selections)
<kbd>⌘ + ⇧ + X</kbd> | 범위로 선택을 확장합니다(Expand Selection to scope)
<kbd>⌘ + ⇧ + M</kbd> | 괄호로 선택을 확장합니다(Expand Selection to brackets) - JS적합
<kbd>⌘ + ⇧ + J</kbd> | 들여 쓰기로 선택을 확장합니다(Expand Selection to indentation) - CSS적합
<kbd>⌘ + ⇧ + A</kbd> | 태그 선택을 확장합니다(Expand Selection to tag) - HTML적합

## 빠른이동(Navigation/Goto Anywhere)
Keypress | Command
-------- | -------
<kbd>⌘ + P</kbd>           | 현재 프로젝트의 모든 폴더 탐색(Quick-open files by name), ※ "@"기호 사용시 단어탐색도 동시 사용 가능
<kbd>⌘ + R</kbd>           | 현재 파일의 단어 탐색(Goto symbol / Goto word in current file)
<kbd>⌘ + ⇧ + R</kbd>       | 현재 프로젝트에서 단어 탐색(Goto symbole in project)
<kbd>⌃ + G</kbd>           | 현재 파일의 라인 이동(Goto line in current file)
<kbd>⌘ + ⌥ + →</kbd>       | 다음 파일(Next File)
<kbd>⌘ + ⌥ + ←</kbd>       | 이전 파일(Previous FIle)
<kbd>⌃ + ⇥</kbd>           | 현재 레이아웃에서의 다음 파일, 즉 열린 순서를 기억하여 순차탭(Next File in Stack)
<kbd>⌃ + ⇧ + ⇥</kbd>       | 현재 레이아웃에서의 이전 파일, 즉 열린 순서를 기억하여 순차탭(Previous File in Stack)
<kbd>⌘ + [1,2,3,...]</kbd> | 현재 열려있는 파일의 번호를 순차적으로 붙여 해당 번호의 파일로 이동(Select Number File)
<kbd>⌃ + L</kbd>           | 현재 커서(또는 선택) 위치로 스크롤 이동(Scroll to Selection)
<kbd>⌃ + ⌥ + ↑</kbd>       | 현재 커서를 기점으로 페이지의 화면 스크롤 위로 이동(Line Up)
<kbd>⌃ + ⌥ + ↓</kbd>       | 현재 커서를 기점으로 페이지의 화면 스크롤 아래로 이동(Line Down)
<kbd>⌃ + M</kbd>           | 괄호 시작점과 끝점으로 이동(Jump to Matching Bracket)

## 찾기/바꾸기(Find/Replace)
Keypress | Command
-------- | -------
<kbd>⌘ + F</kbd>        | 찾기(Find)
<kbd>⌘ + G</kbd>        | 다음 찾기(Find Next)
<kbd>⌘ + ⇧ + G</kbd>    | 이전 찾기(Find Previous)
<kbd>⌥ + ↩</kbd>        | 찾기 모드에서 전체 찾기(Find All)
<kbd>⌘ + I</kbd>        | 향상된 찾기(Incremental Find)
<kbd>⌘ + ⌥ + F</kbd>    | 찾아 바꾸기(Replace)
<kbd>⌘ + ⌥ + E</kbd>    | 다음 바꾸기(Replace Next), ※ 바꿀단어를 미리 정의해야 하므로 약간 비효율적임
<kbd>⌘ + ⌥ + G</kbd>    | 빠른 찾기(Quick Find)
<kbd>⌘ + ⌃ + G</kbd>    | 빠른 모두 찾기(Quick Find All)
<kbd>⌘ + D</kbd>        | 다음 단어 탐색(Quick Add Next)
<kbd>⌘ + K, ⌘ + D</kbd> | 한 번 건너띈후 다음 단어 탐색(Quick Skip Next)
<kbd>⌘ + E</kbd>        | 찾기 선택자(Use Selection for Find)
<kbd>⌘ + ⇧ + E</kbd>    | 대체 선택자(Use Selection for Replace)
<kbd>⌘ + ⇧ + F</kbd>    | 현재 프로젝트의 모든 파일에서 탐색(Find in Files)
<kbd>F4</kbd>           | "파일 탐색 결과화면에서" 다음 찾기(Next Result)
<kbd>⇧ + F4</kbd>       | "파일 탐색 결과화면에서" 이전 찾기(Previous Result)

## 탭 패널(Tabs Panels)
Keypress | Command
-------- | -------
<kbd>⌘ + ⌥ + 1</kbd>      | 한개의 화면(Revert view to single column)
<kbd>⌘ + ⌥ + 2</kbd>      | 2개의 화면(Split view into two columns)
<kbd>⌘ + ⌥ + 3</kbd>      | 3개의 화면(Split view into three columns)
<kbd>⌘ + ⌥ + 4</kbd>      | 4개의 화면(Split view into four columns)
<kbd>⌘ + ⌥ + 5</kbd>      | 4개의그리드(Set view to gird 4 groups)
<kbd>⌘ + ⌥ + ⇧ + 2</kbd>  | 가로 2개 화면(2 Rows)
<kbd>⌘ + ⌥ + ⇧ + 3</kbd>  | 가로 3개 화면(3 Rows)
<kbd>⌃ + ⇧ + Number</kbd> | 현재 파일을 원하는 화면의 그룹으로 이동
<kbd>⌃ + Number</kbd>     | 해당 그룹으로 포커스 이동

## 북마크(Bookmarks)
Keypress | Command
-------- | -------
<kbd>⌘ + F2</kbd>     | (Toggle bookmark)
<kbd>F2</kbd>         | (Next bookmark)
<kbd>⇧ + F2</kbd>     | (Previous bookmark)
<kbd>⇧ + ⌘ + F2</kbd> | (Clear bookmark)

## 프로젝트(Project)
Keypress | Command
-------- | -------
<kbd>⌘ + ⌃ + P</kbd> | Quick Switch Project