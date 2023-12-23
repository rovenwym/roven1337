```js
class Rxven {
    constructor() {
        this.alias  = [ 'Roven', 'Shaku' ]
    }

    contact() {
        const discord  = 'rxven.69'
        const telegram = 't.me/rxven.1'
        const email    = 'rxvenskidders@proton.me'
        
        return discord, telegram, email
    }

    life() {
        const age        = 17
        const occupation = 'Student'
        const hobbies    = [ 'Programming', 'Cracking' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'Javascript (Node.js Framework)', 'Python', 'C#' ];
        const learning          = [ 'C++' ];
        const ide               = 'Visual Studio Code';

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

module.exports = Rxven
```
