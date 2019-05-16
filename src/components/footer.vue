<template>
  <footer class="footer">
      <div id="footer" class="section-3 footer-dark">
        <div class="container">
          <div class="row">
            <!-- Contact us -->
            <div class="span3">
              <h2>Contact us</h2>
              <address class="vcard">
                <span class="street-address">3301 Envato Melbourne, Little Lonsdale St</span> <span class="tel">+1 234
                  123 4567</span> <a href="mailto:info@owltemplates.com" class="email">info@owltemplates.com</a>
                <ul id="social" class="tooltip-demo">
                  <li><a rel="tooltip" title="RSS" href="#"><img alt="RSS" src="img/social_icons/rss.png"></a></li>
                  <li><a rel="tooltip" title="Twitter" href="#"><img alt="Twitter"
                        src="img/social_icons/twitter.png"></a></li>
                  <li><a rel="tooltip" title="Facebook" href="#"><img alt="Facebook"
                        src="img/social_icons/facebook.png"></a></li>
                  <li><a rel="tooltip" title="Dribbble" href="#"><img alt="Dribbble"
                        src="img/social_icons/dribbble.png"></a></li>
                  <li><a rel="tooltip" title="Flickr" href="#"><img alt="Flickr" src="img/social_icons/flickr.png"></a>
                  </li>
                  <li><a rel="tooltip" title="Skype" href="#"><img alt="Skype" src="img/social_icons/skype.png"></a>
                  </li>
                </ul>
              </address>
            </div>
            <!-- Useful Links -->
            <div class="span3">
              <h2>Useful Links</h2>
              <ul class="list">
                <li><a href="#">In faucibus orci luctus et</a></li>
                <li><a href="#">Ultrices posuere cubilia Curae</a></li>
                <li><a href="#">Suspendisse sollicitudin velit sed leo</a></li>
                <li><a href="#">Nam elit agna,endrerit sit amet</a></li>
              </ul>
            </div>
            <!-- twitter feed  -->
            <div class="span3">
              <h2>Twitter Feed</h2>
              <div class="tweets">
                <p> Loading Tweets... </p>
                <ul id="tweet-list">
                </ul>
              </div>
            </div>
            <!-- Newsletter -->
            <div class="span3">
              <h2>Newsletter</h2>
              <form class="navbar-inverse form-search">
                <div class="navbar-search input-append">
                  <input type="text" placeholder="Your Email" class="span2 search-query">
                  <button type="submit" class="btn btn-warning">submit</button>
                </div>
                <div class="clearfix"></div>
              </form>
              <div class="clearfix p1">
                <p class="text-info"><i>Lorem ipsum dolor sit amet, consectetuer adipiscing, sed diam nonummy nibh
                    eui.</i></p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- footer 2 -->
      <div id="copyrights" class="footer-2 footer-dark">
        <div class="container">
          <div class="row">
            <div class="span12">Copyright &copy; 2014.Company name All rights reserved.</div>
          </div>
        </div>
      </div>
    </footer>
</template>
 
<script>
export default {
  name: 'Footer',
  props: {
   
  }
};
</script>
<style scoped lang="scss">

</style>
