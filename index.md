---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Post test

<form method="POST" action="https://api.staticman.net/v3/entry/github/DarkBaptism/test/master/comments">
  <input name="options[redirect]" type="hidden" value="https://darkbaptism.github.io/test">
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="{{ page.slug }}">
  <label><input name="fields[name]" type="text">Name</label>
  <label><input name="fields[email]" type="email">E-mail</label>
  <label><textarea name="fields[message]"></textarea>Message</label>
  
  <button type="submit">Go!</button>
</form>