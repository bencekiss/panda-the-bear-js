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

9. Change the background color of the round icons on the side
$('.action-icon-bg').css('background-color','yellow');
9.b. and the colors of the icons
$('.icon-envelope').css('color','black');
$('.icon-download-alt').css('color','black');

10. Change the placeholder in the name field of the contact form
$('#name').attr('placeholder','Identify Yourself!');

11. Change the value of the name field in the contact form
$('#name').attr('value','Your Nemesis wooo');

12. Change the value of the email field
$('#email').val('koalathebear@gmail.com');

13. Change the value of the submit button
$('#submit').val('En Garde!');

14. (Forgot to) change the placeholder for the message
$('#message').attr('placeholder','State your business!');

15. Disable the submit button and then enable it again
$('#submit').attr('disabled','disabled');
$('#submit').removeAttr('disabled');

16. Delete personal data
$('.bio-info-value').empty();

17. Clone pikachu to the bottom
$('#right-image img').clone().appendTo('section');

18. Clone that guy some more
for(var i = 0; i < 11; i++){ $('#right-image img').clone().appendTo('section');}

19. Add the created_at to the info table (the left span is given from the assignment article, so only the styling and the right span is there).

$(listitem).attr('class','bio-info-item');
var date = new Date();
var rightSpan = document.createElement('span');
var datecreated = document.createTextNode(date);
rightSpan.appendChild(datecreated);
listitem.appendChild(rightSpan);
$(leftSpan).attr('class','bio-info-title');
$(rightSpan).attr('class','bio-info-value');
$('.bio-info').append(listitem);
