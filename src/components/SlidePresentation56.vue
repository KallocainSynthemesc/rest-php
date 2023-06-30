<template>
  <div class="slide">
    <div class="heading">RESTful - Routing et Controllers</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 60%">
          <p>
            MVC divise l'interaction entre l'utilisateur et l'interface en trois
            rôles distincts
          </p>
          <h3>Trois variantes principales de MVC</h3>
          <br />
          <ul>
            <li>
              <h4>MVC (Model-View-Controller):</h4>
              la vue communique directement avec le modèle, ce qui peut conduire
              à un couplage étroit entre les deux
            </li>
            <li>
              <h4>MVP (Model-View-Presenter):</h4>
              le présentateur joue le rôle d'intermédiaire entre la vue et le
              modèle. La vue est passive et ne communique pas directement avec
              le modèle.
            </li>
            <li>
              <h4>MVVM (Model-View-ViewModel):</h4>
              La principale différence avec le MVP est que la View est liée
              directement au ViewModel, de sorte que le ViewModel n'a pas besoin
              d'interagir avec la View par l'intermédiaire d'un Presenter.
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
