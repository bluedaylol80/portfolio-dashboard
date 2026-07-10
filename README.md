# portfolio-dashboard

투자 포트폴리오 현황판을 **비밀번호로 암호화(StaticCrypt)한 상태**로만 호스팅하는 공개 저장소.

- 여기 올라오는 `index.html`은 **암호화된 결과물**입니다. 비밀번호 없이는 내용을 볼 수 없습니다.
- 원본(실제 금액이 든 평문)은 이 저장소에 **절대 커밋되지 않습니다.**
- 갱신은 로컬 `HT_multi/northstar-os/finance/investing/scripts/publish_dashboard.ps1`이 매일 자동 수행합니다.
  - 암호화 → 평문 누출 재검사 → 통과 시에만 `index.html` push.

주소: https://bluedaylol80.github.io/portfolio-dashboard/
