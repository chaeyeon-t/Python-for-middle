# 파이썬 연구소 탈출

중학교 2학년 학생을 위한 방탈출형 파이썬 학습 사이트입니다.
연구소에 갇힌 학생이 7개의 방에서 파이썬 코드로 보안 장치를 풀고 탈출합니다.

- 미션 내용: 문자열·숫자 출력, 사칙연산, 변수, `input()`, `int()`
- 화면 구성: 미션 브리핑 · 코드 편집기 · 입력값 칸 · 터미널
- 채점: 숨겨진 테스트로 자동 채점, 틀린 줄과 오류를 쉬운 한국어로 안내
- 파이썬 실행: 브라우저 안에서 실행 (설치 필요 없음)
- 기록: 학생의 반·번호·이름과 진행 상황을 Firebase(Firestore)에 저장
- 교사용 화면: 시작 화면의 "교사용" → 비밀번호 입력 → 학생 기록 실시간 확인, CSV 내려받기
- 교사용 화면 비밀번호 : ckdcptndjq(창체수업)


## 사이트 주소 (GitHub Pages)

https://chaeyeon-t.github.io/Python-for-middle/

## 저장되는 기록 (`students` 컬렉션)

문서 이름: `2반-15번-김민준`

| 필드 | 내용 |
|---|---|
| class, number, name | 반, 번호, 이름 |
| clearedCount, clearedRooms | 해제한 방 수, 해제한 방 번호 |
| tries | 방별 '보안문 해제 시도' 횟수 |
| currentRoom, finished | 현재 방, 탈출 완료 여부 |
| updatedAt, lastLoginAt | 마지막 저장 시각, 마지막 시작 시각 |
