---
title: 生产计划
type: guide
order: 2
---

## 生产计划

生产计划是对应生产系统所做的一系列计划，可以在不同的生产计划上做多个版本的修改，可以实时的进行报工，对其完成的数量也可以进行实时的监控
![The Vue Instance Lifecycle](/images/plan.png)
## 计划版本
生产计划版本内容
![The Vue Instance Lifecycle](/images/planVersion.png)

## 版本明细
版本明细内容
![The Vue Instance Lifecycle](/images/planVersionDetail.png)

<script>
var app5 = new Vue({
  el: '#app-5',
  data: {
    message: 'Hello Vue.js!'
  },
  methods: {
    reverseMessage: function () {
      this.message = this.message.split('').reverse().join('')
    }
  }
})
</script>

<script>
Vue.component('todo-item', {
  props: ['todo'],
  template: '<li>{{ todo.text }}</li>'
})
var app7 = new Vue({
  el: '#app-7',
  data: {
    groceryList: [
      { id: 0, text: 'Vegetables' },
      { id: 1, text: 'Cheese' },
      { id: 2, text: 'Whatever else humans are supposed to eat' }
    ]
  }
})
</script>
