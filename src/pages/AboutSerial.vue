<script setup>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";

</script>

<template>
  <div>
    <TheHeader></TheHeader>
    <div class="content">
      <div class="fff">
        <h1>О сериале "Кухня"</h1>
        <p>Для многих кухня — это лишь место, где жарится мясо, сверкают ножи и кипит соус. На самом же деле, кухня — это хранилище свежих секретов, месторождение острых интриг, пышных сплетен и, конечно же, идеальная лаборатория для создания рецепта любви. Ресторан под руководством шеф-повара Виктора Баринова и его команда пережили потоп, пожар, стрельбу, нашествие полтергейстов, облавы госинспекторов, визит президента и переезд в Париж. Здесь билась посуда и разбивались сердца, изобретались шедевры кулинарии и проливалась кровь. Самые крутые повара столицы крушили конкурентов, справлялись с загулами шефа и «гениальными» идеями владельцев!</p>
      </div>
      <div class="fff">
        <h1>главные герои</h1>
        <p>Главные герои сериала - Юлия Варламова, Максим Дрозд, Анастасия Панина, Дмитрий Назаров, Сергей Лавыгин, Мария Голубкина и другие. Сюжет сериала полон юмора, интриг и неожиданных поворотов. "Кухня" завоевала популярность среди зрителей и стала одним из самых успешных российских комедийных сериалов.</p>
      </div>
      <div class="fff">
        <h1>История сериала</h1>
        <p>Телесериал «Кухня» впервые вышел в 2012 году. Его производством занимались компании Yellow, Black and White и KeyStone Production по заказу канала СТС, где он транслировался. «Кухня» растянулась на шесть сезонов и завершилась через четыре года, но собрала несколько спин-оффов и полнометражных фильмов.</p>
      </div>
    </div>
  </div>
  <TheFooter></TheFooter>
</template>

<style scoped>
.content {
  padding-top: 20px;
  padding-left: 10%;
  padding-right: 10%;
  background: url("../assets/image/постер1.jpg") no-repeat fixed;
  width: 100%;
  height: 1220px;
}

.fff {
  background: rgba(12, 9, 9, 0.8);
  border-radius: 20px;
  margin-bottom: 7%;
  margin-top: 100px;
  animation: fadeIn 1s ease-in-out;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

h1 {
  text-align: center;
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 10px;
  color: goldenrod;
}

p {
  width: 100%;
  font-size: 20px;
  line-height: 1.6;
  color: goldenrod;
  text-align: center;
}
</style>