<template>
  <div>
    <div class="content">
      <h1>Brice Courtot</h1>
      <img
        class="logo"
        src="logo.png"
        width="300"
        height="300"
        alt="brice courtot"
      />
      <h3>Junior Web Developer @ Noumea, New Caledonia</h3>
      <ul>
        <li>
          <a href="https://www.linkedin.com/in/bricecourtot/">
            <img
              src="linkedin-logo.svg"
              width="64"
              height="64"
              alt="linkedin"
            />
          </a>
        </li>
        <li>
          <a href="https://www.instagram.com/draco_noumea/">
            <img
              src="instagram-logo.svg"
              width="64"
              height="64"
              alt="instagram"
          /></a>
        </li>
        <li>
          <a href="mailto:brice.courtot@gmail.com">
            <img src="mail-icon.svg" width="64" height="64" alt="mail"
          /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: "Brice Courtot - Web Developper @ Noumea",
    meta: [
      {
        key: "description",
        name: "description",
        content:
          "Bonjour, je suis un jeune développeur web basé à Nouméa, en Nouvelle Calédonie. Je suis en licence MIAW à l'université de Nouvelle Calédonie.",
      },
    ],
  },
};
</script>

<style>
html {
  background-color: black;
}

.content {
  text-align: center;
  margin-top: 20vh;
}

h1,
h3,
li,
i,
a {
  color: azure;
}

h1 {
  font-weight: 700;
}

ul {
  list-style-type: none;
  display: inline-flex;
}

li {
  margin-right: 25px;
}
</style>