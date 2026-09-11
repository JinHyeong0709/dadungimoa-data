# 다둥이모아 협력업체 데이터

[다둥이모아](https://github.com/JinHyeong0709/dadungimoa) 앱이 실행 시 내려받는 데이터입니다.

- 공개 주소: https://jinhyeong0709.github.io/dadungimoa-data/merchants.json
- 출처: 서울 열린데이터광장 「서울시 다둥이 행복카드 협력업체 정보」(제공: 우리카드)
- 라이선스: 공공누리 제3유형 (출처표시 + 변경금지)

## 갱신 방법

앱 저장소에서:

```bash
npm run data:build     # 서울 API 재수집 + 지오코딩
npm run data:publish   # 이 저장소로 복사 후 푸시
```

앱은 실행할 때마다 이 파일의 `generatedAt` 을 번들본·기기 캐시와 비교해
더 새로우면 교체합니다. 스토어 재심사 없이 협력업체 정보를 갱신할 수 있습니다.
