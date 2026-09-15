# 배포용 폴더

이 폴더는 `report/index.html`을 GitHub Pages로 공개하기 위한 저장소입니다.

- **공개 주소**: https://surida.github.io/vocal-admission-2028/
- **저장소**: https://github.com/surida/vocal-admission-2028 (Public)

## 보고서를 수정한 뒤 다시 배포하는 방법

1. `../report/index.html`을 수정합니다.
2. 이 폴더로 복사합니다: `cp ../report/index.html index.html`
3. 커밋하고 올립니다:
   ```
   git add index.html
   git commit -m "보고서 갱신"
   git push
   ```
4. 1~2분 뒤 https://surida.github.io/vocal-admission-2028/ 에 반영됩니다.

## 참고

- `robots.txt`로 검색엔진 크롤링을 막아 두었습니다. 링크를 아는 사람만 접근하는 용도입니다 — 완전한 비밀번호 보호는 아닙니다.
- 점검 도구(진단표·학원 점검·대학 평가표)는 Claude Artifact 기능(기기 간 저장)을 쓰기 때문에 이 정적 사이트로 옮기지 않았습니다. 보고서 안의 "점검 도구 열기" 링크가 계속 그 Artifact를 가리킵니다.
- `sources/`의 대학 원본 PDF는 용량 문제로 이 사이트에 포함하지 않았습니다.
