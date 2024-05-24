<template>
  <div class="user-agreement">
    <h1>User Agreement</h1>

    <section>
      <h2>1. Introduction</h2>
      <p>
        Welcome to our apartment management system. This User Agreement governs
        your use of the services provided by our platform. By accessing or using
        our platform, you agree to comply with and be bound by the terms and
        conditions of this agreement.
      </p>
    </section>

    <section>
      <h2>2. Acceptance of Terms</h2>
      <p>
        By using our apartment management system, you agree to these terms and
        conditions. If you do not agree to these terms, please do not use the
        platform.
      </p>
    </section>

    <section>
      <h2>3. Description of Service</h2>
      <p>Our apartment management system allows users to:</p>
      <ul>
        <li>Browse available apartments</li>
        <li>Submit maintenance requests</li>
        <li>Pay rent and other fees</li>
        <li>Communicate with management</li>
        <li>Access community resources and announcements</li>
      </ul>
    </section>

    <section>
      <h2>4. User Responsibilities</h2>
      <p>As a user of our platform, you agree to:</p>
      <ul>
        <li>Provide accurate and complete information</li>
        <li>Keep your account credentials confidential</li>
        <li>Comply with all community rules and guidelines</li>
        <li>Respect the privacy of other users</li>
      </ul>
    </section>

    <section>
      <h2>5. Privacy Policy</h2>
      <p>
        We are committed to protecting your privacy. Please review our
        <a href="/privacy-policy">Privacy Policy</a> to understand how we
        collect, use, and disclose your personal information.
      </p>
    </section>

    <section>
      <h2>6. Limitation of Liability</h2>
      <p>
        We shall not be liable for any direct, indirect, incidental, special, or
        consequential damages resulting from the use or inability to use our
        apartment management system.
      </p>
    </section>

    <section>
      <h2>7. Changes to Terms</h2>
      <p>
        We reserve the right to modify or replace these terms at any time. Your
        continued use of the platform after any such changes constitutes your
        acceptance of the new terms.
      </p>
    </section>

    <section>
      <h2>8. Contact Us</h2>
      <p>
        If you have any questions or concerns about this user agreement, please
        <a href="/contact">contact us</a>.
      </p>
    </section>

    <button @click="acceptTerms">I Accept</button>
  </div>
</template>

<style scoped>
/* Styles for user agreement */
.user-agreement {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}
.user-agreement section {
  margin-bottom: 20px;
}
</style>
