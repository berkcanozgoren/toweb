<template>
  <div class="edrea_tm_section" id="contact">
    <div class="section_inner">
      <div class="edrea_tm_contact">
        <div class="edrea_tm_main_title">
          <h3>Get in <span class="coloring">Touch</span></h3>
        </div>
        <div class="wrapper">
          <div class="left">
            <ul>
              <li>
                <div class="list_inner">
                  <i class="icon-location"></i>
                  <span
                    ><a href="#" class="href_location"
                      >Avon str. 22, NYC, USA</a
                    ></span
                  >
                </div>
              </li>
              <li>
                <div class="list_inner">
                  <i class="icon-phone"></i>
                  <span><a href="#">+77 022 155 02 02</a></span>
                </div>
              </li>
              <li>
                <div class="list_inner">
                  <i class="icon-mail-1"></i>
                  <span
                    ><a href="mailto:example@gmail.com"
                      >example@gmail.com</a
                    ></span
                  >
                </div>
              </li>
              <li>
                <div class="list_inner">
                  <i class="icon-facebook-rect"></i>
                  <span
                    ><a href="https://www.facebook.com">@facebookNick</a></span
                  >
                </div>
              </li>
            </ul>
          </div>
          <div class="right">
            <div class="fields">
              <form
                action="/"
                method="post"
                class="contact_form"
                id="contact_form"
              >
                <div
                  class="returnmessage"
                  data-success="Your message has been received, We will contact you soon."
                ></div>
                <div class="empty_notice">
                  <span>Please Fill Required Fields</span>
                </div>
                <div class="first">
                  <ul>
                    <li>
                      <div class="list_inner">
                        <input
                          id="name"
                          type="text"
                          placeholder="Name"
                          autocomplete="off"
                        />
                      </div>
                    </li>
                    <li>
                      <div class="list_inner">
                        <input
                          id="email"
                          type="text"
                          placeholder="Email"
                          autocomplete="off"
                        />
                      </div>
                    </li>
                  </ul>
                </div>
                <div class="last">
                  <textarea id="message" placeholder="Message"></textarea>
                </div>
                <div class="edrea_tm_button">
                  <a id="send_message" href="#">Send Message</a>
                </div>

                <!-- If you want change mail address to yours, just open "modal" folder >> contact.php and go to line 4 and change detail to yours.  -->
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: `ContactComponent`,
};
</script>
