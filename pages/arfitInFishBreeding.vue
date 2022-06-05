<template>
  <b-container>
    <h1 class="mt-3 mb-3" style="font-weight: bold">
      «ARFIT» IN FISH BREEDING
    </h1>

    <figure class="sign">
      <p>
        <img
          src="../assets/imgs/arfit.png"
          class="about_img"
          alt="Responsive image"
        />
      </p>
      <figcaption>Drug «ARFIT»</figcaption>
    </figure>
    <p>
      The drug-premix “ARFIT” is used in fisheries, mainly, in the industrial
      aquaculture. It is designed to carry out the industrial implementation of
      the technology of production and application of the original biologically
      active additive to feeds – “ARFIT” intended for the larvae and the young
      of the crustaceans (shrimps) and fish.
    </p>
    <h2 class="mt-3 mb-3">The problem and the proposed solution</h2>
    <p>
      It is known that the main problems of intensive aquaculture are connected
      with high elimination of the valuable types of fish and crustaceans at the
      early stages of ontogenesis as they determine the manufacturability of the
      artificial breeding species. In this regard, the traditional introduction
      of the starting dry artificial feed into the diet of larvae immediately
      after the resorption of the yolk sac is extremely inefficient that leads
      to the very low survival rate of larvae, the exposure of the young grown
      in the installations of the closed cycle of water supply to bacterial and
      viral diseases.
    </p>
    <p>
      The solution of the global problem of low survival of the larvae and the
      young of fish and crustaceans consists in the use of highly efficient
      original therapeutic and prophylactic drug-premix «ARFIT».
    </p>
    <p>
      Biotechnology of the preparation of live feed enriched by the innovation
      drug-premix «ARFIT» – phytocomplex of endemic plants with vitamin-lipid
      extract of the cysts of artemia, provides for the increase of the rates of
      linear weight growth of the larvae, the increase of the caloric content of
      the grown objects, the improvement of the taste of the final products of
      aquacurture.
    </p>
    <p>
      With the help of the method of bioencupsulation it is possible to improve
      the biotechnical methods of prevention and treatment of the young. The
      latter direction is especially relevant in modern aquaculture due to the
      sharply increased problems with the diseases of the larvae of fish and
      crustaceans with bacterial and viral infections accompanied by high waste.
      The practice of intensive growing of crustaceans and fish in the marine
      aquaculture with the use of ultrasound has shown that the waste at the
      early stages of ontogenesis, for example, of the white-legged shrimp
      (Penaeus vannamei), is 35-40 %. In case of cultivating the grouper
      (Epinephelus) of the rock bass family (Serranidae), elimination reaches
      90-95 %. In the freshwater aquaculter the survival rate of sturgeon larvae
      (sterlet, Amur sturgeon, etc.) is also very low – not more than 30-45 %,
      pikeperch – 20-25 %.
    </p>
    <p>
      The experience of the local use of the therapeutic and prophylactic premix
      “ARFIT” for the bioencapsulation of live feed (nauplius of crustacea
      artemia) and for the enrichment of the starting artificial dry feeds
      showed high efficiency of this drug, significantly (several times)
      increasing the fish productivity and the survival of the facilities of
      aquaculture.
    </p>
  </b-container>
</template>

<script>
export default {
  layout: 'bigContent',
}
</script>

<style scoped>
.sign {
  float: right; /* Выравнивание по правому краю */
  border: 3px solid rgb(9, 9, 119); /* Параметры рамки */
  padding: 10px; /* Поля внутри блока */
  margin: 10px 0 20px 20px; /* Отступы вокруг */
  border-radius: 10px;
  background: rgba(167, 242, 252, 0.5); /* Цвет фона */
}
.sign figcaption {
  margin: 0 auto 5px; /* Отступы вокруг абзаца */
}
.about_img {
  max-width: 100%;
  max-height: 300px;
  object-fit: contain;
}

@media (max-width: 767px) {
  .sign {
    float: none;
    text-align: center;
  }
}
</style>
