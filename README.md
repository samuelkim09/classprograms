# 🌐 menu

## 📄 pages disponibles

<!-- PAGES-LIST:START -->
<input type="text" id="search" placeholder="🔍 Rechercher une page..." onkeyup="filterPages()" style="width:100%;padding:8px;margin-bottom:10px;">

<ul id="pages">
<li data-title="Lewis_Géométrie_Polarité.html"><a href="Lewis_Géométrie_Polarité.html">Lewis_Géométrie_Polarité.html</a></li>
<li data-title="QCM Mathématiques Première Spé (Bac blanc) - Mathaléa"><a href="qcm-mathématiques-mathaléa-premierespe.html">QCM Mathématiques Première Spé (Bac blanc) - Mathaléa</a></li>
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
