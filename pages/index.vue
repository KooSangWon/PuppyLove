<template>
  <section class="section">
    <div class="hero is-medium is-dark is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title is-1">개사랑</h1>
          <h2 class="subtitle">개를 사랑하는 사이트입니다.</h2>
        </div>
      </div>
    </div>
    <br>

    <div class="columns">
      <div class="column">
        <div class="notification is-medium is-dark is-bold">
          <figure class="image is-squre">
            <img src="https://s7d1.scene7.com/is/image/PETCO/puppy-090517-dog-featured-355w-200h-d" alt="">
          </figure>
        </div>
      </div>
      <div class="column">
        <div class="message is-medium is-dark is-bold">
          <div class="message-header">
            <p>오늘의 개 사진</p>
          </div>
          <div class="message-body">
            <figure class="image is-squre">
              <img v-bind:src="image" alt="">
            </figure>
          </div>
        </div>
      </div>
    </div>

    <article class="message">
      <div class="message-header">개란 무엇인가?</div>
      <div class="message-body">개(학명: Canis lupus familiaris)는 식육목 개과 개속에 속하는 동물로, 회색늑대(Canis lupus)의 아종으로, 현대에서 가장 널리 분포하며 개체 수가 가장 많은 지상 육식 동물이다. 개는 인류가 최초로 가축으로 삼은 동물로 알려져 있으며, 역사적으로 애완견, 사냥견으로서 길러 왔으며 인간의 친구(Man's best friend)라고도 불린다.

          미토콘드리아 DNA 분석 결과 현대의 개와 회색늑대는 대략 10만 년 전에 분화된 것으로 추정되어 왔는데, 2013년 개의 화석을 이용한 분석에서는 33,000 - 36,000년 전 사이에 분화가 이루어 졌을 것으로 보고 있다.
          
          개는 여러 모로 유용하였기 때문에 모든 원시 인류 사회가 개를 길렀다. 개는 사냥, 목축, 운송, 경비와 같은 일에 사용되고 있으며, 애완 동물로 기르기도 한다. 사람들은 이러한 일들에 적합하도록 오래 전부터 개를 다양한 품종으로 육종하였다.
          
          여러 소수 문화에서 개고기를 먹지만, 다른 여러 문화에서는 개고기를 먹는 것을 금하는 금기를 가지고 있기도 하다. 고대 로마 시기의 역사가인 유스티누스는 페르시아의 왕 다리우스가 카르타고에게 개고기와 인신공양을 금지하는 포고를 내렸다고 기록하고 있고, 서구의 대부분 문화에서 개고기를 먹는 것은 금기로 취급된다. 이슬람에서는 재난이 닥친 특별한 상황이 아니라면 개고기가 금지된다.오늘날에도 개고기를 먹는 문제는 문화적 논란의 대상이다. 청나라 만주족은 태조 누르하치가 개한테서 구해진적이 있다는 전설로 인해 개를 먹지 않는다고 한다.
          
          개의 수명은 보통 12 - 16년 정도이지만, 최근 장수하는 개가 늘어나는 추세이다. 2001년 생물학자 레이 쿠니퍼는 전 세계 개의 개체수를 약 4억 마리 정도로 추정했고, 2013년 하지홍은 10억 마리 이상으로 추정했다.</div>
         
          <div class="message-header">개가 주인을 사랑할 때 하는 행동 5가지</div>
          <div class="message-body">
            1. 보호자가 부르면 어떤 상황이던지 달려온다.<br>
            2. 언제든지 당신을 보면 반가워한다.<br>
            3. 강아지가 꼬리를 오른쪽으로 흔든다.<br>
            4. 강아지가 질투심을 보인다.<br>
            5. 강아지가 당신을 감시한다.<br>
          </div>

          <div class="message-header">개의 이상한 행동 10가지</div>
          <div class="message-body">
            01 냄새나는 물건에 구르기<br>
            강아지를 목욕시켰습니다. 갑자기 배설물, 땅바닥, 쓰레기 등에 몸을 비벼대는 경우가 있죠? 참으로 어처구니가 없는 일이 아닐 수 없는데요, 전문가들은 야생의 본능이 남아있는 것으로 사냥감의 분뇨에 몸을 비벼 위장하려는 습성에서 비롯되었을 것으로 추측하고 있습니다.<br><br>
            02 남의 엉덩이 냄새맡기<br>
            강아지는 다른 동물의 엉덩이에서 나는 냄새로 많은 정보를 알아냅니다. 강아지의 코에는 성별, 건강상태, 식습관 등의 정보를 항문의 화학물질로 분석할 수 있는 야콥슨 기관이 있습니다.<br><br>
            03 눕기전 빙글빙글 도는 행동<br>
            야생에서 잠자기 전 필요했던 바닥을 평평하게 다지거나 해충을 쫓는 행동이 오래된 습성으로 자리잡은 것인데, 진화가 거듭되었음에도 여전히 보이는 이 행동은 보호자와 보내는 시간이 길수록 사라지기도 합니다.<br><br>
            04 갑자기 오줌 지리기<br>
            강아지가 반가움에 소변을 지리는 행동을 할 때가 있습니다. 이를 '순종성배뇨'라고 하는데 상대에게 위협이 되지 않음을 알리는 것입니다. 배를 보이거나 꼬리를 감추거나 귀를 납작하게 만드는 행동의 의미와 비슷합니다.<br><br>
            05 달리는 물체 쫓기<br>
            많은 강아지가 다람쥐, 자동차, 자전거 등 달리는 물체에 흥분하는 경우가 있습니다. 이렇게 쫓는 이유는 '사냥본능' 때문입니다. 쫓는 행동으로 인해 보호자, 반려견 또는 행인이 심각한 부상을 당하는 일이 자주 발생하므로 교육/관리가 필요합니다.<br><br>
            06 식분증 : 대변 먹는 행동<br>
            식분증은 부실한 음식 섭취 / 기생충 감염 / 스트레스 / 호기심 / 어미로부터 학습(어릴 때 자신의 분변을 어미가 먹어치워 청소하려는 습성을 배움) 또는 고양이와 동거하는 경우 사료의 단백질 함럄이 높아 고소한 냄새가 나는 고양이똥을 탐하는 경우가 있습니다.<br><br>
            07 큰 소리 공포증<br>
            큰 소리나 지속적인 소음은 일부 강아지에게는 견딜 수 없는 스트레스가 되곤 합니다. 그결과 자기 새끼를 먹어버리거나 천둥, 불꽃놀이 소리에 유리창을 깨고 도망가는 일도 발생합니다. 소음을 차단하거나 특정 소리를 지속적으로 들려주어 무뎌지게 하는 방법이 있습니다.<br><br>
            08 붕가붕가<br>
            성적행동, 놀이, 지배력을 확보하기 위함 등의 이유가 있는 행동으로 지극히 정상적인 행동이지만 간혹 스트레스, 질병의 증상일 때도 있습니다. 너무 과도하면 행동문제를 유발하므로 원인을 파악하고 빈도를 조절해주어야 합니다.<br><br>
            09 꼬리쫓기<br>
            어린 강아지 시기나 왕성한 나이에는 놀이로 볼 수 있습니다.<br>
            하지만 며칠동안 계속하는 경우라면 불안, 강박증일 수 있으며 간질발작과 같은 질병일 수도 있으므로 수의사의 진료가 필요합니다.<br><br>
            10 바닥에 엉덩이 끌기<br>
            배변시에 생기는 불쾌함을 해소하려는 단순한 행동일 수도 있지만 항문낭에 항문낭액이 꽉 찼기 때문일 가능성이 크답니다. 방치하면 항문낭염, 변비와 같은 질병으로 발전할 수 있으므로 항문낭을 짜주거나 진료를 받아보는 것이 좋습니다.<br><br>
          </div>
    </article>

    <div class="box">
        <h1 class="title">보고 싶은 개 정보를 누르세요.</h1>
        <span v-for="dog in dogs" v-bind:key="dog">
          <a href="#" class="button is-dark">
            {{dog}}
          </a> &nbsp;
        </span>
      </div>
  
  
  </section>
</template>

<script>
 import axios from 'axios';
 export default {
    data() {
      return {};
    },
    async asyncData() {
      const myImage = await axios.get('https://dog.ceo/api/breeds/image/random');
      const myDogs = await axios.get('https://dog.ceo/api/breeds/list');
      return { image: myImage.data.message, dogs: myDogs.data.message };
    }
  };

</script>
