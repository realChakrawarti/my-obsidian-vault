---
date: 2022-12-14
---

- To calculate performance/benchmark, mostly network fetch or some async events we can use [performance.now()](https://developer.mozilla.org/en-US/docs/Web/API/Performance/now) but DON'T instead we use Date.now(). Despite having higher precision than Date.now(), the reason for not using performance [[Web API]] is due to 2018 [Spectre](https://spectreattack.com/) vulnerability. 