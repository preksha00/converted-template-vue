<template>
  <header class="site-header header-style-1">
    <div class="header-wrapper">
      <div class="pre-header">
        <div class="container-fluid">
          <div class="d-md-flex justify-content-between align-items-center">
            <div class="pbmit-pre-header-left">
              <ul class="pbmit-contact-info">
                <li>
                  <i class="pbmit-base-icon-letter"></i>
                  <a href="#">Email Address :<span> info@emphires.com</span></a>
                </li>
                <li>
                  <i class="pbmit-base-icon-placeholder-1"></i>
                  <a href="#">
                    Office Address :<span> 12 Tottina, NY, USA</span></a
                  >
                </li>
              </ul>
            </div>
            <div class="pbmit-pre-header-right d-flex">
              <ul class="pbmit-social-links">
                <li class="pbmit-social-li pbmit-social-facebook">
                  <a href="#" target="_blank"
                    ><span>
                      <i class="pbmit-base-icon-facebook-squared"></i
                    ></span>
                  </a>
                </li>
                <li class="pbmit-social-li pbmit-social-twitter">
                  <a href="#" target="_blank"
                    ><span> <i class="pbmit-base-icon-twitter"></i></span>
                  </a>
                </li>
                <li class="pbmit-social-li pbmit-social-instagram">
                  <a href="#" target="_blank"
                    ><span> <i class="pbmit-base-icon-instagram"></i></span>
                  </a>
                </li>
                <li class="pbmit-social-li pbmit-social-youtube">
                  <a href="#" target="_blank"
                    ><span> <i class="pbmit-base-icon-youtube-play"></i></span>
                  </a>
                </li>
              </ul>
              <div class="pbmit-header-search-btn">
                <a href="#"><i class="pbmit-base-icon-search"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="site-header-menu">
        <div class="container-fluid">
          <div class="row g-0">
            <div class="col-md-12">
              <div class="d-flex align-items-center">
                <div class="site-branding">
                  <router-link to="/">
                    <img
                      class="logo-img"
                      alt="Emphires"
                      src="../../assets/images/header/logo-white.svg"
                    />
                    <img
                      class="sticky-logo"
                      alt="Emphires"
                      src="../../assets/images/header/logo-black-3.svg"
                    />
                  </router-link>
                </div>
                <div class="site-navigation">
                  <nav class="main-menu navbar-expand-xl navbar-light">
                    <div class="navbar-header">
                      <!-- Toggle Button -->
                      <button
                        class="navbar-toggler"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent"
                        aria-controls="navbarSupportedContent"
                        aria-expanded="false"
                        aria-label="Toggle navigation"
                      >
                        <i class="pbmit-base-icon-menu-1"></i>
                      </button>
                    </div>
                    <div
                      class="collapse navbar-collapse clearfix"
                      id="navbarSupportedContent"
                    >
                      <ul class="navigation clearfix">
                        <li class="dropdown active">
                          <router-link to="/">Home</router-link>
                        </li>
                        <li>
                          <router-link to="/about">About Us</router-link>
                        </li>
                        <li class="dropdown">
                          <a href="#">Pages</a>
                          <ul>
                            <li><a href="about-us-1.html">About Us 1</a></li>
                            <li>
                              <a href="our-advisers.html">Our Advisers</a>
                            </li>
                            <li>
                              <a href="advisers-details.html"
                                >Advisers Details</a
                              >
                            </li>
                            <li><a href="our-history.html">Our History</a></li>
                            <li><a href="faq.html">Faq</a></li>
                          </ul>
                        </li>

                        <li class="dropdown">
                          <a href="#">Services</a>
                          <ul>
                            <li>
                              <a href="services-details.html"
                                >Services Details</a
                              >
                            </li>
                          </ul>
                        </li>

                        <li class="dropdown">
                          <a href="#">Projects</a>
                          <ul>
                            <li>
                              <a href="project-style1.html">Project Style 1</a>
                            </li>
                            <li>
                              <a href="project-style2.html">Project Style 2</a>
                            </li>
                            <li>
                              <a href="project-details.html">Project Details</a>
                            </li>
                          </ul>
                        </li>

                        <li class="dropdown">
                          <a href="#">Blog</a>
                          <ul>
                            <li>
                              <a href="blog-classic.html">Blog Classic</a>
                            </li>
                            <li><a href="blog-grid.html">Blog Grid</a></li>
                            <li>
                              <a href="blog-details.html">Blog Details</a>
                            </li>
                          </ul>
                        </li>

                        <li><a href="contact-us.html">Contact Us</a></li>
                      </ul>
                    </div>
                  </nav>
                </div>
                <div class="pbmit-right-box ms-auto">
                  <div class="pbmit-header-button">
                    <a href="#">
                      <span class="pbmit-header-button-text-1"
                        >Have any Questions?</span
                      >
                      <span class="pbmit-header-button-text-2"
                        >+0 123 456 789</span
                      >
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- START Slider Demo 1 REVOLUTION SLIDER 6.5.25 -->
    <p class="rs-p-wp-fix"></p>
    <rs-module-wrap
      id="rev_slider_1_wrapper"
      data-alias="slider-demo-1"
      data-source="gallery"
      style="
        visibility: hidden;
        background: transparent;
        padding: 0;
        margin: 0px auto;
        margin-top: 0;
        margin-bottom: 0;
      "
    >
      <rs-module id="rev_slider_1" style="" data-version="6.5.25">
        <rs-slides>
          <rs-slide
            style="position: absolute"
            data-key="rs-3"
            data-title="Slide"
            data-thumb="../../assets/revolution/images/n-slider-01-100x50.jpg"
            data-anim="ms:600;"
            data-in="o:0;"
            data-out="a:false;"
          >
            <img
              src="../../assets/revolution/images/dummy.png"
              alt=""
              title="n-slider-01.jpg"
              width="1920"
              height="950"
              class="rev-slidebg tp-rs-img rs-lazyload"
              data-lazyload="../../assets/revolution/images/n-slider-01.jpg"
              data-bg="p:center top;"
              data-no-retina
            />
            <rs-layer
              id="slider-2-slide-3-layer-0"
              data-type="text"
              data-rsp_ch="on"
              data-xy="xo:30px;yo:408px,408px,303px,190px;"
              data-text="s:70,70,50,28;l:80,80,55,32;fw:800;"
              data-frame_0="x:-50,-50,-31,-19;"
              data-frame_1="st:1190;sp:1000;sR:1190;"
              data-frame_999="o:0;st:w;sR:6810;"
              style="z-index: 5; font-family: 'Nunito'"
              >Human <span class="pbmit-skincolor">Resource</span><br />
              Solution Partner </rs-layer
            ><rs-layer
              id="slider-2-slide-3-layer-3"
              class="rev-btn"
              data-type="button"
              data-rsp_ch="on"
              data-xy="xo:30px;yo:605px,605px,430px,270px;"
              data-text="w:normal;s:13,13,12,12;l:24,24,55,40;ls:1px;fw:800;"
              data-dim="minh:0px,0px,none,none;"
              data-padding="t:17,17,0,0;r:50,50,35,20;b:17,17,0,0;l:50,50,35,20;"
              data-border="bos:solid;boc:#ffffff;bow:2px,2px,2px,2px;bor:6px,6px,6px,6px;"
              data-frame_0="x:-50,-50,-31,-19;"
              data-frame_1="st:2020;sp:1000;sR:2020;"
              data-frame_999="o:0;st:w;sR:5980;"
              data-frame_hover="c:#fff;bgc:#0aadeb;boc:#0aadeb;bor:6px,6px,6px,6px;bos:solid;bow:2px,2px,2px,2px;"
              style="
                z-index: 8;
                background-color: rgba(255, 255, 255, 0);
                font-family: 'Nunito';
                text-transform: uppercase;
              "
              >Contact Us </rs-layer
            ><rs-layer
              id="slider-2-slide-3-layer-8"
              data-type="text"
              data-bsh="c:rgba(0,0,0,0.5);"
              data-rsp_ch="on"
              data-xy="xo:30px,30px,30px,18px;yo:375px,375px,266px,60px;"
              data-text="w:normal;s:13,13,15,11;l:24,24,30,24;ls:3px,3px,2px,1px;fw:700;"
              data-vbility="t,t,t,f"
              data-border="bor:6px,6px,6px,6px;"
              data-frame_0="y:-50,-50,-31,-19;"
              data-frame_1="st:630;sp:1000;sR:630;"
              data-frame_999="o:0;st:w;sR:7370;"
              style="
                z-index: 9;
                background-color: rgba(255, 255, 255, 0);
                font-family: 'Muli';
                box-shadow: 0px 9px 35px 0px rgba(26, 47, 106, 0.07);
              "
              >HR IS ALL ABOUT PEOPLE </rs-layer
            ><rs-layer
              id="slider-2-slide-3-layer-12"
              data-type="text"
              data-rsp_ch="on"
              data-xy="xo:50px,50px,31px,19px;yo:50px,50px,31px,19px;"
              data-text="w:normal;s:20,20,12,7;l:25,25,15,9;"
              data-frame_999="o:0;st:w;sR:8700;"
              style="z-index: 5; font-family: 'Roboto'"
            >
            </rs-layer
            ><a
              id="slider-2-slide-3-layer-13"
              class="rs-layer pbmit-lightbox-video"
              href="https://www.youtube.com/watch?v=WvyK40w1EPY"
              target="_self"
              data-type="image"
              data-rsp_ch="on"
              data-xy="xo:252px,252px,199px,150px;yo:599px,599px,430px,136px;"
              data-text="w:normal;s:20,20,12,7;l:0,0,15,9;"
              data-dim="w:90px,90px,80px,49px;h:90px,90px,80px,49px;"
              data-vbility="t,t,t,f"
              data-frame_0="x:50,50,31,19;"
              data-frame_1="st:2200;sp:1000;sR:2200;"
              data-frame_999="o:0;st:w;sR:5800;"
              style="z-index: 10"
              ><img
                src="../../assets/revolution/images/dummy.png"
                alt="n-play-button"
                class="tp-rs-img rs-lazyload"
                width="90"
                height="90"
                data-lazyload="../../assets/revolution/images/n-play-button.png"
                data-no-retina
              /> </a
            ><!--

                        --><rs-layer
              id="slider-2-slide-3-layer-14"
              data-type="text"
              data-xy="xo:341px,341px,260px,24px;yo:624px,624px,340px,157px;"
              data-text="w:normal;s:15,15,14,12;l:24,24,14,15;ls:1px,1px,0px,0px;fw:600;"
              data-vbility="t,t,f,f"
              data-rsp_bd="off"
              data-frame_0="x:50,50,31,19;"
              data-frame_1="st:2200;sp:1000;sR:2200;"
              data-frame_999="o:0;st:w;sR:5800;"
              style="z-index: 11; font-family: 'Poppins'"
              >How We Work </rs-layer
            ><!--

                        --><rs-layer
              id="slider-2-slide-3-layer-17"
              data-type="image"
              data-rsp_ch="on"
              data-xy="x:r;xo:80px,80px,50px,30px;yo:318px,318px,200px,123px;"
              data-text="w:normal;s:20,20,12,7;l:0,0,15,9;"
              data-dim="w:207px,207px,130px,80px;h:116px,116px,72px,44px;"
              data-vbility="t,t,f,f"
              data-frame_999="o:0;st:w;"
              data-loop_0="x:10px;y:10px;"
              data-loop_999="z:10px;sp:3000;yym:t;"
              style="z-index: 12"
              ><img
                src="../../assets/revolution/images/dummy.png"
                alt=""
                class="tp-rs-img rs-lazyload"
                width="207"
                height="116"
                data-lazyload="../../assets/revolution/images/n-slider-img.png"
                data-no-retina
              /> </rs-layer
            ><!--
            -->
          </rs-slide>
          <rs-slide
            style="position: absolute"
            data-key="rs-4"
            data-title="Slide"
            data-thumb="../../assets/revolution/images/n-slider-02-100x50.jpg"
            data-anim="ms:600;"
            data-in="o:0;"
            data-out="a:false;"
          >
            <img
              src="../../assets/revolution/images/dummy.png"
              alt=""
              title="n-slider-02.jpg"
              width="1920"
              height="950"
              class="rev-slidebg tp-rs-img rs-lazyload"
              data-lazyload="../../assets/revolution/images/n-slider-02.jpg"
              data-bg="p:center top;"
              data-no-retina
            />
            <!--
                        --><rs-layer
              id="slider-2-slide-4-layer-0"
              data-type="text"
              data-rsp_ch="on"
              data-xy="xo:30px;yo:408px,408px,303px,190px;"
              data-text="s:70,70,50,28;l:80,80,55,32;fw:800;"
              data-frame_0="x:-50,-50,-31,-19;"
              data-frame_1="st:1190;sp:1000;sR:1190;"
              data-frame_999="o:0;st:w;sR:6810;"
              style="z-index: 5; font-family: 'Nunito'"
              >Human <span class="pbmit-skincolor">Resource</span><br />
              Solution Partner </rs-layer
            ><!--

                        --><rs-layer
              id="slider-2-slide-4-layer-3"
              class="rev-btn"
              data-type="button"
              data-rsp_ch="on"
              data-xy="xo:30px;yo:605px,605px,430px,270px;"
              data-text="w:normal;s:13,13,12,12;l:24,24,55,40;ls:1px;fw:800;"
              data-dim="minh:0px,0px,none,none;"
              data-padding="t:17,17,0,0;r:50,50,35,20;b:17,17,0,0;l:50,50,35,20;"
              data-border="bos:solid;boc:#ffffff;bow:2px,2px,2px,2px;bor:6px,6px,6px,6px;"
              data-frame_0="x:-50,-50,-31,-19;"
              data-frame_1="st:2020;sp:1000;sR:2020;"
              data-frame_999="o:0;st:w;sR:5980;"
              data-frame_hover="c:#fff;bgc:#0aadeb;boc:#0aadeb;bor:6px,6px,6px,6px;bos:solid;bow:2px,2px,2px,2px;"
              style="
                z-index: 8;
                background-color: rgba(255, 255, 255, 0);
                font-family: 'Nunito';
                text-transform: uppercase;
              "
              >Contact Us </rs-layer
            ><!--

                        --><rs-layer
              id="slider-2-slide-4-layer-8"
              data-type="text"
              data-bsh="c:rgba(0,0,0,0.5);"
              data-rsp_ch="on"
              data-xy="xo:30px,30px,30px,18px;yo:375px,375px,266px,60px;"
              data-text="w:normal;s:13,13,15,11;l:24,24,30,24;ls:3px,3px,2px,1px;fw:700;"
              data-vbility="t,t,t,f"
              data-border="bor:6px,6px,6px,6px;"
              data-frame_0="y:-50,-50,-31,-19;"
              data-frame_1="st:630;sp:1000;sR:630;"
              data-frame_999="o:0;st:w;sR:7370;"
              style="
                z-index: 9;
                background-color: rgba(255, 255, 255, 0);
                font-family: 'Muli';
                box-shadow: 0px 9px 35px 0px rgba(26, 47, 106, 0.07);
              "
              >HR IS ALL ABOUT PEOPLE </rs-layer
            ><!--

                        --><rs-layer
              id="slider-2-slide-4-layer-12"
              data-type="text"
              data-rsp_ch="on"
              data-xy="xo:50px,50px,31px,19px;yo:50px,50px,31px,19px;"
              data-text="w:normal;s:20,20,12,7;l:25,25,15,9;"
              data-frame_999="o:0;st:w;sR:8700;"
              style="z-index: 5; font-family: 'Roboto'"
            >
            </rs-layer
            ><!--

                        --><a
              id="slider-2-slide-4-layer-13"
              class="rs-layer pbmit-lightbox-video"
              href="https://www.youtube.com/watch?v=WvyK40w1EPY"
              target="_self"
              data-type="image"
              data-rsp_ch="on"
              data-xy="xo:252px,252px,199px,150px;yo:599px,599px,430px,136px;"
              data-text="w:normal;s:20,20,12,7;l:0,0,15,9;"
              data-dim="w:90px,90px,80px,49px;h:90px,90px,80px,49px;"
              data-vbility="t,t,t,f"
              data-frame_0="x:50,50,31,19;"
              data-frame_1="st:2200;sp:1000;sR:2200;"
              data-frame_999="o:0;st:w;sR:5800;"
              style="z-index: 10"
              ><img
                src="../../assets/revolution/images/dummy.png"
                alt="n-play-button"
                class="tp-rs-img rs-lazyload"
                width="90"
                height="90"
                data-lazyload="../../assets/revolution/images/n-play-button.png"
                data-no-retina
              /> </a
            ><!--

                        --><rs-layer
              id="slider-2-slide-4-layer-14"
              data-type="text"
              data-xy="xo:341px,341px,260px,24px;yo:624px,624px,340px,157px;"
              data-text="w:normal;s:15,15,14,12;l:24,24,14,15;ls:1px,1px,0px,0px;fw:600;"
              data-vbility="t,t,f,f"
              data-rsp_bd="off"
              data-frame_0="x:50,50,31,19;"
              data-frame_1="st:2200;sp:1000;sR:2200;"
              data-frame_999="o:0;st:w;sR:5800;"
              style="z-index: 11; font-family: 'Poppins'"
              >How We Work </rs-layer
            ><!--

                        --><rs-layer
              id="slider-2-slide-4-layer-17"
              data-type="image"
              data-rsp_ch="on"
              data-xy="x:r;xo:80px,80px,50px,30px;yo:318px,318px,200px,123px;"
              data-text="w:normal;s:20,20,12,7;l:0,0,15,9;"
              data-dim="w:207px,207px,130px,80px;h:116px,116px,72px,44px;"
              data-vbility="t,t,f,f"
              data-frame_999="o:0;st:w;"
              data-loop_0="x:10px;y:10px;"
              data-loop_999="z:10px;sp:3000;yym:t;"
              style="z-index: 12"
              ><img
                src="../../assets/revolution/images/dummy.png"
                alt=""
                class="tp-rs-img rs-lazyload"
                width="207"
                height="116"
                data-lazyload="../../assets/revolution/images/n-slider-img.png"
                data-no-retina
              /> </rs-layer
            ><!--
            -->
          </rs-slide>
        </rs-slides>
        <rs-static-layers
          ><!--
                  --></rs-static-layers
        >
      </rs-module>
    </rs-module-wrap>
    <!-- END REVOLUTION SLIDER -->
  </header>
</template>
