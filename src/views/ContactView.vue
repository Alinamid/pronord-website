<template>
  <section class="page-section">
    <div class="container">
      <h1>Contact</h1>
      <p class="intro">
        Ne puteți contacta pentru informații suplimentare sau colaborări.
      </p>

      <div class="contact-layout">
        <div class="contact-card">
          <p><strong>Telefon:</strong> 07663555572</p>
          <p><strong>Email:</strong> pronord.business@gmail.com</p>
          <p>
            <strong>Adresă:</strong> Șos. Alexandriei 23, Buda, Cornetu, Ilfov
          </p>
        </div>

        <div class="map-card">
          <iframe
            title="Locație Pronord"
            src="https://www.google.com/maps?q=Sos%20Alexandriei%2023%20Buda%20Cornetu%20Ilfov&output=embed"
            width="100%"
            height="320"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.page-section {
  padding: 64px 24px;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

h1 {
  font-size: 40px;
  margin-bottom: 16px;
  color: #0f172a;
}

.intro {
  font-size: 18px;
  color: #475569;
  margin-bottom: 32px;
}

.contact-layout {
  display: grid;
  grid-template-columns: 1fr 1.2fr;
  gap: 24px;
  align-items: stretch;
}

.contact-card,
.map-card {
  background: white;
  border-radius: 20px;
  padding: 32px;
  border: 1px solid #e2e8f0;
  box-shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
}

.contact-card p {
  margin-bottom: 14px;
  font-size: 17px;
  color: #334155;
  line-height: 1.6;
}

.map-card {
  padding: 16px;
  overflow: hidden;
}

.map-card iframe {
  display: block;
  width: 100%;
  border-radius: 14px;
}

@media (max-width: 900px) {
  .contact-layout {
    grid-template-columns: 1fr;
  }
}
</style>