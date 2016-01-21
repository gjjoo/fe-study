# Snippet 사용법 및 설정 방법

`Tools > New Snippet...` 실행 한 후 아래와 같이 작성
```xml
<snippet>
  <content><![CDATA[
Hello ${1:World!}
]]></content>
  <tabTrigger>hello</tabTrigger>
  <scope>source.js</scope>
  <description>hello</description>
</snippet>
```

- `<tabTrigger>`  : <kbd>Ctrl+E</kbd> 또는 <kbd>Tab</kbd>시 해당 약어를 통해 `<content>` 부분 출력
- `<scope>`       : 해당 스니펫 사용 영역 설정 (복수 설정시, `source.js, text.html, source.css`)
- `<description>` : `hello` 타이핑 시 해당 스니펫에 대한 설명 또는 도움말
- `<content>`     : `<![CDATA[ ]]>` XML 주석을 기본적으로 사용, `${숫자:내용}`는 content 출력 시 빠른 편집 도움
