# ☕ cafe-landing

가상의 동네 카페 **"카페 소담(SODAM)"** 을 소개하는 한 페이지짜리 랜딩 페이지입니다.
HTML과 CSS만으로 만든 정적 사이트로, GitHub Pages로 배포되어 있습니다.

🔗 **사이트 보기:** https://timenaturelove-lab.github.io/cafe-landing/

## 폴더 구성

```
cafe-landing/
├── index.html   # 페이지 구조와 내용
├── style.css    # 디자인(색상·글꼴·레이아웃, 반응형)
└── README.md    # 이 설명 파일
```

## 페이지 구성

| 섹션 | 내용 |
|---|---|
| 상단 메뉴 | 로고(SODAM)와 소개·메뉴·오시는 길 바로가기 |
| 히어로 | 메인 문구 "동네의 작은 쉼표, 카페 소담"과 메뉴 보기 버튼 |
| 소개 | 직접 로스팅 · 매일 굽는 빵 · 편안한 공간 (카드 3개) |
| 대표 메뉴 | 커피·베이커리 6종과 가격 |
| 오시는 길 | 주소, 영업시간, 휴무일, 첫 방문 쿠폰 안내 |

## 사용한 기술

- HTML5, CSS3 (프레임워크 없음)
- Google Fonts: Noto Serif KR, Noto Sans KR
- CSS Grid / Flexbox 기반 반응형 레이아웃 (휴대폰 화면 지원)

## 로컬에서 보기

별도 설치 없이 `index.html`을 브라우저로 열면 됩니다.

## 수정과 배포

1. `index.html`(내용)이나 `style.css`(디자인)를 수정합니다.
2. 커밋 후 `main` 브랜치에 푸시합니다.
   ```
   git add .
   git commit -m "수정 내용"
   git push
   ```
3. 1~2분 뒤 GitHub Pages 사이트에 자동 반영됩니다.

## 참고

카페 이름, 주소(`서울시 ○○구 ○○로 12`), 메뉴 가격, 영업시간은 모두 **예시 데이터**입니다.
실제로 사용할 때는 `index.html`에서 해당 내용을 바꿔 주세요.
