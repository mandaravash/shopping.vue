<script >

</script>

<template>
  <main>
<div class="all">
  <h1 class="mb-3 mt-5 text-3xl font-bold pl-5">購物車確認</h1>
  <table class="table-auto border-y-2 border-t-2 border-gray-300">
  <thead>
    <tr>
      <th></th>
      <th>商品圖片</th>
      <th>商品名稱</th>
      <th>價錢</th>
      <th>數量</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><input type="checkbox" class="h-4 w-4"></td>
      <td><img src="../assets/image/300x300.png" class="h-32 w-32"> </td>
      <td>lolipop</td>
      <td>$670</td>
      <td>
        <div class="add-area flex mt-2 ml-5">
          <button class="plus h-5 w-6 rounded border">+</button>
          <input type="number" class="border-2 border-gray-300 h-8 w-16 ">
          <button class="cut h-5 w-6 rounded border">-</button>
        </div>
      </td>
    </tr>
  </tbody>
</table>

<div class="goods flex p-5 flex-col">
<h1 class="mt-2 text-3xl font-bold pl-5">商品數量:1</h1>
<h1 class="mt-2 text-3xl font-bold pl-5">商品金額:670</h1>
</div> 

<div class="down flex mb-24 mt-20 ml-32 gap-96">
<button class="bg-red-800 text-stone-50 btn">回上頁繼續購買</button>
<button class="bg-blue-800 text-stone-50 ml-72 btn">確認購買</button>
</div>

  </div>
  </main>
</template>

<style scoped>

.table-auto {
  margin: auto;
  margin-top: 60px;
  border-collapse: separate;
  border-spacing: 150px 20px;
 
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

</style>

