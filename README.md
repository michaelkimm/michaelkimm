### Hi there 👋

 저는 웹의 생태계가 내포하는 **공유의 가치**를 지향합니다. 이에 저와 사회가 **함께 성장하는 환경을 조성하는데 기여**하고 있습니다. 
 
 1. 더 깊이 있고 근거에 기반한 지식을 쌓기 위해 [토이 프로젝트](https://github.com/f-lab-edu/resell-platform)에서 사용자 API 내 **기술 선택 시 여러 솔루션의 장단점과 사용자 UX의 Trade off를 고려**했습니다. 
 2. 서비스 개발은 많은 팀원을이 **협업**하여 이뤄내는 것이기 때문에 **Issue, PR, Wiki 등 문서화**에 관심이 많습니다.
 3. [티스토리 블로그](https://ujkim-game.tistory.com/) 에서는 사회의 성장에 기여하기 위해 **제가 재생산한 지식과 의견을 주기적으로 작성**했습니다. 

**About me:)**

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
                .techSkills({"Spring🌱, Spring Security🔐, Mysql🐬"})
                .interests({"루틴", "명상", "운동👯"})
                .build();

        introduce(minsuk);
    }
}
```

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
