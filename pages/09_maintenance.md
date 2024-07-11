---
layout: two-cols
---

# Maintenance

- maintenance vs. development cost
- flaky tests

::right::
<div class="fixed top-35 right-20 w-100">
<img src="/images/speed_improvement.png" />
</div>

<style>
.slidev-layout li {
  font-size: 1.7rem;
}
.slidev-layout ul {
  padding-top: 100px;
}
.two-columns {
  gap: 1rem;
  grid-template-columns: 9fr 10fr !important;
}
</style>

<!--
- as your project grows, it is important to think about the cost of maintenance that you are introducing with every new test
- this graph may not look like this for you today, but it can very well look like that later and driving down that debugging and maintenance time is going to be important
- that’s why today we are talking about readability, and not about which framework runs the fastest on CI

- but when we talk about testing and test code, we cannot really skip talking about the application under test
- all that we said today might be useful, but as you scale up, you are still going to be hitting some flaky test - and they are going to add to your debugging time and to your testing time

- [click]
-->
