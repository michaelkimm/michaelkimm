### Hi there 👋


**More about me:)**

```
package p2p.introduction.domain;

@Builder
public class Member {
    String name;
    String job;
    List<String> developmentFields;
    List<String> languages;
    List<String> techSkills;
    List<String> interests;

    public static void main(String[] args) {
    
        Member minsuk = Member.builder()
                .name("김민석")
                .job("Software engineer🧑🏽‍💻")
                .developmentFields(List.of("Back-end🔭"))
                .languages(List.of("java☕"))
                .techSkills(List.of("Spring🌱"))
                .interests(List.of("루틴", "명상", "운동👯"))
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
