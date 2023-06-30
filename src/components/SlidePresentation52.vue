<template>
  <div class="slide">
    <div class="heading">RESTful - Laravel</div>
    <div class="content">
      <h3>Modifier le fichier des hôtes</h3>
      <p>
        <span style="font-size: 1.6rem">→</span>Windows -
        C:/Windows/System32/drivers/etc/hosts<br />
        <span style="font-size: 1.6rem">→</span>Mac - /etc/hosts <br />
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
<span style="color: #6600EE; font-weight: bold">127.0</span><span style="color: #333333">.</span><span style="color: #6600EE; font-weight: bold">0.1</span>	PROJECT_NAME<span style="color: #333333">.</span>test</pre>
      </div>

      <br />
      <h3>Modifier le fichier des hôtes virtuels</h3>
      <p>Windows - C:/xampp/apache/conf/extra/httpd-vhosts.conf</p>
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
        ><span style="color: #333333">&lt;</span>VirtualHost <span style="color: #333333">*</span>:<span style="color: #0000DD; font-weight: bold">80</span><span style="color: #333333">&gt;</span>
    DocumentRoot <span style="background-color: #fff0f0">&quot;C:/xampp/htdocs&quot;</span>
    ServerName localhost
<span style="color: #333333">&lt;/</span>VirtualHost<span style="color: #333333">&gt;</span>
<span style="color: #333333">&lt;</span>VirtualHost <span style="color: #333333">*</span>:<span style="color: #0000DD; font-weight: bold">80</span><span style="color: #333333">&gt;</span>
    DocumentRoot <span style="background-color: #fff0f0">&quot;C:/xampp/htdocs/PROJECT_NAME/public&quot;</span>
    ServerName PROJECT_NAME<span style="color: #333333">.</span>test
 <span style="color: #333333">&lt;/</span>VirtualHost<span style="color: #333333">&gt;</span></pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
