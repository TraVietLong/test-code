<template>
  <div>
    <div class="header-web">
      <div class="menu">
        <div class="logo">
          <img class="custom-image" src="@/assets/image/logo.png" width="100%" height="100%" />
        </div>
        <div class="text-menu-desktop">
          <a class="item-text" href="#">
            Features
          </a>
          <a class="item-text" href="#">
            About
          </a>
          <a class="item-text" href="#">
            Pricing
          </a>
          <a class="item-text" href="#">
            Reviews
          </a>
          <a class="item-text" href="#">
            Contact
          </a>
        </div>
        <div class="text-menu-mobile">
          <div class="icon-menu">
            <b-icon icon="menu-down" v-on:click="open_Sidebar()"></b-icon>
          </div>
          <div class="menu-mobile" id="side-bar-mobile">
            <div class="icon-tab-menu" v-on:click="close_Sidebar()">
              <b-icon icon="arrow-left-square"></b-icon>
            </div>
            <div class="item-text">
              <a href="#">
                Features
              </a>
            </div>
            <div class="item-text">
              <a href="#">
                About
              </a>
            </div>
            <div class="item-text">
              <a href="#">
                Pricing
              </a>
            </div>
            <div class="item-text">
              <a href="#">
                Reviews
              </a>
            </div>
            <div class="item-text">
              <a href="#">
                Contact
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="body-web">
      <div class="banner">
        <b-row class="item-banner mx-0">
          <b-col lg="6" sm="12">
            <div>
              <img class="logo-baner" src="@/assets/image/logo.png" width="100%" height="100%" />
            </div>
            <div class="text-banner">
              <div class="text-item1 mb-4">
                MODER AXURE TEMPLATE FOR BEAUTIFUL PROTOTYPES
              </div>
              <div class="custom-border"></div>
              <div class=" text-item2 mt-4 mb-2">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra justo commodo.
              </div>
              <div class="my-4">
                <b-button class="button-banner" variant="outline-light">Download</b-button>
              </div>
            </div>
          </b-col>
          <b-col lg="6" sm="12" class="form-banner px-0">
            <div>
              <div class="custom-form">
                <div class="text-item" style="background-color: #f5f5f5;">
                  <span>Try Your</span>
                  <span class="mx-1" style="color: orange">FREE</span>
                  <span>Trial Today</span>
                </div>
                <div class="input-item" style="background-color: white;">
                  <div class="py-3">
                    <b-form-input required hide-details placeholder="Name"></b-form-input>
                  </div>
                  <div class="py-3">
                    <b-form-input required hide-details placeholder="Email"></b-form-input>
                  </div>
                  <div class="py-3">
                    <b-form-input required hide-details placeholder="Password"></b-form-input>
                  </div>
                </div>
                <div class="button-item text-center">
                  <span>Get Started</span>
                </div>
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="tab">
        <b-row>
          <b-col lg="2" sm="12">
            <div class="custom-tab">
              <div class="item-tab1 active">
                TAB 1
              </div>
              <div class="item-tab2">
                TAB 2
              </div>
              <div class="item-tab3">
                TAB 3
              </div>
            </div>
          </b-col>
          <b-col lg="5" sm="12" class="px-5">
            <div class="custom-text1 my-3">
              Tabs with soft transitioning effect.
            </div>
            <div class="custom-text2 my-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
              dolor sit amet lacus accusmsan et viverra justo commodo. Proin sodales pulvinar tempor. Cum sociis natoque
              penatibus et dis parturient montes.
            </div>
            <div class="custom-text2 my-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet.
            </div>
            <div>
              <b-button class="button-download" variant="outline-light">Download</b-button>
            </div>
          </b-col>
          <b-col lg="5" sm="12" class="fix-image">
            <img class="" src="@/assets/image/u3.png" width="100%" height="100%" />
          </b-col>
        </b-row>
      </div>
      <div class="layout-list-section">
        <b-row>
          <b-col lg="6" sm="12" class="fix-image-section">
            <img class="" src="@/assets/image/u4.png" width="80%" height="100%" />
          </b-col>
          <b-col lg="6" sm="12" style="display: flex;align-items: center;">
            <div class="form-section">
              <div class="title-section my-3">
                Sub list section
              </div>
              <div class="custom-border-section">
              </div>
              <div class="text-section my-4">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra justo commodo.
              </div>
              <div class="flex-section my-4">
                <div class="pr-3">
                  <img class="icon-section" src="@/assets/image/icon upload.png" width="100%" height="100%" />
                </div>
                <div class="item-section">
                  <span class="title-item-section">Title</span>
                  <span class="text-item-section">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod
                    bibendum laoreet. </span>
                </div>
              </div>
              <div class="flex-section my-4">
                <div class="pr-3">
                  <img class="icon-section" src="@/assets/image/icon download.png" width="100%" height="100%" />
                </div>
                <div class="item-section">
                  <span class="title-item-section">Title</span>
                  <span class="text-item-section">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod
                    bibendum laoreet. Proin gravida
                    dolor sit amet lacus accusmsan et viverra justo commodo.</span>
                </div>
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="layout-picture-section">
        <b-row>
          <b-col lg="6" sm="12" style="display: flex;align-items: center;">
            <div class="form-picture-section">
              <div class="title-section my-3">
                Standard Picture Section
              </div>
              <div class="custom-border-section">
              </div>
              <div class="text-section my-4">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra justo commodo. Proin sodales pulvinar tempor. Cum sociis natoque
                penatibus et dis parturient montes.
              </div>
              <div class="text-section my-4">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet.
              </div>
            </div>
          </b-col>
          <b-col lg="6" sm="12" class="image-picture-section">
            <img class="" src="@/assets/image/u5.png" width="80%" height="100%" />
          </b-col>
        </b-row>
      </div>
      <div class="layout-awesome">
        <div class="form-awesome my-3">
          <div class="title-awesome text-center">
            WHY THIS IS AWESOME
          </div>
        </div>
        <div class="form-awesome my-3">
          <div class="custom-dash"></div>
        </div>
        <div class="form-awesome my-3">
          <div class="text-awesome text-center">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          </div>
        </div>
        <b-row>
          <b-col lg="4" sm="12">
            <div class="item-awesome">
              <img class="icon-item" src="@/assets/image/icon idea.png" width="100%" height="100%" />
              <div class="title-item my-3">
                Thoughtful Design
              </div>
              <div class="text-item my-3">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra
              </div>
            </div>
          </b-col>
          <b-col lg="4" sm="12">
            <div class="item-awesome">
              <img class="icon-item" src="@/assets/image/icon keyboard.png" width="100%" height="100%" />
              <div class="title-item my-3">
                Well Crafted
              </div>
              <div class="text-item my-3">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra
              </div>
            </div>
          </b-col>
          <b-col lg="4" sm="12">
            <div class="item-awesome">
              <img class="icon-item" src="@/assets/image/icon custom.png" width="100%" height="100%" />
              <div class="title-item my-3">
                Easy to Customize
              </div>
              <div class="text-item my-3">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean euismod bibendum laoreet. Proin gravida
                dolor sit amet lacus accusmsan et viverra
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="axure-design">
        <div class="title text-center my-3">
          STYLISH AXURE DESIGN
        </div>
        <div class="custom-dash my-3"></div>
        <div class="text text-center my-5">
          Use the sections you need, remove the ones you don't. Create gorgeous prototypes faster than ever!
        </div>
        <b-button class="button-download" variant="outline-light">Download</b-button>
      </div>
      <div class="contact-us">
        <div class="title-contact text-center">
          CONTACT US
        </div>
        <div class="custom-dash my-3"></div>
        <div class="text-contact text-center my-5">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        </div>
        <b-row class="my-5">
          <b-col lg="6" sm="12">
            <div class="py-3 form-input ">
              <b-form-input required hide-details placeholder="Name"></b-form-input>
            </div>
            <div class="py-3 form-input ">
              <b-form-input required hide-details placeholder="Email"></b-form-input>
            </div>
            <div class="py-3 form-input ">
              <b-form-input required hide-details placeholder="Subject"></b-form-input>
            </div>
          </b-col>
          <b-col lg="6" sm="12">
            <div class="py-3 form-input">
              <b-form-textarea rows="7" required hide-details placeholder="Message" no-resize></b-form-textarea>
            </div>
          </b-col>
        </b-row>
        <b-button class="button-send" variant="outline-light">Send Message</b-button>
      </div>
    </div>
    <div class="footer">
      <img class="icon-footer" src="@/assets/image/icon_footer.png" width="100%" height="100%" />
      <div class="text-footer text-center pb-2">
        © 2021 Axure Themes
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HomePage',
  methods: {
    open_Sidebar(){
      document.getElementById("side-bar-mobile").style.display = "block";
    },
    close_Sidebar(){
      document.getElementById("side-bar-mobile").style.display = "none";
    }
  }
}
</script>
<style>
@import '~/assets/scss/style.scss';
</style>
