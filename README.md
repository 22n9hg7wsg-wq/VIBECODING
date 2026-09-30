# VIBECODING

바이브 코딩으로 만든 연습 프로젝트를 모아 두는 저장소입니다.

## 🌊 사인파 실험대 (Wave Simulator)

두 사인파가 **중첩(superposition)** 되는 모습을 직접 조절하며 관찰할 수 있는 인터랙티브 물리 시뮬레이터입니다.

- 각 파동의 **진폭 · 진동수 · 위상 · 진행 방향** 조절
- 두 파동이 합쳐진 결과 파형을 실시간으로 확인

👉 **바로 실행하기:** https://22n9hg7wsg-wq.github.io/VIBECODING/practice_1/wave-simulator.html

## 📁 폴더 구조

```
VIBECODING/
├── README.md
└── practice_1/
    └── wave-simulator.html   # 사인파 실험대
```

## 🚀 배포 방법 (GitHub Pages)

이 저장소는 **GitHub Pages**로 배포됩니다. 별도의 빌드 과정 없이 HTML 파일이 그대로 웹페이지가 됩니다.

### 처음 설정 (한 번만)

1. 저장소의 **Settings → Pages** 로 이동
2. **Build and deployment** 설정
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `/ (root)` → **Save**
3. **Actions** 탭에서 `pages build and deployment` 가 ✅ 로 끝나면 배포 완료

### 수정 사항 반영하기

GitHub Desktop 기준:

1. 파일 수정 후 GitHub Desktop 에서 변경 내용 확인
2. **Summary** 에 변경 내용을 적고 **Commit to main**
3. **Push origin** 클릭
4. 1~2분 뒤 사이트에 자동 반영

명령어 기준:

```bash
git add .
git commit -m "변경 내용 설명"
git push
```

### 주소 규칙

```
https://<사용자명>.github.io/<저장소명>/<파일 경로>
```

예) `practice_1/wave-simulator.html` → `https://22n9hg7wsg-wq.github.io/VIBECODING/practice_1/wave-simulator.html`

> 💡 폴더 안의 파일 이름을 `index.html` 로 지으면 파일명 없이 폴더 주소만으로도 열립니다.
