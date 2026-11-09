# 꿈속의 수조 CYOA

HTML·CSS·JavaScript로 제작한 정적 웹 CYOA입니다. 별도의 서버나 빌드 도구가 필요하지 않습니다.

## 실행
`index.html`을 브라우저에서 엽니다.

## GitHub Pages 업로드
1. GitHub에서 새 공개 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`, `style.css`, `script.js`, `data.js`, `assets/`를 저장소 **최상위**에 업로드합니다.
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. 게시 주소가 활성화될 때까지 기다린 뒤 열어봅니다.

## 선택지 수정
`data.js`의 `CYOA_DATA`에서 각 항목의 `options`에 `[선택지 이름, 설명]` 형식으로 추가하거나 수정할 수 있습니다. `mode: 'single'`은 단일 선택, `mode: 'multi'`는 복수 선택, `max: 3`은 최대 3개 제한입니다.

## 참고
- 하늘섬은 환경의 '하늘'과 '섬'을 선택하면 자동으로 해금되는 임시 규칙입니다.
- 여과 시설, 날씨, 장비, 특성의 세부 선택지는 미확정 제안입니다.
- 구성원은 현재 다섯 가지 대분류만 선택합니다.
- 선택은 사용자 브라우저의 localStorage에 자동 저장됩니다.
- 나레이터 이미지는 사용자가 제공한 이미지를 포함했습니다.
