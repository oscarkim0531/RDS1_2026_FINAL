# Cancellation Terms — Project Context for Codex

> 이 문서는 ChatGPT에서 진행한 **Cancellation Terms / 사회문화적디자인스튜디오(1) / Research Design Studio (1)** 프로젝트의 대화 맥락을 Codex에서 이어가기 위한 프로젝트 컨텍스트 파일이다.  
> Codex는 이 문서를 먼저 읽고, 이후 `index.html`, `style.css`, 기타 프로젝트 파일을 분석·수정할 때 **아래의 개념, 의도, 결정사항, 구현 상태, 미해결 질문을 우선 기준으로 삼아야 한다.**

---

# 0. 매우 중요한 작업 방식

## GitHub / 배포 관련

- 이 프로젝트 폴더는 사용자가 **직접 GitHub repository에 연결하고 commit / push**할 예정이다.
- Codex는 **별도의 “Site” 기능이나 자동 호스팅/사이트 연결 기능을 사용하지 않는다.**
- Codex는 이 폴더의 로컬 파일만 수정하면 된다.
- 사용자가 요청하지 않는 한 자동 배포, 별도 서비스 연결, Site 생성 등을 하지 않는다.
- 사용자가 GitHub Pages 설정을 직접 진행할 수 있으므로, **코드 수정과 repository 내부 파일 관리에 집중**한다.
- 현재 기본 웹 파일은:
  - `index.html`
  - `style.css`
  - `Cancellation-Terms_Hard-copy_Flip-Book.pdf`
- Prompt C PDF는 현재 **고정된 authored PDF**이며, 웹에서 그대로 인쇄하도록 유지하는 것이 기본 방침이다.

---

# 1. 프로젝트 기본 정보

```text
PROJECT NAME :
Cancellation Terms

YEAR :
2026

PROJECT TYPE :
School Individual Project

COURSE :
Hongik University Visual Communication Design / ResearchDesignStudio(1)

FINAL OUTPUT SPECIFICATIONS :
Spreadsheet (Prompt A), Website (Prompt B), Flipbook (Prompt C)
Flipbook — 280p, 148 × 210 mm, Perfect Binding

PROFESSOR :
Prof. Yuseon Park

SUPPORT :
Mindy Seu, Alvin Ashiatey
```

한국어 수업명:
- 사회문화적디자인스튜디오(1)

영문 수업명:
- Research Design Studio (1)

수업의 전체적 연구 프로세스:
- Research
- Collection
- Classification
- Curation
- Translation
- Preservation

프로젝트는 크게:
- Prompt A — Collection
- Prompt B — Website
- Prompt C — Hard Copy

로 이루어진다.

---

# 2. 프로젝트 전체 핵심 개념

Cancellation Terms는 단순히 “해지 약관이 길고 어렵다”는 문제를 다루는 작업이 아니다.

핵심 문제는 다음과 같다.

> 해지약관은 소비자의 권리와 의무를 규정하는 중요한 정보이지만, 사용자는 ‘해지’라는 목적에 집중하는 순간 그것을 읽어야 할 내용이 아니라 통과해야 할 절차로 받아들인다. 그 결과 정보는 눈앞에 존재하면서도 제대로 인지되지 않고, 사용자는 충분히 읽지 않은 채 그것을 수용한다.

전체 프로젝트의 가장 중요한 구조:

**Existence → Neglect → Residue**

또는

**Collection → Blind Acceptance → Accumulated Consequence**

---

# 3. Prompt A — 연구/수집 배경

Prompt A는 52개의 서비스에서 해지/취소/환불 관련 약관을 수집한 데이터베이스였다.

초기 구조:
- 약 52개 서비스
- 약 24개의 메타데이터 열
- 기업 정보
- 서비스 정보
- 요금
- 약관 전문
- 타이포그래피/스타일
- 일부 다크패턴 관련 변수

초기에는:
- 기업의 기만적 UI
- 웹 타이포그래피
- Dark Pattern
- 기업/서비스의 구조적 문제

등을 폭넓게 다루었다.

그러나 연구가 진행되면서 중심 질문이 바뀌었다.

초기:
> “기업이 사용자를 어떻게 속이는가?”

후기:
> “사용자는 왜 눈앞에 있는 약관을 스스로 지나치는가?”

