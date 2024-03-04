<script >

</script>

<template>
  <main>
<div class="all">
  <h1 class="mb-3 mt-5 text-3xl font-bold pl-5">購買確認及填寫資訊</h1>
  <table class="table-auto border-y-2 border-t-2 border-gray-300">
  <thead >
    <tr>
      <th>商品圖片</th>
      <th>商品名稱</th>
      <th>價錢</th>
      <th>數量</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="../assets/image/300x300.png" class="h-32 w-32"> </td>
      <td>lolipop</td>
      <td>$670</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
<div class="input ml-32 mt-12">
<div class="name text-xl font-bold">姓名</div>
<input type="text" class="text border-solid border-2 border-black-600 rounded-md mt-2">
</div>
<div class="input ml-32 mt-12">
<div class="name text-xl font-bold">電話</div>
<input type="tel" class="text border-solid border-2 border-black-600 rounded-md mt-2">
</div>
<div class="input ml-32 mt-12">
<div class="name text-xl font-bold">地址</div>
<input type="text" class="text border-solid border-2 border-black-600 rounded-md mt-2">
</div>
<div class="input ml-32 mt-12">
<div class="name text-xl font-bold">電子信箱</div>
<input type="email" class="text border-solid border-2 border-black-600 rounded-md mt-2">
</div>
<div class="input ml-32 mt-12">
  <div class="name text-xl font-bold">付款方式</div>
  <input type="radio" name="payment" class="mt-5">信用卡
  &nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;
  <input type="radio" name="payment">貨到付款
</div>
<div class="input ml-32 mt-12">
  <div class="name text-xl font-bold">運送方式</div>
  <input type="radio" name="delivery" class="mt-5">宅配
  &nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;
  <input type="radio" name="delivery">超商取貨
</div>

<div class="goods flex p-5 flex-col">
<h1 class="mt-2 text-3xl font-bold pl-5">商品數量:1</h1>
<h1 class="mt-2 text-3xl font-bold pl-5">商品金額:670</h1>
</div> 

<div class="down flex mb-24 mt-20 ml-32 gap-96">
<button class="bg-red-800 text-stone-50 btn">回上頁繼續加購</button>
<button class="bg-blue-800 text-stone-50 ml-72 btn">確認送出</button>
</div>


 

  </div>
  </main>
</template>

<style scoped>

.table-auto {
  margin: auto;
  border-collapse: separate;
  border-spacing: 200px 10px;
 
}

.text{
  width: 1200px;
}

.goods{
  margin-left: 1100px;
}

.btn{
  width: 150px;
  height: 40px;
  border-radius: 10px;

}

</style>

