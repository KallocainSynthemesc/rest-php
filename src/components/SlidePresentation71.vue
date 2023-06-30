<template>
  <div class="slide">
    <div class="heading">RESTful - Rest client</div>
    <div class="content">
      <p>
        Pour inclure le filtrage, le tri et la pagination, nous pouvons faire le
        code suivant dans la fonction index.
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
        >public function <span style="color: #007020">index</span>()
    {
        <span style="color: #996633">$sortColumn</span> <span style="color: #333333">=</span> request()<span style="color: #333333">-&gt;</span>input(<span style="background-color: #fff0f0">&#39;sort&#39;</span>, <span style="background-color: #fff0f0">&#39;id&#39;</span>);
        <span style="color: #996633">$query</span> <span style="color: #333333">=</span> <span style="color: #0e84b5; font-weight: bold">Country::</span>orderBy(<span style="color: #996633">$sortColumn</span>);
        <span style="color: #996633">$query</span><span style="color: #333333">-&gt;</span>when(request()<span style="color: #333333">-&gt;</span>filled(<span style="background-color: #fff0f0">&#39;filter&#39;</span>), function (<span style="color: #996633">$query</span>) {
            [<span style="color: #996633">$criteria</span>, <span style="color: #996633">$value</span>] <span style="color: #333333">=</span> explode(<span style="background-color: #fff0f0">&#39;:&#39;</span>, request(<span style="background-color: #fff0f0">&#39;filter&#39;</span>));
            <span style="color: #008800; font-weight: bold">return</span> <span style="color: #996633">$query</span><span style="color: #333333">-&gt;</span>where(<span style="color: #996633">$criteria</span>, <span style="color: #996633">$value</span>);
        });
        <span style="color: #008800; font-weight: bold">return</span> <span style="color: #996633">$query</span><span style="color: #333333">-&gt;</span>paginate(<span style="color: #0000DD; font-weight: bold">30</span>);
    }</pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
