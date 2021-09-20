# Mozheyko Snezhana
**Junior Frontend Developer**
## Contact information:
* E-mail: mozheykosn@gmail.com
* Phone: +375(29)2973977
* Telegram: mozheyko_so
* LinkedIn: [mozheyko.snezhana](https://by.linkedin.com/in/snezhana-mozheyko-a72183131/ru)
## Summary
I have been working as a digital marketer for 4 years in marketing agency. Later I decided to study web development, firstly Java Script. I am very motivated to gain experience and become a good specialist.

I learn quickly, I can work in a team and always have many friends at work, I try to be friendly and bring a good mood. I am eager to learn, I enjoy overcoming challenges, and I have a genuine interest in business development and making projects successful.
## Skills
* HTML
* CSS
* JavaScript Basics
* Git/GitHub Basics
* Photoshop, Figma

## Code Example

**Generator of ideas "what to do for the weekend" for my friends:**

``` 
let phrases = [
{ text: 'собраться в Зеленом Попугае', image: 'https://pochemu24.ru/wp-content/uploads/2019/10/inx960x640-745771.jpg' },
{ text: 'поехать в Глубокое и кататься на танках ', image: 'https://img.ru-memorials.ru/memorials/by-vi-glub-park-t-72/by-vi-glub-park-t-72-01-1000.jpg' },
{ text: 'поехать в Поставы, чтобы увидеть самый крупный водопад в мире', image: 'https://rosegardening.org/wp-content/uploads/2018/11/2-41.jpg' },
{ text: 'чиллить на карьере в Новолукомле', image: 'https://tutby.gcdn.co/620x620s/n/02/8/122novoluk12.jpg' },
{ text: 'увидеть Мальдивское побережье в Малорите или где оно там', image: 'https://pbs.twimg.com/media/EBc6t8oXsAEKIb7.jpg:large' },
]
;

function getRandomElement(arr) {
let randIndex = Math.floor(Math.random() * arr.length);
return arr[randIndex];
}

let button = document.querySelector('.button');
let phrase = document.querySelector('.phrase');
let advice = document.querySelector('.advice');
let image = document.querySelector('.image');

button.addEventListener('click', function () {
let randomElement = getRandomElement(phrases);
smoothly(phrase, 'textContent', randomElement.text);
smoothly(image, 'src', randomElement.image); 

if (randomElement.text.length > 30) {
    advice.style.fontSize = '33px';
  } else {
    advice.style.fontSize = '42px';
  }
});
for (let i = 0; i <= 2; i = i + 1) {
smoothly(phrase, 'textContent', phrases[i].text); 
smoothly(image, 'src', phrases[i].image); 
};
```
## Courses:
«JavaScript/Front-end» -  The Rolling Scopes

## Education
Belarusian State University

## Languages
* Russian - native speaker
* English - B1-B2
* Italian - C1
* Polish - A1