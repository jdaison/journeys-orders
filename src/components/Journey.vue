<template>
  <div class="container">
  <Row>
    <Col span="2">
      <div class="number">
          5 
      </div>
    </Col>     

    <Col span="3">
      <div class="vertical-align">
        <div class="client">
          <h2>Tablemac S.A</h2>
        </div>
        <div >
          <h3>2018-01-01</h3>
        </div>
      </div>
    </Col>

    <Col span="2">
      <div class="vertical-align">
        <Icon type="md-jet" />
        <h3>Mula</h3>
      </div>
    </Col>

    <Col span="5">
      <div class="vertical-align">
        <div class="city">Medellín - Cali</div> 
        <div class="product">Arroz</div>
      </div>
    </Col>

    <Col span="3">
      <div class="vertical-align">
        <div class="weight">34,000 kg</div>
      </div>
    </Col>

    <Col span="3">
      <div class="vertical-align">
        <div class="price">$500,000</div>
        <div class="type-price">x Tonelada</div>
      </div>
    </Col>
    
    <Col span="5">
      <div class="vertical-align">
        <div class="note">Por favor tener vehiculo sin olores extraños o residuos..</div>
      </div>
    </Col>

    <Col span="1">
      <div class="vertical-align">
        <Button 
        :size="buttonSize" 
        icon="md-create"
        shape="circle"></Button>
      </div>
    </Col>

    </Row>
  </div>
</template>

<script>
export default {
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .container {
    color: #6A6A6A;  
  }
  .ivu-row {
    border-radius: 10px;
    background-color: #FFFFFF;
    display: flex;
    align-content: center;
  }

  .ivu-col {
    display: flex;
    justify-content: center;
  }

  .vertical-align {
    display: flex;
    flex-direction: column;
    justify-content: space-around
  }

  .number {
    width: 40px;
    height: 40px;
    font-size: 1.5rem;
    vertical-align: middle;
    text-align: center;
    background-color:#19BA9B;
    border-radius: 50%;
    font-weight: bold;
    border: 2px#22A78E solid;
    margin: auto auto;
    color: white;
  }

  .city{
    font-size: 1.1rem;
  }

  .product{
    font-size: 1.1rem;
    font-weight: bold;
  }

  .price{
    font-size: 1.5rem;
    color: #4764AE;
    font-weight: bold;
  }

  .type-price {
    font-size: 0.9rem;
    font-weight: bold;
    color: #4764AE;
  }

  .weight{
    font-size: 1.5rem;
    color: #22A78E;
    font-weight: bold;
  }

  .note{
    font-size: 0.8rem;
  }

  i {
    font-size: 2rem;
  }
  .ivu-btn{
    background-color: #F6AD1D;
  }
</style>
