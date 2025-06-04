---
icon: fas fa-envelope
order: 6
---
<body>
<p>Feel free to message me for any inquiries, I'll be happy to reply within a business day.</p>
<form action="https://formspree.io/f/meokjnzo" method="POST">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email:</label><br>
  <input type="email" id="email" name="_replyto" required><br><br>

  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <button type="submit">Send</button>
</form>
</body>

<style>
  form {
    max-width: 550px;
  }
  input, textarea {
    width: 100%;
    padding: 10px;
    margin-top: 4px;
    margin-bottom: 12px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 1em;
  }
  button {
    padding: 10px 20px;
    background-color: #007acc;
    color: white;
    border: none;
    border-radius: 6px;
    font-size: 1em;
    cursor: pointer;
  }
</style>
