---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h1>Contact Me!</h1>
<p>Want to get in touch? Submit your info below and I'll respond as soon as I'm able.</p>
<form accept-charset="UTF-8" action="https://getform.io/f/f1f79ea2-bc32-40c4-929d-606adab308d0" method="POST" enctype="multipart/form-data" target="_blank">
    <div class="form-group">
        <label for="inputEmail" required="required">Email address</label><br/>
        <input type="email" name="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Enter email">
    </div>
    <div class="form-group">
        <label for="inputName">Name</label><br/>
        <input type="text" name="name" class="form-control" id="inputName" placeholder="Enter your name" required="required">
    </div>
    <div>
        <label for="inputMessage">Message (500 word maximum)</label><br/>
        <textarea name="message" class="form-control" id="inputMessage" required="required" maxlength="500" rows="4" cols="50"></textarea>
    </div>
    <hr>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>