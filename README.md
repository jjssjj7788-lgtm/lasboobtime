# 라스북 수학독서경진대회 2차 시험 타이머

시험장에서 사용하는 카운트다운 타이머입니다. 단일 HTML 파일(`index.html`)로 되어 있어 설치 없이 바로 실행되고, 그대로 배포할 수 있습니다.

## 주요 기능

- **감독관이 시험 시간 직접 설정** (분 단위, ±1 / ±10 버튼, 30/60/90/120분 프리셋)
- **시작 · 정지 · 리셋 버튼**으로 직접 제어
- **큰 숫자**로 시험장 뒤에서도 잘 보이는 심플한 화면
- 남은 시간 **1분 이하면 빨간색 강조**
- **시험 종료 시** 화면 깜빡임 + 알림음 (별도 파일 불필요)
- **전체화면** 버튼, **다크 모드** 지원
- 단축키: `Space` 시작/정지 · `R` 리셋 · `F` 전체화면

## 바로 실행

`index.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다.

## GitHub에 올리기

```bash
git init
git add .
git commit -m "라스북 수학독서경진대회 2차 시험 타이머"
git branch -M main
git remote add origin https://github.com/<사용자명>/<저장소명>.git
git push -u origin main
```

## Vercel 배포

1. [vercel.com](https://vercel.com) 로그인 (GitHub 계정 연동 권장)
2. **Add New → Project** 클릭
3. 위에서 올린 GitHub 저장소 선택 → **Import**
4. 프레임워크 설정은 건드릴 필요 없이(정적 사이트) **Deploy** 클릭
5. 잠시 후 `https://<프로젝트명>.vercel.app` 주소로 접속

> 별도 빌드 설정이 필요 없습니다. `index.html`이 루트에 있으면 Vercel이 자동으로 정적 사이트로 배포합니다.
