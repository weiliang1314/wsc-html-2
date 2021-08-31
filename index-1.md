### 修改部分
<style>
        .btn-a {
            border-bottom: 2px solid transparent;
        }
        
        .pdf-freedom {
            background-color: transparent;
        }
        
        .border-radius {
            border-radius: 1rem;
        }
        
        .h-img {
            height: 9rem;
        }
        
        .btn-a {
            border-bottom: 4px solid transparent;
        }
        
        .btn-a:hover {
            border-bottom: 4px solid #005BF7;
        }
        
        .mx-64 {
            margin: 0 4rem;
        }
        
        .sys-a:hover {
            color: #005BF7;
            font-weight: bold;
        }
        
        .toggle-icon {
            width: 3.125rem;
            height: 1.5rem;
            background-color: #0049FF;
            border-radius: .75rem;
            cursor: pointer;
        }
        
        .toggle-icon:before {
            position: absolute;
            top: .1875rem;
            left: .25rem;
            width: 1.125rem;
            height: 1.125rem;
            border-radius: .5625rem;
            background-color: #fff;
            content: '';
            transition: left .2s linear;
        }
        
        .toggle-icon.right:before {
            left: 1.75rem;
        }
        
        .price-act {
            color: #005BF7;
        }
        
        .go-enter {
            text-decoration: underline;
        }
        
        *[data-dev="auto"] .dev-mobile,
        *[data-dev="desktop"] .dev-mobile,
        *[data-dev="mobile"] .dev-desktop,
        *[data-sys="auto"] .sys-mac,
        *[data-sys="auto"] .sys-linux,
        *[data-sys="auto"] .sys-ios,
        *[data-sys="auto"] .sys-android,
        *[data-sys="auto"] .sys-other,
        *[data-sys="win"] .sys-mac,
        *[data-sys="win"] .sys-linux,
        *[data-sys="win"] .sys-ios,
        *[data-sys="win"] .sys-android,
        *[data-sys="win"] .sys-other,
        *[data-sys="mac"] .sys-win,
        *[data-sys="mac"] .sys-linux,
        *[data-sys="mac"] .sys-ios,
        *[data-sys="mac"] .sys-android,
        *[data-sys="mac"] .sys-other,
        *[data-sys="linux"] .sys-win,
        *[data-sys="linux"] .sys-mac,
        *[data-sys="linux"] .sys-ios,
        *[data-sys="linux"] .sys-android,
        *[data-sys="linux"] .sys-other,
        *[data-sys="android"] .sys-ios,
        *[data-sys="android"] .sys-win,
        *[data-sys="android"] .sys-mac,
        *[data-sys="android"] .sys-linux,
        *[data-sys="android"] .sys-other,
        *[data-sys="ios"] .sys-android,
        *[data-sys="ios"] .sys-win,
        *[data-sys="ios"] .sys-mac,
        *[data-sys="ios"] .sys-linux,
        *[data-sys="ios"] .sys-other,
        *[data-sys="other"] .sys-win,
        *[data-sys="other"] .sys-mac,
        *[data-sys="other"] .sys-linux,
        *[data-sys="other"] .sys-ios,
        *[data-sys="other"] .sys-android,
        *[data-tar="auto"] .tar-alt,
        *[data-tar="nor"] .tar-alt,
        *[data-tar="alt"] .tar-nor,
        .parameter {
            display: none !important;
            margin: 0 !important;
        }
        
        .price-box {
            min-height: 26.5rem;
        }
        
        .redace-img {
            opacity: 0;
            transition: .6s;
        }
        
        .redace-img-1 {
            transition: .6s;
        }
        /*  .redace-img {
            opacity: 0;
            animation: redace-img 3s linear .5s 1;
        }
        
        @keyframes redace-img {
            0% {
                opacity: 0;
            }
            20% {
                opacity: 0.1;
            }
            30% {
                opacity: 0.5;
            }
            50% {
                opacity: 0.7;
            }
            60% {
                opacity: 0.8;
            }
            80% {
                opacity: 0.9;
            }
            90% {
                opacity: 1;
            }
            100% {
                opacity: 0;
            }
        } */
        /*页面滚动出现缩放*/
        
        .scroll-fade-in {
            --translate-y: -50;
            --opacity: 0;
            opacity: var(--opacity);
            transform: matrix(1, 0, 0, 1, 0, var(--translate-y));
            transition-duration: 0ms;
        }
        
        .scroll-fade-in-img {
            --translate-y: -50;
            --opacity: 0;
            --scale: 1;
            opacity: var(--opacity);
            transform: matrix(var(--scale), 0, 0, var(--scale), 0, var(--translate-y));
        }
        /*  
        
        .swiper-pagination {
            position: static !important;
        }
        
        .swiper-pagination-bullet-active {
            background-color: #0049FF !important;
        }
        
        .swiper-button-next,
        .swiper-button-prev {
            margin-top: -10rem !important;
            width: 5.5rem;
            height: 5.5rem;
            background-size: 5.5rem 5.5rem;
        }
        
        .swiper-button-prev {
            left: 3.5rem !important;
            background-image: url(https://images.wondershare.com/pdfelement/project/arrow-l.svg) !important;
        }
        
        .swiper-button-next {
            right: 3.5rem !important;
            background-image: url(https://images.wondershare.com/pdfelement/project/arrow-r.svg) !important;
        } */
        /*tab栏*/
        
        .nav-tabs {
            border-bottom: 2px solid #D6D6D6 !important;
        }
        
        .nav-tabs .nav-link.active,
        .nav-tabs .nav-item.show .nav-link {
            background: none !important;
            border: transparent !important;
            border-bottom: 2px solid #0049FF !important;
            color: #000000 !important;
        }
        
        .nav-tabs .nav-link {
            padding: 0.9375rem 5.625rem !important;
        }
        
        @media (min-width:1900px) {
            .pc-img {
                width: 120%;
            }
        }
        
        @media (min-width:1280px) and (max-width:1450px) {
            .btn-1 {
                padding: .71875rem .5rem !important;
            }
            .display-3 {
                font-size: 2rem;
            }
            .pc-img {
                margin-top: 6.25rem;
            }
        }
        
        @media (max-width:1024px) {
            .frame-img {
                width: 80%;
            }
            .display-4 {
                font-size: 1.8rem;
            }
            .display-3 {
                font-size: 2rem;
            }
            .protect-img {
                width: 80%;
            }
            .pc-img {
                margin-top: 8.75rem;
            }
            .mx-64 {
                margin: 0 2.9375rem;
            }
            .sign-text {
                margin-top: 3rem;
            }
            .redace-text {
                margin-top: 2rem;
            }
        }
        
        @media (max-width:769px) {
            .price-box {
                min-height: auto;
            }
            .protect-img {
                width: 80%;
            }
            .pc-img {
                margin-top: 9.25rem;
            }
            .display-3 {
                font-size: 1.8rem;
            }
        }
        
        @media (max-width:380px) {
            .display-3 {
                font-size: 1.7rem;
            }
            .mx-64 {
                margin: 0 0.5rem;
            }
            .pc-img {
                margin-top: 0;
            }
            .sign-text {
                margin-top: 0rem;
            }
            .redace-text {
                margin-top: 0rem;
            }
            .nav-tabs .nav-link {
                padding: 0.9375rem 0.2rem !important;
            }
        }
        
        .text-action {
            color: #0049ff!important;
        }
    </style>
 <main class="wsc-main px-0" style="overflow: visible;">
            <section class="" style="font-family: DM Sans; color: #000000;">
                <div class="container">
                    <div class="row justify-content-start">
                        <div class="col-xxl-5 order-md-0 order-1  col-md-6 mt-md-5 pt-5">
                            <div class="pt-3  text-center text-md-left pdfelement-left">
                                <div class="font-size-super font-weight-bold text-action  pb-3" style="font-family: Messina sans-serif;">Wondershare <span> PDFelement</span></div>
                                <h1 class="font-weight-bold pb-md-4 pb-2 display-3 pdfelement-title" style="">Protect PDF To<br class="d-xxl-block d-none"> Drive Your Business</h1>
                                <p class="font-weight-normal font-size-huge pe-tips" style="line-height: 26px;">Prevent others from viewing, copying, editing, or<br class="d-xxl-block d-none"> printing your PDF content to keep sensitive data <br class="d-xxl-block d-none">confidential.</p>
                                <div class="pt-md-4 pt-2 pb-2 text-secondary">
                                    <div data-toggle="youtube" class="d-flex align-items-center justify-content-center  justify-content-md-start" data-type="modal" data-youtube="5MUNwkfKfqQ"><img src="https://images.wondershare.com/pdfelement/project/video.svg" alt="" class="img-fluid mr-2"><span class="font-size-large">Watch the Video</span></div>
                                </div>
                                <div class="d-flex pt-3 pt-xxl-4 justify-content-center justify-content-md-start">
                                    <!-- window平台 -->
                                    <a href="#" class="btn  px-4 py-3 btn-lg btn-action sys-win m-0 mr-xl-3 mr-2 mb-xl-0">
                                        <div class="d-flex justify-content-center align-items-center">
                                            <i class="wsc-icon" data-icon="brand-windows"></i>
                                            <div class="ml-2">TRY IT FREE</div>
                                        </div>
                                    </a>
                                    <a href="#" class="btn btn-lg btn-outline-action sys-win m-0 py-3 px-lg-5 px-4 buy-action">BUY NOW</a>
                                    <a href="#" class="btn  px-4 py-3 btn-lg btn-action sys-mac m-0 mr-xl-3 mr-2 mb-xl-0">
                                        <div class="d-flex justify-content-center align-items-center">
                                            <i class="wsc-icon" data-icon="brand-windows"></i>
                                            <div class="ml-2">TRY IT FREE</div>
                                        </div>
                                    </a>
                                    <a href="#" class="btn btn-lg btn-outline-action sys-mac m-0 py-3 px-lg-5 px-4 buy-action">BUY NOW</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-xxl-7 order-md-1 order-0 col-md-6">
                            <div class="dev-desktop pdfelement-banner position-relative">
                                <img src="https://images.wondershare.com/pdfelement/project/pc-1.png" alt="" class="pc-img sys-mac" width="100%">
                                <img src="https://images.wondershare.com/pdfelement/project/pc-1.png" alt="" class="pc-img sys-win" width="100%">

                            </div>
                        </div>
                    </div>
                    <div class="row d-flex justify-content-center mt-md-5 pt-5">
                        <div class="col-4 text-center pb-4 btn-a" style="">
                            <a href="#pass" class="font-size-large font-weight-normal" style="text-decoration: none;color: #000000;">Password Encryption</a>

                        </div>
                        <div class="col-4 text-center pb-4 btn-a">
                            <a href="#redac" class="font-size-large font-weight-normal " style="text-decoration: none;color: #000000;">Mark for Redaction</a>
                        </div>
                        <div class="col-4 text-center pb-4 btn-a">
                            <a href="#sign" class="font-size-large font-weight-normal" style="text-decoration: none;color: #000000;">eSignature</a>
                        </div>
                    </div>
                </div>
            </section>
            <section class="mx-64 mt-5 pb-5 pt-5 pt-md-0" style="background-color: rgba(0, 73, 255, 0.1);border-radius: 16px;font-family: DM Sans; color: #000000;">
                <div class="container mb-md-5">
                    <div class="row d-flex justify-content-center pt-md-5" style="color: #000000;">

                        <h2 class="display-3 font-weight-bold text-center pt-3 pt-md-0" style="font-family: Greenwich;" id="pass">Password Protect a PDF</h2>
                        <p class="text-center pt-3 pb-md-5 font-size-large px-3 px-xl-0">You can limit access to a PDF by setting passwords and by restricting certain features, such as printing and editing. However, you<br class="d-xl-block d-none"> cannot prevent saving copies of a PDF. The copies have the same restrictions
                            as the original PDF.</p>


                    </div>
                    <div class="segement">
                        <nav class="justify-content-center d-flex">
                            <div class="nav nav-tabs font-size-large " id="nav-tab" role="tablist">
                                <a class="nav-item nav-link show active" id="nav-home-tab" data-toggle="tab" href="#nav-home" role="tab" aria-controls="nav-home" aria-selected="false" style="color: rgba(0, 0, 0, 0.18);">Add Open Password</a>
                                <a class="nav-item nav-link " id="nav-profile-tab" data-toggle="tab" href="#nav-profile" role="tab" aria-controls="nav-profile" aria-selected="false" style="color: rgba(0, 0, 0, 0.18);">Set Permissions Password</a>

                            </div>
                        </nav>
                        <div class="tab-content text-center mt-5" id="nav-tabContent">
                            <div class="tab-pane p-2 fade active show" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">
                                <img src="https://images.wondershare.com/pdfelement/project/protect.png" alt="" class="frame-img">
                            </div>
                            <div class="tab-pane p-2 fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab">
                                <img src="https://images.wondershare.com/pdfelement/project/protect.png" alt="" class="frame-img">
                            </div>

                        </div>
                    </div>
                    <div class="text-center mt-md-5">
                        <h3 class="font-size-super font-weight-bold pb-2 pt-3 pt-md-0">Add Open Password</h3>
                        <p class="font-size-large" style="line-height: 24px;">ou can add Open Password to restrict unauthorized to protect your file, especially for file sharing<br class="d-lg-block d-none"> or archiving. People who enter the correct password can access the file or folder. You can also
                            <br class="d-lg-block d-none"> unlock PDF password, just
                            <strong>remove the password.</strong></p>
                        <!--   <div style="color:#0049FF;" 
                        class="d-flex font-size-large font-weight-bold justify-content-center pt-2 pb-5"><a href="#" style="color:
                         #0049FF;">Try Now</a><span class="px-4">|</span><a href="#" style="color: #0049FF;">Learn How</a></div> -->
                        <div class="sys-win pt-2 pb-3 pb-md-5 font-size-large font-weight-bold" style="color: #0049FF;"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_10" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                ga360location="content_1_buttonLink_11">Learn How</a>
                        </div>
                        <div class="sys-mac pt-2 pb-3 pb-md-5 font-size-large font-weight-bold" style="color: #0049FF;"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_10" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                ga360location="content_1_buttonLink_11">Learn How</a>
                        </div>
                    </div>


                </div>

            </section>
            <section class="mx-64 mt-5" id="section-3" style="background: linear-gradient(0deg, rgba(0, 109, 255, 0.15) 0%, rgba(255, 231, 130, 0.0645) 104.95%);  border-radius: 16px;color: #000000;">
                <div class="container-clumn px-md-4 px-xl-5 px-0 freedom-box mt-4">
                    <div class="pdf-freedom border-radius mx-2  py-5">
                        <div class="freedom-conent py-0 py-lg-5">
                            <div class="row justify-content-center px-3 px-lg-0">
                                <div class="col-md-5 text-center text-md-left redace-text">
                                    <h3 class="display-3 font-weight-bold pdfelement-name" id="redac">Redact<br class="d-lg-block d-none"> PDF to Protect</h3>
                                </div>
                                <div class="col-xl-5 col-md-7 px-xl-4 px-3 text-md-left text-center">
                                    <p class="font-size-large font-weight-normal mb-3 px-xl-4 px-0">
                                        Before you share a PDF, you probably want to examine the document for sensitive content or private information that can trace the document to you. Use the Redact tools to remove or redact sensitive images and text or entire pages that are visible in a
                                        PDF.
                                    </p>

                                </div>
                            </div>

                            <div class="row d-flex justify-content-center pt-md-5 pt-0 mt-4 ">
                                <div class="col-md-6 col-xl-5 pt-3 pt-md-0">
                                    <div class="freedom-rowBox">
                                        <div class="position-relative">
                                            <img src="https://images.wondershare.com/pdfelement/project/Frame-11.png" alt="" class="img-fluid   position-absolute" id="frame-1">
                                            <img src="https://images.wondershare.com/pdfelement/project/Frame-1.png" alt="" class="img-fluid">
                                        </div>
                                    </div>
                                    <div class="mt-md-5 text-center text-md-left mt-3">
                                        <div class="display-4 font-weight-bold mt-md-4 mt-0 pdfelement-name">Redact Text</div>
                                        <p class="font-size-large mt-3 width-per pb-md-3 pb-0">
                                            Protect your sensitive information or private information<br class="d-xxl-block d-none"> such as Financial account numbers, ID Card numbers,<br class="d-xxl-block d-none">Home addresses or Private Phone Numbers
                                            that can trace<br class="d-xxl-block d-none"> the document to you when you share PDFs.</p>
                                        <!-- pc端 -->
                                        <div class="pt-md-3  text-action font-weight-bold dev-desktop text-md-left text-center">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_10" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_11">Learn How</a>
                                            </div>
                                            <!-- mac -->
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_10" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_11">Learn How</a>
                                            </div>

                                        </div>

                                    </div>
                                </div>

                                <div class=" col-xl-5 col-md-6 pl-md-5 ml-xl-5 mt-md-0  mt-5 pt-2 pt-md-0">
                                    <div class="freedom-rowBox">
                                        <div class="position-relative">
                                            <img src="https://images.wondershare.com/pdfelement/project/Frame-21.png" alt="" class="img-fluid  position-absolute" id="frame-2">
                                            <img src="https://images.wondershare.com/pdfelement/project/Frame-2.png" alt="" class="img-fluid">
                                        </div>
                                    </div>
                                    <div class=" mt-md-5 mt-3 text-center text-md-left">
                                        <div class="display-4 font-weight-bold mt-md-4 mt-0 pdfelement-name">Redact Image</div>
                                        <p class="font-size-large mt-3 width-per pb-md-3 pb-0">Black out personal and sensitive information on pdf <br class="d-xxl-block d-none">like images, graphics, pictures on your trade report, <br class="d-xxl-block d-none">ressume before publish in media.</p>
                                        <!-- pc端 -->
                                        <div class=" pt-md-3 text-action font-weight-bold dev-desktop ">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>
                                            </div>
                                            <!-- mac -->
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>
                                            </div>

                                        </div>

                                    </div>
                                </div>
                            </div>

                            <div class="row d-flex justify-content-center pt-md-5 pt-0  mt-4">
                                <div class=" col-xl-5 col-md-6 pt-3 pt-md-0">
                                    <div class="freedom-rowBox">
                                        <img src="https://images.wondershare.com/pdfelement/project/Frame-3.png" alt="" class="img-fluid">
                                    </div>
                                    <div class="mt-md-5 mt-3 text-center text-md-left">
                                        <div class="display-4 font-weight-bold mt-md-4 mt-0 pdfelement-name">Black out Entire Page(s)</div>
                                        <p class="font-size-large mt-3 width-per pb-md-3 pb-0">
                                            You may also want to redact or remove entire<br class="d-xxl-block d-none"> pages that show the product purchase price,<br class="d-xxl-block d-none"> loan history of your company.</p>
                                        <!-- pc端 -->
                                        <div class="pt-md-3  text-action font-weight-bold dev-desktop">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_10" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_11">Learn How</a>
                                            </div>
                                            <!-- mac -->
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>

                                            </div>

                                        </div>
                                    </div>

                                </div>
                                <div class="col-xl-5 col-md-6  pl-md-5 ml-xl-5 mt-md-0 mt-5 pt-2 pt-md-0">
                                    <div class="freedom-rowBox">
                                        <img src="https://images.wondershare.com/pdfelement/project/Frame-4.png" alt="" class="img-fluid">
                                    </div>

                                    <div class=" mt-md-5 text-md-left text-center">
                                        <div class="display-4 font-weight-bold mt-md-4 mt-0 pdfelement-name">Create Multiple<br class="d-md-block d-none"> Redactions with Search</div>
                                        <p class="font-size-large mt-3 width-per pb-md-3 pb-0">Use the Search & Redact tool to find and mark<br class="d-xxl-block d-none"> all words for redaction. The search tool doesn’t <br class="d-xxl-block d-none">search secured (encrypted) PDFs.</p>
                                        <!-- pc端 -->
                                        <div class=" pt-md-3 text-action font-weight-bold dev-desktop">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>
                                            </div>
                                            <!-- mac -->
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>

                                            </div>

                                        </div>
                                    </div>

                                </div>


                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="" style="color: #000000;">
                <div class="mx-2 py-xl-3 pt-xl-5 pb-md-4 pb-0 py-md-0 pt-5" style="">
                    <div class="container py-0 pt-md-5 px-xl-0 px-md-3">
                        <div class="row scroll-fade-in justify-content-between pb-3 px-3 px-lg-0" style="--opacity:1; --translate-y:0;">
                            <div class="col-xl-5  col-md-6 pl-md-5 text-md-left text-center sign-text">
                                <h2 class="font-weight-bold display-3 pdfelement-name" id="sign">Sign to<br> Protect a PDF.</h2>
                            </div>
                            <div class=" col-md-6 px-md-5 px-3 mt-md-0 mt-3 text-md-left text-center">
                                <p class="font-size-large font-weight-normal mb-3 px-lg-4 px-0">Add digital signatures and timestamps to documents and allow the PDF receiver to validate the status of a digital signature to determine if the document has been modified since the signature was applied.</p>

                            </div>
                        </div>
                        <div class="row scroll-fade-in px-md-0 px-3 justify-content-between mt-lg-5 mt-md-3   pt-2" style="--opacity:1; --translate-y:0;">
                            <div class=" col-md-6 d-flex align-items-center text-center">
                                <!-- window端 -->
                                <img src="https://images.wondershare.com/pdfelement/project/Frame-5.png" class="scroll-fade-in-img img-fluid sys-mac" alt="" style="--opacity:1; --translate-y:0; --scale:0.991645;">
                                <img src="https://images.wondershare.com/pdfelement/project/Frame-5.png" class="scroll-fade-in-img img-fluid sys-win" alt="" style="--opacity:1; --translate-y:0; --scale:0.991645;">
                            </div>
                            <div class="col-xl-5 col-md-6 mt-4 mt-md-0">
                                <div class="ml-md-5 h-100 w-100" style="display:table;vertical-align:middle">
                                    <div style="display:table-cell;vertical-align:middle" class="text-center text-md-left">
                                        <h2 class="font-weight-bold display-4  mt-md-4 mt-0 pdfelement-name">Encrypt PDF<br> with Digital Signature</h2>
                                        <p class="font-size-large mt-3 width-per pb-xxl-3 pb-0  mb-lg-3 mb-0 pr-md-4" style="line-height: 26px;">

                                            You can opt for a higher level of protection with <br class="d-xxl-block d-none">certificate security, which encrypts your PDF and<br class="d-xxl-block d-none"> authorizes access based on each user’s digital
                                            ID.
                                            <br class="d-xxl-block d-none"> Sign the document and protect it.

                                        </p>
                                        <!-- pc端 -->
                                        <div class="pt-md-3 pt-3 text-action font-weight-bold dev-desktop">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="https://pdf.wondershare.com/how-to/edit-pdf-text.html"
                                                    class="font-size-large text-action pl-3">Learn How</a></div>
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>
                                            </div>

                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="row scroll-fade-in px-md-0 px-3 justify-content-between  mt-n3" style="--opacity:0.592419; --translate-y:20.3791;">
                            <div class="col-xl-5 order-md-0 order-1 col-md-6 pl-md-5 mt-4 mt-md-0">
                                <!-- style="display:table;vertical-align:middle" -->
                                <div class="h-100 ml-2 w-100" style="display:table;vertical-align:middle">
                                    <!-- style="display:table-cell;vertical-align:middle" -->
                                    <div style="display:table-cell;vertical-align:middle" class="text-center text-md-left">
                                        <h2 class="font-weight-bold  mt-0 pdfelement-name">Sign PDF with<br> Electronic Signatures</h2>
                                        <p class="font-size-large mt-3 width-per pb-xxl-3 pb-0  mb-lg-3 mb-0 " style="line-height: 26px;">
                                            Fill your form and send a document to others<br class="d-xxl-block d-none"> for electronic signature collection safely with<br class="d-xxl-block d-none"> real-time status tracking.(Only for Cloud)

                                        </p>
                                        <!-- pc端 -->
                                        <div class="pt-md-3 pt-3 text-action font-weight-bold dev-desktop ">
                                            <!-- window -->
                                            <div class="sys-win"><a href="#" class="font-size-large text-action pr-3" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="https://pdf.wondershare.com/how-to/edit-pdf-image.html"
                                                    class="font-size-large text-action pl-3">Learn How</a></div>
                                            <div class="sys-mac"><a href="#" class="font-size-large text-action pr-3" ga360location="content_1_buttonLink_18" ga360type="prd download" ga360proids="5239" ga360pronames="pdfelementprofull">Try Now</a>|<a href="#" class="font-size-large text-action pl-3"
                                                    ga360location="content_1_buttonLink_19">Learn How</a>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class=" order-md-1 order-0 col-md-6 d-flex align-items-center text-left">
                                <!-- windows -->
                                <img src="https://images.wondershare.com/pdfelement/project/Frame-6.png" class="scroll-fade-in-img sys-win img-fluid" alt="" style="--opacity:0.405688; --translate-y:29.7156; --scale:0.881138;">
                                <img src="https://images.wondershare.com/pdfelement/project/Frame-6.png" class="scroll-fade-in-img sys-mac img-fluid" alt="" style="--opacity:0.405688; --translate-y:29.7156; --scale:0.881138;">

                            </div>

                        </div>
                    </div>
                </div>
            </section>
            <div class="container-column px-xl-5 px-md-4 px-2  mt-md-5 mb-md-0 my-5">
                <div class="pdf-feat border-radius mx-2 py-3 py-5 mt-md-3">
                    <h4 class="display-3 text-center font-weight-bold pt-md-3 px-md-0 px-1 pt-0 pdfelement-title">Other PDFelement features you may like</h4>
                    <div class="container my-lg-5 my-0">
                        <div class="row">
                            <div class="col-6 col-md text-center pt-5">
                                <div class="h-img"><img src="https://images.wondershare.com/pdfelement/images2021/pe/pdfother_icon3.png" alt="" class="img-fluid"></div>
                                <!-- pc端 -->
                                <div class="feat-link dev-desktop">
                                    <!-- Windows -->
                                    <a href="https://pdf.wondershare.com/sign-pdf.html" class="font-size-large sys-win">Sign PDFs</a>
                                    <!-- mac -->
                                    <a href="https://pdf.wondershare.com/sign-pdf.html" class="font-size-large sys-mac">Sign PDFs</a>
                                </div>
                                <!-- 移动端 -->
                                <div class="feat-link dev-mobile">
                                    <!-- 安卓 -->
                                    <a href="https://pdf.wondershare.com/sign-pdf.html" class="font-size-large sys-android">Sign PDFs</a>
                                    <!-- ios -->
                                    <a href="https://pdf.wondershare.com/sign-pdf.html" class="font-size-large sys-ios">Sign PDFs</a>
                                </div>
                            </div>
                            <div class="col-6 col-md text-center pt-md-5 pt-4">
                                <div class="h-img"><img src="https://images.wondershare.com/pdfelement/images2021/pe/pdfother_icon2.png" alt="" class="img-fluid"></div>
                                <!-- pc端 -->
                                <div class="feat-link dev-desktop">
                                    <!-- Windows -->
                                    <a href="https://pdf.wondershare.com/how-to/annotate-pdf.html" class="font-size-large sys-win">Annotate PDFs</a>
                                    <!-- mac -->
                                    <a href="https://pdf.wondershare.com/how-to/annotate-pdf.html" class="font-size-large sys-mac">Annotate PDFs</a>
                                </div>
                                <!-- 移动端 -->
                                <div class="feat-link dev-mobile">
                                    <!-- 安卓 -->
                                    <a href="https://pdf.wondershare.com/how-to/annotate-pdf.html" class="font-size-large sys-android">Annotate PDFs</a>
                                    <!-- ios -->
                                    <a href="https://pdf.wondershare.com/how-to/annotate-pdf.html" class="font-size-large sys-ios">Annotate PDFs</a>
                                </div>
                            </div>
                            <div class="col-6 col-md text-center pt-md-5 pt-4">
                                <div class="h-img"><img src="https://images.wondershare.com/pdfelement/pdf-function/convert-icon.png" alt="" class="img-fluid"></div>
                                <!-- pc端 -->
                                <div class="feat-link dev-desktop">
                                    <!-- Windows -->
                                    <a href="https://pdf.wondershare.com/convert-pdf.html" class="font-size-large sys-win">Convert PDFs</a>
                                    <!-- mac -->
                                    <a href="https://pdf.wondershare.com/convert-pdf.html" class="font-size-large sys-mac">Convert PDFs</a>
                                </div>
                                <!-- 移动端 -->
                                <div class="feat-link dev-mobile">
                                    <!-- 安卓 -->
                                    <a href="https://pdf.wondershare.com/convert-pdf.html" class="font-size-large sys-android">Convert PDFs</a>
                                    <!-- ios -->
                                    <a href="https://pdf.wondershare.com/convert-pdf.html" class="font-size-large sys-ios">Convert PDFs</a>
                                </div>
                            </div>
                            <div class="col-6 col-md text-center pt-md-5 pt-4">
                                <div class="h-img"><img src="https://images.wondershare.com/pdfelement/images2021/pe/pdfother_icon4.png" alt="" class="img-fluid"></div>
                                <!-- pc端 -->
                                <div class="feat-link dev-desktop">
                                    <!-- Windows -->
                                    <a href="https://pdf.wondershare.com/pdf-forms.html" class="font-size-large sys-win">PDF Forms</a>
                                    <!-- mac -->
                                    <a href="https://pdf.wondershare.com/pdf-forms.html" class="font-size-large sys-mac">PDF Forms</a>
                                </div>
                                <!-- 移动端 -->
                                <div class="feat-link dev-mobile">
                                    <!-- 安卓 -->
                                    <a href="https://pdf.wondershare.com/pdf-forms.html" class="font-size-large sys-android">PDF Forms</a>
                                    <!-- ios -->
                                    <a href="https://pdf.wondershare.com/pdf-forms.html" class="font-size-large sys-ios">PDF Forms</a>
                                </div>
                            </div>
                            <div class="col-6 col-md text-center pt-md-5 pt-4">
                                <div class="h-img"><img src="https://images.wondershare.com/pdfelement/pdf-function/ocr_icon.png" alt="ocr" class="img-fluid"></div>
                                <!-- pc端 -->
                                <div class="feat-link dev-desktop">
                                    <!-- Windows -->
                                    <a href="https://pdf.wondershare.com/ocr-page.html" class="font-size-large sys-win">OCR</a>
                                    <!-- mac -->
                                    <a href="https://pdf.wondershare.com/ocr-page.html" class="font-size-large sys-mac">OCR</a>
                                </div>
                                <!-- 移动端 -->
                                <div class="feat-link dev-mobile">
                                    <!-- 安卓 -->
                                    <a href="https://pdf.wondershare.com/ocr-page.html" class="font-size-large sys-android">OCR</a>
                                    <!-- ios -->
                                    <a href="https://pdf.wondershare.com/ocr-page.html" class="font-size-large sys-ios">OCR</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!doctype html>
            <html>

            <head>
                <meta charset="utf-8">
                <title>无标题文档</title>
            </head>

            <body>
                <style>
                    .border-color {
                        border: 1px solid #dfdfdf;
                    }
                    
                    .toggle-icon {
                        width: 3.125rem;
                        height: 1.5rem;
                        background-color: #0049FF;
                        border-radius: .75rem;
                        cursor: pointer;
                    }
                    
                    .toggle-icon:before {
                        position: absolute;
                        top: .1875rem;
                        left: .25rem;
                        width: 1.125rem;
                        height: 1.125rem;
                        border-radius: .5625rem;
                        background-color: #fff;
                        content: '';
                        transition: left .2s linear;
                    }
                    
                    .toggle-icon.right:before {
                        left: 1.75rem;
                    }
                    
                    .price-act {
                        color: #005BF7;
                    }
                    
                    .price-box {
                        min-height: 26.5rem;
                    }
                    
                    @media (max-width:769px) {
                        .price-box {
                            min-height: auto;
                        }
                    }
                </style>
                <div class="container mt-lg-5">
                    <div class="pdf-plan py-lg-5 pt-3">
                        <h4 class="display-3 text-center font-weight-bold pdfelement-title">Choose the PDFelement plan that works for you.</h4>
                        <div class="row mt-lg-5">
                            <div class="col-lg-4 col-md-6 pt-3">
                                <div class="border-color px-lg-4 px-3">
                                    <div class="price-box py-lg-5 py-3">
                                        <div class="font-size-super font-weight-bold">PDFelement for Desktop</div>
                                        <p class="font-size-normal py-lg-3 py-2 my-0">The easiest way to create, edit, convert, and sign PDF documents.</p>
                                        <div class="py-2 d-flex align-items-center">
                                            <span class="d-inline-blcok font-size-small price-act">Annually</span>
                                            <span class="d-inline-block mx-3 toggle-icon position-relative"></span>
                                            <span class="d-inline-blcok font-size-small">One-Time Price</span>
                                        </div>
                                        <!-- Annually -->
                                        <div class="pt-4 annually">
                                            <div><span class="font-size-super font-weight-bold">$79.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$129</span></div>
                                            <!-- pc端 -->
                                            <div class="dev-desktop py-3">
                                                <!-- window平台 -->
                                                <a href="https://download.wondershare.com/pdfelement-pro_full5239.exe" class="btn btn-action sys-win m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <i class="wsc-icon" data-icon="brand-windows"></i>
                                                        <div class="ml-2">TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5239&license_id=267&sub_lid=0&coupon_id=9599&currency=USD&language=English&verify=77d76d0f66f7030c1df215675b59a42b" class="btn btn-outline-action sys-win m-0">BUY NOW</a>
                                                <!-- mac平台 -->
                                                <a href="https://download.wondershare.com/mac-pdfelement_full5237.dmg" class="btn btn-action sys-mac m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <i class="wsc-icon" data-icon="brand-macos"></i>
                                                        <div class="ml-2">Try It Free</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5237&license_id=267&sub_lid=0&coupon_id=9599&currency=USD&language=English&verify=a055a0ebf3c0aa6229b496add5137f70" class="btn btn-outline-action sys-mac m-0">BUY NOW</a>
                                            </div>
                                            <!-- 移动端 -->
                                            <div class="dev-mobile py-3 text-center">
                                                <!-- 安卓 -->
                                                <a href="https://download.wondershare.com/pdfelement-pro_full5239.exe" class="btn btn-action mr-md-3 mb-3 sys-android">TRY IT FREE</a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5239&license_id=267&sub_lid=0&coupon_id=9599&currency=USD&language=English&verify=77d76d0f66f7030c1df215675b59a42b" class="btn btn-outline-action sys-android mb-3">BUY NOW</a>
                                                <!-- ios -->
                                                <a href="https://download.wondershare.com/mac-pdfelement_full5237.dmg" class="btn btn-action mr-md-3 mb-3 sys-ios">TRY IT FREE</a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5237&license_id=267&sub_lid=0&coupon_id=9599&currency=USD&language=English&verify=a055a0ebf3c0aa6229b496add5137f70" class="btn btn-outline-action sys-ios mb-3">BUY NOW</a>
                                            </div>
                                            <!-- pc端 -->
                                            <div class="pt-1 dev-desktop">
                                                <!-- win -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-win" data-platform="mac" data-toggle="platform">Switch to Mac >></a>
                                                <!-- mac -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-mac" data-platform="win" data-toggle="platform">Switch to Windows >></a>
                                            </div>
                                            <!-- 移动端端 -->
                                            <div class="pt-1 dev-mobile">
                                                <!-- 安卓 -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-android" data-platform="ios" data-toggle="platform">Switch to Mac >></a>
                                                <!-- ios -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-ios" data-platform="android" data-toggle="platform">Switch to Windows >></a>
                                            </div>
                                        </div>

                                        <!--one Time Price -->
                                        <div class="pt-4 timeprice" style="display: none;">
                                            <div><span class="font-size-super font-weight-bold">$129.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$159</span></div>
                                            <!-- pc端 -->
                                            <div class="dev-desktop py-3">
                                                <!-- window平台 -->
                                                <a href="https://download.wondershare.com/pdfelement-pro_full5239.exe" class="btn btn-action sys-win m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <i class="wsc-icon" data-icon="brand-windows"></i>
                                                        <div class="ml-2">TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5239&license_id=1804&sub_lid=0&coupon_id=9598&currency=USD&language=English&verify=f41fb7ed9d3b06646af62548c3df3ea2" class="btn btn-outline-action sys-win m-0">BUY NOW</a>
                                                <!-- mac平台 -->
                                                <a href="https://download.wondershare.com/mac-pdfelement_full5237.dmg" class="btn btn-action sys-mac m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <i class="wsc-icon" data-icon="brand-macos"></i>
                                                        <div class="ml-2">TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5237&license_id=1804&sub_lid=0&coupon_id=9598&currency=USD&language=English&verify=2204ec98ef8368d6a0c35a651093bf01" class="btn btn-outline-action sys-mac m-0">BUY NOW</a>
                                            </div>
                                            <!-- 移动端 -->
                                            <div class="dev-mobile py-3 text-center">
                                                <!-- 安卓 -->
                                                <a href="https://download.wondershare.com/pdfelement-pro_full5239.exe" class="btn btn-action mr-md-3 mb-3 sys-android">TRY IT FREE</a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5239&license_id=1804&sub_lid=0&coupon_id=9598&currency=USD&language=English&verify=f41fb7ed9d3b06646af62548c3df3ea2" class="btn btn-outline-action sys-android mb-3">BUY NOW</a>
                                                <!-- ios -->
                                                <a href="https://download.wondershare.com/mac-pdfelement_full5237.dmg" class="btn btn-action mr-md-3 mb-3 sys-ios">TRY IT FREE</a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=5237&license_id=1804&sub_lid=0&coupon_id=9598&currency=USD&language=English&verify=2204ec98ef8368d6a0c35a651093bf01" class="btn btn-outline-action sys-ios mb-3">BUY NOW</a>
                                            </div>
                                            <!-- pc端 -->
                                            <div class="pt-1 dev-desktop">
                                                <!-- win -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-win" data-platform="mac" data-toggle="platform">switch to mac >></a>
                                                <!-- mac -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-mac" data-platform="win" data-toggle="platform">switch to Windows >></a>
                                            </div>
                                            <!-- 移动端端 -->
                                            <div class="pt-1 dev-mobile">
                                                <!-- 安卓 -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-android" data-platform="ios" data-toggle="platform">switch to mac >></a>
                                                <!-- ios -->
                                                <a href="javascript:;" class="font-size-small go-enter sys-ios" data-platform="android" data-toggle="platform">switch to Windows >></a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="col-lg-4 col-md-6 pt-3">
                                <div class="border-color px-lg-4 px-3">
                                    <div class="price-box py-lg-5 py-3">
                                        <div class="font-size-super font-weight-bold">PDFelement for iOS</div>
                                        <p class="font-size-normal py-lg-3 py-2 my-0">Edit, merge, organize, compress, sign & secure your documents on the go.</p>
                                        <div class="py-2 d-flex align-items-center">
                                            <span class="d-inline-blcok font-size-small price-act">Annually</span>
                                            <span class="d-inline-block mx-3 toggle-icon position-relative"></span>
                                            <span class="d-inline-blcok font-size-small">One-Time Price</span>
                                        </div>
                                        <!-- Annually -->
                                        <div class="pt-4 annually">
                                            <div><span class="font-size-super font-weight-bold">$29.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$59.99</span></div>
                                            <div class="py-3">
                                                <a href="https://apps.apple.com/app/apple-store/id1516765045?pt=169436&ct=featurepage-sign-youtube-lhq&mt=8" class="btn btn-action m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <div>TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=7628&license_id=267&sub_lid=0&coupon_id=9600&currency=USD&language=English&verify=2c5e2b5a3bc68f2ad0297b2eb2877221" class="btn btn-outline-action  m-0">BUY NOW</a>
                                            </div>
                                        </div>

                                        <!--one Time Price -->
                                        <div class="pt-4 timeprice" style="display: none;">
                                            <div><span class="font-size-super font-weight-bold">$39.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$79.99</span></div>
                                            <div class="py-3">
                                                <a href="https://apps.apple.com/app/apple-store/id1516765045?pt=169436&ct=featurepage-sign-youtube-lhq&mt=8" class="btn btn-action m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <div>TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=7628&license_id=1804&sub_lid=0&coupon_id=9601&currency=USD&language=English&verify=18377b03551336bdd9251d76a85eba54" class="btn btn-outline-action  m-0">BUY NOW</a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="col-lg-4 col-md-6 pt-3">
                                <div class="border-color px-lg-4 px-3">
                                    <div class="price-box py-lg-5 py-3">
                                        <div class="font-size-super font-weight-bold">Document Cloud</div>
                                        <p class="font-size-normal py-lg-3 py-2 my-0">Collaborate on work, on the web. Easy Cloud-based Document Management.</p>
                                        <div class="py-2 d-flex align-items-center">
                                            <span class="d-inline-blcok font-size-small price-act">Semiannually</span>
                                            <span class="d-inline-block mx-3 toggle-icon position-relative"></span>
                                            <span class="d-inline-blcok font-size-small">Annually</span>
                                        </div>
                                        <!-- Semiannually -->
                                        <div class="pt-4 annually">
                                            <div><span class="font-size-super font-weight-bold">$19.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$39.99</span></div>
                                            <div class="py-3">
                                                <a href="https://cloud.pdfelement.io/sso/authorize?redirect_uri=https://cloud.pdfelement.io/?source=featured-page" class="btn btn-action m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <div>TRY IT FREE</div>
                                                    </div>
                                                </a>
                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=7985&license_id=2583&sub_lid=0&coupon_id=9602&currency=USD&language=English&verify=b4a6169843be6e63645b6aca52f3909e" class="btn btn-outline-action  m-0">BUY NOW</a>
                                            </div>
                                        </div>

                                        <!--Annually -->
                                        <div class="pt-4 timeprice" style="display: none;">
                                            <div><span class="font-size-super font-weight-bold">$29.99</span><span class="font-size-small ml-2" style="text-decoration: line-through;">$59.99</span></div>
                                            <div class="py-3">
                                                <a href="https://cloud.pdfelement.io/sso/authorize?redirect_uri=https://cloud.pdfelement.io/?source=featured-page" class="btn btn-action m-0 mr-xl-3 mb-xl-0">
                                                    <div class="d-flex justify-content-center align-items-center">
                                                        <div>TRY IT FREE</div>
                                                    </div>
                                                </a>

                                                <a href="https://store.wondershare.com/index.php?method=index&submod=checkout&pid=7985&license_id=498&sub_lid=0&coupon_id=9600&currency=USD&language=English&verify=764cc4fc421c7f5c76adef88043e6ebc" class="btn btn-outline-action  m-0">BUY NOW</a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="text-center py-4 font-size-large">Team licenses available. <a href="https://pdf.wondershare.com/business/" style="color: #005BF7;text-decoration: underline;">Learn more</a></div>
                    </div>
                </div>
            </body>

            </html>
        </main>
          <script>
        //鼠标滚动事件
        var frame1 = document.querySelector("#frame-1");
        var frame2 = document.querySelector("#frame-2");
        var section = document.querySelector("#section-3")
        var sectiontop = section.offsetTop;

        console.log(sectiontop)
        window.onscroll = function() {
            var scroll = document.documentElement.scrollTop;

            if (scroll > sectiontop - 300) {
                frame1.classList.add("redace-img")
                frame2.classList.add("redace-img")
            } else {
                frame1.classList.remove("redace-img")
                frame1.classList.add("redace-img-1")
                frame2.classList.remove("redace-img")
                frame2.classList.add("redace-img-1")
            }
        }


        $(function() {
            var offsetHeight = $('footer').offset().top;
            $('.buy-action').on('click', function() {
                $('body,html').animate({
                    scrollTop: offsetHeight
                }, 300)
            })
            var view_height = window.innerHeight || window.outerHeight
            var scrollElement = document.scrollingElement || document.documentElement || document.body
            var scroll_fade_in = document.querySelectorAll('.scroll-fade-in')
            var scroll_fade_in_imgs = document.querySelectorAll('.scroll-fade-in-img')
            var scrollRatio = 1 / 0.6
            scrollFadeInit()

            function scrollFadeInit() {
                scroll_fade_in.length > 0 && scroll_fade_in[0].getBoundingClientRect().top <= view_height &&
                    scroll_fade_in.forEach(function(el) {
                        el.getBoundingClientRect().top <= view_height && scrollFadeIn(el)
                    })

                scroll_fade_in_imgs.length > 0 && scroll_fade_in_imgs[0].getBoundingClientRect().top <= view_height &&
                    scroll_fade_in_imgs.forEach(function(el) {
                        el.getBoundingClientRect().top <= view_height && scrollFadeIn(el, 0, true)
                    })
            }
            //监听滚动元素队列
            function scrollFadeIn(el, delta, isImg) {
                requestAnimationFrame(function() {
                    delta = delta || 0
                    var rect = el.getBoundingClientRect()
                    var vh = view_height / (scrollRatio + delta * 0.1)
                    if (rect.top <= vh) {
                        el.style.setProperty('--opacity', 1)
                        el.style.setProperty('--translate-y', 0)
                        return
                    }

                    var ratio = (rect.top - vh) / vh
                    ratio = ratio <= 1 ? ratio : 1
                    var multi = +el.getAttribute('data-multiple')
                    multi = multi || 1
                    el.style.setProperty('--opacity', (1 - 1 * ratio))
                    el.style.setProperty('--translate-y', 50 * ratio * multi)
                    isImg && el.style.setProperty('--scale', 1 - 0.2 * ratio)
                })
            }
            loop(0, function(previousScrollTop, scrollTop) {
                scrollFadeInit()
            })

            function loop(previousScrollTop, callback) {
                function repeat() {
                    requestAnimationFrame(function() {
                        loop(previousScrollTop, callback)
                    })
                }
                var scrollTop = scrollElement.scrollTop
                if (previousScrollTop === scrollTop) {
                    return repeat()
                } else {
                    callback && callback(previousScrollTop, scrollTop)
                    previousScrollTop = scrollTop
                }
                return repeat()
            }
        })
    </script>