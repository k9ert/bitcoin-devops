+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1110
#background = "light"
form_name = "defaultContact"

title = "Contact Form"
subtitle  = "*Get in contact and send me a message*"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/xyyjbnkv" #default: formspree.io
email = "kneunert@gmail.com"
button = "Send Button" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Your Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Your Message *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
