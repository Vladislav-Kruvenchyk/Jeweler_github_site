<template>
  <div class="activity">
    <div class="activity_box_header">
      <div class="activity_block">
        <div class="activity_box_left">
          <div class="activity_box_title">
            <h1 class="activity_title">Текущие и будущие мероприятия</h1>
          </div>
        </div>
        <div class="activity_box_right">
          <div class="activity_slider_right">
            <h1 class="activity_info_right">Все мероприятия</h1>
            <div class="activity_control_right"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="activity_container">
      <div class="activity_wrapper">
        <div class="activity_content">
          <div class="activity_inner">
            <div class="activity_img"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">2 января 2020 г. – 7 января 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">ЭКСПО ЕЛКА</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">Парк интерактивных развлечений</p>
          </div>
        </div>
        <div class="activity_content_one">
          <div class="activity_inner">
            <div class="activity_img_one"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">5 февраля 2020 г. – 9 февраля 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">Junwex Петербург</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">Выставка ювелирных изделий</p>
          </div>
        </div>
        <div class="activity_content_one">
          <div class="activity_inner">
            <div class="activity_img_one"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">7 февраля 2020 г. – 9 февраля 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">Невский ларец</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">
              Выставка-ярмарка народных художественных промыслов и ремесел
            </p>
          </div>
        </div>
        <div class="activity_content">
          <div class="activity_inner">
            <div class="activity_img_one"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">14 февраля 2020 г. – 23 февраля 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">ПОНАЕХАЛИ!</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">Специализированная арт-ярмарка</p>
          </div>
        </div>
        <div class="activity_content_one">
          <div class="activity_inner">
            <div class="activity_img_one"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">18 февраля 2020 г. – 21 февраля 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">VET.CAMP</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">Конференция для ветеринарных врачей</p>
          </div>
        </div>
        <div class="activity_content_one">
          <div class="activity_inner">
            <div class="activity_img_one"></div>
          </div>
          <div class="activity_item">
            <p class="activity_data">26 февраля 2020 г. – 28 февраля 2020 г.</p>
          </div>
          <div class="activity_item">
            <p class="activity_subject">ExpoHoReCa</p>
          </div>
          <div class="activity_item">
            <p class="activity_desc">Специализированная выставка</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Activity",
};
</script>

<style lang="scss" scoped>
.activity {
  width: 100%;
  height: 984px;
  background: #ffc41e;
  &_box_header {
    display: flex;
    width: 100%;
    justify-content: center;
    margin-top: 5rem;
  }
  &_block {
    display: flex;
    width: 1114px;
  }
  &_box_left {
    display: flex;
    width: 50%;
    margin-left: 2rem;
  }
  &_box_title {
    display: flex;
  }
  &_title {
    display: flex;
    justify-content: flex-start;
    font-family: Plumb;
    font-style: normal;
    font-weight: 500;
    font-size: 30px;
    line-height: 130%;
    letter-spacing: -0.01em;
    color: #2e373b;
  }
  &_box_right {
    display: flex;
    width: 50%;
    margin-right: 2rem;
  }
  &_slider_right {
    display: flex;
    justify-content: flex-end;
  }
  &_info_right {
    display: flex;
    width: 12rem;
    font-family: "Plumb";
    font-style: normal;
    font-weight: 500;
    font-size: 21px;
    line-height: 130%;
    text-align: right;
    letter-spacing: -0.01em;
    text-decoration-line: underline;
    color: #2e373b;
  }
  &_control_right {
    display: flex;
    width: 32px;
    height: 14px;
    margin-top: 8px;
    background: url("../assets/img/block_activity/Arrow 1 (1).png");
    background-size: cover;
  }
  // Контент блока
  &_container {
    display: flex;
    width: 100%;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 4rem;
  }
  &_wrapper {
    display: flex;
    width: 1114px;
    height: 800px;
    flex-wrap: wrap;
    justify-content: center;
  }
  &_content {
    display: flex;
    flex-direction: column;
    width: 21rem;
    height: 24rem;
  }
  &_content_one {
    display: flex;
    flex-direction: column;
    width: 21rem;
    height: 24rem;
    margin-left: 1rem;
  }
  &_inner {
    display: flex;
  }
  &_img {
    width: 350px;
    height: 240px;
    background: url("../assets/img/block_activity/Rectangle 8.png");
    background-size: cover;
  }
  &_img_one {
    width: 350px;
    height: 240px;
    background: url("../assets/img/block_activity/Rectangle 8 (1).png");
    background-size: cover;
  }
  &_item {
    display: flex;
  }
  &_data {
    font-family: "Circe";
    height: 1.4rem;
    margin-top: 15px;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 135%;
    color: #2e373b;
  }
  &_subject {
    font-family: "Plumb";
    margin-top: 15px;
    font-style: normal;
    font-weight: 500;
    font-size: 21px;
    line-height: 130%;
    letter-spacing: -0.01em;
    color: #f6404f;
  }
  &_desc {
    font-family: "Circe";
    margin-top: 15px;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 135%;
    color: #2e373b;
  }
}
</style>
