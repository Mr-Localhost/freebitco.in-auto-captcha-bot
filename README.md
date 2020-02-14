Right Click on Browser select inspect and insert the code on console area

$(document).ready(function() {
    setTimeout(function() {
        $("#play_without_captchas_button").trigger('click');
    },2000);
    setTimeout(function() {
        $("#free_play_form_button").trigger('click');
    },3000);
});
