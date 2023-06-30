<template>
  <div class="slide">
    <div class="heading">RESTful - Pagination</div>
    <div class="content">
      <p>
        Vous pouvez paginer de grands ensembles de données et effectuer les
        requêtes par petits morceaux, en laissant le consommateur de l'API de
        progresser dans la pagination.
      </p>
      <br />
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
        ><span style="color: #333333">/</span>users?page<span style="color: #333333">=</span><span style="color: #0000DD; font-weight: bold">1</span></pre>
      </div>
      <p>
        Cet exemple affiche la première page avec la taille de page par défaut.
      </p>
      <br />
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
        >/users?page<span style="color: #333333">=</span><span style="color: #0000DD; font-weight: bold">2</span><span style="color: #333333">&amp;</span>limit<span style="color: #333333">=</span><span style="color: #0000DD; font-weight: bold">5</span></pre>
      </div>
      <p>soit avec la limite ou size, on peut imposer la taille de la page.</p>
      <br />
      <p>
        Mais il peut y avoir d'autres styles de pagination, comme le décrit par
        exemple la spécification JSON:API :
      </p>
      <ul>
        <li>first: première page de données</li>
        <li>last : dernière page de données</li>
        <li>prev : la page précédente des données</li>
        <li>next : la page de données suivante</li>
      </ul>
    </div>
  </div>
</template>

<style scoped></style>
