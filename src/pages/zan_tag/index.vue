<template>
  <div class="container">

    <view class="doc-title zan-hairline--bottom">Tag</view>

    <view class="zan-panel">
      <view class="zan-cell zan-cell--last-child">
        <view class="zan-tag">灰色</view>
        <view class="zan-tag zan-tag--danger">红色</view>
        <view class="zan-tag zan-tag--disabled">不可用</view>
      </view>
    </view>
    <view class="zan-panel">
      <view class="zan-cell zan-cell--last-child">
        <view class="zan-tag zan-tag--danger">会员折扣</view>
        <view class="zan-tag zan-tag--warn">返现</view>
        <view class="zan-tag zan-tag--primary">返现</view>
        <view class="zan-tag zan-tag--primary zan-tag--disabled">不可用</view>
      </view>
    </view>

    <view class="zan-panel">
      <view class="zan-cell zan-cell--last-child">
        <view class="zan-tag zan-tag--plain">灰色</view>
        <view class="zan-tag zan-tag--danger zan-tag--plain">会员折扣</view>
        <view class="zan-tag zan-tag--warn zan-tag--plain">返现</view>
        <view class="zan-tag zan-tag--primary zan-tag--plain">返现</view>
        <view class="zan-tag zan-tag--primary zan-tag--plain zan-tag--disabled">返现不可用</view>
      </view>
    </view>
  </div>
</template>

<script>
  export default {
  }
</script>
<style  scoped >
  .zan-tag + .zan-tag {
    margin-left: 10px;
  }
</style>
