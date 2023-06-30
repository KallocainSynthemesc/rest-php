<template>
  <div class="slide">
    <div class="heading">RESTful - Route Réalisation</div>
    <div class="content">
      <p>
        Lorsque l'on utilise un client HTTP comme
        <a href="https://www.postman.com/downloads/">postman</a>, on peut
        maintenant appeler :
      </p>
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
        <pre
          style="margin: 0; line-height: 125%"
        >GET PROJECT_NAME<span style="color: #333333">.</span>test<span style="color: #000000; background-color: #fff0ff">/api/</span>pseudos</pre>
      </div>
      <br />
      <p>
        Exercice: Lancez le projet et essayez d'appeler le point de terminaison
        REST "PROJECT_NAME.test/api/pseudos" à l'aide de la méthode GET.
      </p>
      <p>
        En raison de la politique CORS (restrictions de sécurité qui devraient
        être configurées sur le serveur PHP), nous ne pouvons plus utiliser mon
        client REST dans le navigateur.
      </p>
    </div>
  </div>
</template>

<style scoped></style>
