# Tableau de bord (test)

<canvas id="graphique-test" style="max-height: 400px;"></canvas>

<script>
  new Chart(document.getElementById('graphique-test'), {
    type: 'bar',
    data: {
      labels: ['Chapitre 1', 'Chapitre 2', 'Chapitre 3', 'Chapitre 4'],
      datasets: [{
        label: 'Note moyenne',
        data: [12, 15, 9, 14]
      }]
    }
  });
</script>