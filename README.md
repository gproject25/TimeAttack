

[타임어택] git 협업 흐름으로 자기소개 페이지 만들기

Repository 구조:
    - README.md
    - members
        - about.md
        - skills.md
        - goals.md
        - tmi.md



작업 단위 브랜치 계획
1. feature/readme
2. feature/about: 간단한 자기소개 (members/about.md)
3. feature/skills: 관심 있는 기술 (members/skills.md)
4. feature/goals: 단기/장기 목표 (members/goals.md)
5. feature/TMI: 취미활동 (members/TMI.md)

각 작업은 독립적인 브랜치에서 진행됩니다 (ex: feature/skills -> 기술 작성).

작업이 완료될 때마다 Pull Request를 생성하여 순차적으로 병합할 예정

