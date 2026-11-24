# 연구 웹사이트 (GitHub Pages)

빌드 도구 없이 바로 올라가는 정적 사이트입니다.

## 파일 구성
- `index.html` — 사이트 내용 (✏️ 표시된 부분과 `[ ]` 안의 내용을 바꾸세요)
- `style.css` — 디자인 (맨 위 `:root`의 색상만 바꿔도 톤이 바뀝니다)
- `.nojekyll` — GitHub이 Jekyll 처리를 건너뛰게 하는 빈 파일
- `profile.jpg` — (직접 추가) 프로필 사진. 없으면 이니셜이 표시됩니다
- `cv.pdf` — (직접 추가) CV 파일

## 올리는 방법
1. GitHub에서 **New repository** → 이름을 정확히 `USERNAME.github.io` 로 만듭니다 (USERNAME = 내 GitHub 아이디), Public 선택.
2. 저장소 화면에서 **Add file → Upload files** → 이 폴더의 파일을 모두 끌어다 놓고 **Commit changes**.
3. **Settings → Pages** 에서 Source가 `Deploy from a branch`, Branch가 `main` / `/ (root)` 인지 확인.
4. 1~2분 뒤 `https://USERNAME.github.io` 에서 사이트가 열립니다.

## 수정하기
GitHub 웹에서 `index.html`을 열고 연필 아이콘으로 바로 수정 → Commit 하면 자동으로 반영됩니다.
