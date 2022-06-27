### Hi there 👋


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
