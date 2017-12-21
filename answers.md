1.
var image = document.querySelector(".profile-image");

image.src
"http://bitmakerlabs.github.io/panda-the-bear-js/images/self-portrait-grassbg.jpg"
image.src = "https://placebear.com/400/400"
"https://placebear.com/400/400"

2.
var x = document.querySelector("#left-image > img")
x.src = "http://www.mwendengao.com/wp-content/uploads/2016/03/Lonely-road-300x300.jpg"

3.
var banner = document.querySelector('#employment > .info-title')
banner.innerText = 'Bitmaker'

4.
var b = document.querySelector('body')
b.style.backgroundColor = 'red'

5.
change the colour of each element using the highlight class. Use a for loop to do this.

var b = querySelectorAll('.highlight')
b.forEach (function(item){
  item.style.background = 'red'
}
)

6.
Change the font family of the h1 to 'monospace'.
var c = document.querySelector('h1')
c.style.fontFamily = 'arial'

7.
Find a way to select the round icons in the sidebar and then change their colour.
var button = querySelectorAll('.action-icon-bg')
button.forEach(function(item){
   item.style.background = 'blue';});

8.
Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".
var d = document.getElementById('name')
d.placeholder = 'identify yourself'

9.
Change the placeholder attribute of the message field to "state your business".
var e = document.querySelector('textarea#message')
e.placeholder = "State your business"

10.
Give the name field a "value" attribute of "your nemesis".
var e = document.querySelector('input#name')
e.placeholder = 'the joker'

11.
Change the value attribute of the email field to "koalathebear@gmail.com".
var d = document.querySelector('input#email')
d.placeholder = 'koalathebear@gmail.com'

12.
Change the value of the submit button on the contact form to "En garde!".
var d = document.querySelector('input#submit')
d.value = 'en garde'

13.
We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).
var d = document.querySelector('input#submit')
d.disabled = true

14. We should help Panda protect their privacy by erasing their personal details from the sidebar.
var d = document.querySelectorAll(".bio-info-value")
d.forEach(function(item){
    item.innerText = ""})


Panda Part 2
1. removing time travel using jquery
$("#time-travel").parent().remove();

1. That drawing of Pikachu is really cute. Let’s duplicate it using cloneNode() and insert it at the bottom of the .portfolio-container using insertAdjacentHTML() or appendChild().

var pikachu = document.querySelector('[title="Pikachu"]')
var pika_clone = pikachu.cloneNode(false)
var pika_bottom = pika_clone.appendChild(pikachu)
for (var i = 0; i <= 10; i++){pika_bottom}

2.
var listItem = document.createElement('li');
undefined
listItem
<li>​</li>​
var leftSpan = document.createElement('span')
undefined
var lastUpdated = document.createTextNode('Page last updated on');
undefined
leftSpan.appendChild(lastUpdated)
"Page last updated on"
var rightSpan = document.createElement('span')
undefined
var date = Date();
undefined
var dateMessage = document.createTextNode(date);
undefined
rightSpan.appendChild(dateMessage);
"Wed Dec 20 2017 23:28:12 GMT-0500 (EST)"
var ul = document.querySelector('ul.bio-info');
undefined
leftSpan.className = 'bio-info-title'
"bio-info-title"
rightSpan.className = "bio-info-value bio-info-date";
"bio-info-value bio-info-date"
ul.appendChild(leftSpan); ul.appendChild(rightSpan);
<span class=​"bio-info-value bio-info-date">​Wed Dec 20 2017 23:28:12 GMT-0500 (EST)​</span>​
