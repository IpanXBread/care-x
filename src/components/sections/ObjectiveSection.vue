<template>
  <section id="objectives" class="section">
    <div class="content-wrapper">
      <div class="title-container">
        <h1 class="title">OBJEKTIF<br>PROGRAM</h1>
      </div>
      <div class="text-container">
        <p class="objective-text">
          • <strong>Meningkatkan inovasi dalam sektor penjagaan</strong> – Menyediakan penyelesaian baharu yang lebih baik dan mampu milik untuk golongan sasaran.
        </p>
        <p class="objective-text">
          • <strong>Menyokong pertumbuhan perniagaan dalam sektor penjagaan</strong> – Memberikan latihan, bimbingan, rangkaian, dan infrastruktur bagi membolehkan perniagaan berkembang dan berdaya saing.
        </p>
        <p class="objective-text">
          • <strong>Mewujudkan ekosistem penjagaan yang mampan</strong> – Memastikan perkhidmatan penjagaan berkualiti tinggi dapat diakses oleh rakyat negeri Selangor tanpa mengira status ekonomi mereka
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ObjectiveSection'
}
</script>

<style scoped>
.section {
  padding: 4rem 2rem;
}

.content-wrapper {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: flex-start;
  gap: 4rem;
}

.title-container {
  flex: 1;
  position: sticky;
  top: 100px;
}

.title {
  font-size: 3.5rem;
  color: var(--text-primary);
  line-height: 1.2;
  font-weight: bold;
}

.text-container {
  flex: 2;
  background-color: var(--background-light);
  padding: 3rem;
  border-radius: var(--border-radius);
}

.objective-text {
  font-size: 1.2rem;
  line-height: 1.8;
  text-align: justify;
  color: var(--text-secondary);
  margin-bottom: 1.5rem;
}

.objective-text:last-child {
  margin-bottom: 0;
}

@media (max-width: 768px) {
  .content-wrapper {
    flex-direction: column;
    gap: 2rem;
    text-align: center;
  }

  .title-container {
    position: static;
  }

  .title {
    font-size: 2.5rem;
  }

  .text-container {
    padding: 2rem;
  }
}
</style> 