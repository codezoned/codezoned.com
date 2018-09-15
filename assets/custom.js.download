$(function () {
  $('a[href*="#"]:not([href="#"])').click(function (e) {
    var target = $(e.target.hash);

    if (target.length) {
      $('html, body').animate({
        scrollTop: target.offset().top
      }, 1000);

      return false;
    }
  });
});