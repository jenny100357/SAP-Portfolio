# SAP ERP 운영·개발 포트폴리오 웹사이트

첨부된 현대오토에버 포트폴리오 PPT 내용을 바탕으로 만든 정적 웹사이트입니다. HTML 파일만으로 동작하며 별도 빌드 도구나 서버 코드는 필요하지 않습니다.

## 로컬에서 확인하기
1. `index.html`을 더블클릭합니다.
2. 브라우저에서 화면과 링크를 확인합니다.

## GitHub Pages 게시하기
1. GitHub에 로그인하고 새 저장소(repository)를 만듭니다.
   - 저장소 이름 예시: `sap-erp-portfolio`
   - GitHub Free를 사용한다면 공개(public) 저장소로 만드는 것이 가장 간단합니다.
2. 이 ZIP의 압축을 풉니다.
3. `index.html`과 `README.md`를 저장소 최상위(root)에 업로드합니다. ZIP 파일 자체만 올리는 것이 아니라 압축을 푼 파일을 올려야 합니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Build and deployment → Source**에서 `Deploy from a branch`를 선택합니다.
6. Branch를 `main`, 폴더를 `/(root)`로 선택한 뒤 **Save**를 누릅니다.
7. 배포가 완료되면 Pages 설정 화면에 표시되는 사이트 URL을 엽니다. 보통 `https://깃허브아이디.github.io/저장소이름/` 형태입니다.
8. 첫 배포와 수정 반영에는 몇 분이 걸릴 수 있습니다.

공식 가이드: https://docs.github.com/en/pages/quickstart
게시 설정 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 게시 전 반드시 확인할 사항
- 공개 웹사이트는 인터넷에서 누구나 볼 수 있습니다. 고객사명, 시스템 상세, 내부 화면, 데이터, 소스 코드 등 공개 권한이 없는 정보는 올리지 마세요.
- 전화번호는 웹사이트에서 제외했습니다. 이메일은 원본 PPT의 주소를 반영했으므로 공개가 부담되면 HTML의 `mailto:` 주소와 표시 내용을 수정하거나 연락처 섹션을 삭제하세요.
- 원본 PPT의 Suviol 프로젝트 종료일은 프로젝트 이력 페이지와 상세 페이지에서 다르게 기재되어 있어 웹사이트에 확인 메모를 남겼습니다. 실제 기간을 확인한 뒤 정리해 주세요.
- 원본 PPT의 S/4HANA Cloud Private Edition – Financial Accounting 항목은 자격증인지 교육 이수인지 명확하지 않아 확인 메모가 필요합니다.
- 원본 PPT에 기재된 경력 개월 수와 프로젝트 날짜는 실제 제출 시점에 맞게 다시 확인하세요.

## 편집하기
- 문구: `index.html` 안의 해당 문장을 직접 수정합니다.
- 디자인: 파일 상단 `<style>`의 색상 변수(`--navy`, `--blue` 등)를 수정합니다.
- 프로젝트 추가/삭제: `id="projects"` 아래의 `<article class="project">` 블록을 복사하거나 수정합니다.
