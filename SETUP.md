# 드레더 (Dread0r) README 전체본

## 적용

`README.md`는 파도 배너, 소개 문구, 조회수, Streak와 AI·기술 카드를 포함한 전체본입니다. 닉네임은 드레더 (Dread0r), 회사명은 PALDYN으로 표기하며 조회수·Streak는 GitHub 계정 `Dread0r`를 사용합니다.

작업실 배너를 사용하려면 `README-workspace.md`의 내용을 저장소 루트 `README.md`로 사용하세요. 해당 배너는 `assets/dread0r-workspace.png`에 포함되어 있으며, 이미지에는 Dread0r가 표시됩니다.

`assets/`도 저장소 루트에 함께 올리세요. 기존 폴더는 삭제하지 말고 합칩니다. 라이선스 파일과 THIRD-PARTY-NOTICES.md도 함께 보관하세요. `README.md` 코드만 붙여넣고 이미지 파일을 생략하면 로컬 이미지가 표시되지 않습니다.

## Snake 갱신

Snake SVG는 이전 계정명 `enxec`으로 수집한 2026-10-19 스냅샷입니다. 현재 표시 이름은 Dread0r로 바꿨으며, 원본 데이터의 계정명은 출처 기록을 위해 `INITIAL-SNAPSHOT.json`과 `THIRD-PARTY-NOTICES.md`에 보존합니다.

현재 프로필 README 저장소 `Dread0r/Dread0r`에는 `.github/workflows/readme-snake.yml`이 없습니다. 자동 갱신을 추가할 경우 기여 데이터 대상은 `Dread0r`, 출력 파일은 `assets/readme-polish/snake-dark.svg`와 `assets/readme-polish/snake-light.svg`로 설정하세요.

## 표시와 외부 서비스

AI·기술 카드와 Snake는 패키지 안의 SVG를 읽습니다. 작업실 배너도 로컬 PNG입니다. 원문의 파도 배너·조회수·Streak는 기존 외부 서비스 주소를 그대로 사용하므로, 그 서비스에 문제가 생기면 해당 이미지는 표시되지 않을 수 있습니다. 이번 작업에서 외부 이미지 서비스의 응답은 확인하지 않았습니다.

로컬 파일 존재, SVG XML, README의 이미지 경로와 GitHub 계정 매개변수를 검사했습니다. GitHub 페이지에서의 실제 렌더링은 확인하지 않았습니다.

참고:
- https://github.com/Platane/snk
- https://raw.githubusercontent.com/Platane/snk/v3/svg-only/action.yml
- https://raw.githubusercontent.com/actions/checkout/v7/action.yml