따라서 최종적으로는 기업 스타일/다크패턴 변수를 제거하고 **해지 약관 전문 자체와 사용자의 태도**가 중심이 되었다.

Prompt A의 중요한 연구 흐름:

**구독경제 배경조사  
→ 52개 서비스 수집  
→ 24개 메타데이터 구조화  
→ 타이포/다크패턴 계량화  
→ 연구 중심이 ‘기업의 기만’에서 ‘사용자의 맹목적 수용’으로 이동  
→ 기업/스타일 변수 소거  
→ 해지 약관 전문이 핵심 데이터로 남음**

---

# 4. Prompt B와 Prompt C의 의미 차이

## Prompt B의 핵심 질문

> **맹목적 수용은 어떻게 발생하는가?**

Prompt B의 주인공은 **사용자의 행동과 인지**다.

사용자는 약관을 읽으러 들어온 사람이 아니라 **해지라는 목적지에 도달하려는 사람**이다.

약관은 점차:

**정보 → 절차 → 장애물**

로 바뀐다.

Prompt B의 핵심 정의:

> 해지라는 목적에 집중하는 동안 사용자는 약관을 읽어야 할 정보가 아닌 통과해야 할 절차로 받아들이며, 그 과정에서 정보는 눈앞에 존재하면서도 인지되지 않는 맹점으로 변한다.

짧게:
- Prompt B = 지나치는 순간
- The Process of Blind Acceptance

Prompt B는 “기업이 나쁘다”, “다크패턴이다”가 중심이 되면 안 된다.  
핵심은 **사용자가 어떻게 읽지 않게 되는가**다.

---

## Prompt C의 핵심 질문

> **그렇게 지나친 정보는 정말 사라지는가?**

Prompt C의 주인공은 **정보 그 자체**에 더 가깝다.

사용자는 읽지 않았지만:
- 약관은 남아 있고
- 동의/수용한 조건은 남아 있고
- 환불/위약금/책임/소멸 관련 정보도 효력을 가진다.

Prompt C의 핵심 정의:

> 사용자가 인지하지 않고 흘려보낸 약관은 사라지지 않는다. 외면된 정보는 계속 축적되고 남아 있으며, 결국 사용자의 선택과 책임을 규정하는 무게로 되돌아온다.

짧게:
- Prompt C = 지나친 뒤 남는 것
- The Residue of Blind Acceptance
- The Weight of What Was Ignored

Prompt B와 C 관계:

**B = 원인 / 과정**  
**C = 잔존 / 결과**

또는:

**B = During**  
**C = After**

---

# 5. Prompt B — 현재 메인 방향

Prompt B는 과거에 두 개의 웹사이트가 있었지만, 현재는 **두 번째 웹사이트를 메인으로 개발**한다.

## Website 1

첫 번째 웹사이트는 다음과 같은 서사적/챕터형 구조였다.

**Title → Question → Task → Distraction → Forced Consent → Self-awareness → Evidence Archive → Verdict**

핵심 인터랙션:
- 사용자가 도망가는 “해지하기” 버튼을 추적
- 마우스 궤적에서 약관 단어 생성
- 선으로 단어와 버튼 연결

Website 1의 강점:
- User Movement → Terms Generation
- Obstacle → Trace → Record

문제:
- 연구 질문이 너무 많이 섞임
  - 사용자의 무관심
  - 시스템 감시
  - 기업 비대칭
  - 기업의 잘못
- 인터랙션 문법이 통일되지 않음

따라서 Website 1은 **과정/실패/피벗의 증거**로 남기고, 현재 디자인에 기능을 대거 다시 합치지 않는다.

---

## Website 2 — 현재 개발의 Canonical Foundation

현재 Prompt B는 이 두 번째 웹사이트를 기반으로 한다.

초기 구조:
- 7-column grid desktop
- 왼쪽 2 column 비움
- 오른쪽 5 column에 약관 전문
- Korean serif
- warm ivory background
- JetBrains Mono UI
- red point color

초기 3-Layer 구조:

### Layer 1
현재 막 생성된 선명한 붉은 단어 블록

### Layer 2
약관 전문

### Layer 3
이전 단어 블록의 잔상 / residue / sediment

기본 의미:
> ignored information doesn’t disappear; it sediments into visible trace.

키워드:
- 퇴적
- 잔상
- 침전
- residual layer
- accumulated residue

---

# 6. Prompt B의 현재 핵심 시각/개념 대립

