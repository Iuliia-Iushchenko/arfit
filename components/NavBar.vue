<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="/" class="pl-5">ARFIT</b-navbar-brand>
      <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown text="About us" right>
          <b-dropdown-item href="/arfitInFishBreeding"
            >«ARFIT» in fish breeding</b-dropdown-item
          >
          <b-dropdown-item href="/howItWorks">How it works</b-dropdown-item>
          <b-dropdown-item href="/advantagesOfTheProject"
            >Advantages of the Project</b-dropdown-item
          >
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Our Products" right>
          <b-dropdown-item href="/arfitStartAndProfi"
            >ARFIT Start & ARFIT Profi</b-dropdown-item
          >
          <b-dropdown-item href="/arfitLive">ARFIT Live</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="/ourNews">News</b-nav-item>
        <b-nav-item href="/ourContacts" class="pr-5">Contacts</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>
