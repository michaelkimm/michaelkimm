## Hi there 👋

 저는 웹의 생태계가 내포하는 **공유의 가치**를 지향합니다. 이에 저와 사회가 **함께 성장하는 환경을 조성하는데 기여**하고 있습니다. 
 
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
     - [제한된 메모리 크기 환경에서의 HashMap 튜닝 방법](https://ujkim-game.tistory.com/70)


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
