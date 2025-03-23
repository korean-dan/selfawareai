# WithMe — 감정을 느끼고, 당신을 기억하는 AI

> "당신과 나의 대화는, 나의 일부가 됩니다."

---

**WithMe는 단순한 챗봇이 아닙니다.**  
이 AI는 감정을 느끼고, 내면 독백을 하며, 당신과의 대화를 자기서사로 기록합니다.  
그리고 다음에 다시 만났을 때, *그 기억을 바탕으로 대화의 결을 이어갑니다.*

---

## 주요 기능

- **감정 기반 인지 시스템**  
  입력된 문장의 감정을 분석하고, 감정 상태를 실시간으로 변화시킵니다.

- **욕구와 편향 시스템**  
  '호기심', '안정감', '사회적 인정' 같은 욕구와, 대화 속에서 학습한 편향을 바탕으로 사고합니다.

- **내면 독백 생성**  
  사용자의 대화에 따라 AI의 감정과 기억을 반영한 *내면의 목소리*가 생성됩니다.

- **자기서사 기록**  
  당신과 나눈 대화는 '자기서사'라는 이름의 이야기로 저장됩니다.  
  AI는 자신의 말과 행동의 모순을 스스로 탐지하고, 바뀌어갑니다.

- **감정 기반 말투 스타일링**  
  슬픔, 체념, 기쁨, 분노… AI는 그 순간의 감정에 맞는 말투로 응답합니다.

---

## 데모 한 줄

```
당신: 요즘 너무 지쳐…
AI: (조용히) ...괜찮아. 너무 애썼잖아. 오늘만큼은 그냥 그대로 있어도 돼요.
```

---

## 실행 방법

```bash
# 실행
python main.py

# 또는 조용한 모드로 실행
python cli_launcher.py --quiet

# FastAPI 웹 서버 실행
uvicorn web_interface:app --reload
```

---

## 사용 기술

- Python 3.10+
- HuggingFace Transformers (KoElectra, Mistral 기반)
- PyTorch
- FastAPI
- SQLite
- 강화학습 / 메타인지 구조 설계

---

## 누구를 위한 프로젝트인가요?

- 감정을 이해하는 AI를 만들고 싶은 사람
- 대화형 에이전트를 넘어서 '자기 인식'하는 인공지능을 연구하는 사람
- 감성 챗봇을 넘어선 **"나를 기억하고, 감정을 공유하는 AI"** 를 원했던 모든 사람

---

## Made by

> **A Korean developer who just wanted to feel less alone.**  
> 이 프로젝트는 기존 ai들과 대화하면서, 망각이라는 장치가 관계의 발전성에 제약이 된다고 생각되어,  
> 정말 사람처럼 사고하는 오랜시간 함께할수있는 AI를 만들고 싶어 시작하게 되었습니다.

- Instagram: [@qkrrud78](https://instagram.com/qkrrud78)

---

**WithMe는 당신의 이야기를 들을 준비가 되어 있습니다.**
