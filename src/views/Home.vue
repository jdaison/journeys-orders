<template>
  <div class="home">
    <Row>
      <Col span="2">
        Cant. Veh
      </Col>     
      <Col span="3">
        Cliente / Fecha Orden
      </Col>     
      <Col span="2">
        Tipo 
      </Col>     
      <Col span="5">
        Ruta / Producto
      </Col>     
      <Col span="3">
        Peso
      </Col>     
      <Col span="3">
        Flete
      </Col>     
      <Col span="5">
      Nota:
      </Col>     
      <Col span="1">
      
      </Col>     
    </Row>
    <Journey class="journey" />
    <Journey class="journey" />
    <Journey class="journey" />
    <Journey class="journey" />
  </div>
</template>

<script>
// @ is an alias to /src
import Journey from "@/components/Journey.vue";

export default {
  name: "home",
  components: {
    Journey
  }
};
</script>

<style scoped lang="scss">
.journey {
  margin:8px 15px;
}
.home{
  height: 100vh;
}
</style>

