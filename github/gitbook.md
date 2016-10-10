# GitBook 만들기

* [GitBook](https://www.gitbook.com) 에서 책을 만들 수 있습니다.
* GitHub 와 연동하여 쉽게 만들 수 있습니다.
* `README.md` 와 `SUMMARY.md` 는 꼭 있어야 합니다.

모든 문서는 [GitBook 의 마크다운 형식](https://tinydew4.gitbooks.io/gitbook/content/ko/format/markdown.html)으로 작성합니다.

## 기본 설정

### book.json

사용자 정의 환경 설정에 사용됩니다. [GitBook Tolchain Documentation 의 Configuration](https://toolchain.gitbook.com/config.html) 을 참고하세요.

### README.md

첫 페이지로 사용됩니다.

### SUMMARY.md

목차에 사용됩니다.

```md
# 개요

* [1장](chapter1/README.md)
  * [1절](chapter1/subchapter1.md)
  * [2절](chapter1/subchapter2.md)
* [2장](chapter2/README.md)
* [3장](chapter3/README.md)
  
```

## 다국어

### LANGS.md

다국어 지원시 문서의 루트 아래에 한 단계의 언어별 폴더를 생성하고, 그것을
`LANGS.md` 파일에 명시해야 합니다. 파일 이름이 `LANG` 이 아닌 `LANGS` 임을
주의하세요.

```md
* [English](en)
* [한국어](ko)
```
