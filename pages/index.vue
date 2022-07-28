<template>
  <main>
    <section class="hero-banner">
      <div class="overlay">
        <h1 class="title">Technology Support & Solutions</h1>
        <h2 class="subtitle mb-10">Enabling business growth through technology.</h2>
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
    <section class="testimonials">
      <div class="container">
        <h2>Our Work Speaks for Itself</h2>
        <div class="quotes">
          <figure>
            <figcaption>Hope Federal Credit Union</figcaption>
            <blockquote>
              <p>
                Justin made the implementation and purchase of a new firewall and cabinet solution extremely simple for
                us here at Hope Federal Credit Union. His attention to detail, consideration of time, and obvious
                professional expertise gave me a great deal of solace through this process. He saved us thousands of
                dollars and made himself available to answer any and all questions. Highly recommended!
              </p>
            </blockquote>
          </figure>
          <figure>
            <figcaption>Gold Standard Cleaning Services</figcaption>
            <blockquote>
              <p>
                I am a small business owner. I was experiencing issues with my business’s domain, website, google
                business profile and email. Once he took over, the situation was painless. Seybertech had me back up and
                all systems running within 48 hours. Their prices are very reasonable and they provide a top-notch
                service! If I could go back in time, the only thing I would do differently is: I wouldn’t have waited a
                week to call! Thank you again for everything!
              </p>
            </blockquote>
          </figure>
          <figure>
            <figcaption>Mark Everett Attorney at Law, PLLC</figcaption>
            <blockquote>
              <p>
                Professional and extremely responsive. I would recommend them in a heartbeat! They take on a project and
                work diligently until it is complete to customer’s satisfaction. Best around! (West Virginia for the
                Gospel) I would not hesitate to recommend them to anyone looking any kind of IT services. The owner is a
                great guy who keeps his word and values close relationships with his clients. Great job!
              </p>
            </blockquote>
          </figure>
          <figure>
            <figcaption>Matthew P. Crimmel Esq. Attorney at Law, PLLC</figcaption>
            <blockquote>
              <p>
                Professional, knowledgeable, and experienced. SeyberTech is not only thorough but is also well apprised
                on rapidly changing technology. Highly recommended.
              </p>
            </blockquote>
          </figure>
          <figure>
            <figcaption>Wagoner Desai, PLLC</figcaption>
            <blockquote>
              <p>
                Seybertech has been our go to for anything technology related for our business and we have never had a
                better experience with a local technology support company. More than once, they’ve delivered above and
                beyond to help us focus on the day to day of our practice. Thanks for the good work!
              </p>
            </blockquote>
          </figure>
          <figure>
            <figcaption>Enliven Chiropractic and Wellness</figcaption>
            <blockquote>
              <p>
                We've hired Justin for several years to handle critical parts of our IT system. His service is always
                professional and done correctly the first time.
              </p>
            </blockquote>
          </figure>
        </div>
      </div>
    </section>
    <section class="about">
      <div class="container">
        <h2>More About Us</h2>
        <p>
          SeyberTech is a locally and veteran-owned West Virginia based technology services company on a mission to
          optimize technology for businesses small to large from startups to enterprise level companies. We offer over
          15 years of technology industry experience providing IT and technical services to a wide range of clients,
          from early stage startups, to thriving local business to large corporations.
        </p>
        <p>
          Justin Seybert comes from an extensive technology background spanning from cyber security consulting for
          Federal clients to serving Fortune 100 technology companies in system design, integration and support.
        </p>
      </div>
    </section>
    <section class="cta" id="free-assessment">
      <div class="container">
        <h2>Schedule a free technology assessment today.</h2>
        <div class="form">
          <form name="contact" method="POST" data-netlify="true" data-netlify-recaptcha="true">
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
            <div data-netlify-recaptcha="true"></div>
            <button class="btn" type="submit">Get Assessment</button>
          </form>
        </div>
      </div>
    </section>
  </main>
</template>

<style lang="postcss" scoped>
.hero-banner {
  @apply w-full text-center rounded-lg;
  background: center center / cover no-repeat url(~/static/img/point.jpg);

  .overlay {
    @apply block w-full h-full py-48 px-8;
    background: #ffffff44;
  }

  h1,
  h2 {
    @apply drop-shadow  drop-shadow-lg;
  }
}

.services {
  @apply mb-6;
  margin-top: -3rem;

  .container {
    @apply grid gap-4 px-4 max-w-screen-lg m-auto md:gap-10 md:grid-cols-2 md:px-8;

    div {
      @apply py-10 px-6 bg-white rounded-lg shadow-lg border border-gray-100 text-center md:text-left md:px-10;

      h4 {
        @apply text-gray;
      }
    }
  }
}

.steps {
  @apply text-center my-6 mx-4 px-4 py-16 bg-gray-50 shadow-lg rounded-lg border border-gray-100 md:px-8;

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

.testimonials {
  @apply w-full border border-gray-200 rounded-lg px-4 py-16 md:p-10 md:m-6;

  h2 {
    @apply text-center mb-8 text-primary;
  }

  p {
    @apply mt-2 text-gray;
  }

  .container {
    @apply w-full;

    .quotes {
      @apply w-full grid gap-4 md:grid-cols-2 md:gap-8 lg:grid-cols-3;

      figure {
        @apply border border-gray-50 rounded-lg shadow-lg p-8;

        figcaption {
          @apply font-bold mt-2;
        }
      }
    }
  }
}

.about {
  @apply text-center px-4 py-20 bg-gray-50 shadow-lg rounded-lg border border-gray-100 m-4 md:px-4 md:m-6;

  .container {
    @apply max-w-lg m-auto;
  }

  p {
    @apply mt-4 text-gray;
  }
}

.cta {
  @apply px-8 py-20 shadow-lg rounded-lg border border-primary-100 m-4 md:m-6;
  background: linear-gradient(60deg, #00a0e433, #00a0e411);

  h2 {
    @apply text-center mb-8;
  }
}
</style>