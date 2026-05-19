# my_shortcuts

사용하는 단축키와 단축키 툴을 정리한 저장소.

## 목차

- [PyCharm / IntelliJ](#pycharm--intellij)
- [macOS & 윈도우 관리](#macos--윈도우-관리)
- [Vim / IdeaVim](#vim--ideavim)
- [Chrome (Vimium)](#chrome-vimium)
- [iTerm](#iterm)
- [GitHub](#github)
- [설정 파일](#설정-파일)

---

## PyCharm / IntelliJ

| 동작 | 단축키 |
|---|---|
| import 팝업 | `cmd + .` |
| 한 줄 지우기 | `cmd + backspace` |
| 한 줄 복제 | `cmd + D` |
| 줄 이동 | `shift + alt + G` |
| 컨텍스트 테스트 실행 (이후 재실행 `ctrl + R`) | `ctrl + shift + R` |
| 파일 맨 위 / 맨 아래 | `cmd + HOME` / `cmd + END` |
| 탭 이동 | `ctrl + 방향키` |
| split 탭 이동 | `opt + tab` |
| 터미널 토글 | `ctrl + D` |
| breakpoint 생성 | `cmd + F8` |
| documentation 보기 | `F1` |
| 선언부로 이동 (반대 창) | `alt + D` |
| 뒤로 가기 | `ctrl + cmd + 방향키` |
| 폰트 축소 / 확대 | `ctrl + shift + ,` / `ctrl + shift + .` |
| git annotate | `ctrl + Q + ctrl + A` |
| 검색 이전 / 다음 결과 | `shift + cmd + G` / `cmd + G` |
| action 검색 | `cmd + shift + P` |

---

## macOS & 윈도우 관리

> 사용 중인 툴: **Rectangle.app**, **Apptivate**

| 동작 | 단축키 |
|---|---|
| 프로그램 전환 | `cmd + tab` |
| 같은 앱 창 전환 | `` cmd + ` `` |
| 화면 밝기 | `fn + O` / `fn + P` |
| 뒤로 가기 | `cmd + [` |
| 데스크탑 이동 | `ctrl + cmd + 방향키` |
| 창 반쪽 정렬 | `opt + cmd + 방향키` |
| maximize | `ctrl + opt + backspace` |
| fullscreen | `cmd + ctrl + F` |
| 정확한 창 이동 | `cmd + ctrl + 1~5` |
| version control | `ctrl + V` |
| 사전 | `ctrl + shift + 2` |

---

## Vim / IdeaVim

### 모드

| 동작 | 키 |
|---|---|
| insert mode | `i` |
| visual mode | `v` |
| undo / redo | `u` / `ctrl + r` |

### 편집

| 동작 | 키 |
|---|---|
| 복사 (yank) / 붙여넣기 | `y` / `p` |
| 지우기 | `d` |
| 한 줄 복사 / 삭제 | `yy` / `dd` |

### 이동

| 동작 | 키 |
|---|---|
| 줄 처음 / 줄 끝 | `0` / `$` |
| 첫 글자 | `^` |
| 앞으로 특정 문자 점프 | `f + 문자` |
| 뒤로 특정 문자 점프 | `F + 문자` |
| 반 페이지 아래 / 위 | `ctrl + d` / `ctrl + u` |
| 한 줄씩 아래 / 위 스크롤 | `ctrl + e` / `ctrl + y` |

---

## Chrome (Vimium)

| 동작 | 키 |
|---|---|
| 단축키 도움말 | `?` |
| 위 / 아래 스크롤 | `u` / `d` |
| 검색창 열기 (현재 탭 / 새 탭) | `o` / `O` |
| 히스토리 뒤로 / 앞으로 | `H` / `L` |
| 새 탭 / 탭 닫기 | `t` / `x` |
| 페이지 내 검색 | `/` |
| 탭 이동 | `J` / `K` |
| 다음 / 이전 검색 결과 | `n` / `N` |
| 링크 힌트 | `f` |
| 최상단 / 최하단 | `gg` / `G` |
| URL 복사 | `yy` 또는 `cmd + L` |
| 커서 위치 화면 중앙으로 | `zz` |
| 탭 이동 (네이티브) | `shift + cmd + [` / `]` |

---

## iTerm

| 동작 | 단축키 |
|---|---|
| 한 줄 지우기 | `ctrl + U` |
| 명령어 맨 끝으로 이동 | `ctrl + E` |
| 창 나누기 | `cmd + D` |
| 창 이동 | `cmd + opt + 방향키` |
| 스크롤 위 / 아래 | `cmd + up` / `cmd + down` |
| 탭 복제 / 새 탭에 복제 | `shift + cmd + D` / `opt + D` |
| URL 복사 | `cmd + L` |

### copy mode

| 동작 | 단축키 |
|---|---|
| copy mode 진입 | `cmd + ctrl + C` |
| 선택 시작 | `enter` |
| 선택 | `shift + 방향키` |
| 선택 중지 | `ctrl + space` |
| copy mode 종료 | `esc` |

---

## GitHub

| 동작 | 단축키 |
|---|---|
| 마크다운 preview | `cmd + shift + P` |

---

## 설정 파일

- [`config_files/.ideavimrc`](./config_files/.ideavimrc) — IdeaVim 설정 (leader = `space`)
  - 플러그인: `surround`, `multiple-cursors`, `ideajoin`
  - 검색: `incsearch` + `hlsearch` + `ignorecase`/`smartcase`, `<leader>ch` 하이라이트 해제
  - 리팩토링: `<leader>rn` rename · `<leader>rv` 변수 추출 · `<leader>rm` 메서드 추출 · `<leader>oi` import 정리 · `<leader>F` 코드 정렬
  - 이동: `gd` 선언 · `gr` 사용처 · `<leader>ff` 파일 · `<leader>fc` 클래스 · `<leader>fg` 전체 검색 · `ctrl + o/i` 뒤/앞 점프
  - 테스트: `<leader>tn` 실행 · `<leader>tf` 실패 테스트 재실행
  - 기타: `<leader>vr` 설정 리로드 (`:source ~/.ideavimrc`) · `<leader>ip` import 팝업 보기
