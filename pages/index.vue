<template>

  <VContainer fluid >
    <v-parallax
    src="https://i.imgur.com/wNZ7P1K.png"
    gradient="to bottom, rgba(0,0,0,.4), rgba(0,0,0,.9)"

    eager
  >

    <VRow no-gutters class="fill-height" justify="center" align="center">


      <VCol cols="12" md="6" order-md="first">
        <p class="text-medium-emphasis text-subtitle-1">
          <v-icon class="primary ma-1" size="small">mdi-clock</v-icon>Seu sistema em 24h
        </p>
        <h1 class="font-weight-bold text-md-h2 text-h4">
          Inicie o seu sistema de <span class="text-primary">apostas online</span> em menos de 24
          horas!
        </h1>
        <p class="text-md-h6 text-caption text-medium-emphasis">
          Tenha até 50% mais conversão em seu site com um sistema de altíssima qualidade e
          conversão.
        </p>
        <v-row class="mt-4">
          <v-col cols="6" md="4">
            <v-btn
              rounded="lg"
              block
              variant="elevated"
              min-height="60"
              class="text-capitalize"
              href="https://wa.link/0d4m4u"
              color="primary"
              >Quero meu sistema</v-btn
            >
          </v-col>
        </v-row>
      </VCol>
      <VCol cols="12" md="5" order="first">
        <VImg src="https://i.imgur.com/WDQAmWw.png" width="800"></VImg>
      </VCol>
      </VRow>
    </v-parallax>

      <VRow>
      
      <VCol cols="12" md="6">
        <VImg src="https://i.imgur.com/eg9zbSy.png"     gradient="to right, rgba(0,0,0,.1), rgba(0,0,0,.7)"        width="650"></VImg>
      </VCol>
      <VCol cols="12" md="5">
        <p class="text-md-h2 text-h4 font-weight-bold">Quem somos nós?</p>
        <h1 class="text-subtitle-1 text-medium-emphasis">
          A Quantum iGaming tem como sua missão, entregar a melhor experiência para seu usuário
          final, bem como um modelo simples e dinâmico de gestão para operadores, para que seu
          negócio tenha escala.
        </h1>
        <v-card
          variant="tonal"
          class="mb-2"
          color="primary"
          prepend-icon="mdi-check-circle"
          title="Mais de 50% EM CONVERSÃO"
          rounded="xl"
          flat
          elevation="0"
        >
          <v-card-text>
            Nosso sistema converte até 50% a mais que os outros sistemas do mercado, fazendo com que
            você tenha até o DOBRO de resultados com o mesmo esforço empregado
          </v-card-text>
        </v-card>
        <v-card
          variant="tonal"
          class="mb-2"
          color="primary"
          prepend-icon="mdi-check-circle"
          title="Parceiro de negócios"
          rounded="xl"
        >
          <v-card-text>
            Atuamos como verdadeiros Partners, direcionando quanto integrações, políticas,
            funcionamento e orientação inicial para que você possa começar bem o seu negócio.
          </v-card-text>
        </v-card>
        <v-card
          variant="tonal"
          color="primary"
          prepend-icon="mdi-check-circle"
          title="Equipe profissional"
          rounded="xl"
        >
          <v-card-text>
            Nosso time é treinado constantemente em prol da excelência na resolução de problemas,
            suporte e orientações, tudo isso em 24/7.
          </v-card-text>
        </v-card>
        <v-row class="mt-4">
          <v-col cols="12">
            <v-btn
              rounded="lg"
              block
              variant="elevated"
              href="https://wa.link/0d4m4u"
              min-height="60"
              class="text-capitalize"
              color="primary"
              >Quero meu sistema</v-btn
            >
          </v-col>
        </v-row>
      </VCol>
      <VCol cols="12" class="align-center justify-center text-center mt-6">
        <p class="text-md-h2 text-h4 mt-4 font-weight-bold">Conheça nossos produtos</p>
        <h1 class="text-subtitle-1 text-medium-emphasis">
          Os melhores produtos e serviços iGaming possíveis para garantir sua vantagem competitiva.
        </h1>
        <v-row justify="center" class="mt-4">
          <v-col cols="12" md="3">
            <v-card variant="tonal" color="primary" rounded="xl" elevation="0" height="250">
              <v-card-title>
                <h1 class="text-h2 mt-4 font-weight-bold">R$ 5.500</h1>
              </v-card-title>
              <v-card-text class="text-center">
                <p class="mt-2 text-caption text-medium-emphasis">
                  Plataforma com layout personalizável, afiliação e jogos ao vivo com API Oficial
                  (mais de 1.000 jogos inclusos e GGR de 20%)
                </p>
              </v-card-text>
              <v-card-actions>
                <v-btn color="primary" variant="outlined" block href="https://quantumgaming.cloud">VER DEMO</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card variant="tonal" color="primary" rounded="xl" flat elevation="0" height="250">
              <v-card-title>
                <h1 class="text-h2 mt-4 font-weight-bold">R$ 1.500</h1>
              </v-card-title>
              <v-card-text class="text-center">
                <p class="mt-2 text-caption text-medium-emphasis">
                  Plataforma com layout personalizável, afiliação e jogos clonados (10 jogos) sem
                  GGR
                </p>
              </v-card-text>
              <v-card-actions>
                <v-btn color="primary" variant="outlined" class="mt-5" block href="https://patosbet.fun">VER DEMO</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </VCol>
    </VRow>
  </VContainer>

  <v-footer class="d-flex flex-column mt-15" color="primary" >
    <div class="px-4 py-2 text-center w-100">
      {{ new Date().getFullYear() }} — <strong>Quantum Gaming</strong>
    </div>
  </v-footer>

  <navBar />
</template>

<script setup>
import navBar from "@/components/navbar.vue";
</script>
