---
layout: default
permalink: /contact/
title: Contact
---

<div class="wrap {{ page.title }}">

  <h1>Contact</h1>

  <ul>
    <li>
      <h2>To Schedule:</h2>
      <p>Call us at: {{ site.phone }} to speak to our scheduling consultant.</p>
    </li>

    <li>
      <form action="/my-handling-form-page" method="post">
        <div>
          <label for="name">Name:</label>
          <input type="text" id="name" name="user_name" />
        </div>
        <div>
          <label for="mail">E-mail:</label>
          <input type="email" id="mail" name="user_mail" />
        </div>
        <div>
          <label for="msg">Message:</label>
          <textarea id="msg" name="user_message"></textarea>
        </div>
      </form>
    </li>
  </ul>

  <section class="location">
    <h3>We are located in Rowlett, TX and proudly serve the entire DFW Metroplex and surrounding areas.</h3>
    <img src="http://placehold.it/350x150" alt="" class="map">
    <ul>
      <li>Phone: {{ site.phone }}</li>
      <li>Email: {{ site.email }}</li>
    </ul>
  </section>

</div>
