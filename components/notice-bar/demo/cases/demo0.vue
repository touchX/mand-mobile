<template>
  <div class="md-example-child md-example-child-notice-bar md-example-child-notice-bar-0">
    <md-notice-bar>为了确保您的资金安全，请设置支付密码</md-notice-bar>
  </div>
</template>

<script>import {NoticeBar} from 'mand-mobile'

export default {
  name: 'notice-bar-demo',
  title: '基本',
  components: {
    [NoticeBar.name]: NoticeBar,
  },
}
</script>