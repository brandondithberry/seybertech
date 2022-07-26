<template>
  <main>
    <section class="hero-banner">
      <div class="overlay">
        <h1 class="title text-left">Technology Support & Solutions</h1>
        <h2 class="subtitle mb-8">Enabling business growth through technology.</h2>
        <a href="/free-assessment" class="btn">Free Assessment</a>
      </div>
    </section>
    <section class="services">
      <div class="container">
        <div>
          <h3>Managed IT Services</h3>
          <h4>✓ IT & Network Support</h4>
          <h4>✓ Backups (On or Off Site)</h4>
          <h4>✓ Business Continuity</h4>
          <h4>✓ Endpoint Administration</h4>
        </div>
        <div>
          <h3>Enterprise Technical Solutions</h3>
          <h4>✓ Technology Consulting</h4>
          <h4>✓ Engineering Support</h4>
          <h4>✓ Design & Implementation</h4>
          <h4>✓ Technology Assessment</h4>
        </div>
        <div>
          <h3>Cyber Security Services</h3>
          <h4>✓ Vulnerability & Penetration Testing</h4>
          <h4>✓ Ransomware Prevention</h4>
          <h4>✓ Next Generation Firewalls</h4>
          <h4>✓ Cyber Risk & Compliance</h4>
        </div>
        <div>
          <h3>Branding & Inbound Marketing</h3>
          <h4>✓ Web Design & Development</h4>
          <h4>✓ Logos & Brand Identity Design</h4>
          <h4>✓ Search Engine Optimization</h4>
          <h4>✓ Paid Search & Paid Social</h4>
        </div>
      </div>
    </section>
  </main>
</template>

<style lang="postcss" scoped>
.hero-banner {
  @apply w-full;
  background: center center / cover no-repeat url(~/static/img/point.jpg);

  .overlay {
    @apply block w-full h-full py-48 px-8;
    background: linear-gradient(0deg, #fff, #ffffff00);
  }
}

.services {
  .container {
    @apply grid grid-cols-2 gap-10 px-8 max-w-screen-lg m-auto;

    div {
      @apply p-10 bg-white rounded-lg shadow-lg border;

      h4 {
        @apply text-gray;
      }
    }
  }
}

@media all and (max-width: 992px) {
  .services {
    .container {
      @apply grid-cols-1;
    }
  }
}
</style>