# AI가 행동하는 시대, 보안의 기준이 바뀐다

**AI 에이전트의 새로운 보안 위협과 대응 전략** · 오영주 지음

📕 **완성본 PDF**: [AI가_행동하는_시대_보안의_기준이_바뀐다.pdf](./AI가_행동하는_시대_보안의_기준이_바뀐다.pdf) (47쪽)

## 폴더 구성

```
├── AI가_행동하는_시대_보안의_기준이_바뀐다.pdf   완성본
├── manuscript/                  원고 (bookforge 조판 원본)
│   ├── book.json                제목·저자·스타일 설정
│   ├── outline.json             장 목록과 장 표지 요약
│   └── chapters/ch-00~08.md     장별 원고
└── planning/
    ├── 책프로필.md
    └── 목차.md
```

## 목차

1. 들어가며
2. AI가 일을 시작한 날
3. 보안은 IT팀의 일이라는 착각
4. 문서 속에 숨은 명령
5. 너무 많은 열쇠를 건넨 비서
6. 편리한 연결이 만든 뒷문
7. 몰래 새어 나간 데이터
8. 맡기기 전의 다섯 기준
9. 강의실의 보안 리터러시

## PDF 다시 만들기

원고(`manuscript/chapters/*.md`)를 고친 뒤 [bookforge](https://github.com/gongnyang/bookforge) 스킬로 다시 조판한다.

```bash
python3 <bookforge>/scripts/build.py manuscript
python3 <bookforge>/scripts/qc_gate.py manuscript   # 통과 시 manuscript/final/ 에 PDF 생성
```
