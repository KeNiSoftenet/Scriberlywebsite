<template>
  <section class="testimonials-one" >
    <div class="container" id="testimonials">
      <div class="row">
        <div class="col-lg-6">
          <div class="testimonials-one__image-block swiper-container">
            <div class="swiper-wrapper" id="sync2">
              <swiper :options="swiperOptionsVerticle">
                <swiper-slide>
              <div class="item clearfix">
                <div class="testimonials-one__image">
                  <img src="/images/testi-1-1.jpg" class="testimonials-one__thumb" alt="Awesome Image" />
                </div><!-- /.testimonials-one__image -->
              </div><!-- /.item -->
                </swiper-slide>
                <swiper-slide>
              <div class="item clearfix">
                <div class="testimonials-one__image">
                  <img src="/images/testi-1-2.jpg" class="testimonials-one__thumb" alt="Awesome Image" />                  
                </div><!-- /.testimonials-one__image -->
              </div><!-- /.item -->
                </swiper-slide>
                <swiper-slide>
              <div class="item clearfix">
                <div class="testimonials-one__image">
                  <img src="/images/testi-1-3.jpg" class="testimonials-one__thumb" alt="Awesome Image" />
                </div><!-- /.testimonials-one__image -->
              </div><!-- /.item -->
                </swiper-slide>
              </swiper>
            </div><!-- /.owl-carousel owl-theme -->
          </div><!-- /.testimonials-one__image-block -->
        </div><!-- /.col-lg-6 -->
        <div class="col-lg-6">
          <div class="testimonials-one__content">
            <div class="block-title text-left">
              <h2 class="block-title__title light-text-color">Applications</h2><!-- /.block-title__title -->
            </div><!-- /.block-title -->
            <div class="swiper-wrapper" id="sync1">
              <swiper :options="swiperOptions">
                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Computerized Prescriber Order Entry</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Quick, free form entry on an easy-to-use interface</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Automated order processing and instant confirmation</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Secured messaging/communication between pharmacy, prescriber, and facility</li><!-- /.pricing-one__list-item -->                                                        
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

              <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Digital Resident Charts</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Automatic sorting of Orders upon order completion</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Adaptable, easily navigable interface and tools for your daily charting needs. </li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Space efficient for small or limited space nursing stations.</li><!-- /.pricing-one__list-item -->                            
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>
                
                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Electronic New Admission or Readmission, BPMH</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Automatically populate previous resident data on Readmission</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Simple, familiar, and easy to use form flow</li><!-- /.pricing-one__list-item -->                      
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">PDF Medication Administration Records</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Generate Report from the app</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Simple, familiar, and easy to use flow like your paper bound MAR </li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Good back-up application for your eMAR</li><!-- /.pricing-one__list-item -->   
                      <li class="testimonials-one__text">No more printing of monthly MAR Reports</li><!-- /.pricing-one__list-item -->                            
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Electronic Drug Record Book & Reorder</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Medication is ordered through the app</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Orders can be received manually or using a barcode scanner</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Eliminate paper and the need to manually record the ordering and receipt of medications</li><!-- /.pricing-one__list-item -->   
                      <li class="testimonials-one__text">Customized filter for viewing and printing reports</li><!-- /.pricing-one__list-item -->                            
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Digital Narcotic Binder</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Monitor Individual & Ward Count</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">View and Print reports within the app</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Easily view pending narcotic & controlled substances for destruction</li><!-- /.pricing-one__list-item -->                         
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Integrated eFax Application</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Healthcare version of Electronic Faxing (HIPAA & PHIPA Compliant)</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Receive, print, and send faxes within the app</li><!-- /.pricing-one__list-item -->                      
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>
                 
                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Electronic Lab Requisition Form</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Complete the form electronically</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Send or print within the app</li><!-- /.pricing-one__list-item -->                     
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>
 
                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">LTC Pharmacy Workflow</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Independent Pharmacy hosted application</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Complete flow management from receiving orders (fax, telephone, or digital submission) to data entry, PV1 & PV2, filling, weekly batch processing & scheduling, checking, and shipping</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Paperless signing of Batch Hardcopies </li><!-- /.pricing-one__list-item -->                         
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

                <swiper-slide>
                  <div class="item">                  
                    <h4 class="light-text-color">Delivery App</h4><!-- /.pricing-one__amount -->                          
                    <ul>
                      <li class="testimonials-one__text">Simple Android app to track your delivery status </li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Provide list of packages delivered to each facility</li><!-- /.pricing-one__list-item -->
                      <li class="testimonials-one__text">Web Portal based access to view and print reports</li><!-- /.pricing-one__list-item -->                         
                    </ul><!-- /.pricing-one__list -->
                  </div><!-- /.item -->
                </swiper-slide>

 


              </swiper>
            </div><!-- /.owl-carousel owl-theme -->
          </div><!-- /.testimonials-one__content -->
        </div><!-- /.col-lg-6 -->
      </div><!-- /.row -->
    </div><!-- /.container -->
  </section>
</template>

<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper'
  import 'swiper/css/swiper.css'

  export default {
    name: "Testimonial",
    components: {
      Swiper,
      SwiperSlide
    },
    directives: {
      swiper: directive
    },
    data() {
      return {
        swiperOptions: {
          slidesPerView : 1,
          loop: true,
          speed: 1000,
          spaceBetween : 30,
          autoplay: {
            delay: 3000,
            disableOnInteraction: false
          },
          pagination: {
            el: '.swiper-pagination',
            type: 'bullets',
            clickable: true
          },
        },

        swiperOptionsVerticle: {
          direction: 'vertical',
          autoplay: {
            delay: 3000,
            disableOnInteraction: false
          },
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          },
        }
      }
    },
  }
</script>

<style scoped>
  .testimonials-one__image-block.swiper-container {
    height: 500px;
  }
</style>
