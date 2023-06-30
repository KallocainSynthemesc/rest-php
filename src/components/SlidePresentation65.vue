<template>
  <div class="slide">
    <div class="heading">RESTful - Route Verbs</div>
    <div class="content">
      <p>
        Nous avons déjà vu Route::get mais nous avons en fait toutes les
        méthodes HTTP en tant que Route Verbs :
      </p>
      <div class="flex-container">
        <div style="width: 68%">
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
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>post<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">//Gérer quelqu&#39;un qui envoie une requête POST à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>put<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer quelqu&#39;un qui envoie une requête PUT à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>delete<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer quelqu&#39;un qui envoie une requête DELETE à cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>any<span style="color: #333333">(</span><span style="color: #0044DD">&#39;/&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer toute demande de verbe vers cette route</span>
        <span style="color: #333333">});</span>
        <span style="color: #997700; font-weight: bold">Route:</span><span style="color: #333333">:</span>match<span style="color: #333333">([</span><span style="color: #FF0000; background-color: #FFAAAA">&#39;</span>get<span style="color: #FF0000; background-color: #FFAAAA">&#39;</span><span style="color: #333333">,</span> <span style="color: #FF0000; background-color: #FFAAAA">&#39;</span>post<span style="color: #FF0000; background-color: #FFAAAA">&#39;</span><span style="color: #333333">],</span> <span style="color: #0044DD">&#39;/&#39;</span><span style="color: #333333">,</span> function <span style="color: #333333">()</span> <span style="color: #333333">{</span>
          <span style="color: #888888">// Gérer les requêtes GET ou POST vers cette route</span>
        <span style="color: #333333">});</span></pre>
          </div>
        </div>
        <div style="width: 29%">
          <img
            src="../assets/illustrations/machinetranslation-1926.svg"
            style="width: 99%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
