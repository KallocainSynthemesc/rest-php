<template>
  <div class="slide">
    <div class="heading">RESTful - Route avec apiResource</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 48%">
          <h3>
            Un exemple de contrôleur de ressources API pour l'entité Pseudo
          </h3>
          <br />
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
<span style="color: #008800; font-weight: bold">class</span> <span style="color: #BB0066; font-weight: bold">PseudoResource</span> <span style="color: #008800; font-weight: bold">extends</span> Controller
<span style="color: #333333">{</span>
    <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">index</span><span style="color: #333333">(){</span> <span style="color: #888888">//GET}</span>}
  
    <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">store</span><span style="color: #333333">(</span>Request $request<span style="color: #333333">){</span> <span style="color: #888888">//POST}</span>}
  
    <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">show</span><span style="color: #333333">(</span>$id<span style="color: #333333">){</span> <span style="color: #888888">//GET/{id}</span>}

    <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">update</span><span style="color: #333333">(</span>Request $request<span style="color: #333333">,</span> $id<span style="color: #333333">){</span> <span style="color: #888888">//PUT</span>}

    <span style="color: #008800; font-weight: bold">public</span> function <span style="color: #0066BB; font-weight: bold">destroy</span><span style="color: #333333">(</span>$id<span style="color: #333333">){</span> <span style="color: #888888">//DELETE</span>}
<span style="color: #333333">}</span></pre>
          </div>
        </div>
        <div style="width: 48%">
          <p>
            nous pouvons utiliser Route::apiResource() pour mapper
            automatiquement automatiquement toutes ces méthodes par défaut à
            leurs routes et verbes HTTP
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
    <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>apiResource<span style="color: #333333">(</span><span style="color: #FF0000; background-color: #FFAAAA">&#39;</span>users<span style="color: #FF0000; background-color: #FFAAAA">&#39;</span><span style="color: #333333">,</span><span style="color: #997700; font-weight: bold">PseudoResource:</span><span style="color: #333333">:</span>class<span style="color: #333333">);</span></pre>
          </div>
          <br />
          <p>
            Ainsi, notre fichier api.php ne fait que déléguer au
            ResourceController et reste propre.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
