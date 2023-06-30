<template>
  <div class="slide">
    <div class="heading">RESTful - Route Definitions</div>
    <div class="content">
      <p>Créons notre première route API REST dans routes/api.php</p>
      <!-- HTML generated using hilite.me -->
      <div
        style="
          background: #ffffff;
          overflow: auto;
          width: auto;
          border: solid gray;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
        "
      >
        <pre style="margin: 0; line-height: 125%">
        <span style="color: #0e84b5; font-weight: bold">Route::</span>get(<span style="background-color: #fff0f0">&#39;/pseudos&#39;</span>, function (){
            <span style="color: #008800; font-weight: bold">return</span> <span style="color: #0e84b5; font-weight: bold">Pseudo::</span>all();
        });</pre>
      </div>

      <br />
      <p>
        Avec <span style="background-color: #fff0f0">&#39;/pseudos&#39;</span>,
        nous définissons le point de terminaison
      </p>
      <p>
        avec
        <span style="color: #0e84b5; font-weight: bold">Pseudo::</span>all(); ,
        nous obtenons les informations pour tous les pseudos à partir de la base
        de données.
      </p>
      <h3>
        Si vous renvoyez le résultat d'un appel Eloquent dans un contrôleur, il
        sera automatiquement transformé en chaîne de caractères, et donc renvoyé
        en JSON. Cool
      </h3>
    </div>
  </div>
</template>

<style scoped></style>
