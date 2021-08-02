<template>
  <section class="testimonials-one" id="testimonials">
    <div class="container">
      <div class="block-title text-center">
        <h2 class="block-title__title black-text-color">Applications</h2><!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <div class="row">
        <div class="col-lg-12">
          <div class="testimonials-one__content">
            <div class="swiper-wrapper" id="sync1">
              <swiper :options="swiperOptions">
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Computerized Prescriber Order Entry</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Quick, free form entry on an easy-to-use interface</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Automated order processing and instant confirmation</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Secured messaging/communication between pharmacy, prescriber, and facility</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"></li>
                          </ul><!-- /.pricing-one__list -->
                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Digital Resident Charts</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Automatic sorting of Orders upon order completion</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Adaptable, easily navigable interface and tools for your daily charting needs. </li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Space efficient for small or limited space nursing stations.</li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->
                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Electronic New Admission or Readmission, BPMH</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Automatically populate previous resident data on Readmission</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Simple, familiar, and easy to use form flow </li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->
                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">PDF Medication Administration Records</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Generate Report from the app</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Simple, familiar, and easy to use flow like your paper bound MAR </li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Good back-up application for your eMAR</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>No more printing of monthly MAR Reports</li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->
                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Electronic Drug Record Book & Reorder</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Medication is ordered through the app</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Orders can be received manually or using a barcode scanner</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Eliminate paper and the need to manually record the ordering and receipt of medications</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Customized filter for viewing and printing reports</li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->
                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Digital Narcotic Binder</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Monitor Individual & Ward Count</li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>View and Print reports within the app </li><!-- /.pricing-one__list-item -->
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Easily view pending narcotic & controlled substances for destruction</li><!-- /.pricing-one__list-item -->                                                        
                          </ul><!-- /.pricing-one__list -->                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Integrated eFax Application</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Healthcare version of Electronic Faxing (HIPAA & PHIPA Compliant)</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Receive, print, and send faxes within the app</li><!-- /.pricing-one__list-item -->                                                        
                          </ul><!-- /.pricing-one__list -->                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Electronic Lab Requisition Form</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Complete the form electronically</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Send or print within the app</li><!-- /.pricing-one__list-item -->                                                        
                          </ul><!-- /.pricing-one__list -->                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">LTC Pharmacy Workflow</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Independent Pharmacy hosted application</li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Complete flow management from receiving orders (fax, telephone, or digital submission) to data entry, PV1 & PV2, filling, weekly batch processing & scheduling, checking, and shipping</li><!-- /.pricing-one__list-item -->                                                        
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Paperless signing of Batch Hardcopies </li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->                          
                        </div><!-- /.pricing-one__single -->
                    </div><!-- /.item -->           
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                      <div class="pricing-one__single">
                          <h4 class="pricing-one__amount">Delivery App</h4><!-- /.pricing-one__amount -->                          
                          <ul class="pricing-one__list">
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Simple Android app to track your delivery status </li><!-- /.pricing-one__list-item -->                            
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Provide list of packages delivered to each facility</li><!-- /.pricing-one__list-item -->                                                        
                            <li class="cta-three__list-item"><i class="fa fa-check"></i>Web Portal based access to view and print reports</li><!-- /.pricing-one__list-item -->                            
                          </ul><!-- /.pricing-one__list -->                          
                        </div><!-- /.pricing-one__single -->
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
          slidesPerView : 3,
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
