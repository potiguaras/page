<template>
  <v-app>
    <v-app-bar app color="primary darken-2" elevate-on-scroll>
      <v-toolbar-title class="headline text-uppercase">
        <h1 class="headline">Potiguaras Valley</h1>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content>
      <v-container fluid pt-0>
        <v-row tag="section" class="primary darken-2 text-center">
            <v-col>
              <v-row>
                <v-col class="d-flex align-end">
                  <v-img height="200" contain :src="require('./assets/icon.png')"></v-img>
                </v-col>
              </v-row>
              <v-row>
                <v-col>
                  <h2 class="display-4 d-none d-md-block font-weight-bold">Potiguaras Valley</h2>
                  <h2 class="display-3 d-md-none font-weight-bold">Potiguaras Valley</h2>
                </v-col>
              </v-row>
            </v-col>
        </v-row>
        <v-row tag="section" align="center" class="text-justify">
          <v-col sm="6">
            <h2 class="display-3 text-center">Quem Somos</h2>
            <br>
            <p class="body-1">
              A Potiguaras Valley é a Comunidade empreendedora de inovação 
              e startups da Região do Seridó e Trairí do Rio Grande do Norte; 
              que tem como intuito reunir startups locais e capacitar pessoas 
              que desejam empreender de uma forma inovadora e criativa.
            </p>
            <p>
              Além disso, a Comunidade visa criar um movimento de desenvolvimento 
              do Ecossistema por meio de eventos que despertem o mercado de startups 
              e gerem perspectivas inovadoras para novos negócios e, a partir disso, 
              contribuir com o desenvolvimento econômico da região interiorana.
            </p>
          </v-col>
        </v-row>
        <v-row tag="section" class="primary darken-2 text-center" 
          align="center"
        >
          <v-col>
            <h2 class="display-3 text-center">Valores</h2>
            <br>
            <v-row justify="space-around">
              <v-col cols="12" sm="3">
                <h3 class="text-uppercase">Coragem</h3>
                <p>
                  Porque é necessário sermos determinados para mudarmos nossa realidade;
                </p>
              </v-col>
              <v-col cols="12" sm="3">
                <h3 class="text-uppercase">Diversidade</h3>
                <p>
                  Sabemos que as diferenças são essenciais para a troca de conhecimento;
                </p>
              </v-col>
            </v-row>
            <v-row justify="space-around">
              <v-col cols="12" sm="3">
                <h3 class="text-uppercase">Empatia</h3>
                <p>
                  Colocar-se no lugar do outro é indispensável para termos espírito 
                  de comunidade e bem comum;
                </p>
              </v-col>
              <v-col cols="12" sm="3">
                <h3 class="text-uppercase">Respeito</h3>
                <p>
                  Todos na comunidade possuem vez e voz para compartilhar suas ideias.
                </p>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
  section.row{
    height: calc(100vh - 64px);
  }
</style>