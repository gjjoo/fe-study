# Photoshop & Sublime text

## 웹디자이너와 웹퍼블리셔 그리고 프론트엔드 개발자 위치에 대한 고찰
예전에는 웹디자이너는 디자인만, 퍼블리셔는 마크업만, 개발자는 개발 코딩만, DBA는 DB 관리만..
이런 식으로 각자의 역할에만 집중하는걸 선호하기도 했고 다른 파트의 영역을 침범한다던지 침범 당한 다는걸
안좋게 받아 들였었습니다. 하지만 최근에는 현대 아트 축구와 같이 다같이 공격하고 다같이 수비하는 그런 방법을 선호합니다. 그러므로 프론트엔드 개발자는 웹디자인, 포토샵 뿐만 아니라 백엔드 부분에도 어느정도 알아야 팀에 도움이 되는 사람이 될 수 있습니다. 그러므로 효과적인 포토샵 사용을 위해 그리고 디자이너와 협력을 위해 간단한 예시를 준비했습니다.

## 레이어(Layer) 관련
- **잘못된 포토샵 Layer 사례**
  - [kakao-story](../Resources/img/kakao-story.png)
  - [hangame-archlord](../Resources/img/hangame-archlord.png)
  - [naver-mileage](../Resources/img/naver-mileage.png)
- **훌륭한 포토샵 Layer 및 Grid 활용 사례**
  - [daily-magazine](../Resources/img/daily-magazine.png)
  - [frostbite](../Resources/img/frostbite.png)

## 그리드(Gird) 관련
- **웹 그리드 시스템**
  - [960.gs](http://960.gs/)
  - [Golden Grid System](http://www.jonikorpi.com/golden-grid-system/)
  - [Muller Grid System](http://muellergridsystem.com/)
  - [Singularity Grid System](http://singularity.gs/)
  - [Susy Grid System](http://susy.oddbird.net/)
  - [Jeet Grid System](http://jeet.gs/)
  - [Unit Grid System](http://unit.gs/)
- **온라인 그리드 시스템 도구**
  - [Gridpak](http://gridpak.com/)
  - [GirdCalculator](http://gridcalculator.dk/)
  - [Modulargrid](http://modulargrid.org/#app)
  - [Thesquaregrid](http://thesquaregrid.com/)
  - [1200px](http://1200px.com/)
- **Photoshop 그리드 플러그인**
  - [Guide Guide Me](http://guideguide.me/)
  - [Modular Grid Pattern](http://modulargrid.org/#panel)

## 기타 웹 관련 포토샵 플러그인
- [SpecKing](http://www.wuwacorp.com/specking/)
- [PNG_EXPRESS](http://www.pngexpress.com/)
- [Uber Spacer](http://uberplugins.cc/)
- [Uber Line](http://uberplugins.cc/uberline-plugin-for-photoshop/)
- [Uber Stock](http://uberplugins.cc/uberstock-plugin-for-photoshop/)
- [Titlemizer](http://titlemizer.levits.ky/)
- [FontAwesomePS](http://creativedo.co/FontAwesomePS)
- [Zeick](https://gumroad.com/l/Zeick)
- [Renamy](http://www.klaia.com/Renamy/)
- [Randomuser](https://randomuser.me/photoshop)
- [CSS Hat2](http://csshat.com/)
- [Cut & Slice Me](http://www.cutandslice.me/)

```md
※ 포토샵 및 웹디자인은 프론트쪽과 관련있는 Layer, Image, Grid 관련해서만 짚고 넘어가므로 다른 기타부분은 자세히 다루지 않습니다.
```

## 개발 에디터 서브라임 시작하기에 앞서 도구의 중요성이란?
사람에게 도구란 빠르고 정확하고 편하게 사람을 인도 해왔던걸 의미합니다.
예를들어 벽에 못을 박아야 하는데 돌을 사용해야 할까요 망치를 사용해야 할까요.. 아니면 손을 써야 할까요?
또 하나의 예로 포토샵을 보자면 웹디자이너가 PSD로 작업한 결과물을 가지고 웹퍼블리셔가 보통 작업을 합니다.
그런데 디자이너분이 이미지를 폴더로 관리해서 넘겨주지 않고 그냥 PSD만 주신거죠.
이럴때는 어떻게 해야 할까요?

포토샵 기능에서 이미지를 자르는 기능을 볼 때 플러그인 기능을 포함하여 대략 5가지정도 됩니다.
Slice툴을 이용하여 하나하나 자를 수도 있고, CC이상의 포토샵기능에서 지원하는 Export 기능을 활용할수도 있고,
유료 플러그인을 이용하여 손쉽게 자를수도 있을거고,  CC2015에서 Nodejs기반으로 새롭게 생긴 기능을 사용할수도 있겠죠.
이와 같이 다양하고 손쉽게 이미지를 자를 수 있는 기능이 존재함에도 아직까지도 옛날에 했던 방식을 사용하는 사람들을 보면 안타까울 따름입니다.
개발자에게 있어서 코딩도구란 아주 중요하죠..

Eclipse, Aptana, VisualStudio, Editplus, Webstorm, Sublime 등등 여러 에디터 도구들이 존재합니다.
그중 해외에서 제일 인기있고 무료인 서브라임에 대해서 A부터 Z까지 전체적으로 알아보는 시간을 가지도록 하겠습니다.
어떤 기능이 있는지 알아야 활용할 가치가 있고 기회가 있다고 생각합니다. 그러므로 전체적인 기능을 살펴본 후 각자의 편의에 맞게 사용하시면 되겠습니다.

## 서브라임 텍스트
- 기능 & 단축키
- 패키지
- 스니펫 & 메크로