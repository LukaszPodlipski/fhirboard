<template>
  <div id="healthStack" class="hero-section flex flex-col gap-36">
    <div class="flex flex-col justify-center gap-8 max-w-[650px] center">
      <h2 class="text-header-2xl leading-10 text-center">
        How Does FHIR Board Speed Up Your Work with FHIR?
      </h2>
      <div class="flex flex-col justify-center gap-2 max-w-[650px] mt-12">
        <p class="text-header-m text-center">FHIR Board accelerates your workflow by:</p>
        <ul>
          <li class="text-caption-s">
            • Automatically converting FHIR ViewDefinitions to SQL queries.
          </li>
          <li class="text-caption-s">
            • Delivering instant data visualizations through Apache Superset integration.
          </li>
          <li class="text-caption-s">
            • Allowing quick combinations of various FHIR resources with the help of saved views.
          </li>
          <li class="text-caption-s">
            • Including predefined use cases for immediate implementation
          </li>
        </ul>
      </div>
      <p class="text-header-m--bold-strong text-center mt-12">
        Additionally, our AI-powered features enable the generation of ViewDefinitions from simple
        text descriptions, making FHIR data analysis more intuitive and accessible.
      </p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.hero-section {
  width: 100%;
  padding: 120px 36px;
  background: linear-gradient(180deg, rgba(255, 255, 255, 1) 0%, rgba(98, 169, 240, 0.298) 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

ul > li {
  margin-top: 12px;
}
</style>
