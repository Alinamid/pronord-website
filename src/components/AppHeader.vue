<template>
  <header class="header">
    <div class="container header-content">
      <div class="logo">PRONORD</div>

      <nav class="nav">
        <RouterLink to="/" class="nav-link">Acasă</RouterLink>
        <RouterLink to="/servicii" class="nav-link">Servicii</RouterLink>
        <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background: #ffffff;
  border-bottom: 1px solid #e2e8f0;
  position: sticky;
  top: 0;
  z-index: 10;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 24px;
}

.header-content {
  min-height: 72px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo {
  font-size: 22px;
  font-weight: 700;
  color: #0f172a;
  letter-spacing: 1px;
}

.nav {
  display: flex;
  align-items: center;
  gap: 24px;
}

.nav-link {
  text-decoration: none;
  color: #334155;
  font-weight: 600;
  transition: color 0.2s ease;
}

.nav-link:hover {
  color: #2563eb;
}

.nav-link.router-link-active {
  color: #2563eb;
}
</style>