<template>
  <div class="slide">
    <div class="heading">RESTful - Route avec apiResource</div>
    <div class="content">
      <p>
        Exercice : Pouvez-vous transférer le code que vous avez écrit dans
        api.php dans le contrôleur nouvellement créé ?
      </p>
      <br />
      <p>
        Exercice: Pouvez-vous mettre en œuvre la méthode : store et update ?
        Vous pouvez utiliser la
        <a
          href="https://laravel.com/docs/10.x/eloquent#inserting-and-updating-models"
          >documentation</a
        >
        pour résoudre le problème.
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
        <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">store</span><span style="color: #333333">(</span>Request $request<span style="color: #333333">){</span> <span style="color: #888888">//POST}}</span>

        <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">update</span><span style="color: #333333">(</span>Request $request<span style="color: #333333">,</span> $id<span style="color: #333333">){</span> <span style="color: #888888">//PUT }</span></pre>
      </div>
      <br />
      <p>
        Exercice : pouvez-vous créer CountryResource comme PseudoResource pour
        le modèle Country et le lier dans api.php.
      </p>
    </div>
  </div>
</template>

<style scoped></style>
