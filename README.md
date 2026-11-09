# 빨대 축구 (Straw Soccer)

교과서 176쪽 해보기 「빨대 축구하기」를 디벗 마이크로 하는 3D 게임.

- 방 만들기(2인 1:1 · 4인 2:2) → 방 번호 4자리 → 방 들어가기 / 관전하기(선생님 화면)
- 디벗 마이크에 '후~' 불기 (안 되면 [후~] 버튼), 손가락으로 빨대 옮기기 — 빨대는 늘 공을 향함
- 먼저 3골 또는 3분 뒤 많이 넣은 팀 승리, 비기면 연장(먼저 넣으면 승리)
- 혼자 연습(컴퓨터와 1:1), 한 기기로 둘이서
- 통신: Firebase 실시간 DB (방장 기기가 물리를 계산), `?local` = 같은 컴퓨터 탭끼리 시험

주소: https://moonclipse-t.github.io/Straw-Soccer/
소스: `Vibe Code(과학1)/_build/decks/game_straw` + `sims/strawcore.js · strawview.js · strawnet.js` → `node tools/build.mjs game_straw`
