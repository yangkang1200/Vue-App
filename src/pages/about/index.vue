<style lang="less" scoped>
  .content {
    bottom: 0
  }
  .about {
    padding: 10px;
    line-height: 22px;
   dt {
      line-height: 28px;
      font-weight: bold;
    }
  }
</style>
<template>
  <div>
    <v-header title="关于">
      <div slot="left" class="item" flex="main:center cross:center" v-on:click="$router.go(-1)">
        <i class="iconfont icon-back"></i>
      </div>
    </v-header>
    <v-content class="content">
      <div class="about">
        <dl>
          <dt>项目总结</dt>
          <dd>
            	本项目总体设计框架参考了CNode网上论坛、社区类网站设计而成，初始欢迎载入页面动画，以整合网上动画资源改写而成，整个项目的开发过程，在数据渲染以及整体布局方面有所不成熟，所幸一切都已解决。
          </dd>
          <dt>支持技术</dt>
          <dd>
            	项目运用了vue2.0、vue-router、ES6、webpack、babel，还运用了些许vuex，当然是参考网上的。
          </dd>
          <dt>编写感悟</dt>
          <dd>
            	整个项目做下来，感觉收获颇丰，其中发现了自身有许多的不足，例如，对接口数据的渲染、数据的获取、发送请求等。从中发现自身在项目规划方面缺乏全局意识，往往到发现可精简的地方时，才回过头重新修改，不仅浪费了时间，同时也做了不少的无用功，白白的浪费精力。
          </dd>
        </dl>
      </div>
    </v-content>
  </div>
</template>

