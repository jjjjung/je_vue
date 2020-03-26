<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <section>
      <b-card no-body>
        <b-tabs pills card vertical>
          <b-tab title="git" active>
            <b-card-text>
              <h5>git clone</h5>
              <p>서버의 모든 파일을 로컬로 다운로드</p>
            </b-card-text>
          </b-tab>
          <b-tab title="Tab 2"><b-card-text>Tab contents 2</b-card-text></b-tab>
          <b-tab title="Tab 3"><b-card-text>Tab contents 3</b-card-text></b-tab>
        </b-tabs>
      </b-card>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'JE vue'
    }
  }
}
</script>

<style lang="scss">

</style>
