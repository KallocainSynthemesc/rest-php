<template>
  <div class="slide">
    <div class="heading">RESTful - Route</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 65%">
          <h2>On l'a fait d'une manière un peu moche</h2>
          <br />
          <p>
            Supposons que notre API se développe et que nous souhaitions
            également disposer d'un point de terminaison pour "Country ".
            api.php va être surchargé de fonctions à un moment donné.
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
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>get<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/countries&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">//Gérer quelqu&#39;un qui envoie une requête GET à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>post<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/countries&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">//Gérer quelqu&#39;un qui envoie une requête POST à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>put<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/countries/{id}&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer quelqu&#39;un qui envoie une requête PUT à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>delete<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/countries/{id}&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer quelqu&#39;un qui envoie une requête DELETE à cette route</span>
        <span style="color: #333333">});</span></pre>
          </div>
        </div>
        <div style="width: 32%">
          <img
            src="../assets/illustrations/uglydonkey.svg"
            style="width: 99%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
