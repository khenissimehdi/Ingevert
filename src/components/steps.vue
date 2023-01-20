<template>
  <div class="steps-steps-list">
    <div class="steps-numerics">
      <app-number></app-number>
      <div class="steps-divider"></div>
      <app-number value="2" rootClassName="number-root-class-name"></app-number>
      <div class="steps-divider1"></div>
      <app-number value="3" rootClassName="number-root-class-name1"></app-number>
    </div>
    <div class="steps-captions">
      <span class="steps-caption">{{ Caption }}</span>
      <span class="steps-caption1">{{ Caption1 }}</span>
      <span class="steps-caption2">{{ Caption2 }}</span>
      <span class="steps-caption3">{{ Caption3 }}</span>
    </div>
  </div>
</template>

<script>
import AppNumber from './number'

export default {
  name: 'Steps',
  props: {
    Caption1: {
      type: String,
      default: 'Cherchez la boîte de collecte la plus proche',
    },
    Caption3: String,
    Caption2: {
      type: String,
      default: 'Déposez votre objet',
    },
    Caption: {
      type: String,
      default: "Rendez vous a l'esipe",
    },
  },
  components: {
    AppNumber,
  },
}
</script>

<style scoped>
.steps-steps-list {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.steps-numerics {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.steps-divider {
  height: 60px;
  display: flex;
  align-items: center;
  border-color: #222223;
  border-style: dotted;
  border-width: 2px;
  flex-direction: column;
  justify-content: space-between;
}
.steps-divider1 {
  height: 60px;
  display: flex;
  align-items: center;
  border-color: #222223;
  border-style: dotted;
  border-width: 2px;
  flex-direction: column;
  justify-content: space-between;
}
.steps-captions {
  gap: 60px;
  width: 510px;
  height: 513px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.steps-caption {
  font-size: 24px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 80px;
}
.steps-caption1 {
  font-size: 24px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 80px;
}
.steps-caption2 {
  font-size: 24px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 80px;
}
.steps-caption3 {
  font-size: 24px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 80px;
}
@media(max-width: 479px) {
  .steps-caption {
    font-size: 16px;
    line-height: 40px;
  }
  .steps-caption1 {
    font-size: 16px;
    line-height: 40px;
  }
  .steps-caption2 {
    font-size: 16px;
    line-height: 40px;
  }
  .steps-caption3 {
    font-size: 16px;
    line-height: 40px;
  }
}
</style>
