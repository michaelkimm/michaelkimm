## Hi there 👋

 저는 웹의 생태계가 내포하는 **공유의 가치**를 지향합니다. 이에 저와 사회가 **함께 성장하는 환경을 조성하는데 기여**하고 있습니다. 
 
 **팀원이 main에서 branch를 파지 않고 fork 해서 작업 후 fork된 repo를 지우다가 원본 repo(웹 백엔드 api, resell-platform repo)를 지운 상황이 발생**했습니다. 코드와 ReadMe는 local에도 존재하기 때문에 백업이 바로 가능하지만, WIKI와 issue, pr 및 pr 리뷰 기록은 github에 바로 저장되는 것이라서 바로 백업이 어렵습니다. 현재 Github 회사와 컨택하며 원본 repo를 복구하기 위해 노력중입니다.
 
  **앞으로 이런 일이 일어나지 않게 하고, 일어나더라도 피해를 최소화** 하기 위해 다음과 같은 대책을 마련했습니다.
  1. **WIKI**까지 따로 백업 해두는 방안을 마련하겠습니다. 
  2. 팀원과 github 사용 방법을 재정비하여 실수가 일어나지 않도록 대비하겠습니다.
 
 *복구가 정상적으로 되기 전에 기업 서류 평가가 이뤄질 수 있어 resell-platform-temporary 프로젝트 임시 복구한 상황입니다. 임시 repo의 WIKI는 온전한 상태가 아니지만, 빠르게 복구하여 기업 서류 제출에 문제 없도록 하겠습니다.
 
### **About me:)**

``` java
package p2p.introduction.domain;

@Builder
class Member {
    String name;
    String job;
    String[] developmentFields;
    String[] languages;
    String[] techSkills;
    String[] interests;
}

public class Main() {
    public static void main(String[] args) {
    
        Member minsuk = Member.builder()
                .name("김민석")
                .job("Software engineer🧑🏽‍💻")
                .developmentFields({"Back-end🔭"})
                .languages({"java☕"})
                .techSkills({"Spring🌱, Spring Security🔐, Mysql🐬, MyBatis🦤"})
                .interests({"루틴", "명상", "운동👯"})
                .build();

        introduce(minsuk);
    }
}
```

## Hard Skill
 1. 더 깊이 있고 근거에 기반한 지식을 쌓기 위해 **기술 선택 시 여러 솔루션의 장단점과 사용자 UX의 Trade off를 고려**했습니다. 
     - [사용자의 UX를 고려한 JWT 로그인 보안 전략 수립 및 구현](https://ujkim-game.tistory.com/74)
     - [브루트포스 공격 특성을 고려한 비밀번호 해싱 알고리즘 선정 및 적용](https://ujkim-game.tistory.com/67).
     - [Filter를 사용하여 반복되는 응답 로직 제거(feat.StandardResponse)](https://ujkim-game.tistory.com/72)
     - [집합의 개념과 이상현상을 고려한 ERD 설계](https://ujkim-game.tistory.com/63)
     - [제한된 메모리 크기 환경에서의 LinkedList와 HashMap 튜닝 방법](https://ujkim-game.tistory.com/75)


 2. 알고리즘 문제 **1일 1커밋 지향**
     - 모든 알고리즘 문제의 해결법 **사고 과정 글로 정리**.
     - 문제를 나만의 언어로 추상화 하고 이를 요구사항(시간, 공간 복잡도)에 맞는 적절한 자료구조와 알고리즘을 선정하는 **사고 과정**이 중요하다고 생각합니다. 이에 **모든 사고 과정을 글로 정리**하고 있습니다. 정리된 글은 [Algorithm_diary repository](https://github.com/michaelkimm/Algorithm_diary)에서 확인할 수 있습니다. 더 많은 사람과 공유하기 위해 블로그로 옮길 예정입니다.
 
 
## Soft SKill
 1. 서비스 개발은 많은 팀원을이 **협업**하여 이뤄내는 것이기 때문에 **Issue, PR, Wiki 등 문서화**에 관심이 많습니다.
 2. [티스토리 블로그](https://ujkim-game.tistory.com/) 에서는 사회의 성장에 기여하기 위해 **제가 재생산한 지식과 의견을 주기적으로 작성**했습니다. 



<!--
**michaelkimm/michaelkimm** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
