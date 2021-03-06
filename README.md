## Hi there ๐

 ์ ๋ ์น์ ์ํ๊ณ๊ฐ ๋ดํฌํ๋ **๊ณต์ ์ ๊ฐ์น**๋ฅผ ์งํฅํฉ๋๋ค. ์ด์ ์ ์ ์ฌํ๊ฐ **ํจ๊ป ์ฑ์ฅํ๋ ํ๊ฒฝ์ ์กฐ์ฑํ๋๋ฐ ๊ธฐ์ฌ**ํ๊ณ  ์์ต๋๋ค. 
 
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
                .name("๊น๋ฏผ์")
                .job("Software engineer๐ง๐ฝโ๐ป")
                .developmentFields({"Back-end๐ญ"})
                .languages({"javaโ"})
                .techSkills({"Spring๐ฑ, Spring Security๐, Mysql๐ฌ, MyBatis๐ฆค, JUnit5, Mockito๐ธ"})
                .interests({"๋ฃจํด", "๋ช์", "์ด๋๐ฏ"})
                .build();

        introduce(minsuk);
    }
}
```

## Hard Skill
 1. ๋ ๊น์ด ์๊ณ  ๊ทผ๊ฑฐ์ ๊ธฐ๋ฐํ ์ง์์ ์๊ธฐ ์ํด **๊ธฐ์  ์ ํ ์ ์ฌ๋ฌ ์๋ฃจ์์ ์ฅ๋จ์ ๊ณผ ์ฌ์ฉ์ UX์ Trade off๋ฅผ ๊ณ ๋ ค**ํ์ต๋๋ค. 
     - [์ฌ์ฉ์์ UX๋ฅผ ๊ณ ๋ คํ JWT ๋ก๊ทธ์ธ ๋ณด์ ์ ๋ต ์๋ฆฝ ๋ฐ ๊ตฌํ](https://ujkim-game.tistory.com/74)
     - [๋ธ๋ฃจํธํฌ์ค ๊ณต๊ฒฉ ํน์ฑ์ ๊ณ ๋ คํ ๋น๋ฐ๋ฒํธ ํด์ฑ ์๊ณ ๋ฆฌ์ฆ ์ ์  ๋ฐ ์ ์ฉ](https://ujkim-game.tistory.com/67).
     - [Filter๋ฅผ ์ฌ์ฉํ์ฌ ๋ฐ๋ณต๋๋ ์๋ต ๋ก์ง ์ ๊ฑฐ(feat.StandardResponse)](https://ujkim-game.tistory.com/72)
     - [์ ํ๋ ๋ฉ๋ชจ๋ฆฌ ํฌ๊ธฐ ํ๊ฒฝ์์์ LinkedList์ HashMap ํ๋ ๋ฐฉ๋ฒ](https://ujkim-game.tistory.com/75)
     - [์ด์ํ์๊ณผ ์ ๊ทํ ์์ค์ ๊ณ ๋ คํ ERD ์ค๊ณ](https://ujkim-game.tistory.com/64)


 2. ์๊ณ ๋ฆฌ์ฆ ๋ฌธ์  **1์ผ 1์ปค๋ฐ ์งํฅ**
     - ๋ชจ๋  ์๊ณ ๋ฆฌ์ฆ ๋ฌธ์ ์ ํด๊ฒฐ๋ฒ **์ฌ๊ณ  ๊ณผ์  ๊ธ๋ก ์ ๋ฆฌ**.
     - ๋ฌธ์ ๋ฅผ ๋๋ง์ ์ธ์ด๋ก ์ถ์ํ ํ๊ณ  ์ด๋ฅผ ์๊ตฌ์ฌํญ(์๊ฐ, ๊ณต๊ฐ ๋ณต์ก๋)์ ๋ง๋ ์ ์ ํ ์๋ฃ๊ตฌ์กฐ์ ์๊ณ ๋ฆฌ์ฆ์ ์ ์ ํ๋ **์ฌ๊ณ  ๊ณผ์ **์ด ์ค์ํ๋ค๊ณ  ์๊ฐํฉ๋๋ค. ์ด์ **๋ชจ๋  ์ฌ๊ณ  ๊ณผ์ ์ ๊ธ๋ก ์ ๋ฆฌ**ํ๊ณ  ์์ต๋๋ค. ์ ๋ฆฌ๋ ๊ธ์ [Algorithm_diary repository](https://github.com/michaelkimm/Algorithm_diary)์์ ํ์ธํ  ์ ์์ต๋๋ค. ๋ ๋ง์ ์ฌ๋๊ณผ ๊ณต์ ํ๊ธฐ ์ํด ๋ธ๋ก๊ทธ๋ก ์ฎ๊ธธ ์์ ์๋๋ค.
 
 
## Soft SKill
 1. ์๋น์ค ๊ฐ๋ฐ์ ๋ง์ ํ์์์ด **ํ์**ํ์ฌ ์ด๋ค๋ด๋ ๊ฒ์ด๊ธฐ ๋๋ฌธ์ **Issue, PR, Wiki ๋ฑ ๋ฌธ์ํ**์ ๊ด์ฌ์ด ๋ง์ต๋๋ค.
 2. [ํฐ์คํ ๋ฆฌ ๋ธ๋ก๊ทธ](https://ujkim-game.tistory.com/) ์์๋ ์ฌํ์ ์ฑ์ฅ์ ๊ธฐ์ฌํ๊ธฐ ์ํด **์ ๊ฐ ์ฌ์์ฐํ ์ง์๊ณผ ์๊ฒฌ์ ์ฃผ๊ธฐ์ ์ผ๋ก ์์ฑ**ํ์ต๋๋ค. 



<!--
**michaelkimm/michaelkimm** is a โจ _special_ โจ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- ๐ญ Iโm currently working on ...
- ๐ฑ Iโm currently learning ...
- ๐ฏ Iโm looking to collaborate on ...
- ๐ค Iโm looking for help with ...
- ๐ฌ Ask me about ...
- ๐ซ How to reach me: ...
- ๐ Pronouns: ...
- โก Fun fact: ...
-->
