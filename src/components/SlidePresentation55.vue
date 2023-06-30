<template>
  <div class="slide">
    <div class="heading">RESTful - Routing et Controllers</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 60%">
          <h2>Qu'est-ce que MVC ?</h2>
          <p>
            MVC divise l'interaction entre l'utilisateur et l'interface en trois
            rôles distincts
          </p>
          <h3>Trois variantes principales de MVC</h3>
          <br />
          <ul>
            <li>
              <h4>Model:</h4>
              Représente une table de base de données individuelle par exemple
              "Entreprise" ou "Chien".
            </li>
            <li>
              <h4>View:</h4>
              Représente le template qui transmet vos données à l'utilisateur
              final
            </li>
            <li>
              <h4>Controller:</h4>
              Reçoit les requêtes HTTP du navigateur, obtient les bonnes
              données, valide les entrées de l'utilisateur et renvoie finalement
              une réponse à l'utilisateur
            </li>
          </ul>
        </div>
        <div style="width: 40%">
          <img src="../assets/illustrations/mvc.svg" style="width: 99%" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