- Sentence ↔ Word
- Continuous ↔ Fragmented
- Reading ↔ Interruption
- Black ↔ Red
- Semantic Text ↔ Data Block
- Context ↔ Extract
- Present vivid block ↔ Past faded residue

핵심 개념 문장:

> 사용자가 방대한 해지 약관을 통과하는 동안, 약관에서 파생된 단어들이 화면에 발생하고 침전되며 원래 문맥을 점점 가린다. 읽으려는 흐름과 지나치려는 흐름이 충돌하고, 중요한 정보는 결국 눈앞에 존재하면서도 인지되지 않는 상태가 된다.

---

# 7. Prompt B — 개발 과정에서 발생했던 주요 문제 5개

## 문제 1 — 사용자가 아닌 시스템이 단어를 생성함

초기 코드:
```js
setInterval(generateWordBlock, 400);
```

사용자가 가만히 있어도 단어가 생성되었다.

문제:
- 사용자 행동과 정보 파편의 인과관계가 약함
- “사용자가 지나치기 때문에 흔적이 생긴다”는 논리와 불일치

개발 방향:
- 단어 생성은 scroll movement / passage에 연결

---

## 문제 2 — 변화가 아니라 같은 현상의 반복

초기:
- 일정 속도
- 일정 크기
- 랜덤 위치
- 같은 밀도

문제:
- “읽을 수 있음 → 방해 → 문맥 상실 → 맹점”이라는 progression이 약함

개발 방향:
- 진행에 따라 density / block frequency 변화
- 사용자가 텍스트보다 단어 블록에 시선을 빼앗기도록 구성

---

## 문제 3 — Layer z-index 버그

초기 CSS에서:
- Layer 3 = z 10
- Terms = z 20
- Layer 1 = z 30

이었지만 뒤쪽 selector가 Layer 3을 다시 z 30으로 override했다.

개발 후:
```css
--z-residue: 10;
--z-terms: 20;
--z-active: 30;
```

으로 구조를 명시적으로 고정했다.

---

## 문제 4 — 단어와 원문 관계

한 차례 개발 버전에서:
- 현재 보고 있는 약관 구간에서 직접 단어를 추출하도록 변경

하지만 사용자 피드백:
> 이것은 필요 없다. 현재 108개의 단어가 정해진 순서대로 나오고, 위치만 무작위인 것이 좋다.

따라서 현재:
- Google Sheet의 108개 단어 사용
- 저장된 순서대로 반복
- 위치는 랜덤
- 원문 현재 위치와 직접 데이터 매칭하지 않음

이 결정은 **현재 유지해야 한다.**

---

## 문제 5 — B→C Print가 단순 파일 실행처럼 보임

현재:
- Web → fixed PDF → browser print

개발 중 Passage Record 추가:
- 진행률
- fragment 수
- scroll distance
- session mode

하지만 사용자 결정:
- Prompt C PDF의 속표지 및 내부 내용은 변경하지 않는다.
- 고정 PDF를 그대로 인쇄한다.
- Passage Record는 웹 내부 기록/전환 장치로 유지 가능

---

# 8. Prompt B — 현재까지 확정된 인터랙션 개발 흐름

개발 과정은 다음과 같이 바뀌었다.

## 초기
- 약관 전문 전체가 처음부터 화면에 존재
- 단어는 시간 기반 자동 생성

문제:
- 텍스트 전체가 그래픽 덩어리로 보임
- 사용자가 읽으려 하지 않음

---

## Typing Interaction 도입

해결:
- Layer 2 약관 전문을 한글 글자 단위로 타이핑되듯 생성
- 사용자의 시선이 새로 생성되는 글자 끝을 따라감

의도:
> 처음에는 본문을 읽으려 하지만, 이후 붉은 단어 블록이 시선을 빼앗는다.

---

## Auto Scroll 도입

문제:
- 텍스트 생성 속도를 사용자가 직접 따라가기 어려움

해결:
- 자동 스크롤
- typing point를 화면 75% 위치에 유지
- 화면 아래 25%는 빈 공간으로 둠

현재 구조:

```text
0%
│
│  이미 생성된 약관
│
│
75% ─── 현재 타이핑되는 지점
│
│       의도적 빈 공간
│
100%
```

CSS:
```css
padding-bottom: 25vh;
```

