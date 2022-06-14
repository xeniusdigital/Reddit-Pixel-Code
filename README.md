# Reddit-Pixel-Code
Pixel tracking code for Reddit 


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
  
  
  
  
  
  
  
