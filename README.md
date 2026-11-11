# 개인 스킬 안내

이 폴더에서 관리하는 스킬 21개의 용도와 요청 예시입니다. 각 스킬의 자세한 절차는 이름에 연결된 `SKILL.md`에서 확인할 수 있습니다.

Codex 채팅에 아래 요청 예시를 입력하면 됩니다. 스킬 이름을 직접 언급하거나 `$ig-reel`처럼 지정할 수 있습니다. 필요한 자료는 실행 중 요청받을 수 있습니다.

## 사업 아이디어와 계획

| 스킬 | 언제 쓰나 | 요청 예시 |
| --- | --- | --- |
| [office-hours](office-hours/SKILL.md) | 초기 아이디어의 고객 문제, 수요 근거, 핵심 전제와 빠른 검증 행동을 정할 때 | `office-hours로 이 사업 아이디어를 진단해줘. [아이디어와 경험]` |
| [business-research](business-research/SKILL.md) | 사업 가설에 관한 외부 근거를 조사하고 반론·재검증과 조사 기록을 관리할 때 | `business-research로 [고객 문제]의 수요와 현재 대안을 조사해줘.` |
| [business-plan-review](business-plan-review/SKILL.md) | 작성한 실행 계획의 고객 가치, 획득 경로, 비용, 1인 운영 범위와 검증 방법을 검토할 때 | `business-plan-review로 이 고객 검증 계획을 검토해줘. [계획]` |
| [grilling](grilling/SKILL.md) | 계획·설계·결정의 빈틈을 질문으로 짚고, 답변에 따라 구체화할 때 | `grilling으로 이 계획에서 빠진 결정을 질문해줘. [계획]` |
| [grill-me](grill-me/SKILL.md) | `grilling`을 호출하는 짧은 진입점이 필요할 때 | `grill-me로 이 설계를 검토해줘. [설계]` |

`office-hours`는 초기 문제 진단, `business-research`는 근거 조사, `business-plan-review`는 실행 계획 검토에 맞습니다. 필요한 작업부터 선택하면 됩니다. `grill-me`의 현재 파일은 `grilling` 호출 지침만 담고 있습니다.

## 브라우저·글쓰기·제품 시연

| 스킬 | 언제 쓰나 | 요청 예시 |
| --- | --- | --- |
| [aside-browser](aside-browser/SKILL.md) | Aside로 웹 조사, 로그인된 브라우저 조작, 스크린샷, 다운로드, 웹 화면 검증을 할 때 | `aside-browser로 [사이트]의 신청 흐름을 확인해줘.` |
| [humanize-korean](humanize-korean/SKILL.md) | 한글 글의 번역투·기계적인 문장 패턴을 진단하고 원문의 사실과 문체를 보존해 다듬을 때 | `humanize-korean으로 이 글을 자연스럽게 다듬어줘. [원문]` |
| [stageshow](stageshow/SKILL.md) | 제품 소개에 쓸 앱 화면 일러스트나 커서가 움직이는 시연 애니메이션을 만들 때 | `stageshow로 검색 결과가 나타나는 제품 시연 애니메이션을 만들어줘.` |

Aside 작업에는 Aside CLI와 브라우저 연결이 필요합니다. `stageshow`는 React·CSS로 제품 화면과 동작을 연출합니다.

## Instagram 콘텐츠 제작과 운영

