## aboutMe:
```js
import { useEffect } from 'react';
import { Link } from 'react-router-dom';

function MarinaGutkevich ({frontend_developer, react_developer}) {
  
  const name = 'Marina Gutkevich';
  const profession = [frontend_developer, react_developer]; 
  const education = ('higher', 'yandex.practicum');
  const telegram = '@gutmalina';

  useEffect(() => {
    return {
        code: [Javascript, TypeScript],
        frameworks: [React, Redux],
        tools: [API, Websocket, Node.js, Express.js, MongoDB, Mongoose, Webpack, Eslint],
        architecture: [ООП, БЭМ], 
        layout: [HTML5, CSS3, adaptive, PixelPerfect, Figma],
        team: [Git, GitHub]
    }
  }, [education]);

  return (
    <body>
      <header>{`HI, MY NAME IS ${name}. I AM ${profession}`}/>
      <main><section>{'YOU WILL FIND MY WORKS IN THE REPOSITORY'}/></main>
      <footer><Link>{telegram}</Link>/>
    </body>
  )
};

export default MarinaGutkevich;
```
<p padding="0" align="center">~~~~~~~~~~</p>

## statistics: 
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gutmalina&theme=github_dark) 
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gutmalina&theme=github_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gutmalina&theme=github_dark)

<p padding="0" align="center">~~~~~~~~~~</p>
