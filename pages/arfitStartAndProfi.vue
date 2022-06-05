<template>
  <div>
    <b-img src="../assets/imgs/shrimp.jpg" fluid alt="Responsive image"></b-img>
    <b-container class="bv-example-row mt-2">
      <b-row>
        <b-col sm="6" class="arfit__logo_box">
          <b-container class="bv-example-row">
            <b-row class="arfit__logo_row">
              <img
                class="arfit__logo"
                src="../assets/imgs/arfit-start.png"
                width="40%"
                alt="ARFIT logo"
              />
            </b-row>
            <b-row class="arfit__logo_row">
              <img
                class="arfit__logo"
                src="../assets/imgs/arfit-profi.png"
                width="40%"
                alt="ARFIT logo"
              />
            </b-row>
          </b-container>
        </b-col>
        <b-col sm="6">
          <b-list-group class="list__group mt-3">
            <b-list-group-item class="list__item"
              ><h5>THE PROTEIN-VITAMIN FEED ADDITIVE!</h5>
            </b-list-group-item>
            <b-list-group-item class="list__item"
              ><h5>
                EFFECTIVE SOLUTION TO THE LOW SURVIVAL RATES OF LARVAE AND
                JUVENILE SHRIMPS WITHOUT USAGE OF ANTIBIOTICS!
              </h5></b-list-group-item
            >
            <b-list-group-item class="list__item"
              ><h5>INCREASES PRESERVATION RATE!</h5></b-list-group-item
            >
          </b-list-group>
        </b-col>
      </b-row>
    </b-container>
    <div class="arfit__info">
      <p>
        The prophylactic immunomodulation protein-vitamin complexes «ARFIT
        START» and «ARFIT PROFI» are developed and manufactured according to the
        unique patented technology.
      </p>
      <p>
        «ARFIT» is recommended to use as an enriching additive for larvae and
        juvenile shrimp and ﬁsh. The product itself is a grist of dark brown
        color.
      </p>
    </div>

    <b-container class="product__description bv-example-row">
      <b-row class="product__description_row">
        <b-col class="description_column" sm>
          <div class="description_item">
            <p>
              «ARFIT START» size of grist is 0,2 – 0,5 mm. Add to dry feed as 5%
              of feed mass.
            </p>
          </div>
        </b-col>
        <b-col class="description_column" sm>
          <div class="description_item">
            <p>
              «ARFIT PROFI» size of grist is 0,5 -1,0 mm; 1,0-1,5 mm. Add to dry
              feed as 5% of feed mass.
            </p>
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container class="product__description bv-example-row">
      <b-row class="product__description_row">
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/system.png"
              alt="icon"
            />
            <p>Great solution for recirculating aquaculture system</p>
          </div></b-col
        >
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/ammonial.png"
              alt="icon"
            />
            <p>Neutralize ammonial</p>
          </div></b-col
        >
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/balance.png"
              alt="icon"
            />
            <p>Help to maintain a nitrogen balance</p>
          </div></b-col
        >
      </b-row>
    </b-container>
    <div class="arfit__info">
      <p class="mb-2">
        The protein-vitamin additives «ARFIT START» and «ARFIT PROFI» raise the
        immune status of aquaculture and mariculture objects, help to provide
        protection against bacterial and viral infections, as well as
        adaptability to ﬂuctuations of nitrates in the water and other harmful
        factors. Moreover «ARFIT START» and «ARFIT PROFI» stimulate the rapid
        linear-weight growth of cultivated organisms, especially during the
        early stages of ontogenesis.
      </p>
      <p>
        The most important role in these processes play Omega-3 PUFAs and
        cholesterol derivatives, which are precursors of hormones that provide
        growth and protection, also support transport systems for PUFAs,
        enhancing their action.
      </p>
      <p>
        «ARFIT START» and «ARFIT PROFI» suitable for use in recirculating water
        systems, reservoirs with sea or fresh water.
      </p>
      <p>
        «ARFIT START» and «ARFIT PROFI» complexes which main advantage is to
        enhance the immune defense of cultivated organisms. The healing e􀀁ect of
        the additives is achieved, ﬁrstly, through the action of the
        phytocomplex in its composition, natural (not synthesized) biologically
        active substances that exhibit immunomodulating, antibacterial,
        antiviral, antitumor, antiparasitic features.
      </p>
    </div>
    <b-container class="bv-example-row round__block">
      <b-row>
        <b-col
          ><div class="round">
            <div class="round__text">
              <p>70 to 90 % preservation rate of all planting material!</p>
            </div>
          </div></b-col
        >
        <b-col
          ><div class="round">
            <div class="round__text">
              <img src="../assets/imgs/litle-shrimps.png" alt="" />
            </div></div
        ></b-col>
        <b-col
          ><div class="round">
            <div class="round__text">
              <p>
                Reduces the traditional duration terms of growing juveniles to
                marketable species level!
              </p>
            </div>
          </div></b-col
        >
        <b-col
          ><div class="round">
            <div class="round__text">
              <p>
                100% natural product made from environmentally friendly wild
                plants of Russian origin!
              </p>
            </div>
          </div></b-col
        >
        <b-col
          ><div class="round">
            <div class="round__text">
              <p>Completely safe, non-toxic, and non-addictive!</p>
            </div>
          </div></b-col
        >
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  layout: 'bigContent',
}
</script>

<style scoped>
.arfit__logo {
  margin: 0 auto;
  object-fit: contain;
}
.arfit__logo_box {
  text-align: center;
  display: flex;
  align-items: center;
}

.list__group {
  border: none;
}
.list__item {
  border: none;
}
.arfit__info {
  margin: 35px;
  font-size: 18px;
}

.description_column {
  margin-bottom: 5px;
  padding: 10px;
}

.description_item {
  display: flex;
  justify-content: center;
  flex-direction: column;
  height: 100%;
  text-align: center;
  border-radius: 10px;
  background-color: rgb(36 73 143);
  color: #fff;
}

.description_item p {
  margin: 0;
  padding: 20px;
  font-size: 18px;
}

.product__description {
  margin-top: 20px;
  margin-bottom: 20px;
}
.product__description_row {
  height: 100%;
}
.product__description_column {
  height: 200px;
  margin-bottom: 5px;
}
.product__description_item {
  display: flex;
  justify-content: center;
  flex-direction: column;
  height: 100%;
  text-align: center;
  border: 3px solid rgb(36 73 143);
  border-radius: 10px;
  background-color: rgba(167, 242, 252, 0.5);
}
.product__description_item p {
  max-width: 75%;
  margin: 0 auto;
  margin-top: 10px;
}
.priduct__description_img {
  height: 70px;
  width: auto;
  object-fit: contain;
}

.round__block {
  text-align: center;
}

.round {
  display: flex;
  justify-content: center;
  margin: 15px;
}

.round__text {
  justify-content: center;
  align-items: center;
  display: flex;
  min-height: 250px;
  min-width: 250px;
  max-height: 250px;
  max-width: 250px;
  border-radius: 100%;
  border: 3px solid rgb(36 73 143);
  background-color: rgba(167, 242, 252, 0.5);
  text-align: center;
}

.round p {
  padding: 0 15px;
  margin: 0;
  font-size: 18px;
}

.round__text img {
  height: 100%;
  width: 100%;
  border-radius: 100%;
}
</style>