오토스크롤은 line wrap 때마다 탁탁 튀는 방식이 아니라 **interpolation / smooth follow** 방식으로 조정되었다.

---

# 9. 붉은 단어 블록 — 현재 확정 규칙

## 데이터

- Google Sheet의 108개 단어
- 배열 순서대로
- 1 → 2 → 3 → ... → 108 → 다시 1
- 단어 자체는 random selection 하지 않음
- 위치만 random

## 생성 공간

가로:
- 화면 전체 너비

세로:
- 화면 높이의 25% ~ 75%

즉:

```text
screen top = 0
screen bottom = 1

word block region:
0.25 → 0.75
```

이유:
- 너무 위쪽에 생기면 Auto Scroll로 바로 지나감
- 너무 아래쪽에 생기면 typing point와 시선 경쟁이 지나치게 큼
- 중앙 50% 영역이 가장 안정적

## Layer

### Active
현재 단어:
- Layer 1
- 선명한 red
- red border
- ivory fill

### Residue
이전 단어:
- Layer 3로 실제 DOM 이동
- opacity 감소
- 누적

### Line
- 이전 단어 center와 현재 단어 center 연결
- 시간적 trajectory의 흔적으로 해석
- 선을 따라 다음 생성 위치를 인지할 수 있도록 `2.2px`, round cap 사용
- 아직 유지 중
- 필요하면 향후 제거 가능

---

# 10. Layer 2 — 현재 텍스트 볼륨

전체 약 9만 자 corpus를 웹에서 전부 재생하면 시간이 지나치게 길어져, Prompt B 웹 버전은 **편집된 corpus**를 사용한다.

현재 편집된 텍스트:
- 12,222 characters
- 이전 5,841자 편집본의 두 배보다 조금 긴 분량
- 전체 전문의 앞부분에서 `[제5조] 렌탈료 지급`의 7개 항이 모두 완결되는 구조적 경계까지 사용

---

# 11. Typing Speed — 현재 결정

현재 최신 요구:

초반:
```text
30 chars/sec
```

가속 시작 문장:

```text
netflix.com 웹사이트로 이동하여 ‘계정’ 페이지를 클릭하면 다음 결제일을 확인할 수 있습니다.
```

**이 문장의 첫 글자가 시작되는 시점부터 가속**

가속 후:
```text
150 chars/sec
```

최신 결정:
- 더 이상 180 → 240 / 360 / 840처럼 증가하지 않는다.
- **가속 후 150 chars/sec로 끝까지 고정**

즉:

```text
30 cps
↓
target sentence begins
↓
150 cps
↓
end
```

---

# 12. SPACE — Hold to Read

현재 중요한 인터랙션.

## 의미

사용자는 시스템의 흐름을 그대로 따라가거나,
읽고 싶다면 SPACE를 누르고 있어야 한다.

### 진행 중 SPACE HOLD
```text
SPACE held → 가속 구간을 60 chars/sec로 감속 (초반 30 chars/sec 구간은 유지)
SPACE released → normal current speed
```

즉:
- 읽고 싶으면 저항해야 함
- 손을 놓으면 다시 시스템 흐름에 실림

개념적으로:

**Hold → Read**  
**Release → Pass**

이 인터랙션은 Prompt B의 핵심과 잘 맞는다.

> 사용자는 목적지에 빨리 도달할 것인지, 정보를 읽기 위해 흐름에 저항할 것인지 선택한다.

---

# 13. 현재 두 가지 Mode — 최신 v9 방향

현재 랜딩에서 **두 가지 탐색 방식**을 선택한다.

## MANUAL

설명:
> 사용자가 직접 스크롤합니다.

행동:
- 사용자가 직접 스크롤
- 자동 스크롤 없음
- 타이핑 없이 전체 약관을 처음부터 펼쳐 둠
- 새 영역을 아래로 통과할 때 word fragment 생성
- 마지막 100% 도달 후 사용자가 직접 Print 영역으로 이어서 스크롤

개념:
> 내가 약관을 지나친다.

---

## AUTO

설명:
> 자동으로 스크롤됩니다.

행동:
- 시스템이 자동으로 passage를 통과
- 붉은 word fragment는 가속 시작 전에는 생성하지 않음
- 가속이 시작된 뒤의 생성 구간에만 108개가 균등하게 분배
- SPACE HOLD 동안 60 chars/sec로 감속
- AUTO scroll은 멈추지 않고 실제 타이핑 끝점을 느리게 따라감
- 읽기 위해 저항한 시간만큼 목적지 도달도 늦어짐

