<template>
    <div class="list-item editingClass editing">
        <label class="checkbox">
            <input type="checkbox" v-model="item.checked" >
            <span class="checkobx-custom"></span>
        </label>
        <input type="text" v-model="item.text" placeholder="write something">
        <a class="delete-item">
            <span class="icon-trash"></span>
        </a>
    </div>
</template>
<script>
export default {
  props: [' item']
}
</script>

<style lang="less" scoped>
@import "../common/style/list-items.less";
</style>
