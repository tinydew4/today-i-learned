# 중급 사용법

이 문서는 Git 으로 협업시 필요한 명령을 제공합니다. 

## 협업

다음 명령들은 로컬 저장소를 변경합니다.

내 원격 저장소는 `origin` 으로 협업 저장소는 `upstream` 으로 가정합니다.
다음 작업으로 협업 저장소의 변경사항을 내 저장소에 적용할 수 있습니다.
모든 로컬 저장소 변경사항은 [원격 저장소 갱신](basic.md#원격-저장소-갱신)을 해야
내 원격 저장소에 반영됩니다.

### 협업 저장소 변경 내용을 로컬 저장소에 적용

```bash
git fetch upstream
git checkout [변경사항을 적용할 브랜치명]
git merge upstream/master
```

### 다른 브랜치의 끝을 master 브랜치와 동기화

```bash
git checkout [변경할 브랜치명]
git rebase master
```

## 원격 저장소 목록

다음 명령들은 원격 저장소 목록에만 적용됩니다.

### 추가

```bash
git remote add [원격지 별칭] [원격지 URL]
```

### 삭제

```bash
git remote remove [원격지 별칭]
```

### 나열

```bash
git remote
```

`-v` 옵션을 추가하면 각 저장소 주소도 함께 표시한다.

```bash
git remote -v
```
