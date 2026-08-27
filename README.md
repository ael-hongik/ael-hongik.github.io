# AEL Website — Applied Electromagnetics Lab, Hongik University

연구실 홈페이지 소스입니다. `index.html` 파일 하나로 전체 사이트(탭 8개)가 동작합니다.

## 배포 (GitHub Pages)

1. github.com 로그인 → 우측 상단 **+** → **New repository**
2. Repository name: `아이디.github.io` (예: `ael-hongik.github.io`) → **Public** → **Create repository**
3. **uploading an existing file** 링크 클릭 → `index.html`과 이 `README.md`를 드래그 → **Commit changes**
4. 1~2분 후 `https://아이디.github.io` 접속 → 완료

(저장소 이름을 `ael` 등으로 하면 주소가 `https://아이디.github.io/ael/`이 됩니다.)

## 내용 수정 방법

`index.html`을 텍스트 편집기로 열어 수정한 뒤, GitHub 저장소에서 해당 파일 열기 → 연필 아이콘(Edit) → 붙여넣기 → Commit 하면 1~2분 내 사이트에 반영됩니다.

- **뉴스 추가**: `<!-- ================= HOME` 아래 `<div class="news">` 안에 기존 `<div class="nitem">...</div>` 블록을 복사해 맨 위에 붙여넣고 날짜·내용만 교체
- **논문 추가**: `<!-- ================= PUBLICATIONS` 아래 해당 그룹(`Journal articles` / `Conference proceedings`)의 `<div class="pub">...</div>` 블록 복사 후 수정
- **멤버 추가**: `<!-- ================= TEAM` 아래 `<div class="member">...</div>` 블록 복사 후 수정
- **사진 추가/교체**: 이미지를 `photos/` 폴더에 업로드한 뒤, Photos 탭의 해당 앨범 `<div class="pgrid">` 안에 기존 `<a class="phl">...</a>` 블록을 복사해 파일명만 바꿔 추가. 현재 사진은 구 사이트 화면 캡처본이므로, 고화질 원본으로 같은 파일명으로 덮어쓰면 화질이 개선됨

수정이 번거로우면 이 파일과 함께 Claude에게 요청하면 됩니다.
