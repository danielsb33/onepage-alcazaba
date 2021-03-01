$(document).ready(function() {
    $('a[href^="#"]').click(function() {
      var destino = $(this.hash);
      if (destino.length == 0) {
        destino = $('a[name="' + this.hash.substr(1) + '"]');
      }
      if (destino.length == 0) {
        destino = $('html');
      }
      $('html, body').animate({ scrollTop: destino.offset().top }, 500);
      return false;
    });

    var menu = $(".menu").html();
    $(".responsive-menu").append(menu);
    $(".responsive-menu ul").removeClass("main-menu");
    $(".responsive-menu ul").addClass("mobile-menu");
    $(".menu ul li:first-child").addClass("active");
  
    $(".menu-button").click(function() {
      var respMenu = $(".responsive-menu");
      var height = (respMenu.css("height") == "220px") ? "0px" : "220px";
      respMenu.animate({
        height: height
      }, 0);
    });

    $(".mobile-menu-icon").click(function() {
      var respMenu = $(".responsive-menu");
      var height = (respMenu.css("height") == "220px") ? "0px" : "220px";
      respMenu.animate({
        height: height
      }, 100);
    });
  
    $(".menu-button").click(function(event) {
      event.preventDefault();
      var href = $(this).attr('href');
      $('html, body').animate({
        scrollTop: scrollAmount
      }, 1000);
    });
    
  
  });

  $(document).ready(function(){
    $(".owl-carousel").owlCarousel({
      items: 1,
      loop: true,
      nav: false,
      autoplay: true,
      autoplayTimeout: 8000,
      animateOut: 'fadeOut',
      dots: false
    });
  });

