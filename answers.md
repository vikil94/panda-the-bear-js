1.

var profileImage = document.querySelector('.profile-image')
profileImage.src = "https://placebear.com/200/300"

2. 

var skyImage = document.querySelector('#left-image')
var image = skyImage.querySelector('img')
image.src = 'https://placebear.com/200/300'

3. 

var header = document.querySelector('section')
var title = header.querySelector('.highlight')
title.innerText = "Vikil"

4.

var employment = document.querySelector('div #employment')
var title = employment.querySelector('.info-title')
title.innerText = "Hello"

5.

var body = document.body
body.style.backgroundColor = "red"
"red"

6.

var highlight = document.querySelectorAll('.highlight')
for (var i = 0; i <= highlight.length; i++) {
    var item = highlight[i]; item.style.color = "red";
    }

7. 

var h1 = document.querySelector('h1')
undefined
h1.style.fontFamily = "monospace"
"monospace"


8. 

var round = document.querySelector('.action-container')
undefined
round.style.backgroundColor = "red";
"red"

9. 

var form = document.querySelector('form')
undefined
var input = form.querySelector('#name')
undefined
input.placeholder = "identify yourself"
"identify yourself"

10. 

var form = document.querySelector('form')
var message = form.querySelector('#message')
undefined
message.placeholder = "state your business"

11. 

var email = form.querySelector('#email')
undefined
email.placeholder = "koalathebear@gmail.com"

12. 

var submit = form.querySelector('#submit')
undefined
submit.value = "En Garde!"
"En Garde!"

13. 

submit.disabled = true;
true

14.

var aside = document.querySelector('aside')
var info = aside.querySelector('.bio-info')
aside.removeChild(info)


PART 2


1. 

var div = document.querySelector('#time-travel')
var title = div.querySelector('.bar-title')
div.removeChild(title)

2.

var div = document.querySelector('#right-image')
var image = div.querySelector('img')
var container = document.querySelector('.portfolio-container')
var image1 = div.cloneNode(image)
container.appendChild(image1)

3. 

const listItem = document.createElement('li');
undefined
const leftSpan = document.createElement('span');


undefined
var lastUpdated = document.createTextNode('Page last updated on');


undefined
leftSpan.appendChild(lastUpdated);


"Page last updated on"
listItem.appendChild(leftSpan);


<span>​Page last updated on​</span>​
const rightSpan = document.createElement('span');
undefined
var updatedInfo = document.createTextNode(Date());
undefined
rightSpan.appendChild(updatedInfo)
"Today"
listItem.appendChild(rightSpan);


<span>​Today​</span>​
var ul = document.querySelector('.bio-info')
undefined
ul.appendChild(listItem)