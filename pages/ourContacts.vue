<template>
  <div class="content__container">
    <div class="content">
      <h1 style="color: deepskyblue; font-weight: bold; text-align: center">
        OUR CONTACTS
      </h1>
      <b-card
        no-body
        class="overflow-hidden"
        style="max-width: 500px; background: rgba(0, 0, 0, 0.25)"
      >
        <b-row no-gutters>
          <b-col>
            <b-card-body
              title="Arikara (Canada) Inc."
              style="color: deepskyblue"
            >
              <div class="container">
                <img src="../assets/imgs/geo-alt-fill.svg" alt="" />
                <b-card-text>
                  276 Silver Birch ave, Toronto, Ontario, Canada, M4E3L5
                </b-card-text>
              </div>
              <div class="container">
                <img src="../assets/imgs/envelope-fill.svg" alt="" />
                <p>arfit@ips-pacific.com</p>
              </div>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>

      <b-card
        no-body
        class="overflow-hidden"
        style="max-width: 500px; background: rgba(0, 0, 0, 0.25)"
      >
        <b-row no-gutters>
          <b-col>
            <b-card-body
              title="IPS Pacific Co., Ltd"
              style="color: deepskyblue"
            >
              <div class="container">
                <img src="../assets/imgs/geo-alt-fill.svg" alt="" />
                <b-card-text>
                  Office 2207-09, 22/F., Tower Two, Lippo Centre, 89 Queensway,
                  Admiralty Hong Kong, HK
                </b-card-text>
              </div>
              <div class="container">
                <img src="../assets/imgs/envelope-fill.svg" alt="" />
                <p>info@arfit.hk</p>
              </div>
            </b-card-body>
          </b-col>
        </b-row>
      </b-card>
    </div>
  </div>
</template>

<style scoped>
.content__container {
  display: table;
  height: 100%;
  width: 100%;
}
.content {
  display: table-cell;
  vertical-align: middle;
}

.container-fluid {
  margin-top: 40px;
}

.container {
  display: flex;
}

.container p {
  padding-left: 10px;
  margin: 0;
  color: #fff;
}

.card {
  margin: 20px auto;
}

.card:hover {
  box-shadow: rgba(rgb(46, 24, 24), rgb(76, 90, 76), rgb(39, 39, 53), 0.7);
}
</style>

<style>
html,
body {
  height: 100%;
}

body {
  background-image: url(../assets/imgs/backgraund_img.jpg);
  height: 100vh;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  background-attachment: fixed;
}
</style>
