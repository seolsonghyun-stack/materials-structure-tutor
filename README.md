# meterieal structure T

신소재 전공 학부생을 위한 한국어 Codex 스킬입니다. 결정구조, 결함, 결합, 구조와 물성의 관계를 출처가 확인된 그림과 함께 설명합니다. 공간 배치가 중요한 질문에는 직접 회전할 수 있는 3D 모형을 곁들입니다.

## 기능

- 3D 모형을 마우스, 터치 또는 회전 버튼으로 조작합니다.
- 원소와 화학종마다 고유한 색을 지정합니다. 해당 결정상과 기준 자리의 배위수가 출처로 확인되면 배위선과 출처 링크를 표시합니다.
- 단위격자를 각 축에서 1~8개 반복해 결정구조를 살펴볼 수 있습니다.
- 화학식, 결정상, 조건을 원문에서 대조합니다. 실제 구조 데이터와 이상화한 모형을 구분하고, 질문한 개념을 구조의 구체적 위치와 연결해 설명합니다.

## 설치

이 저장소를 내려받아 `SKILL.md`, `agents/`, `assets/`가 들어 있는 폴더를 개인 Codex 스킬 디렉터리에 `materials-structure-tutor`라는 이름으로 넣습니다. 일반적인 경로는 `~/.codex/skills/materials-structure-tutor/`입니다. `CODEX_HOME`을 별도로 설정했다면 그 아래 `skills/`를 사용합니다.

## 사용 예시

> $materials-structure-tutor로 NaCl에서 Cl⁻가 Na⁺를 어떻게 둘러싸는지 설명해줘.

대화에서 인라인 시각화를 지원하면 모형을 그 자리에서 돌려 볼 수 있습니다. 내장 예시는 NaCl의 중심 Na⁺를 둘러싼 Cl⁻ 여섯 개와 단위격자 반복을 보여줍니다. [OpenStax Chemistry 2e §10.6](https://openstax.org/books/chemistry-2e/pages/10-6-lattice-structures-in-crystalline-solids)
