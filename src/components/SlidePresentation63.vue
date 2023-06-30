<template>
  <div class="slide">
    <div class="heading">RESTful - Route Parameters</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 56%">
          <p>
            Si la route que vous définissez a des paramètres - des segments de
            la structure URL qui sont variables, il est simple de les définir
            dans votre route et de les passer à la closure
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
          <p>
            {id} dans 'pseudos/{id}' est injecté en tant que variable dans la
            fonction.
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
            ><span style="color: #000000; background-color: #fff0ff">/users/</span><span style="color: #0000DD; font-weight: bold">1</span> avec cette URL la valeur de $id serait 1</pre>
          </div>
          <br />
          <p>
            vous pouvez utiliser des regexes pour exécuter la fonction si un
            paramètre répond à des exigences particulières
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
        <span style="color: #0e84b5; font-weight: bold">Route::</span>get(<span style="background-color: #fff0f0">&#39;users/{id}&#39;</span>, function (<span style="color: #996633">$id</span>) {
        <span style="color: #000000; background-color: #fff0ff">//</span>
        })<span style="color: #333333">-&gt;</span>where(<span style="background-color: #fff0f0">&#39;id&#39;</span>, <span style="background-color: #fff0f0">&#39;[0-9]+&#39;</span>);</pre>
          </div>
        </div>
        <div style="width: 42%">
          <img src="../assets/illustrations/syringe.svg" style="width: 99%" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
