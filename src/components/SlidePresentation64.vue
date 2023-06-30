<template>
  <div class="slide">
    <div class="heading">RESTful - Route Parameters</div>
    <div class="content">
      <p>
        Exercice : Pouvez-vous implémenter la fonction de manière à ce qu'elle
        renvoie l'utilisateur correct sous forme de JSON en fonction du
        paramètre ID passé dans l'URL ?
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
        <pre style="margin: 0; line-height: 125%">
        <span style="color: #0e84b5; font-weight: bold">Route::</span>get(<span style="background-color: #fff0f0">&#39;/pseudos/{id}&#39;</span>, function (<span style="color: #996633">$id</span>){
            <span style="color: #000000; background-color: #fff0ff">//</span><span style="color: #996633">$id</span> a la valeur du parametre dans <span style="color: #000000; font-weight: bold">le</span> chemin
        });</pre>
      </div>
      <br />
      <p>
        Pour le point de terminaison GET: /pseudos/1, je m'attends à un résultat
        similaire :
      </p>
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
        {
          <span style="color: #007700">&quot;id&quot;</span>: <span style="color: #0000DD; font-weight: bold">1</span>,
          <span style="color: #007700">&quot;pseudo&quot;</span>: <span style="background-color: #fff0f0">&quot;Kilian&quot;</span>,
          <span style="color: #007700">&quot;email&quot;</span>: <span style="background-color: #fff0f0">&quot;k.s@gmail.com&quot;</span>,
          <span style="color: #007700">&quot;country_id&quot;</span>: <span style="color: #0000DD; font-weight: bold">84</span>
        }</pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
