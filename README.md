# Big5 성격 유형 검사

Big Five 성격 이론을 기반으로 한 정적 웹앱입니다.

44개 문항에 응답하면 다음 5가지 성격 차원에 대한 결과를 시각적으로 확인할 수 있습니다.

- 개방성 (Openness)
- 성실성 (Conscientiousness)
- 외향성 (Extraversion)
- 친화성 (Agreeableness)
- 신경성 (Neuroticism)

## 주요 기능

- 44문항 Big Five 검사
- 5점 척도 응답 방식
- 레이더 차트 기반 결과 시각화
- 차원별 상세 해석 제공
- 결과 화면 PDF 저장 지원

## 실행 방법

별도 빌드 없이 브라우저에서 바로 실행할 수 있습니다.

1. 저장소를 클론합니다.
2. `index.html`을 브라우저에서 엽니다.

또는 간단한 정적 서버로 실행할 수 있습니다.

```bash
python3 -m http.server 8000
```

이후 브라우저에서 `http://localhost:8000`으로 접속합니다.

## 배포 주소

GitHub Pages로 배포되어 있습니다.

- https://choonsik.github.io/Big5/

## 기술 스택

- HTML
- CSS
- JavaScript
- Chart.js