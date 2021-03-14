---
layout: page
title: Contact
permalink: /contact/
weight: 4
---

# **Contact Me**

If you want to get in touch, fill out the form below.

<!-- <div class="form-group"></div>
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xqkgrgdl" method="post">
   
   <fieldset id="fs-frm-inputs">
     <label for="full-name">Full Name</label>
     <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
     <label for="email-address">Email Address</label>
     <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
     <label for="message">Message</label>
     <textarea rows="5" name="message" id="message" placeholder="Aenean lacinia bibendum nulla sed consectetur. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla nullam quis risus." required=""></textarea>
     <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
   </fieldset>
   <input type="submit" value="Submit">
   
 </form>
</div> -->

<form id="simple-contact-form" action="https://formspree.io/f/xqkgrgdl" method="POST">
     <!-- <div class="form-row"> -->
       <div class="form-group">
       <label for="full-name">Full Name</label>
         <input class="form-control" id="full-name" name="name" placeholder="John Doe" type="text" required>
       </div>
     <!-- </div> -->
     <!-- <div class="form-row"> -->
       <div class="form-group">
          <label for="email-address">Email Address</label>
         <input class="form-control" id="email-address" name="_replyto" placeholder="email@address.com" type="email" required>
       </div>
      <!-- </div> -->
      <div class="form-group">
        <label for="message">Message</label>
          <textarea class="form-control" id="message" name="message" placeholder="Message" rows="5"></textarea>
          <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission" required>
        </div>
     <button class="btn btn-primary" type="submit">Send</button>
   </form>