AUTO timing:
- 고정 56초 passage clock을 사용하지 않음
- 12,222자 corpus의 실제 생성 끝점을 viewport 75%에서 추적
- SPACE를 누르면 생성과 스크롤이 함께 느려짐
- 완료 후 Print handoff는 약 4초

개념:
> 시스템이 나를 약관의 끝까지 데려간다.

---

# 14. Landing — 현재 구조

현재 최신 랜딩은 단순 “스크롤하세요”가 아니다.

제목 / 안내:

```text
Cancellation Terms
두 가지 진행 방식 중 하나를 선택해 시작하세요.
```

Mode:
- MANUAL — `사용자가 직접 스크롤합니다.`
- AUTO — `자동으로 스크롤됩니다.`

Layout:
- `Cancellation Terms`는 랜딩에서 가장 큰 정보 위계
- 안내 문장은 제목에서 충분히 떨어뜨리고 mode 버튼 바로 위에 배치
- mode 버튼은 작고 중앙 정렬하며, mode 이름은 설명보다 분명하게 크게 표시

키:
```text
← / → : 모드 선택
SPACE : 시작
```

진행 중:
```text
SPACE를 누르고 있는 동안 흐름이 느려집니다.
```

기본 선택:
- AUTO

중요:
- Landing은 timer로 자동 종료되지 않음
- 사용자가 SPACE를 눌러야만 시작
- 사용자가 랜딩의 의미와 인터랙션을 인지한 뒤 경험에 진입

---

# 15. Percentage Indicator

왼쪽 아래 고정.

기존:
```text
PASSAGE 037%
```

현재:
- PASSAGE label 없음
- 숫자 + 작은 %만 표시
- 00 → 99 → 100
- 3자리 000 형식 사용하지 않음
- AUTO에서는 스크롤 위치가 아니라 `typedIndex / totalCharacters`로 계산
- 따라서 첫 화면이 채워지는 동안에도 실제 생성량과 함께 즉시 증가
- MANUAL에서는 전체 문서가 이미 펼쳐져 있으므로 실제 passage 스크롤 위치로 계산

Typography:
- **Apotek Bold**
- Adobe Fonts Kit:
  - `nfx4doc`

기존 `<head>`에 포함된 Adobe Fonts script:

```html
<script>
  (function(d) {
    var config = {
      kitId: 'nfx4doc',
      scriptTimeout: 3000,
      async: true
    },
    h=d.documentElement,t=setTimeout(function(){h.className=h.className.replace(/\bwf-loading\b/g,"")+" wf-inactive";},config.scriptTimeout),tk=d.createElement("script"),f=false,s=d.getElementsByTagName("script")[0],a;h.className+=" wf-loading";tk.src='https://use.typekit.net/'+config.kitId+'.js';tk.async=true;tk.onload=tk.onreadystatechange=function(){a=this.readyState;if(f||a&&a!="complete"&&a!="loaded")return;f=true;clearTimeout(t);try{Typekit.load(config)}catch(e){}};s.parentNode.insertBefore(tk,s)
  })(document);
</script>
```

CSS 기본 방향:

```css
.scroll-progress__number {
    font-family: "apotek", "Helvetica Neue", Arial, sans-serif;
    font-weight: 700;
}
```

`%`:
- 동일 family
- smaller
- lighter
- baseline 아래쪽에 배치

---

# 16. Final / Print Transition

과거 문제:
- typing 완료 직후 `scrollIntoView()` 실행
- Print 버튼으로 “팍” 튐

이것은 사용자가 명확히 문제라고 피드백함.

현재 최신 방향:
- `scrollIntoView()` 사용하지 않음
- typing이 끝났다고 강제로 100% 처리하지 않음
- **실제 passage 100% 도달까지 기다림**
- text typing 완료 + progress ≈ 100% 조건에서 ending unlock

## MANUAL

- 사용자가 100%까지 스크롤
- Print 영역이 아래에서 자연스럽게 열림
- 이후 사용자가 직접 스크롤해서 접근

## AUTO

- 실제 타이핑 끝점을 따라 끝까지 이동
- Print 영역 unlock
- 이후 약 4초 동안 부드러운 handoff
- Print area center에 자연스럽게 이동

