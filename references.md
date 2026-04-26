# 참고와 인용

이 책은 안드레이 카파시의 공개 강의와 인터뷰를 중요한 출발점으로 삼습니다. 그렇지만 이 책은 강의록이나 인터뷰를 그대로 옮긴 번역본이 아닙니다. 카파시가 LLM과 에이전트를 설명할 때 사용하는 큰 흐름, 직관, 몇몇 예시를 바탕으로 삼되, 고려대학교 보건과학대학 바이오시스템의과학부 1학년 학생들이 읽을 수 있도록 한국어 산문으로 다시 구성한 해설서입니다.

본문에서 카파시의 설명 순서나 특정 예시를 직접 따라가는 곳에는 가까운 자리에 출처를 표시합니다. 본문 인용 링크는 가능한 한 참고문헌 페이지가 아니라 영상의 해당 시점으로 바로 연결합니다. 직접 인용은 필요한 경우에만 짧게 사용하고, 대부분의 설명은 의생명과학 학생을 위한 맥락에 맞추어 다시 씁니다.

본문의 영상 인용은 독자의 읽기 흐름을 끊지 않기 위해 ` ([링크](...))`처럼 앞말과 한 칸 띄어 표시합니다. 시간 정보는 문장 안에 쓰지 않고, YouTube URL의 `t=` 값 안에만 남깁니다.

<a id="deep-dive-into-llms-like-chatgpt"></a>

**Deep Dive into LLMs like ChatGPT**

Karpathy, A. (2025, February 5). *Deep Dive into LLMs like ChatGPT* [Video lecture]. YouTube.

https://www.youtube.com/watch?v=7xTGNNLPyMI

이 책에서 LLM의 전체 제작 과정, 토큰화, 사전학습, Transformer, assistant로의 후속 훈련, hallucination, 문맥 창, 도구 사용, reasoning model, reinforcement learning을 설명할 때 가장 자주 참고하는 자료입니다.

주요 연결 지점:

- 00:00:00: 전체 강의의 문제의식 ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=0s))
- 00:01:47: FineWeb과 Common Crawl ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=107s))
- 01:56:21: "models need tokens to think" ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=6981s))
- 02:11:10: 강화학습을 학교 공부에 비유하는 대목 ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=7870s))
- 02:33:12: reasoning model ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=9192s))
- 03:09:26: 에이전트와 사람의 감독 ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=11366s))
- 03:21:24: ChatGPT 입력창 뒤에서 일어나는 일의 요약 ([링크](https://www.youtube.com/watch?v=7xTGNNLPyMI&t=12084s))

<a id="summoning-ghosts-not-building-animals"></a>

**Andrej Karpathy -- "We're summoning ghosts, not building animals"**

Patel, D. (2025, October 17). *Andrej Karpathy -- "We're summoning ghosts, not building animals"* [Interview with Andrej Karpathy]. YouTube.

https://www.youtube.com/watch?v=lXUZvyajciY

이 책에서 "에이전트의 해"가 아니라 "에이전트의 10년"이라는 시간 감각, AI가 생물학적 지능과 다른 방식으로 만들어진다는 관점, AI 시대의 교육과 tutor, 지식으로 가는 ramp를 설명할 때 참고하는 인터뷰입니다.

주요 연결 지점:

- 00:00:00: "에이전트의 해"가 아니라 "에이전트의 10년"이라는 시간 감각 ([링크](https://www.youtube.com/watch?v=lXUZvyajciY&t=0s))
- 02:00:49: 좋은 tutor의 역할 ([링크](https://www.youtube.com/watch?v=lXUZvyajciY&t=7249s))
- 02:02:34: 지식으로 올라가는 ramp ([링크](https://www.youtube.com/watch?v=lXUZvyajciY&t=7354s))

<a id="skill-issue-code-agents-autoresearch"></a>

**Skill Issue: Andrej Karpathy on Code Agents, AutoResearch, and the Loopy Era of AI**

No Priors. (2026, March 20). *Skill Issue: Andrej Karpathy on Code Agents, AutoResearch, and the Loopy Era of AI* [Interview with Andrej Karpathy]. YouTube.

https://www.youtube.com/watch?v=kwSVtQ7dziU&t=69s

이 책에서 vibe coding, 의도 구현(manifesting), AI 에이전트, AutoResearch, 연구 자동화, 에이전트형 작업 흐름을 생각할 때 참고하는 인터뷰입니다.

주요 연결 지점:

- 00:00:00: code라는 동사와 의도 구현(manifesting) ([링크](https://www.youtube.com/watch?v=kwSVtQ7dziU&t=0s))
- 00:03:40: 여러 에이전트를 통한 macro action ([링크](https://www.youtube.com/watch?v=kwSVtQ7dziU&t=220s))
- 00:16:11: AutoResearch의 동기와 목표 ([링크](https://www.youtube.com/watch?v=kwSVtQ7dziU&t=971s))

<a id="andrej-karpathy-home"></a>

**Andrej Karpathy**

Karpathy, A. (n.d.). *Andrej Karpathy*.

https://karpathy.ai/

카파시의 이력과 교육 활동을 소개할 때 참고한 개인 홈페이지입니다.

## 더 읽을거리

**Training language models to follow instructions with human feedback**

Ouyang, L., Wu, J., Jiang, X., et al. (2022). *Training language models to follow instructions with human feedback*. arXiv.

https://arxiv.org/abs/2203.02155

7장에서 사람 labeler, labeling instruction, RLHF가 assistant의 말투와 행동을 바꾸는 과정을 더 깊게 보고 싶을 때 읽을 수 있는 논문입니다.

**The Llama 3 Herd of Models**

Dubey, A., Jauhri, A., Pandey, A., et al. (2024). *The Llama 3 Herd of Models*. arXiv.

https://arxiv.org/abs/2407.21783

8장에서 Llama 계열 모델과 hallucination 완화, post-training, 안전성 평가를 더 자세히 살펴보고 싶을 때 참고할 수 있는 기술 보고서입니다.
