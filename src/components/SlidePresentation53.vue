<template>
  <div class="slide">
    <div class="heading">RESTful - Laravel</div>
    <div class="content">
      <h2>Les dossiers</h2>
      <div class="flex-container">
        <div style="width: 48%">
          <h3>app</h3>
          <p>
            l'essentiel de votre application réelle. Les modèles, les
            contrôleurs, les commandes et le code de votre domaine PHP
          </p>
          <h3>bootstrap</h3>
          <p>Les fichiers que Laravel utilise pour démarrer.</p>
          <h3>config</h3>
          <p>Les fichiers de configuration</p>
          <h3>database</h3>
          <p>
            Là où vivent les migrations de bases de données, les seeds et les
            factories.
          </p>
          <h3>vendor</h3>
          <p>où Composer installe ses dépendances</p>
        </div>
        <div style="width: 48%">
          <h3>public</h3>
          <p>
            Point d'entrée du serveur (index.php). Les fichiers public (images,
            css, js, téléchargements)
          </p>
          <h3>resources</h3>
          <p>Les fichiers nécessaires à d'autres scripts.</p>
          <h3>routes</h3>
          <p>Itinéraires HTTP, console ou commandes Artisan</p>
          <h3>storage</h3>
          <p>caches, logs et les fichiers système compilés</p>
          <h3>tests</h3>
          <p>tests unitaires et d'intégration</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
