---
layout: page-fullwidth
meta_title: "Contact"
header:
    # title: ''
    image_fullwidth: contact-banner.jpg
permalink: "/contact/"
---
<div class="row t60">
    <div class="medium-6 columns b30">
    <h1>Contact us</h1>    
    {%include _contact.html%}
<h2>Leave us a message</h2>
<!-- <form action="https://getform.io/f/465b6217-42b1-4af3-9b17-64e8738c955d" method="POST"> -->
<form name="contact" method="POST" data-netlify="true">
    <input type="text" id="name" name="name" placeholder="Your name" required>
    <input type="email" id="email" name="email" placeholder="your@email.com" required>
    <textarea id="subject" name="subject" placeholder="Your message" style="height:170px" required></textarea>
    <button type="submit">Send</button>
</form>

    </div>

    <div class="medium-6 columns b30">
        <div style="width: 100%"><iframe width="100%" height="600" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=Ho%20Tim%20Building,%20CUHK+(HKIER)&amp;t=&amp;z=15&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe></div>
    </div><!-- /.medium-6.columns -->
</div>

