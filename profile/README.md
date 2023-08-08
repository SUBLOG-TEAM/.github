# SUBLOG

안녕하세요. 팀 서브로그의 Organizations 입니다! 😄

---

### 🥥 Git-Flow 브랜치 전략

**Git-Flow 브랜치 전략**에 따라 기능별로 브랜치를 나누어 작업하고 있고 모든 브랜치에 대해 pull request를 통한 리뷰 완료 후 Merge를 하고 있습니다.

![1](https://github.com/COCONUT-TEAM/backend/assets/7845568/24866eab-aa99-44fb-acb4-7b7a3619ef28)

✅ master : 제품으로 출시될 수 있는 브랜치

✅ develop : 다음 출시 버전을 개발하는 브랜치. feature에서 리뷰완료한 브랜치를 Merge

✅ feature : 기능을 개발하는 브랜치

✅ hotfix : 출시 버전에서 발생한 버그를 수정하는 브랜치

#### 참고문헌

- [우아한 형제들 기술블로그 "우린 Git-flow를 사용하고 있어요"](https://woowabros.github.io/experience/2017/10/30/baemin-mobile-git-branch-strategy.html)
- [README 참고](https://github.com/f-lab-edu/event-recommender-festa)

### 🥥 PR 규칙

- 신규개발 건은 `develop` 을 base로 `feature/#이슈번호` 의 브랜치명으로 생성 후 작업한 다음 PR을 날립니다.
- 백엔드 파트는 `backend` 라벨을 달고, 프론트 파트는 `fronted` 라벨을 답니다.
- 모든 PR은 반드시 코드리뷰를 받는 것을 권장합니다.
- 로컬에서 작업한 기능은 `Squash Push`를 사용하고, PR 은 `Merge Request`를 사용합니다.

## 🥥 DB ERD 구조
