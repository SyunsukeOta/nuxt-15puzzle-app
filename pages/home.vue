<template>
  <section>
    <p class="title tx_black" id="fifpuzzle">15パズル</p>
    <div class="text tx_black" id="desc">15パズルは、<br>ブロックをスライドさせて<br>この形にするゲームです。</div>
    <a href="play.html">
      <div class="black button" id="startbutton">
        <div class="bt_text tx_white text">始める</div>
      </div>
    </a>
    <div id="base">
      <div class="gray frout_black frame" id="right">
        <div class="container">
          <div class="block blue">
            <div class="text tx_white bl_text bold">1</div>
          </div>
          <div class="block blue">
            <div class="text tx_white bl_text bold">2</div>
          </div>
          <div class="block blue">
            <div class="text tx_white bl_text bold">3</div>
          </div>
          <div class="block blue">
            <div class="text tx_white bl_text bold">4</div>
          </div>
        </div>

        <div class="container">
          <div class="block orange">
            <div class="text tx_white bl_text bold">5</div>
          </div>
          <div class="block orange">
            <div class="text tx_white bl_text bold">6</div>
          </div>
          <div class="block orange">
            <div class="text tx_white bl_text bold">7</div>
          </div>
          <div class="block orange">
            <div class="text tx_white bl_text bold">8</div>
          </div>
        </div>

        <div class="container">
          <div class="block yellow">
            <div class="text tx_white bl_text bold">9</div>
          </div>
          <div class="block yellow">
            <div class="text tx_white bl_text bold">10</div>
          </div>
          <div class="block yellow">
            <div class="text tx_white bl_text bold">11</div>
          </div>
          <div class="block yellow">
            <div class="text tx_white bl_text bold">12</div>
          </div>
        </div>

        <div class="container">
          <div class="block green">
            <div class="text tx_white bl_text bold">13</div>
          </div>
          <div class="block green">
            <div class="text tx_white bl_text bold">14</div>
          </div>
          <div class="block green">
            <div class="text tx_white bl_text bold">15</div>
          </div>
          <div class="block">
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
#fifpuzzle {
  position: absolute;
  top: 150px;
  left: 102.75px;
}

#desc {
  position: absolute;
  top: 300px;
  left: 102.75px;
}

#startbutton {
  position: absolute;
  top: 560px;
  left: 102.75px;
}

#right {
  position: absolute;
  top: 50%;
  left: 693px;
  position: absolute;
  transform: translate(0, -50%);
  box-sizing: content-box;
}
</style>