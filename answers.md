1. Changing the picture on the page:
$('.highlight img').attr('src','https://placebear.com/g/400/400');

2. Changing the picture of the sky:
$('#left-image img').attr('src', 'http://lorempixel.com/output/abstract-q-c-325-220-3.jpg');


3. Changing the name of the "Panda The Bear"
name = "Bence Not The Bear";
$('h1.highlight').html(name);

4. Changing the Employment to Experience
var i = $('#employment .info-title i.icon-suitcase');
$('#employment .info-title').text("   Experience").prepend(i);


5. Remove the fake time-travel
$('#time-travel').parent().remove();

6. Change the color of the body
$('body').css('color','cornsilk');

7. Change the color of the .highlight class
$('.highlight').css('color','darksalmon');

8. Change the font family of h1 to monospace
$('h1').css('font-family','monospace');

9. 