## Fragment sentence completion

- 108개 단어는 총 9개의 문장으로 구성됨
- `일부 프로모션 상품의 경우 … 고객센터 연결이 필요합니다` 문장 12단어는 최신 Sheet에서 제거됨
- AUTO에서는 108개 전체를 가속 이후의 텍스트 생성 구간에 균등 분배하여 마지막 글자와 마지막 완결 문장이 함께 도착
- MANUAL에서 문장 중간에 끝난 경우에만 다음 종결어까지 420ms 간격으로 천천히 완결
- 마지막 fragment 문장이 완결된 뒤에만 Ending 영역을 unlock

## Cancellation decision flow

```text
해지하기
→ 정말 해지하시겠습니까? (예 / 아니오)
→ 예: 검은 회고 화면
→ 플립북 인쇄하기
```

- `아니오`는 붉고 굵은 테두리, `예`는 회색 테두리로 작은 dark-pattern cue를 구성
- `아니오`는 확인창만 닫고 Ending 영역으로 복귀
- `예`는 검은 화면에서 끝없이 생성되는 `약관 텍스트`와 붉은 단어 블록 중 무엇에 집중했는지 질문
- 첫 질문과 아래 두 선택 문장 사이에는 별도 수직 간격을 둠

중요:
- 갑작스러운 jump 금지
- 마지막은 “페이지 다음 구간이 이어지는 것”처럼 보여야 함

---

# 17. Passage Record

웹 끝에 존재.

현재 기록:
- progress
- fragment count
- furthest scroll distance
- mode
- timestamp

localStorage:

```js
localStorage["cancellationTermsSession"]
```

그러나 중요:
- 이 데이터를 Prompt C PDF 내부에 삽입하지 않는다.
- Prompt C 표지/속표지 내용은 변경하지 않는다.
- 현재는 웹에서 경험의 기록으로만 사용.

---

# 18. Prompt C — Flipbook

파일:

```text
Cancellation-Terms_Hard-copy_Flip-Book.pdf
```

물리 규격:
- 280p
- 148 × 210 mm
- Perfect Binding
- 기존 PDF는 첫 production/instruction sheet 포함 시 PDF page count가 281처럼 보일 수 있음

## Part 1
- continuous terms
- current word
- previous word residue
- accumulation

## Part 2
- red / black / gray / pale-red pixel saturation
- information becomes visual mass
- reading collapses

## Part 3
- clean archive
- service name + full terms
- restoration / preservation

Core transformation:

**Text → Word → Enlarged Word / Pixel → Visual Noise → Archive**

개념:

> Information the user did not read loses semantic structure, returns as visual mass, and blocks the user’s field of view.

---

# 19. Prompt B → C Translation

중요:

Prompt C는 웹사이트의 단순 인쇄 버전이 아니다.

> Prompt C freezes a temporal web mechanism into a sequence of physical frames.

변환:

```text
Scroll → Page Flip
Viewport → A5 Page
Real-time Word Generation → Page-by-page Word Appearance
Previous Word Fading → Pale Fixed Residue
Web Accumulation → Printed Accumulation
Digital Saturation → Pixel Saturation
Print Button → Physical Artifact
Fluid Web Time → Fixed Sequence of 280 Sheets
```

전체:

**Prompt A의 데이터가 Prompt B에서 행동이 되고, Prompt B의 행동이 Prompt C에서 물질과 시간으로 변환된다.**

---

# 20. Prompt C에서 현재 유지할 것

- fixed authored PDF 유지
- session-specific 280p 생성 기능은 만들지 않음
- 속표지/본문/마지막 페이지 변경하지 않음
- 웹에서 print 버튼을 누르면 현재 PDF 그대로 browser print dialog 호출

기술 구조:

```text
Website
→ hidden iframe
→ Cancellation-Terms_Hard-copy_Flip-Book.pdf
→ browser print()
```

Print 영역에는 두 개의 행동이 존재한다.
- `해지하기` — 확인 팝업과 회고 화면을 거친 뒤 인쇄로 연결
- `처음으로 돌아가기` — 페이지 상태를 초기화하고 랜딩으로 복귀

---

# 21. 현재 색/타입/시각 시스템

## Background
warm ivory

예:
```css
--color-bg: #fbfbf9;
```

## Text
almost black

