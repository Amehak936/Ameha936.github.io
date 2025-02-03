# Site settings
title: AK
email: AK@gmail.com
url: https://S-McPhail.github.io/cyber-portfolio
description: "Portfolio of cybersecurity work samples for a junior-level cyber security professional."
keywords: "cybersecurity, cyber, security, portfolio, tech"
skills: "Cybersecurity - Analyst - Ethical Hacker"
meta_author: AK

# Google webmaster tools
google_verify:

# https://ssl.bing.com/webmaster/configure/verify/ownership Option 2 content= goes here
bing_verify:

# Contact form:
# - static : pass through formspree.io to validate email sending
# - disqus : replace contact form by disqus thread
# - comment the line below if you want to stick with the default PHP contact form
contact: static

# If you use disqus you need disqus shortname
# https://help.disqus.com/customer/portal/articles/466208
disqus_shortname: 

# Color settings (hex-codes without the leading hash-tag)
color:
  primary: f7b801 #80B3FF
  primary-rgb: "247,184,1" #"128,179,255"
  secondary: 7678ed #FD6E8A
  secondary-dark: 3d348b #A2122F

# Footer settings
footer:
  copyright: Shaun McPhail
  location: Location
  social: Around the Web
  credits: Credits

# Social networks usernames (many more available: google-plus, flickr, dribbble, pinterest, instagram, tumblr, linkedin, etc.)
social:
  - title: linkedin
    url: https://www.linkedin.com/in/shaunmcphail56
  - title: github
    url: https://github.com/S-McPhail

# Email Address (make sure to include "mailto:" before your email!)
email:
  email-url: mailto:shaunmcphail56@gmail.com

# Postal address (add as many lines as necessary)
location:
  - line: Raleigh, North Carolina
# Credits content
credits: 'Freelancer is a free to use, open source Bootstrap theme created by <a href="http://startbootstrap.com">Start Bootstrap</a>.
Cyber icons created by <a href="https://www.flaticon.com/free-icons/cyber-attack" title="cyber attack icons">Freepik - Flaticon</a>.'

# Build settings
markdown: kramdown
permalink: pretty

#for posts
defaults:
  - scope:
      path: ""
      type: "posts"
    values:
      permalink: ""