| 스킬 | 언제 쓰나 | 요청 예시 |
| --- | --- | --- |
| [ig-reel](ig-reel/SKILL.md) | 릴스 후킹 문장 3개, 대본, 화면 자막과 시간 구성을 만들 때 | `$ig-reel [실제로 겪은 일]을 30초 릴스 대본으로 만들어줘.` |
| [ig-caption](ig-caption/SKILL.md) | 캡션을 쓰고 첫 125자 미리보기, 길이, 해시태그와 행동 유도 문구를 점검할 때 | `$ig-caption 이 릴스의 캡션을 써줘. [대본]` |
| [ig-carousel](ig-carousel/SKILL.md) | 카드뉴스의 표지·슬라이드별 문구를 구성하고 승인 후 이미지 파일 제작을 진행할 때 | `$ig-carousel [내용]을 7장 카드뉴스로 구성해줘.` |
| [ig-story](ig-story/SKILL.md) | 하루 스토리의 장면 순서, 화면 문구와 투표·질문·링크 스티커를 구성할 때 | `$ig-story [오늘 있었던 일]로 스토리 5장을 구성해줘.` |
| [ig-profile](ig-profile/SKILL.md) | 프로필을 자체 12개 항목으로 평가하고 이름·소개·링크·고정 게시물 등의 개선안을 받을 때 | `$ig-profile 이 프로필을 평가하고 소개 문구를 고쳐줘. [프로필 자료]` |
| [ig-plan](ig-plan/SKILL.md) | 한 주의 콘텐츠 주제, 형식, 게시 일정과 교류할 계정을 계획할 때 | `$ig-plan [대상 독자와 주제]에 맞춰 이번 주 콘텐츠를 계획해줘.` |
| [ig-human](ig-human/SKILL.md) | 영어 초안의 상투적인 표현·특수문자·문장 패턴을 정리하고 자체 규칙으로 점검할 때 | `$ig-human 이 영어 캡션을 자연스럽게 다듬어줘. [원문]` |
| [ig-comment](ig-comment/SKILL.md) | 다른 사람의 게시물에 달 댓글 초안을 만들 때 | `$ig-comment 이 게시물에 내 경험을 보태는 댓글을 써줘. [게시물과 내 경험]` |
| [ig-reply](ig-reply/SKILL.md) | 내 게시물에 달린 댓글을 유형별로 분류하고 답글 초안을 만들 때 | `$ig-reply 내 게시물에 달린 댓글의 답글을 써줘. [댓글 목록]` |
| [ig-dm](ig-dm/SKILL.md) | 요청 자료 전달, 첫 대화, 협업 제안과 후속 연락용 DM 초안을 만들 때 | `$ig-dm 자료를 요청한 사람에게 보낼 전달 메시지를 써줘. [맥락]` |
| [ig-repurpose](ig-repurpose/SKILL.md) | 긴 영상·팟캐스트·글에서 독립적인 소재를 뽑아 여러 콘텐츠로 재구성할 때 | `$ig-repurpose 이 글에서 릴스와 카드뉴스 소재를 뽑아줘. [원문]` |
| [ig-audit](ig-audit/SKILL.md) | 제공한 게시물·인사이트에서 성과 차이를 분석하고 다음 콘텐츠 방향을 정할 때 | `$ig-audit 최근 게시물의 성과를 비교해줘. [게시물별 지표]` |
| [ig-viral](ig-viral/SKILL.md) | 분야별 릴스 사례를 조사하고 각 계정의 평소 조회수 대비 성과와 후킹 패턴을 비교할 때 | `$ig-viral [분야]의 릴스 사례를 조사하고 참고할 패턴을 정리해줘.` |

### 실행 전에 알아둘 점

- Instagram 스킬은 콘텐츠·메시지 초안과 분석을 제공합니다. 게시와 발송은 사용자가 진행합니다.
- `ig-reel`은 말투 프로필이 없으면 본인의 릴스 3개를 요청하도록 되어 있습니다. 실제 사건, 수치, 결과를 제공하면 대본을 구체화할 수 있습니다.
- 원본의 말투·참고 사례·기록 파일 경로는 `~/.claude/instagram/`입니다. Codex에서도 이 경로를 참조합니다.
- Python 도구 6개는 표준 라이브러리로 실행됩니다. 후킹·문체 점수와 발화 시간 계산은 영어 중심이므로 한국어에 적용할 때 해석에 주의가 필요합니다. 한글 윤문에는 `humanize-korean`을 선택할 수 있습니다.
- `ig-viral`의 실제 사례 수집에는 브라우저 접근이나 사용자가 제공한 자료가 필요합니다. 카드뉴스 이미지 제작에는 렌더링 도구가 필요합니다.
- 스킬에 적힌 플랫폼 수치와 운영 요령은 작성 당시 기준일 수 있습니다. 현재 사양이 중요한 작업에서는 공식 자료를 확인합니다.

Instagram 스킬 13개의 원본은 [Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)이며 MIT 라이선스입니다. 각 스킬 폴더의 `LICENSE`에 원본 고지가 있습니다.

## 새 스킬을 추가할 때

해당 스킬의 `SKILL.md`를 읽고 이 안내의 알맞은 표에 용도와 요청 예시를 한 줄 추가합니다. 실행 절차나 상세 설정은 각 `SKILL.md`에서 관리하고, 이 파일은 사람이 스킬을 찾는 안내로 사용합니다.
