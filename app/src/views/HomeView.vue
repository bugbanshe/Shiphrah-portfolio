<template>
  <div
    class="bg-black text-green-400 font-mono h-screen flex flex-col items-center"
  >
    <!-- Profile -->
    <section class="hero">
      <div class="hero-content">
        <h1 class="name">
          <span class="gradient-text">Shiphrah Wairima</span
          ><span class="cursor">|</span>
        </h1>
        <p class="animated-text">
          <span id="changing-text"></span>
        </p>
        <p class="tagline">
          <i
            >Roses are red, Violets are blue, A hacker in heels, Will always
            outsmart you.</i
          >
        </p>
        <div class="social-links">
          <a href="mailto:your-email@example.com" class="button">📩 Email Me</a>
          <a href="https://linkedin.com/in/yourprofile" class="button linkedin"
            >🔗 LinkedIn</a
          >
          <a href="https://twitter.com/yourtwitter" class="button twitter"
            >🐦 Twitter</a
          >
        </div>
      </div>
    </section>

    <section class="about">
      <div class="container">
        <h2>About Me</h2>
        <p>Cybersecurity & AI Governance | Advocate for Women in Tech</p>
        <p>
          For me, cybersecurity and AI governance have always been about people.
        </p>
        <p>
          I started by securing systems and investigating threats, but I
          realized something bigger: there weren’t enough women in the room, and
          Africa wasn’t part of critical AI and cybersecurity conversations. So,
          I made it my mission to change that.
        </p>

        <h3>What I Do:</h3>
        <ul>
          <li>
            <strong>Cybersecurity Leadership:</strong> I specialize in
            penetration testing, SOC operations, threat intelligence, and
            incident response.
          </li>
          <li>
            <strong>AI Governance & Policy:</strong> As the Global Ambassador
            for Kenya at the Global Council for Responsible AI, I advocate for
            ethical AI policies that include Africa.
          </li>
          <li>
            <strong>Women in Tech Advocacy:</strong> Co-founded
            <b>Silicon Kenya Organisation</b>, helping 300+ people start careers
            in tech & freelancing.
          </li>
          <li>
            <strong>Innovation & Research:</strong> Working on
            **quantum-resistant cryptography solutions** and enhancing security
            frameworks for emerging threats.
          </li>
        </ul>
        <p>
          If you're looking for guidance, collaboration, or mentorship, let’s
          connect!
        </p>
      </div>
    </section>

    <!-- Featured Events Section -->
    <section class="p-10">
      <h2 class="text-3xl mb-5">📢 Featured Awards , Talks & Events</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
        <div class="bg-gray-900 p-5 rounded-lg">
          <!-- <img src="src/assets/techexpo.jpg" alt="Event 1" class="rounded-lg" /> -->
          <h3 class="text-2xl mt-3">Tech Expo 2024</h3>
          <p class="text-gray-400">Spoke about TechPrenureship.</p>
          <a href="#" class="link">See More →</a>
        </div>
        <div class="bg-gray-900 p-5 rounded-lg">
          <!-- <img
            src="src/assets/youthmonth.jpg"
            alt="Event 2"
            class="rounded-lg"
          /> -->
          <h3 class="text-2xl mt-3">Youth Month 2024</h3>
          <p class="text-gray-400">
            Panel discussion on Technology and Digital Transformation.
          </p>
          <a href="#" class="link">See More →</a>
        </div>

        <div class="bg-gray-900 p-5 rounded-lg">
          <!-- <img src="src/assets/GCRAI.jpg" alt="Event 3" class="rounded-lg" /> -->
          <h3 class="text-2xl mt-3">Global Ambassador 2024</h3>
          <p class="text-gray-400">Global Council of Responsible AI.</p>
          <a href="#" class="link">See More →</a>
        </div>

        <div class="bg-gray-900 p-5 rounded-lg">
          <!-- <img src="src/assets/Wtechnet.jpg" alt="Event 4" class="rounded-lg" /> -->
          <h3 class="text-2xl mt-3">Womentech Network</h3>
          <p class="text-gray-400">
            WomenTech Network Community Award Local Winner for Kenya.
          </p>
          <a href="#" class="link">See More →</a>
        </div>

        <div class="bg-gray-900 p-5 rounded-lg">
          <!-- <img
            src="src/assets/Generation.jpg"
            alt="Event 4"
            class="rounded-lg"
          /> -->
          <h3 class="text-2xl mt-3">generation</h3>
          <p class="text-gray-400">Global Alumni Ambasadors Council.</p>
          <a href="#" class="link">See More →</a>
        </div>
      </div>
    </section>

    <!-- Companies & Brands -->
    <section class="terminal mt-10">
      <h2 class="text-3xl glitch">> Companies & Brands</h2>
      <p class="mt-2">I have worked with:</p>
      <div class="flex justify-center space-x-4 mt-3">
        <!-- <img
          src="src/assets/logos/generation.png"
          alt="generation"
          class="w-20"
        /> -->
        <!-- <img
          src="src/assets/logos/womentech_network.jpg"
          alt="womentech network"
          class="w-20"
        /> -->
        <!-- <img
          src="src/assets/logos/global_council_for_responsible_ai.png"
          alt="global_council_for_responsible_ai"
          class="w-20"
        /> -->
        <!-- <img
          src="src/assets/logos/techsisterske.png"
          alt="techsisterske"
          class="w-20"
        /> -->
        <!-- <img
          src="src/assets/logos/lish_ai.png"
          alt="Lish AI Labs"
          class="w-20"
        /> -->
        <!-- <img
          src="src/assets/logos/thetechinteractive.png"
          alt="thetechinteractive"
          class="w-20"
        /> -->
      </div>
    </section>

    <!-- Awards & Speaking Engagements -->
    <section class="terminal mt-10">
      <h2 class="text-3xl glitch">> Awards & Speaking Engagements</h2>
      <ul class="mt-4">
        <li>🏆 Top 50 Women in Cybersecurity 2024</li>
        <li>🎤 Speaker at Tech Expo 2024</li>
        <li>🏆 Best Cybersecurity Project – XYZ Conference</li>
      </ul>
    </section>

    <!-- Newsletter Subscription -->
    <section class="newsletter">
      <h2 class="text-3xl glitch">Subscribe to My Newsletter</h2>
      <p>
        Get the latest updates on cybersecurity, bug bounties, and my events.
      </p>
      <form
        action="https://your-substack-url.com"
        method="post"
        target="_blank"
      >
        <input
          type="email"
          name="email"
          placeholder="Enter your email"
          required
          class="email-input"
        />
        <button type="submit" class="subscribe-button">Subscribe</button>
      </form>
    </section>
  </div>
</template>

<script setup></script>
