<template>
  <section class="page-section">
    <div class="container">
      <h1>Servicii</h1>
      <p class="intro">
        Serviciile oferite de echipa Pronord.
      </p>

      <div class="cards">
        <article class="card">
          <h2>Montare aer condiționat</h2>
          <p>
            Oferim servicii profesionale de montaj pentru aparate de aer condiționat,
            rapid și în siguranță.
          </p>
        </article>

        <article class="card">
          <h2>Service sisteme climatizare</h2>
          <p>
            Realizăm verificări, întreținere și reparații pentru sisteme de climatizare,
            pentru funcționare optimă și durată de viață extinsă.
          </p>
        </article>

        <article class="card">
          <h2>Montare sisteme climatizare</h2>
          <p>
            Instalăm sisteme de climatizare pentru locuințe, birouri și spații comerciale,
            adaptate nevoilor fiecărui client.
          </p>
        </article>
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

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
}

.card {
  background: white;
  border-radius: 20px;
  padding: 24px;
  box-shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
  border: 1px solid #e2e8f0;
}

.card h2 {
  margin-bottom: 12px;
  color: #1e293b;
}

.card p {
  color: #64748b;
  line-height: 1.6;
}

@media (max-width: 900px) {
  .cards {
    grid-template-columns: 1fr;
  }
}
</style>