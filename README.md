[![Keagan's GitHub stats](https://github-readme-stats.vercel.app/api?username=keygun-development)](https://github.com/keygun-development/github-readme-stats)

# Hi, I'm Keagan! 👋


## 🚀 About Me
```javascript

import User from "@muldev/vue-user-registry";

export default {
    name: 'Keagan'

    data() {
        return {
            user: new User({
                Age: 21,
                Hobbies: [
                    'Programming',
                    'Playing soccer',
                    'Going out with friends',
                    'Gaming'
                ],
                Education: 'Software Development',
                School: 'Graafschap College',
                City: 'Lichtenvoorde, Netherlands',
                Current_Job: 'Freave'
            })
        }
    },

    methods: {
        register: async function() {
            await this.user.post('/api/auth/register')
                .then(response => {
                    console.log(response)
                })
                .catch(err => {
                    console.log(err)
                })
        }
    }
}
```


## 🛠 Skills
```javascript
export default function skills() {
    return [
        'Vue',
        'Javascript',
        'JQuery',
        'HTML',
        'CSS',
        'SCSS',
        'SASS',
        'Typescript',
        'Blade',
        'PHP',
        'Laravel',
        'API',
        'JSON',
        'Firebase',
        'Tailwind',
        'Bootstrap',
        'MongoDB',
        'Webpack',
        'Mysql',
        'Node.js',
        'Composer'
    ];
};
```


## 🔗 Links
[![linkedin](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/keagan.mulder/)
