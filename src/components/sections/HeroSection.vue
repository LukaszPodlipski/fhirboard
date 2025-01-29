<template>
  <div id="hero" class="hero-section">
    <div class="flex flex-col items-center justify-center gap-8 mb-16">
      <div class="flex flex-col items-center justify-center">
        <h1 class="text-header-3xl text-gradient text-center">Transform FHIR Data</h1>
        <h1 class="text-header-3xl text-gradient text-center">into Insights, Effortlessly</h1>
      </div>
      <p class="text-header-m text-center max-w-[800px]">
        FHIR Board is an open-source application designed to streamline FHIR data analytics and
        visualization workflows. The tool bridges the gap between raw FHIR datasets and actionable
        insights by providing a user-friendly interface for working with FHIR ViewDefinitions.
      </p>
      <a target="_blank" href="https://github.com/the-momentum/fhirboard">
        <button class="app-button text-header-xs--bold">Check Out Our Open-Source Tools</button>
      </a>
    </div>
  </div>
</template>

<style scoped lang="scss">
.hero-section {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgb(255, 255, 255);
  background: linear-gradient(180deg, rgba(255, 255, 255, 1) 10%, rgb(198, 219, 254) 100%);

  padding: 160px 24px;
}
</style>
