# Reddit-Pixel-Code
Pixel tracking code for Reddit 

https://advertising.reddithelp.com/en/categories/measurement/install-reddit-pixel


<!-- Reddit Pixel -->
<script>
!function(w,d){if(!w.rdt){var p=w.rdt=function(){p.sendEvent?p.sendEvent.apply(p,arguments):p.callQueue.push(arguments)};p.callQueue=[];var t=d.createElement("script");t.src="https://www.redditstatic.com/ads/pixel.js",t.async=!0;var s=d.getElementsByTagName("script")[0];s.parentNode.insertBefore(t,s)}}(window,document);rdt('init','t2_9xa0b069', {"optOut":false,"useDecimalCurrencyValues":true,"aaid":"<AAID-HERE>","email":"<EMAIL-HERE>","externalId":"<EXTERNAL-ID-HERE>","idfa":"<IDFA-HERE>"});rdt('track', 'PageVisit');
</script>
<!-- DO NOT MODIFY UNLESS TO REPLACE A USER IDENTIFIER -->
<!-- End Reddit Pixel -->
  
 
 Paste the code on your website:
  <!-- Example -->
<!DOCTYPE html>
<html lang="en">
  <head>
     PUT PIXEL CODE HERE
  </head>
  
  Set up standard conversion events:
  <script>
  rdt('track', 'Purchase', {
      "currency": "USD",
      "itemCount": 1,
      "transactionId": "12345678",
      "value": 100
  });
</script>
  
 Add To Cart
  <script>
  rdt('track', 'AddToCart', {
      "currency": "USD",
      "itemCount": 1,
      "value": 100
  });
</script>
  
  Add To Wishlist:
  <script>
  rdt('track', 'AddToWishlist', {
      "currency": "USD",
      "itemCount": 1,
      "value": 100
  });
</script>
  
  Lead:
  <script>
  rdt('track', 'Lead', {
      "currency": "USD",
      "transactionId": "12345678",
      "value": 100
  });
</script>
  
  Signup:
  <script>
  rdt('track', 'SignUp', {
      "currency": "USD",
      "transactionId": "12345678",
      "value": 100
  });
</script>
  
  Page Visit:
  <script>
  rdt('track', 'PageVisit');
</script>
  
  View Content:
  <script>
  rdt('track', 'ViewContent');
</script>
  
  Search:
  <script>
  rdt('track', 'Search');
</script>
  
  
 ===================================================
Event Name        Description                                             Code
PageVisit         User lands on your landing page (default event)         rdt('track', 'PageVisit');

ViewContent       User lands on a specific webpage, like a product page   rdt('track', 'ViewContent');

Search            User performs a search                                  rdt('track', 'Search');
  
AddToCart         User adds a product to the shopping cart                rdt('track', 'AddToCart');

AddToWishlist     User adds a product to a wishlist                       rdt('track', 'AddToWishlist');

Purchase          User completes the purchase                             rdt('track', 'Purchase');

Lead              User submits information expressing interest 
                  in the advertised product/offer                         rdt('track', 'Lead');

SignUp            User completes a registration or sign up form           rdt('track', 'SignUp');

Custom (Beta)	Additional user actions outside of the predefined standard events	rdt('track', 'Custom', {customEventName:'YOUR CUSTOM EVENT HERE'});
 
  
  ==================================================
  
  
  
  
