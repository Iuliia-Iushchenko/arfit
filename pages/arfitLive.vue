<template>
  <div>
    <b-img src="../assets/imgs/shrimp.jpg" fluid alt="Responsive image"></b-img>
    <b-container class="bv-example-row mt-2">
      <b-row>
        <b-col sm="6" class="arfit__logo_box"
          ><img
            class="arfit__logo"
            src="../assets/imgs/arfit-live.png"
            width="60%"
            alt="ARFIT logo"
        /></b-col>
        <b-col sm="6">
          <b-list-group class="list__group">
            <b-list-group-item class="list__item"
              ><h5>THE PROTEIN-VITAMIN COMPLEX FOR ARTEMIA ENRICHMENT</h5>
            </b-list-group-item>
            <b-list-group-item class="list__item"
              ><h5>
                CONSISTS OF HIGH QUALITY NATURAL ELEMENTS
              </h5></b-list-group-item
            >
            <b-list-group-item class="list__item"
              ><h5>NON-GMO</h5></b-list-group-item
            >
          </b-list-group>
        </b-col>
      </b-row>
    </b-container>
    <div class="arfit__info">
      <p>
        «ARFIT LIVE», developed and manufactured according to the unique
        patented technology. «ARFIT LIVE» is a feed additive for Artemia
        enrichment. «ARFIT LIVE» reliably establishes the therapeutic
        immunomodulation effect which is also important for survival of shrimp
        and fish larvae. Moreover, this protein-vitamin complex increases the
        rate of linear weight growth of shrimp and fish.
      </p>
      <p>The product itself is a paste substance of dark brown color.</p>
    </div>
    <b-container class="product__description bv-example-row">
      <b-row class="product__description_row">
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/DNA.png"
              alt="icon"
            />
            <p>does not contain hormones</p>
          </div></b-col
        >
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/check.png"
              alt="icon"
            />
            <p>completely safe, non-toxic and non-addictive</p>
          </div></b-col
        >
        <b-col class="product__description_column" sm
          ><div class="product__description_item">
            <img
              class="priduct__description_img"
              src="../assets/imgs/leaves.png"
              alt="icon"
            />
            <p>a 100% natural product</p>
          </div></b-col
        >
      </b-row>
    </b-container>
    <div class="arfit__info">
      <div class="tablecontainer">
        <p class="mb-2">
          It is known that the main problems of intensive aquaculture in world
          practice are associated with high elimination of shrimp at the early
          stages of ontogenesis. One of the frequent reasons for this is the
          traditional introduction of dry artificial food into the larvae diet,
          which does not provide conditions that prevent the occurrence of
          bacterial and viral diseases in shrimp, which in turn leads to their
          high losses. With intensive crustacean cultivation in the RAS, it is
          usually observed that the losses at the early stages of ontogenesis of
          the shrimp is on average 35-40%.
        </p>
        <p>
          The existing practice of world aq uacu ltu re has convincingly
          demonstrated special nutritional value of Artemia naupliuses as a
          starting live feed for the larvae of various crustacean species grown
          in factory conditions. However, even the introduction of Artemia
          nauplius into the diet as a starting live food after the transition of
          crustacean larvae to external nutrition does not completely solve the
          abovementioned problem.
        </p>
      </div>
    </div>
    <div class="product__main-block">
      <h4 class="product__main-sentence">
        The solution of the global problem of low survival
        <br />
        of larvae and juvenile shrimps is «ARFIT LIVE».
      </h4>
    </div>
    <div class="arfit__info">
      <div class="tablecontainer">
        <p class="mb-2">
          «ARFIT LIVE» is a specially created micronized form of a natural
          substrate with a unique composition of biologically active substances,
          which consists of organic fatty acids, carbohydrates, specific
          polypeptides, vitamins, and microelements. The unique composition and
          optimal micronization of the natural substrate are the main conditions
          that provide high bioavailability of the feed additive.
        </p>
        <p>
          «ARFIT LIVE» is particularly effective in the early stages of
          ontogenesis, increasing the survival rate of shrimps (and fish)
          several times and providing up to 70-90 % preservation rate of all
          planting material by enhancing the immune status of larvae and
          juveniles.
        </p>
      </div>
    </div>
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="6" class="img_food">
          <img src="../assets/imgs/filled_food.png" width="80%" alt="..." />
        </b-col>
        <b-col sm="6" class="img_food">
          <img src="../assets/imgs/empty_food.png" width="80%" alt="..." />
        </b-col>
      </b-row>
    </b-container>
    <div class="arfit__info">
      <div class="tablecontainer">
        <p>
          Observations of the minimum time of keeping nauplius in the enriching
          solution until the food tube of the crustacean is completely filled
          with «ARFIT LIVE», with the temperature of the aqueous solution of
          20-22 °C, have shown that 30-50% of crustaceans fill the food tube
          after 30 minutes from the be ginning of bioencapsulation, if the
          number of food organisms of 1-40 microns in size is in the range from
          0.0788 to 1.2619 million/ml.
        </p>
      </div>
    </div>
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="6" class="img_food">
          <img src="../assets/imgs/artemia_nauplii.png" width="80%" alt="..." />
        </b-col>
        <b-col sm="6" class="img_food">
          <img
            src="../assets/imgs/enriched_artemia_nauplii.png"
            width="80%"
            alt="..."
          />
        </b-col>
      </b-row>
    </b-container>
    <h2 class="text-center">
      ARTEMIA ENRICHMENT <br />
      STRATEGIES
    </h2>
    <div class="product__main-block">
      <h4 class="product__main-sentence">
        Please, pay attention that the tank and water are well disinfected
        <br />
        Artemia can only be enriched from instar II 4-6 hours afer hatching.
      </h4>
    </div>
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="6">
          <div>
            <b-table
              :items="items"
              :fields="fields"
              striped="striped"
              head-variant="light"
              bordered="bordered"
              table-variant="info"
              caption-top
            >
              <template #table-caption>Optimal conditions</template>
            </b-table>
          </div>
        </b-col>
        <b-col sm="6">
          <div class="arfit__process">
            <p>
              Add 1,5 kg of salt (sea salt or table salt without additives) in
              the enrichment tank which contains 100 liters ofwater.
            </p>
            <p>
              Fill a container with freshwater (20-220 C) than add «ARFIT LIVE»
              to the water 200 g/liter and blend it for 1 to 1,5 minutes. After
              blending add this mixture to the salty water 1-1, 2 g : 1 liter of
              solution.
            </p>
            <p>Enrich for period of 6 to 12 hours.</p>
          </div>
        </b-col>
      </b-row>
    </b-container>
    <h2 class="text-center">
      GUIDELINES FOR THE ENRICHMENT <br />
      OF ARTEMIA BY «ARFIT LIVE»
    </h2>
    <div class="pb-3">
      <b-table
        :items="values"
        :fields="elements"
        striped="striped"
        head-variant="light"
        bordered="bordered"
        table-variant="info"
        caption-top
        class="arfit__table"
      >
      </b-table>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'bigContent',
  data() {
    return {
      fields: ['condition', 'value'],
      items: [
        { condition: 'Density (/ml)', value: 400 },
        { condition: 'Salinity (ppt)', value: 15 },
        { condition: 'Temperature (C)', value: '21-22' },
        { condition: 'Aeration', value: 'medium' },
      ],
      elements: ['№', 'indicators', 'value'],
      values: [
        {
          '№': 1,
          indicators: 'Enriching complex: «ARFIT LIVE», g/I',
          value: '0, 75+0,25+0, 125',
        },
        {
          '№': 2,
          indicators: 'Duration of the enrichment period, hours',
          value: '6',
        },
        { '№': 3, indicators: 'Number of enrichments, times', value: '2' },
        {
          '№': 4,
          indicators: 'Time of applying the «ARFIT LIVE» for the second time',
          value: '1-2 hours before the end of bioencapsulation',
        },
        {
          '№': 5,
          indicators:
            'Amount of the «ARFIT LIVE» for repeated application, g/I ',
          value: '0,5',
        },
        {
          '№': 6,
          indicators: 'Color of enriched metanauplius',
          value: 'Red-brown',
        },
      ],
    }
  },
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
.product__main-block {
  border-top: 5px solid rgb(36 73 143);
  border-bottom: 5px solid rgb(36 73 143);
  background-color: rgba(167, 242, 252, 0.5);
}
.product__main-sentence {
  color: rgb(36 73 143);
  text-align: center;
  padding: 10px;
}
.tablecontainer {
  -webkit-column-width: 250px;
  -moz-column-width: 250px;
  column-width: 250px;
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
  -webkit-column-gap: 60px;
  -moz-column-gap: 60px;
  column-gap: 60px;
}
.tablecontainer p {
  padding: 0;
  margin: 0;
}
.img_food {
  text-align: center;
}
.text-center {
  color: rgb(36 73 143);
  margin: 30px;
}
.arfit__process {
  font-size: 18px;
  margin-top: 45px;
}

.arfit__process p {
  margin-bottom: 25px;
}

.arfit__table {
  font-size: 18px;
}
</style>
