# EnvStudio 피드백

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
</p>

## EnvStudio 소개

**EnvStudio**는 WinUI 3로 구축된 현대적인 Windows 환경 변수 관리 도구입니다. 20년 된 "시스템 속성 → 환경 변수" 대화상자를 네이티브 Windows 11 경험으로 대체합니다.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/ko/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/ko/cover2.png" width="48%" />
</p>

## 다운로드

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## 주요 기능

- **직관적인 비주얼 에디터** — 모던 WinUI 3 인터페이스로 환경 변수를 쉽게 추가, 편집, 삭제, 재정렬.
- **PATH 목록 관리** — 드래그 앤 드롭 정렬, 중복 감지, 끊어진 링크 감지.
- **EXE 덮어쓰기 감지** — PATH의 모든 디렉토리에서 실행 파일을 스캔하고, 목록 앞부분 항목에 의해 재정의되는 것을 표시. 한 번 클릭으로 경합 항목으로 이동.
- **범위 충돌 감지** — 사용자 변수가 같은 이름의 시스템 변수를 가릴 때 취소선과 경고 아이콘으로 실제로 유효한 값을 항상 확인.
- **비파괴 토글** — 변수를 삭제하지 않고 비활성화. 레지스트리 값을 조용히 이름 변경하여 원본 데이터 보존. 언제든 원클릭으로 재활성화.
- **삭제 안전 검사** — 변수 삭제 전 다른 변수의 `%VARNAME%` 참조를 스캔하여 잠재적 손상을 경고.
- **변수 확장 미리보기** — `%VAR%` 참조가 포함된 값에 마우스를 올리면 툴팁으로 완전히 해석된 경로 표시.
- **외부 변경 감지** — 레지스트리를 실시간 모니터링. EnvStudio 실행 중 다른 프로그램이 환경 변수를 수정하면 즉시 새로고침 알림.
- **프로필 시스템** — 다양한 개발 환경(예: "Java 8", "Node.js", "AI/ML")을 위한 변수 프로필 저장, 전환, 적용.
- **스냅샷 & 롤백** — 변경 전 자동 스냅샷, Git 스타일 diff 뷰와 원클릭 롤백.
- **검색 및 필터** — 사용자 및 시스템 범위에서 정규식으로 빠르게 검색. 일치하는 PATH 하위 항목이 자동 확장되고 일치 수 배지 표시.
- **내보내기** — 변수를 PowerShell, Batch 또는 .env 파일 형식으로 내보내기. 팀 공유 및 시스템 재설치 후 복원에 편리.
- **UAC 권한 상승** — 시스템 변수 편집을 위한 원활한 관리자 권한 상승.
- **즉시 브로드캐스트** — `WM_SETTINGCHANGE`를 통해 변경 사항을 시스템 전체에 즉시 알림.

## 100% 오프라인 · 완전 무료

EnvStudio는 **완전히 오프라인으로 작동하며, 원격 측정이나 데이터 수집이 없습니다.** 환경 설정은 오직 여러분의 PC에만 남습니다.

모든 기능이 **완전 무료**이며, 광고나 유료 벽이 없습니다. 향후 기부 옵션이 추가될 수 있지만, 기능이 제한되는 일은 절대 없을 것입니다.

자세한 내용은 [개인정보 보호정책](https://prunelab.net/ko/products/envstudio/privacy)을 참조하세요.

---

## 피드백

> **참고:** 이 저장소에는 EnvStudio의 소스 코드가 **포함되어 있지 않습니다.** 사용자 피드백 수집 및 이슈 추적 전용입니다.

| 작업 | 링크 |
|------|------|
| 버그 신고 | [버그 리포트 작성](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| 기능 제안 | [기능 요청 제출](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| 모든 이슈 보기 | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## 신고 전에

중복을 피하기 위해 먼저 [기존 이슈](https://github.com/PruneLab/EnvStudio-Feedback/issues)를 검색해 주세요.

버그 신고 시 다음 정보를 포함해 주세요:
- **EnvStudio 버전** (설정 → 정보에서 확인)
- **Windows 버전** (예: Windows 11 23H2)
- **재현 단계**
- **예상 동작** vs **실제 동작**
- 스크린샷 (해당하는 경우)

## 기능 아이디어

여러분의 아이디어를 기다립니다! 제출 전에:
- 이미 유사한 제안이 있는지 확인
- 사용 사례 설명 — 이 기능이 어떤 문제를 해결할까요?
- 목업이나 참고 링크도 항상 환영합니다
