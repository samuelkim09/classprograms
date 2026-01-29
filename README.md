# 🌐 menu

## 📄 pages disponibles

<!-- PAGES-LIST:START -->
<input type="text" id="search" placeholder="🔍 Rechercher une page..." onkeyup="filterPages()" style="width:100%;padding:8px;margin-bottom:10px;">
<ul id="pages">
<li data-title="Bac blanc anticipé de maths spé"><a href="Bac_blanc_anticipé_de_maths_spé.html">Bac blanc anticipé de maths spé</a></li>
<li data-title="Lewis • Géométrie • Polarité (1re spé Physique-Chimie)"><a href="Lewis_Géométrie_Polarité.html">Lewis • Géométrie • Polarité (1re spé Physique-Chimie)</a></li>
<li data-title="QCM Mathématiques Première Spé (Bac blanc) - Mathaléa"><a href="qcm-mathématiques-mathaléa-premierespe.html">QCM Mathématiques Première Spé (Bac blanc) - Mathaléa</a></li>
<li data-title="Quiz vocabulaire anglais - Esclavage (1re LV1)"><a href="quiz_vocabulaire_anglais_esclavage.html">Quiz vocabulaire anglais - Esclavage (1re LV1)</a></li>
</ul>
<script>
function filterPages() {
  const q = document.getElementById('search').value.toLowerCase();
  document.querySelectorAll('#pages li').forEach(li => {
    li.style.display = li.dataset.title.toLowerCase().includes(q) ? '' : 'none';
  });
}
</script>
<!-- PAGES-LIST:END -->

---
🔄 Liste générée automatiquement à partir des fichiers HTML.
