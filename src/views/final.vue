<script >

</script>

<template>
  <main>
<div class="all">
  <h1 class="mb-3 mt-5 text-3xl font-bold pl-5">完成購買</h1>
  <table class="table-auto border-y-2 border-t-2 border-gray-300">
  <thead>
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

<table class="table-auto border-y-2 border-t-2 border-gray-300">
  <thead>
    <tr>
      <th>姓名</th>
      <th>電話</th>
      <th>地址</th>
      <th>付款方式</th>
      <th>電子信箱</th>
      <th>運送方式</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>xxx</td>
      <td>0900000000</td>
      <td>xxx-xxxxxxx-xxx</td>
      <td>貨到付款</td>
      <td>000@gmail.com</td>
      <td>宅配</td>
    </tr>
  </tbody>
</table>

<button class="btn bg-blue-800 text-slate-100 mt-8">回首頁</button>

  </div>
  </main>
</template>

<style scoped>

.table-auto {
  margin: auto;
  margin-top: 60px;
  border-collapse: separate;
  border-spacing: 140px 30px;
 
}

.text{
  width: 1200px;
}

.goods{
  margin-left: 1100px;
}

.plus{
  width: 32px;
  height: 32px;
  border: 1px solid rgb(174, 174, 174);
  border-radius:20px 0%  0% 20px;
  font-size: larger;
}
  .cut{
  width: 32px;
  height: 32px;
  border: 1px solid rgb(174, 174, 174);
  border-radius: 0% 20px 20px 0%;
  font-size: larger;
  }

  .btn{
    width: 100%;
    height: 40px;
    border-radius: 10px;
    
  }

</style>

