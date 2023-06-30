<template>
  <div class="slide">
    <div class="heading">Conception de services RESTful</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 48%">
          <h2>Consultation des personnes</h2>
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
            <span style="color: #007700">GET</span> /pseudos HTTP/1.1</pre>
          </div>
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
            <pre style="margin: 0; line-height: 125%">[
            {
                <span style="background-color: #fff0f0">&quot;id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">24</span>,
                <span style="background-color: #fff0f0">&quot;pseudo&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;jules&quot;</span>,
                <span style="background-color: #fff0f0">&quot;email&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;dd@gmail.com&quot;</span>,
                <span style="background-color: #fff0f0">&quot;country_id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">151</span>,
            },
            {
                <span style="background-color: #fff0f0">&quot;id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">26</span>,
                <span style="background-color: #fff0f0">&quot;pseudo&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Kilian&quot;</span>,
                <span style="background-color: #fff0f0">&quot;email&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;champ@work.fr&quot;</span>,
                <span style="background-color: #fff0f0">&quot;country_id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">84</span>,
            }
        ]</pre>
          </div>
        </div>
        <div style="width: 48%">
          <h2>Consultation des bankaccounts</h2>
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
            <span style="color: #007700">GET</span> /countries HTTP/1.1</pre>
          </div>
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
          [
              {
                  <span style="background-color: #fff0f0">&quot;id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">240</span>,
                  <span style="background-color: #fff0f0">&quot;code&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">891</span>,
                  <span style="background-color: #fff0f0">&quot;alpha2&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;CS&quot;</span>,
                  <span style="background-color: #fff0f0">&quot;alpha3&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;SCG&quot;</span>,
                  <span style="background-color: #fff0f0">&quot;nom_en_gb&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Serbia and Montenegro&quot;</span>,
                  <span style="background-color: #fff0f0">&quot;nom_fr_fr&quot;</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Serbie-et-Monténégro&quot;</span>
              },
              {
                  <span style="background-color: #fff0f0">&quot;id&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">241</span>,
                  <span style="background-color: #fff0f0">&quot;code&quot;</span><span style="color: #333333">:</span> <span style="color: #0000DD; font-weight: bold">894</span>,
                  ...
              }
          ]</pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
