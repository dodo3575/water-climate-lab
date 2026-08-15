# files 폴더

게시판(Research / Education)에 첨부하는 파일을 여기에 올려주세요.

## 사용법
1. GitHub 저장소에서 이 `files` 폴더로 들어갑니다.
2. **Add file → Upload files**로 PDF, 이미지, hwp 등 원하는 파일을 업로드합니다.
3. `research.html` 또는 `education.html`의 게시물 안에서 아래처럼 링크를 겁니다.

```html
<a class="file-chip" href="files/파일이름.pdf" download>
  <span class="clip">📎</span> 파일이름.pdf
</a>
```

## 주의사항
- 파일명은 영문/숫자 위주로 하고 띄어쓰기는 `_`나 `-`로 바꾸는 걸 추천합니다.
  (띄어쓰기나 특수문자가 있으면 링크가 깨질 수 있습니다.)
- 파일명은 `research.html` / `education.html` 안의 `href="files/..."` 부분과
  정확히 똑같아야 합니다 (대소문자 포함).
