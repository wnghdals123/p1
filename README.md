# 미니 앱

의존성 없는 단일 HTML 미니 앱 모음. 각 앱은 `apps/<name>/index.html` 하나로 완결됩니다.

## 앱

| 앱 | 설명 | 경로 |
|----|------|------|
| 집중 타이머 | 포모도로 + 오늘 할 일 · 생산성 | [`apps/focus/`](apps/focus/index.html) |
| 만화경 페인트 | 대칭 생성 아트 · 창의적 장난감 | [`apps/kaleido/`](apps/kaleido/index.html) |
| 스네이크 | 먹을수록 빨라지는 클래식 · 게임 | [`apps/snake/`](apps/snake/index.html) |

## 실행

정적 파일이라 서버가 필요 없습니다. 로컬에서 보려면:

```bash
python3 -m http.server -d apps 8000
```

그리고 http://localhost:8000 를 엽니다.
