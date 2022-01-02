# Aleksandra Khrapkova
Front-end Developer
## About me:
Hi, my name is Alexandra and I'm a junior front-end developer. My goal is to become a professional full-stack Javascript developer. I want to create cool websites, web and mobile apps with WOW effect! I love complex tasks, constantly working on myself, strive to gain new knowledge and perfection in my profession.

## Contacts info:
* Location: Russia, Arkhangelsk
* Email: axi83@mail.ru
* Telegram: [@magicwebdev](https://telegram.me/magicwebdev)
* Discord: magicwebdev#4653
* GitHub: [magicwebdev](https://github.com/magicwebdev)

## Education:
Northern (Arctic) Federal University named after M.V. Lomonosov (NArFU)
Еngineer in the specialty "Information systems and technologies"
## English:
А2 (Pre-Intermediate)
## Experience:
2010 - 2011
Programmer at the NArFU Software Implementation and Development Laboratory

2012 - Present
Freelancer
## Skills:
* HTML&CSS;
* JavaScript;
* C#;
* SQL;
* Figma.

## Code example:
```javascript
function checkCookies(){
    let cookieDate = localStorage.getItem('cookieDate');
    let cookieNotification = document.querySelector('.cookie');
    let cookieBtn = cookieNotification.querySelector('.cookie__btn');

    if( !cookieDate || (+cookieDate + 31536000000) < Date.now() ){
        setTimeout(function () {
          cookieNotification.classList.add('show');
        }, 10000);
    }

    cookieBtn.addEventListener('click', function(){
        localStorage.setItem( 'cookieDate', Date.now() );
        cookieNotification.classList.remove('show');
    })
  }
checkCookies();
```
## Projects:
* [DesignVisions](https://designvisions.ru/)
* [Фирма Репетитор](https://xn--80akajdusffcfvbr.xn--p1ai/)
