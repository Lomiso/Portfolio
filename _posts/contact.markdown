---
layout: page
title: Contact
permalink: /contact/
---


[github](https://github.com/Lomiso)
<br>
email leandre.le-grives@epitech.eu


<form action="/testform" method="post">
  <ul>
    <li>
      <label for="name">Nom&nbsp;:</label>
      <input type="text" id="name" name="user_name" />
    </li>
    <li>
      <label for="mail">E-mail&nbsp;:</label>
      <input type="email" id="mail" name="user_mail" />
    </li>
    <li>
      <label for="msg">Message&nbsp;:</label>
      <textarea id="msg" name="user_message"></textarea>
    </li>
    <div class="button">
  <button type="reset">Envoyer le message</button>
</div>
  </ul>
</form>

<style>form {
  margin: 0 auto;
  width: 400px;
  padding: 1em;
  border: 1px solid #ccc;
  border-radius: 1em;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

form li + li {
  margin-top: 1em;
}

label {
  display: inline-block;
  width: 90px;
  text-align: right;
}

input,
textarea {
  font: 1em sans-serif;
  width: 300px;
  box-sizing: border-box;
  border: 1px solid #999;
}

input:focus,
textarea:focus {
  border-color: #000;
}

textarea {
  vertical-align: top;
  height: 5em;
  resize: vertical;
}

.button {
  padding-left: 90px;
  margin-top: 1em
}

button {
  margin-left: 0.5em;
}
</style >
<br>

[Accueil](/index/)<br>
[Projets](/project/)<br>
[A propos](/about/) <br>