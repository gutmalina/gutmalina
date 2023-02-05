## aboutMe:
```js
import { useState, useEffect } from 'react';
import { Link } from 'react-router-dom';

function MarinaGutkevich ({frontend_developer, react_developer}) {

  const [stack, setStack] = useState({});
  const name = 'Marina Gutkevich';
  const profession = [frontend_developer, react_developer]; 
  const education = ('higher', 'yandex.practicum');
  const telegram = '@gutmalina';

  useEffect(() => {
    setStack({
      code: [Javascript, TypeScript],
      frameworks: [React, Redux],
      tools: [API, Websocket, Node.js, Express.js, MongoDB, Mongoose, Webpack, Eslint],
      architecture: [ООП, БЭМ], 
      layout: [HTML5, CSS3, adaptive, PixelPerfect, Figma],
      team: [Git, GitHub]
    });
  }, [education]);

  return (
    <body>
      <header>{`HI, MY NAME IS ${name}. I AM ${profession}`}</header>
      <main>
        <section>{`MY Stack: ${stack}`}</section>
      </main>
      <footer><Link>{telegram}</Link></footer>
    </body>
  )
};

export default MarinaGutkevich;
```

## statistics: 
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gutmalina&theme=github_dark) 
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gutmalina&theme=github_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gutmalina&theme=github_dark)

