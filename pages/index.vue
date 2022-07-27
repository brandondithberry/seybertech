<template>
  <main>
    <section class="hero-banner">
      <div class="overlay">
        <h1 class="title text-left">Technology Support & Solutions</h1>
        <h2 class="subtitle mb-8">Enabling business growth through technology.</h2>
        <nuxt-link :to="{ path: '/', hash: '#free-assessment' }" class="btn">Free Assessment</nuxt-link>
      </div>
    </section>
    <section class="services">
      <div class="container">
        <div>
          <h3>Managed IT Services</h3>
          <h4>✓ IT Support & Management</h4>
          <h4>✓ Network Support & Management</h4>
          <h4>✓ System Monitoring & Backups</h4>
          <h4>✓ Software & Cloud Management</h4>
          <h4>✓ Help Desk Services</h4>
        </div>
        <div>
          <h3>Enterprise Technical Solutions</h3>
          <h4>✓ Solution Optimization</h4>
          <h4>✓ Software & Web Applications</h4>
          <h4>✓ Engineering Support</h4>
          <h4>✓ Design & Implementation</h4>
          <h4>✓ System Architecture</h4>
        </div>
        <div>
          <h3>Cyber Security Services</h3>
          <h4>✓ Vulnerability Scanning</h4>
          <h4>✓ Penetration Testing</h4>
          <h4>✓ Threat Detection & Response</h4>
          <h4>✓ Next Generation Firewalls</h4>
          <h4>✓ Cyber Risk & Compliance</h4>
        </div>
        <div>
          <h3>Branding & Inbound Marketing</h3>
          <h4>✓ Web Design & Development</h4>
          <h4>✓ Custom CMS Development</h4>
          <h4>✓ Logos & Brand Identity Design</h4>
          <h4>✓ Search Engine Optimization</h4>
          <h4>✓ Paid Search & Paid Social</h4>
        </div>
      </div>
    </section>
    <section class="steps">
      <div class="container">
        <h2>Easy 3 Step Process</h2>
        <div>
          <h3>Step 1: Free Assessment</h3>
          <p>Get a free on site or remote consultation from an industry expert to assess your technology challenges.</p>
        </div>
        <div>
          <h3>Step 2: Identify Opportunities</h3>
          <p>
            After we’ve assessed your business, we’ll provide optimization opportunities, and pinpoint any technology
            roadblocks.
          </p>
        </div>
        <div>
          <h3>Step 3: Implement Solutions</h3>
          <p>
            We’ll provide a strategic plan and implement the perfect solution, so you can focus on growing your
            business.
          </p>
        </div>
      </div>
    </section>
    <section class="cta" id="free-assessment">
      <div class="container">
        <h2>Schedule a free technology assessment today.</h2>
        <div class="form">
          <form name="contact" method="POST" data-netlify="true">
            <div class="grid">
              <label>First Name <input type="text" name="firstname" /></label>
              <label>Last Name <input type="text" name="lastname" /></label>
            </div>
            <div class="grid">
              <label>Company Name <input type="text" name="company" /></label>
              <label>Email <input type="email" name="email" /></label>
            </div>
            <div>
              <label>Message <textarea name="message"></textarea></label>
            </div>
            <button class="btn" type="submit">Get Assessment</button>
          </form>
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
  @apply pb-20;

  .container {
    @apply grid grid-cols-2 gap-10 px-8 max-w-screen-lg m-auto;

    div {
      @apply p-10 bg-white rounded-lg shadow-lg border border-gray-100;

      h4 {
        @apply text-gray;
      }
    }
  }
}

.steps {
  @apply text-center px-8 py-20 bg-gray-50 shadow-lg rounded-lg border border-gray-100 m-4;

  .container {
    @apply max-w-lg m-auto;
  }

  h2 {
    @apply text-primary;
  }

  h3 {
    @apply mt-8 mb-2;
  }

  p {
    @apply mt-2 text-gray;
  }
}

.cta {
  @apply px-8 py-20 shadow-lg rounded-lg border border-primary-100 m-4;
  background: linear-gradient(60deg, #00a0e433, #00a0e411);

  h2 {
    @apply text-center mb-8;
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