---
layout: two-cols
---

# Test design

- focusing on behaviors
- arrange - act - assert
- testing patterns


::right::
<img src="/images/project_1.png" class="w-80 my-15" />
<img src="/images/aaa.png" class="w-80 mt-10" />

<style>
.slidev-layout li {
  font-size: 1.7rem;
}
.slidev-layout ul {
  padding-top: 25%;
}
</style>

<!--
- quoting Kent C. Dodds - The more your tests resemble the way your software is used, the more confidence they can give you.
- ideally, tests focus on risk mitigation, so behaviors that are most critical are covered first
- as project scales up, when you group things by behavior, they will naturally fall into project structure
- the big question is oftentimes which pattern to choose - POM, Custom commands, BDD,... - which one is the best?
- the problem with that is that no approach is the best, because you cannot apply one way of doing things into different projects
- the good thing about scaling is that the project itself will "guide" you to the best practice
- but there are definitely things to be aware of - e.g. when doing abstractions
-->

---
src: ./05a_abstractions.md
---
