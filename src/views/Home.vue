<template>
  <div id="layout-home">
    <Header/>
    <div class="layout-content">
      <div class="container-fluid">
        <div class="row align-items-center">
          <div class="col-lg-6">
              <div class="l-h-img">
                  <img src="../assets/img/ed4m.png">
              </div>
          </div>
          <div class="col-lg-4 offset-1">
              <div class="l-h-text">
                  <div class="l-h-name">
                    СИМУЛЯЦИЯ
                    ЖЕЛЕЗНОЙ
                    ДОРОГИ
                  </div>
                  <div class="l-h-desc">
                    Ты сможешь управлять прототипами
                    поездов! Более 40 единиц подвижного
                    состава, реалистичное управление
                    и уникальный геймплей ждёт тебя!
                  </div>
                  <button class="btn btn-startgame">
                    Начать игру
                    <svg width="32" height="15" viewBox="0 0 32 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path d="M0 7.5H31M31 7.5L24.5 1M31 7.5L24.5 14" stroke="black" stroke-width="1.08333"/>
                    </svg>  
                  </button>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
export default {
  name: 'Home',
  components: {
    Header
  }
}
</script>
