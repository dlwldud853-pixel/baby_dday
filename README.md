# 🍼 아기 D-day

출산 예정일까지 남은 날을 예쁘게 보여주는 D-day 위젯이에요.  
Notion, 카카오톡 링크 공유 등 어디서든 바로 쓸 수 있어요.

---

## 기본 URL

```
https://dlwldud853-pixel.github.io/baby_dday/babydday.html
```

파라미터 없이 접속하면 기본 이름·날짜·사진으로 표시돼요.

---

## 커스텀 방법

URL 뒤에 `?`를 붙이고 아래 항목을 원하는 대로 바꿔서 사용하세요.

| 파라미터 | 설명 | 예시 |
|---|---|---|
| `name` | 아기 이름 (태명) | `name=뿌콩이` |
| `date` | 출산 예정일 (YYYY-MM-DD) | `date=2027-03-15` |
| `img` | 배경 사진 URL | `img=https://...` |

**예시 URL:**
```
https://dlwldud853-pixel.github.io/baby_dday/babydday.html?name=콩이&date=2027-03-15&img=https://이미지주소
```

---

## 배경 사진 URL 구하는 법

사진 파일을 직접 올릴 수 없고, **인터넷에 공개된 이미지 주소**가 필요해요.

### 방법 1 — Imgur (제일 간단)
1. [imgur.com](https://imgur.com) 접속
2. 사진 업로드
3. 업로드된 사진 우클릭 → **이미지 주소 복사**
4. 복사한 주소를 `img=` 뒤에 붙여넣기

### 방법 2 — Pinterest
1. Pinterest에서 원하는 사진 열기
2. 사진 우클릭 → **이미지 주소 복사**
3. 복사한 주소를 `img=` 뒤에 붙여넣기

---

## Notion에 넣는 법

1. Notion 페이지에서 `/embed` 입력
2. **Embed** 블록 선택
3. 위에서 만든 커스텀 URL 붙여넣기
4. 완료!

---

## D-day 계산 기준

| 상태 | 표시 |
|---|---|
| 예정일 이전 | D-30 |
| 예정일 당일 | D-DAY |
| 예정일 이후 | D+3 |
