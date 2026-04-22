<template>
  <section class="hero">
    <div class="container">
      <div class="hero-card">
        <p class="eyebrow">Bine ați venit</p>
        <h1>Bine ați venit pe pagina noastră, echipa Pronord</h1>
        <p class="description">
          Oferim soluții profesionale și servicii adaptate nevoilor dumneavoastră.
        </p>

        <div class="actions">
          <RouterLink to="/servicii" class="primary-btn">Vezi servicii</RouterLink>
          <RouterLink to="/contact" class="secondary-btn">Contactează-ne</RouterLink>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  padding: 80px 24px;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

.hero-card {
  background: linear-gradient(135deg, #1e3a8a, #2563eb);
  color: white;
  border-radius: 24px;
  padding: 64px 48px;
  box-shadow: 0 20px 45px rgba(37, 99, 235, 0.18);
}

.eyebrow {
  font-size: 14px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1.2px;
  margin-bottom: 12px;
  opacity: 0.9;
}

h1 {
  font-size: 48px;
  line-height: 1.15;
  margin: 0 0 20px;
}

.description {
  font-size: 18px;
  line-height: 1.6;
  max-width: 700px;
  margin-bottom: 32px;
}

.actions {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}

.primary-btn,
.secondary-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 48px;
  padding: 0 22px;
  border-radius: 12px;
  text-decoration: none;
  font-weight: 700;
  transition: 0.2s ease;
}

.primary-btn {
  background: white;
  color: #1d4ed8;
}

.primary-btn:hover {
  transform: translateY(-1px);
}

.secondary-btn {
  border: 1px solid rgba(255, 255, 255, 0.5);
  color: white;
}

.secondary-btn:hover {
  background: rgba(255, 255, 255, 0.08);
}

@media (max-width: 768px) {
  .hero {
    padding: 40px 16px;
  }

  .hero-card {
    padding: 32px 24px;
  }

  h1 {
    font-size: 32px;
  }

  .description {
    font-size: 16px;
  }
}
</style>