<template>
  <div class="visual-wrap">
    <div class="inner">
      <!-- 왼쪽 -->
      <div class="ma-txt">
        <h4>여행의 시작은 가방도와 함께</h4>
        <h1>여행짐은 가방도에</h1>
        <h1 class="mablue">맡기세요!</h1>
        <button>예약하기 ></button>
      </div>
      <!-- 오른쪽 -->
      <div class="ma-img">
        <img src="/public/images/ma/ma_visual/mavisual.gif" alt="ma-viusal" />
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style scoped>
/* 전체영역 */
.visual-wrap .inner {
  margin-top: 50px;
  display: flex;
  max-width: 1300px;
  /* background-color: antiquewhite; */
}
/* 왼쪽 */
.ma-txt {
  margin-top: 10%;
  margin-right: 5%;
  width: 40%;
  text-align: right;
}
.ma-txt > h4 {
  font-size: 16px;
  color: #5a5a5a;
  margin-bottom: 10px;
}
.ma-txt > h1 {
  font-size: 40px;
  color: #0d0604;
  line-height: 45px;
}
.ma-txt .mablue {
  color: #0066b3 !important;
}
.ma-txt > button {
  width: 200px;
  height: 50px;
  font-size: 20px;
  background: #0066b3;
  color: white;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  transition: 0.3s;
  margin-top: 20px;
}
.ma-txt > button:hover {
  background: #162b50;
}
/* 오른쪽 */
.ma-img {
  width: 60%;
  min-width: 390px;
}
.ma-img > img {
  width: 100%;
}
</style>
