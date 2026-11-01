# youtube-shorts-from-longform

![card](docs/card.png)

롱폼 영상 대본 한 편을 **완결형 쇼츠 4편(45~75초)** 으로 다시 쓰는 **Claude Code / 에이전트 스킬**입니다. 롱폼을 줄이는 게 아니라 가장 놀라운 대목 하나만 떼어 처음부터 다시 씁니다.

## 담긴 내용
- 1초 훅, 긴장, 알맹이, **한 방으로 닫는 완결형** 구조 (문장 10~16개, 300~450자)
- 쇼츠 제목·화면 위 헤더·썸네일 글 규칙(나쁜 예와 좋은 예 포함)
- **이어지게 쓰기**: 쇼츠만 보는 사람이 이해되도록 고리를 메우는 법
- 네 편을 서로 다른 대목에서 고르는 법, 화면(장면) 고르기
- 내기 전 점검: 사실과 정확히 맞는가, 소리 내어 읽어도 매끄러운가

## 쓰는 법
```bash
mkdir -p .claude/skills/youtube-shorts-from-longform
cp SKILL.md .claude/skills/youtube-shorts-from-longform/
```
"이 대본으로 쇼츠 4편 만들어 줘"라고 롱폼 대본과 함께 요청하세요. 함께 쓰면 좋은 스킬: [youtube-explainer-script](https://github.com/ai-offwork/youtube-explainer-script).

## 주의
- 새 사실을 만들지 않도록 되어 있습니다(대본에 있는 숫자·인과만). 그래도 공개 전에 사실을 확인하세요.

## 만든 곳
인스타 [@ai.offwork.kr](https://www.instagram.com/ai.offwork.kr/) — AI 업무 꿀팁

## 고지
- 개인이 만든 **비공식 프로젝트**이며 Anthropic(Claude, Claude Code), Google(YouTube)과 제휴·후원·승인 관계가 없습니다. 각 이름은 해당 회사의 상표이며, 여기서는 사용 가능한 도구로 언급할 뿐입니다.
- **AI가 쓴 대본·그림은 사람이 검수·편집해서 쓰세요.** 유튜브는 사람의 가공 없이 대량 제작된 반복 콘텐츠("inauthentic content")에 수익화 제재를 하고, 사실적으로 바꾸거나 합성한 콘텐츠는 공개 시 표시하도록 요구합니다. 최신 정책은 유튜브 공식 도움말에서 확인하세요.
- 사실 확인은 사용자의 책임입니다. 다른 채널의 영상·대본을 베끼지 마세요.

## 라이선스
MIT
