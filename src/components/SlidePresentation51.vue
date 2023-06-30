<template>
  <div class="slide">
    <div class="heading">RESTful - Laravel</div>
    <div class="content">
      <h2>Installation</h2>
      <br />
      <h3>Install Xampp</h3>
      <p>
        Installer Xampp à partir de
        <a href="https://www.apachefriends.org/index.html"
          >https://www.apachefriends.org/index.html</a
        >
      </p>
      <br />
      <h3>Installer Composer</h3>
      <p>
        Télécharger et exécuter l'installateur
        <a href="https://getcomposer.org/download"
          >https://getcomposer.org/download</a
        >
      </p>
      <br />
      <h3>Créer un nouveau projet Laravel avec Composer</h3>
      <p>
        Ouvrez un terminal dans le dossier htdocs.<br />
        <span style="font-size: 1.6rem">→</span>Windows - C:\Xampp\htdocs<br />
        <span style="font-size: 1.6rem">→</span>Mac - /opt/lampp/htdocs
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
        >composer create<span style="color: #333333">-</span>project <span style="color: #333333">--</span>prefer<span style="color: #333333">-</span>dist laravel<span style="color: #333333">/</span>laravel PROJECT_NAME</pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
