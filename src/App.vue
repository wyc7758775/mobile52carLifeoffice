<template>
  <div id="app">
    <Header></Header>
    <Nav></nav>
    <Introduce></Introduce>
    <Feature></Feature>
    <Team></Team>
    <Cooperate></Cooperate>
    <Product></Product>
    <New></New>
    <Case></Case>
    <Footer></Footer>
    <router-view/>
  </div>
</template>

<script>
import Header from '@/components/common/header'
import Nav from '@/components/common/nav'
import Introduce from '@/components/common/introduce'
import Feature from '@/components/common/feature'
import Team from '@/components/common/team'
import Cooperate from '@/components/common/cooperate'
import Product from '@/components/common/product'
import New from '@/components/common/new'
import Case from '@/components/common/case'
import Footer from '@/components/common/footer'
export default {
  name: 'App',
  components:{
    Header,
    Nav,
    Introduce,
    Feature,
    Team,
    Cooperate,
    Product,
    New,
    Case,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
