# 명령어

## 사용법  
`git [--version] [--help] [-C <path>] [-c name=value] [--exec-path[=<path>]]`  
`[--html-path] [--man-path] [--info-path] [-p | --paginate | --no-pager]`  
`[--no-replace-objects] [--bare] [--git-dir=<path>] [--work-tree=<path>]`
`[--namespace=<name>] <command> [<args>]`

## 다음은 다양한 상황에서 사용되는 일반적인 Git 명령입니다:

### 작업 영역 시작 (자세한 내용: git help tutorial)
* clone : 새 디렉토리에 저장소 복제
* init : 빈 Git 저장소 생성 또는 기존 저장소 초기화

### 변경과 관련된 작업 (자세한 내용: `git help everyday`)
* add : 인덱스에 파일 내용을 추가
* mv : 파일, 디렉토리, 심볼릭 링크를 이동 또는 이름 변경
* reset : 현재 HEAD 를 특정 상태로 재설정
* rm : 작업 트리와 인덱스에서 파일 제거

### 히스토리와 상태 검사 (자세한 내용: `git help revisions`)
* bisect : 버그가 발생한 커밋을 이진 검색으로 찾기
* grep : 패턴에 일치하는 줄을 출력
* log : 커밋 로그 보기
* show : 객체의 여러 유형 보기
* status : 작업 트리 상태 보기

### 공통 히스토리를 증가, 표시, 변경
* branch : 브랜치 나열, 생성, 삭제
* checkout : 브랜치 변경 또는 작업 트리 파일 복원
* commit : 저장소에 변경사항 기록
* diff : 커밋/커밋, 커밋/작업 트리, 등등간 차이점 보기
* merge : 2개 이상의 개발 히스토리를 합침
* rebase : 다른 기본 끝의 상단에 커밋을 다시 적용
* tag : GPG 로 서명된 태그 객체를 생성, 나열, 삭제, 검증

### 협업 (자세한 내용: `git help workflows`)
* fetch : 다른 저장소로부터 객체와 참조 다운로드
* pull : 다른 저장소 또는 로컬 브랜치로부터 가져와서 통합
* push : 관련 객체로 원격 참조를 갱신

`git help -a` 와 `git help -g` 는 가능한 하위 명령과 일부 개념 가이드를  
나열합니다. 하위명령이나 개념에 대한 내용은 `git help <command>` 또는  
`git help <concept>` 를 보세요.
