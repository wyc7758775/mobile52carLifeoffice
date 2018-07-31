<template>
    <div>
        <div class="header">
            <div class="title">52嗨停</div>
            <div class="search">
                <i class="el-icon-search"></i>
                <i class="el-icon-tickets"></i>
            </div>
        </div>

    </div>
</template>

<script>
export default {
  name: "vheader"
};
</script>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  height: rgb(255,255,255);
  padding: 2vw 0;
}
.title{
    padding-left: 3vw;
    font-size: 6vw;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(65,137,220);
}
.search{
    font-size: 6vw;
    padding-right: 3vw;
}
</style>
