<template>
  <div class="slide">
    <div class="heading">Conception de services RESTful</div>
    <div class="content">
      <h2>Définition du format des données en JSON</h2>
      <div class="flex-container">
        <div style="width: 40%">
          <h3>Pseudo</h3>
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
          <br />
          <h3>Country</h3>
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
                <span style="color: #007700">&quot;id&quot;</span>: <span style="background-color: #fff0f0">84</span>,
                <span style="color: #007700">&quot;code&quot;</span>: <span style="color: #0000DD; font-weight: bold">1</span>, 
                <span style="color: #007700">&quot;alpha2&quot;</span>: <span style="background-color: #fff0f0">&quot;DE&quot;</span>, 
                <span style="color: #007700">&quot;alpha3&quot;</span>: <span style="background-color: #fff0f0">&quot;DEU&quot;</span>
                <span style="color: #007700">&quot;nom_en_gb&quot;</span>: <span style="background-color: #fff0f0">&quot;Germany&quot;</span>
                <span style="color: #007700">&quot;nom_fr_fr&quot;</span>: <span style="background-color: #fff0f0">&quot;Allemagne&quot;</span>
              }</pre>
          </div>
        </div>
        <div style="width: 55%">
          <img
            src="../assets/illustrations/classDiaModel.svg"
            style="width: 100%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