```css
--color-text: #111111;
```

## Point
harsh red

```css
--color-point: #d0121b;
```

## Terms
- Sandoll Korean serif
- `sandoll-myeongjoneo1`
- desktop large text
- strong weight

## Word Blocks
- JetBrains Mono
- red text
- red border
- ivory fill
- bold

## Progress
- Apotek Bold

---

# 22. 유지해야 할 3-Layer z-index

```css
--z-residue: 10;
--z-terms: 20;
--z-active: 30;
```

절대 다시 한 selector에서 Layer 1 / Layer 3 z-index를 묶어서 override하지 말 것.

---

# 23. 현재 코드에서 유지해야 할 기술적 원칙

- `window.onload` 중복 사용하지 않음
- `setInterval(generateWordBlock, 400)` 같은 시간 기반 단어 생성으로 돌아가지 않음
- scroll interaction은 `requestAnimationFrame` 기반으로 처리
- fragment DOM 폭증 제한 유지
- resize 시 layer / SVG geometry recalculation
- PDF print 실패 시 fallback 가능
- `prefers-reduced-motion` 고려
- mobile layout이 완전히 깨지지 않게 유지
- Adobe Fonts kit 유지
- external Google Sheet load 실패 시 fallback vocabulary 유지 가능

---

# 24. Google Sheet Word Data

108개 단어를 별도의 Google Sheet CSV에서 불러온다.

원칙:
- sheet order 보존
- random word selection 금지
- random position만 허용
- 배열 끝까지 가면 다시 처음으로 loop

현재 conceptual role:
- Terms 전체에서 추출/선별된 약관 관련 핵심 단어의 curated sequence

---

# 25. 현재 unresolved / 앞으로 판단할 것

## 1. MANUAL / AUTO 두 모드가 정말 필요한가?

현재 기능적으로는 구현되었지만,
개념적으로 최종 결정은 아직 열려 있다.

검토할 질문:

- 두 모드가 프로젝트 의미를 강화하는가?
- 아니면 기능 선택처럼 보이는가?
- 사용자의 blind acceptance를 더 잘 드러내는 것은 어느 쪽인가?
- AUTO는 “시스템이 사용자를 끌고 간다.”
- MANUAL은 “사용자가 스스로 지나친다.”
- 이 대비가 충분히 의미 있다면 유지

---

## 2. 연결선

현재 유지.

해석:
- 단어들 사이의 의미 관계가 아니라
- 시간적 순서 / trajectory

하지만 여전히:
- visual clutter가 될 수 있음
- inherited device처럼 보일 수 있음

향후 검토:
- 유지
- 더 약하게
- 완전 제거

---

## 3. Passage Record

좋은 장치지만:
- 프로젝트 핵심보다 과도하게 UI처럼 보이면 안 됨
- Print 앞의 조용한 기록이어야 함

---

## 4. AUTO rhythm

현재:
- passage는 실제 타이핑 끝점을 추적
- print handoff 4초

실제 브라우저에서:
- 너무 느리거나
- 너무 기계적이거나
- fragment 밀도가 떨어지는지
테스트 필요

---

## 5. Typing / Fragment Balance

가장 중요.

사용자가:

초반:
> “본문을 읽는다.”

중반:
> “본문과 단어 블록을 동시에 본다.”

후반:
> “본문은 흘리고 단어 블록을 읽는다.”

가 되어야 한다.

단어가 너무 많으면 처음부터 본문을 읽지 않는다.  
단어가 너무 적으면 시선 전환이 일어나지 않는다.

---

# 26. Codex가 앞으로 수정할 때 사용하는 판단 기준

어떤 기능을 추가/수정하기 전에 다음을 먼저 확인한다.

## Concept
이 기능이:
> “사용자가 해지라는 목적에 집중하며 약관을 읽지 않고 지나치는 과정”

을 강화하는가?

## Interaction
사용자의 행동이 의미와 직접 연결되는가?

## Visual
장식적 효과가 아니라 정보/행동 구조를 시각화하는가?

## System
하나의 interaction grammar로 설명 가능한가?

## Portfolio
결과를 한 문장으로 설명할 수 있는가?

---

# 27. 하지 말아야 할 것

