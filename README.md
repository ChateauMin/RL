# MountainCar-v0 Deep Q-Learning

이 프로젝트는 OpenAI Gym의 `MountainCar-v0` 환경을 해결하기 위한 **딥 Q-러닝(Deep Q-learning)** 알고리즘을 구현한 코드입니다. 강화학습을 통해 에이전트가 자동차를 언덕 위로 밀어 올리는 문제를 풀도록 학습시킵니다.

## 프로젝트 개요

- **환경**: `MountainCar-v0` (OpenAI Gym)
- **목표**: 자동차가 두 언덕 사이를 오르내리는 환경에서, 자동차를 언덕 정상에 도달하게끔 학습하는 것입니다.
- **알고리즘**: 딥 Q-러닝(DQN)을 사용하여, 신경망을 통해 상태-행동 가치 함수(Q-value)를 근사합니다.
- **핵심 아이디어**:
  - 경험 재생(Experience Replay)
  - 타겟 네트워크(Target Network)
  - ε-greedy 정책을 통한 탐험과 활용

## 설치 방법

1. **필수 라이브러리 설치**:
   해당 프로젝트를 실행하려면 먼저 필요한 라이브러리를 설치해야 합니다. 아래 명령어를 사용하여 필요한 라이브러리들을 설치할 수 있습니다.

   ```bash
   pip install gym tensorflow numpy


---

### Markdown 포맷 설명:
- **제목**: `#`과 `##`를 사용해 제목을 작성합니다. GitHub에서는 이들이 자동으로 헤딩으로 표시됩니다.
- **코드 블록**: 코드나 명령어는 ```bash ```나 ```python ``` 등의 구분자로 감싸주면 코드로 구분되어 표시됩니다.
- **목록**: `-`이나 `*`를 사용해 항목을 나열할 수 있습니다. 순서가 중요한 목록은 `1.`, `2.`와 같이 숫자와 점을 사용합니다.
- **링크**: `[텍스트](링크)` 형태로 링크를 추가할 수 있습니다.

이렇게 작성된 **README.md** 파일은 GitHub에서 잘 보이도록 가독성이 높고, 직관적으로 프로젝트를 이해할 수 있게 해줍니다.
