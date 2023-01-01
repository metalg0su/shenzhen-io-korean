# SHENZHEN I/O 한글화
## 개요
Zachtronics 사에서 만든 Shenzhen I/O 의 한글 번역입니다.

스팀판 게임에 적용할 수 있습니다.

+(wizroad3) 23.1.1. 중문 한글화로 변경하였습니다. (stirngs.csv 이슈) 게임실행 후 control panel에서 중국어(汉语) 선택
(오프닝은 기본 영어로 나오는 것을 확인하였으나 한글로 보고 싶다면 설정을 중국어로 바꾼 후 문서\My Games\SHENZHEN IO\(user id)\config.cfg 파일만 남기고 삭제 후 다시 실행하면 볼 수 있는 것을 확인하였음. 더 좋은 방법 제보 바람)

## 진행 상황
> 체크됨: 초벌 번역이 되었다는 의미.

- [x] 다이얼로그 (messages.zh)
  - [x] LONGTENG 필수 대화
  - [x] LONGTENG 스팸 메일
  - [x] ??(스포일러)
- [x] 인게임 요구사항 설명문 (descriptions.zh)
  - [x] LONGTENG
  - [x] ??(스포일러)
- [x] 여타 메시지 & 단어들 (strings.csv)

> 참고: `strings.csv`의 경우, 언어 인코딩 문제로 영문 번안 적용 불가하여 중문 번역 진행함

## 적용법
1. [번역물 다운로드](https://github.com/wizroad3/shenzhen-io-korean/archive/refs/heads/master.zip)
1. 번역물 압축 해제
1. Shenzhen 로컬 폴더로 이동
   1. 스팀 라이브러리에서 게임 우클릭 -> 로컬 폴더 열기 를 통해서 이동 가능
1. 번역물 내의 `strings.csv`, `descriptions.zh`, `messages.zh`, `textures` 을 [라이브러리 폴더]/Contents 아래에 덮어 씀
1. 게임실행 후 control panel에서 중국어(汉语) 선택
1. 끝

## 기타
### 오역, 제안, 번역 기여
오역, 제안, 번역 기여를 원하시면 이슈나 PR로 만들어 주세요.
- ISSUE: https://github.com/metalg0su/shenzhen-io-korean/issues
- PR: https://github.com/metalg0su/shenzhen-io-korean/pulls

### ----
[스팀 댓글](https://steamcommunity.com/profiles/76561198015916974/recommended/504210/) 보고 번역이 가능하다는 사실을 깨달았습니다.

이후 자크한테 번역 해도 되냐고 메일로 물어본 뒤 진행했습니다.

원문에 대한 모든 저작권은 Zachtronics한테 있어요.

### ---
(wizroad3) 사족
개발자이긴 하지만 사정상 github를 다운로드 용도 외 처음써봐서(..) 맞게 하는 것인지 모르겠습니다. 혹시 실례가 됐다면 죄송합니다.
metalg0su님 덕분에 게임을 재밌게 플레이 하다가 한글화가 안된 곳까지 게임을 진행하여서 이어서 한글화를 해봤습니다. 이 자리를 빌어 감사드립니다.
아직 게임을 클리어한건 아니라서, 의역 및 오역이 많을 수 있습니다.
