<template>
  <full-height-page>
    <template #header>
      <s-sub-menu>
        <v-tab :to="`/designs/${$route.params.projectTypeId}/`" nuxt exact>General Settings</v-tab>
        <v-tab :to="`/designs/${$route.params.projectTypeId}/pdfdesigner/`" nuxt>PDF Designer</v-tab>
        <v-tab :to="`/designs/${$route.params.projectTypeId}/reportfields/`" nuxt>Report Fields</v-tab>
        <v-tab :to="`/designs/${$route.params.projectTypeId}/findingfields/`" nuxt>Finding Fields</v-tab>
      </s-sub-menu>
    </template>
   
    <nuxt-child />
  </full-height-page>
</template>
