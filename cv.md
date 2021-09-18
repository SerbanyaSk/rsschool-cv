# Sergey Kondratyuk

---

## My contacts

- **Telegram:** https://t.me/SerbanyaSk
- **Discord:** SerbanyaSk#8303
- **VK:** https://vk.com/serbanyask
- **Email:** serbanya.sk@gmail.com

---

### About Me

I am best able to work with symbolic systems, so I am a musician and a novice web developer. I am unhurried, calm and patient, which allows me to work with monotonous tasks. However, I do not tolerate monotonous tasks that can be automated, I like a responsive interface, a beautiful design, and I believe that every project in the world should have its own website.

> Everything seems complicated until it becomes easy.

---

### Skills

I'm learning the basics:

- HTML5 & CSS3
- JavaScript
- PHP & MySQL
- Git \* GitHub

I am well acquainted with **Visual Basic for Applications**.

---

### My code example

My solution to the problem **Handshake problem** on the site Сodewars.

Description:
_Johnny is a farmer and he annually holds a beet farmers convention "Drop the beet".
Every year he takes photos of farmers handshaking. Johnny knows that no two farmers handshake more than once. He also knows that some of the possible handshake combinations may not happen.
However, Johnny would like to know the minimal amount of people that participated this year just by counting all the handshakes.
Help Johnny by writing a function, that takes the amount of handshakes and returns the minimal amount of people needed to perform these handshakes (a pair of farmers handshake only once)._

```js
function getParticipants(handshakes) {
  let people = 1;
  let numberHandshakes = 0;
  let i = 1;
  while (true) {
    while (i != people) {
      numberHandshakes += people - i;
      i++;
    }
    if (numberHandshakes >= handshakes) break;
    people++;
    numberHandshakes = 0;
    i = 1;
  }
  return people;
}
```

---

### My education

- Technical school specializing in **software development**
- All intensive **HTML & CSS** courses https://webref.ru/
- **JavaScript**: _JavaScript for children. Self-help guide on programming_ and i'm studying https://learn.javascript.ru/
- More than 10 thousand lines of code when solving tasks on automation of document flow in the enterprise using Visual Basic for Applications(currently successfully used)
- currently in the process of RS Schools Course "JavaScript/Front-end"

---

### Knowledge of languages

- Russian: native
- Ukrainian: second native
- English Basic User (Elementary English)