- Website 1의 기능을 대거 다시 합치지 말 것
- 기업의 기만 / dark pattern 프로젝트로 되돌리지 말 것
- 새 interaction 여러 개를 동시에 추가하지 말 것
- 108 word system을 contextual extraction으로 다시 바꾸지 말 것
- 전체 9만 자 corpus로 되돌리지 말 것
- Prompt C PDF를 임의로 수정하지 말 것
- Session-specific flipbook을 큰 기능으로 추가하지 말 것
- overly decorative UI 추가 금지
- 진행률을 dashboard처럼 만들지 말 것
- Print 버튼으로 강제 jump 금지
- Site / 별도 hosting integration 자동 연결 금지

---

# 28. 현재 프로젝트를 설명하는 가장 중요한 문장

## Prompt B

> 해지라는 목적에 집중하는 동안 사용자는 약관을 읽어야 할 정보가 아닌 통과해야 할 절차로 받아들이며, 그 과정에서 정보는 눈앞에 존재하면서도 인지되지 않는 맹점으로 변한다.

## Prompt C

> 사용자가 인지하지 않고 흘려보낸 약관은 사라지지 않는다. 외면된 정보는 계속 축적되고 남아 있으며, 결국 사용자의 선택과 책임을 규정하는 무게로 되돌아온다.

## 전체

> Prompt A의 데이터가 Prompt B에서 행동이 되고, Prompt B의 행동이 Prompt C에서 물질과 시간으로 변환된다.

---

# 29. 현재 최신 작업 파일

이 Markdown이 생성된 시점에서 가장 최신 개발 버전:

```text
Prompt B v10
index.html
style.css
Cancellation-Terms_Hard-copy_Flip-Book.pdf
```

v10의 핵심:
- MANUAL / AUTO mode
- AUTO = live typing-edge follow
- MANUAL = direct scroll
- SPACE = hold to read at 60 chars/sec without stopping
- typing 30 → 150 fixed
- 12,222-character edited corpus ending after a complete section
- typing point 75%
- bottom 25vh breathing space
- fragment region 25%–75%
- 108 ordered words, random positions
- AUTO progress and 108 fragments are driven by accelerated typed-character ratio
- cancellation confirmation → black reflection → fixed PDF print
- Apotek progress
- natural ending / no scrollIntoView jump
- fixed Prompt C PDF print
- restart button returns to the landing

---

# 30. Codex에게 요청하는 기본 행동

Codex는 새로운 대화를 시작하면 먼저:

1. 이 문서를 읽는다.
2. 현재 repository의 `index.html`과 `style.css`를 읽는다.
3. 이 문서와 실제 코드 사이에 차이가 있으면 **실제 코드를 우선 확인한 뒤 사용자에게 차이를 알려준다.**
4. 사용자의 새 피드백을 기존 개념과 비교한다.
5. 수정이 개념적으로 약하면 그대로 구현하기 전에 문제를 지적한다.
6. 사용자가 코드 수정까지 명확히 요청하면 실제 파일을 수정한다.
7. 가능한 경우 최소한의 기능으로 개념을 가장 강하게 전달한다.
8. 작업 후 어떤 파일을 수정했는지, 어떤 핵심 로직을 변경했는지 설명한다.
9. 자동 deploy / Site 생성은 하지 않는다.

---

# 31. 사용자와의 협업 톤

사용자는 단순 코딩 보조가 아니라 **시니어 시각디자이너 / 인터랙션 디자이너처럼 주도적으로 비평하고 개발하는 동료**를 원한다.

따라서:
- 단순 동의 금지
- 약한 개념이면 비판
- 기능보다 Concept & Rationale 우선
- 하이엔드 포트폴리오 퀄리티 우선
- 장식적 디자인보다 구조와 논리 우선
- 사용자의 요구를 정확히 유지하면서도, 더 강한 대안이 있으면 제안
- 코드 구현 시 디자인 의도를 주석/구조에도 반영

---

# 32. 마지막으로 기억해야 할 현재 핵심

이 웹사이트는 결국:

> **“약관을 읽는 웹사이트”가 아니라, 읽을 수 있는 정보가 어떻게 ‘통과해야 할 절차’로 변하는지를 경험시키는 웹사이트다.**

따라서 앞으로 모든 수정의 최종 질문은 하나다.

> **이 변화가 사용자가 ‘읽는 상태’에서 ‘지나치는 상태’로 이동하는 과정을 더 명확하게 만드는가?**

그렇지 않다면 제거하거나 다시 설계해야 한다.
