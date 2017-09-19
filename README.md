# Jagjeet-singh
Chapters Website:
Ans-3"title"
let h = document.querySelector('.item-page__main-title');
undefined
h 
<h1 title=​"The Glass Castle:​ A Memoir" data-a8n=​"item-page__main-title" class=​"item-page__main-title" style=​"word-wrap:​ break-word;​">​The Glass Castle: A Memoir​</h1>​
h.textContent="The transparent";
"The transparent"

Ans-4"Picture"
let cover = document.querySelector('.product-image__image--single');
undefined
cover
<img class=​"product-image__image--single" src=​"https:​/​/​dynamic.indigoimages.ca/​books/​074324754x.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=38&lang=en" data-a8n=​"product-image__image" alt=​"The Glass Castle:​ A Memoir by Jeannette Walls">​
cover.src
"https://dynamic.indigoimages.ca/books/074324754x.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=38&lang=en"
cover.src = "https://static.pexels.com/photos/46710/pexels-photo-46710.jpeg";

Ans-5"nav item"
let nav = ["I" , "Love" , "Basketball" , "because" , "of" , "kobe" , "bryant" , "the" , "greatest" , "player"];    
undefined
let n = document.querySelectorAll('[class^=top-nav__list-link]');
undefined
n
 [a.top-nav__list-link, a.top-nav__list-link--active, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link, a.top-nav__list-link]
n = Array.from(document.querySelectorAll('[class^=top-nav__list-link]'));
n.map( (navitem, idx) => navitem.textContent = n[idx]);

Ans-6"logo"
let logo = document.querySelector('[data-a8n-indigo-logo]');

 logo = document.querySelector('[data-a8n=indigo-logo]');

<a href=​"https:​/​/​www.chapters.indigo.ca/​en-ca/​?link-usage=Header%3A%20https%3A%2F%2Fwww.chapters.indigo.ca%2Fen-ca%2F" class=​"indigo-logo" data-a8n=​"indigo-logo">​…​</a>​

let ownEl = document.createElement('img');


ownEl
<img>​
ownEl.src = 'https://i.pinimg.com/736x/65/a5/65/65a565ca06d684e63a5be65132f05c69--music-logo-logo-development.jpg';
"https://i.pinimg.com/736x/65/a5/65/65a565ca06d684e63a5be65132f05c69--music-logo-logo-development.jpg"
ownEl
let oldEl = document.querySelector('[data-a8n=indigo-logo] svg');

undefined
oldEl
<svg xmlns=​"http:​/​/​www.w3.org/​2000/​svg" width=​"130" height=​"66" viewBox=​"0 0 130 66">​…​</svg>​
logo.replaceChild(ownEl, oldEl);
<svg xmlns=​"http:​/​/​www.w3.org/​2000/​svg" width=​"130" height=​"66" viewBox=​"0 0 130 66">​…​</svg>​

"ans-7"
let foods = {'price':'$5', 'weight': '2kg', 'location': 'barrie'};
undefined
bv-primary.js:74 scout-to-render: 3654ms
foods
{price: "$5", weight: "2kg", location: "barrie"}
let some_html = '<ul> <li> asd</li> <li> qwer </li> <li> zxcvc </li> </ul>';
undefined
let section = document.getElementById('item-page__item-purchase-container');
undefined
section
<section class=​"item-purchase__container" id=​"item-page__item-purchase-container" aria-labelledby=​"product-purchase-label" data-a8n=​"item-purchase-container">​…​</section>​
section.innerHTML = some_html;
function render(obj) {
   let snippet = `
   <ul>
    <li>${obj.name}</li>
    <li>${obj.calories}</li>
    <li>${obj.taste}</li>
   </ul>
   `;

	node.innerHTML = snippet;
}
render(object)
VM10230:12 Uncaught ReferenceError: object is not defined
    at <anonymous>:12:8
(anonymous) @ VM10230:12
function render(obj) {
   let some_html = `
   <ul>
    <li>${obj.name}</li>
    <li>${obj.calories}</li>
    <li>${obj.taste}</li>
   </ul>
   `
return some_html;
}

undefined
render
ƒ render(obj) {
   let some_html = `
   <ul>
    <li>${obj.name}</li>
    <li>${obj.calories}</li>
    <li>${obj.taste}</li>
   </ul>
   `
return some_html;
}
render (foods)
section.innerHTML = render (foods);


Ans-9
let ko = document.querySelector(".product-image__image--single");


console.log(ko.src);'https://dynamic.indigoimages.ca/books/074324754x.jpg?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=38&lang=en'?altimages=false&scaleup=true&maxheight=515&width=380&quality=85&sale=37&lang=en
undefined
a.setAttribute('title', 'beautiful');


ko.setAttribute('title', 'georgiancollege');

Ans-10
let button =document.getElementById("add-to-cart-button");

bv-primary.js:74 scout-to-render: 3650ms
btn
<button type=?"button" id=?"add-to-cart-button" data-a8n=?"item-page__button-add-to-cart" class=?"common-button add-to-cart-button__primary ">?add to cart?</button>?
btn.addEventListener('click',function(){document.documentElement.innerHTML-" ";});
