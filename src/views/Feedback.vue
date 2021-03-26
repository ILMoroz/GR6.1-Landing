<template>
    <div id="layout-feedback" >
        <div class="layout-content-feedback">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-5">
                        <div class="desc-feedback">
                            Форма
                            обратной
                            связи
                        </div>
                    </div>
                    <div class="col-lg-4 offset-1">
                        <div class="form-feedback">
                            <form action="">
                                <div class="form-group">
                                    <label for=""> Имя <br>
                                        <input placeholder="Введите Имя" type="text">
                                    </label>
                                </div>
                                <div class="form-group">
                                    <label for="">
                                        Ваша почта <br>
                                        <input placeholder="Введите E-Mail" type="text">
                                    </label>
                                </div>
                                <div class="form-group">
                                    <label for="">
                                        Текст обращения <br>
                                        <textarea placeholder="Введите Ваше обращение..." name="" id="" cols="30" rows="10">
                                            Что то 
                                        </textarea>
                                    </label>
                                </div>
                                <div class="form-button">
                                    <button class="btn btn-send">
                                        Отправить
                                        <svg width="32" height="15" viewBox="0 0 32 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M0 7.5H31M31 7.5L24.5 1M31 7.5L24.5 14" stroke="white" stroke-width="1.08333"/>
                                        </svg>
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <Footer />
    </div>
</template>

<script>
import Footer from '@/components/Footer.vue'
export default {
  components: {
    Footer
  }
}
</script>
