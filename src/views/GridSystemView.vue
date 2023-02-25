<template>
  <v-container class="red" fluid>
    <!--fluid width 100% & css-flex : 100vh-->
    <v-card class="yellow pa-3"> cols </v-card>

    <v-card class="pa-3" outlined>
      <v-row>
        <!-- 과거 : layout = row -->
        <!--gutter col 사이 간격 default : 24 px-->

        <v-col>
          <!-- 과거 : v-flex = v-col -->
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
    </v-card>

    <v-card class="mt-5 pa-3">
      <v-row>
        <!-- 과거 : layout = row -->
        <!--gutter col 사이 간격 default : 24 px-->

        <v-col>
          <!-- 과거 : v-flex = v-col -->
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-spacer />

        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-spacer />
        <!-- 공백 -->
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
    </v-card>

    <v-card class="mt-5 pa-3" outlined>
      <v-row :style="{ height: '120px' }" class="red" align="start">
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
      <v-row :style="{ height: '120px' }" class="yellow" align="center">
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
      <v-row :style="{ height: '120px' }" class="green" align="end">
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
    </v-card>

    <v-card class="mt-5 pa-3" outlined>
      <v-row :style="{ height: '120px' }" class="blue" align="start">
        <v-col align-self="start">
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col align-self="center">
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
        <v-col align-self="end">
          <v-card class="pa-3" outlined> col </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'GridSystem',
};
</script>
