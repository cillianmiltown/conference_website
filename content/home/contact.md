+++
# Contact widget.
widget = "contact"  # Do not modify this line!
active = true  # Activate this widget? true/false

title = "Contact"
subtitle = ""

# Order that this section will appear in.
weight = 130

# Automatically link email and phone?
autolink = true

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form = 0
+++

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xyylabzr"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
