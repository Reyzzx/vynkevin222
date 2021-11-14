```TypeScript
import { contact, User, About } from './Instagram'

export default class ME implements User {
    public static firstName = 'Kevin'
    public static lastName = 'Paratama'
    public static username = 'Sneazy'
    public static website = 'https://aboutmevin.herokuapp.com'
    public static aliases = ['SNEAZY']
    public static skills = ['HTML', 'CSS', 'JavaScript', 'NodeJS', 'Python']
    public static info = {
        age: 15,
        country: 'Indonesia',
        city: 'Jakarta',
        school: 'Smp_Trimulia',
        org: null,
        likes: ['JavaScript', 'Eat_Sleep', 'PlayGame'],
        hobbies: ['Coding', 'Smoke', 'Music'],
        reach: [
            {
                name: contact.WhatsApp,
                url: 'https://wa.me/6285732415700?text=Haii Kak Vin...'
            },
            {
                name: contact.Instagram,
                url: 'https://instagram.com/ardynvyn__'
            },
            {
                name: contact.Telegarm,
                url: 'https://t.me/Sneazy'
            },
            {
                name: contact.Discord,
                url: 'VYN [ Pro ]#2931'
            },
            {
              name: contact.github,
              url: 'https://github.com/vynsneazy'
            },
            {
              name: contact.twiter,
              url: 'https://mobile.twitter.com/Ardiyan_Kevin'
            }
        ]
    }
    public static projects = [
        {
            name: 'Sneazy_Bot',
            homepage: 'https://github.com/vynsneazy',
            repo: 'https://github.com/vynsneazy/SN',
            language: ["JavaScript","Shell","Python"],
            maintanied: false
        },
        {
            name: 'api_sneazy',
            homepage: 'https://www.npmjs.com/package/lolkil-api',
            repo: 'https://github.com/LoliKillers/lolkil-api',
            lenguage: ["JavaScript", "Html", "CSS"],
            maintanied: false
         }
    ]
}
```
