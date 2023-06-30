<template>
  <div class="slide">
    <div class="heading">RESTful - Route Verb Delete</div>
    <div class="content">
      <p>
        Exercice : pouvez-vous implémenter la méthode de suppression? Je veux
        que vous renvoyiez le Pseudo supprimé à l'appelant sous forme de JSON.
        Vérifier avec une requête GET suivante que le Pseudo a bien été
        supprimé. Vérifiez dans la
        <a href="https://laravel.com/docs/10.x/eloquent#retrieving-models"
          >documentation</a
        >
        si vous pouvez trouver une fonction qui fait ce dont nous avons besoin.
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
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>delete<span style="color: #333333">(</span><span style="color: #FF0000; background-color: #FFAAAA">&#39;</span><span style="color: #333333">/</span>pseudos<span style="color: #333333">/{</span>id<span style="color: #333333">}</span><span style="color: #FF0000; background-color: #FFAAAA">&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">(</span>$id<span style="color: #333333">){</span>
          <span style="color: #888888">//mettre l&#39;implémentation ici</span>
        <span style="color: #333333">});</span></pre>
      </div>

      <br />
      <p>
        Pour le point de terminaison DELETE: /pseudos/1, je m'attends à un
        résultat similaire :
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
