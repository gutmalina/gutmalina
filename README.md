import { useEffect } from 'react';
import { Link } from 'react-router-dom';

function MarinaGutkevich ({frontend_developer, react_developer}) {
  
  const name = 'Marina Gutkevich';
  const profession = [frontend_developer, react_developer]; 
  const education = ('higher', 'yandex.practicum');

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

  const contact = {
    email: 'gutmalina@mail.ru',
    telegram: '@gutmalina',
    hh: 'https://hh.ru/applicant/resumes/view?resume=048cbf53ff0aeb96920039ed1f463436654b46',
    linkedin: 'www.linkedin.com/in/gutmalina',
    instagram: ['https://instagram.com/gutmalina', 'https://instagram.com/gutmalina.art']
  }

  return (
    <body>
        <header>
          <h1 className="title">{`Hi, my name is ${name}. I am ${profession}`}</h1>
        </header>
        <main>
          <section>{'you will find my works in the repository'}</section>
        </main>
        <footer>
          <nav className="listContact">
            <Link>{contact.email}</Link>
            <Link>{contact.telegram}</Link>
            <Link>{contact.hh}</Link>
            <Link>{contact.linkedin}</Link>
            <Link>{contact.instagram}</Link>
          </nav>
        </footer>

    </body>
  )

};

export default MarinaGutkevich;

<!-- <h2 align="center">Привет, будем знакомиться - я Марина
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="26"/></h2>
<h3 margin="0" align="center">И я Junior Frontend developer</h3>
<p padding="0" align="center">~~~~~~~~~~</p>
 
 - :mortar_board: Закончила обучение на курсе Яндекс.Практика по направлению Frontend developer
 - :mag_right:  Во время учебы мы изучали CSS, HTML, JavaScript и базовые основы Backend разработки
 - :memo: Знакомились с Figma, GIT, GitHub, Webpack, React, MongoDB, express.js, Node.js
 - :eyes: Создавали проекты, применяя БЭМ, ООП, адаптив, API. Все проекты проходили ревью
 - :muscle:  Сейчас активно занимаюсь поиском работы, перечитываю, повторяю полученные знания, самостоятельно верстаю, решаю [задачки](https://www.codewars.com/users/gutmalina) [![codewars](https://www.codewars.com/users/gutmalina/badges/micro)](https://www.codewars.com/users/gutmalina/badges/micro)
 - :sparkles: Уверена, со временем научусь писать лаконичный и чистый код
 - :point_right: Мое резюме [на Linkedin](www.linkedin.com/in/gutmalina), [на hh.ru](https://hh.ru/applicant/resumes/view?resume=048cbf53ff0aeb96920039ed1f463436654b46), или [в формате PDF](./image/%D0%93%D1%83%D1%82%D0%BA%D0%B5%D0%B2%D0%B8%D1%87%20%D0%9C%D0%B0%D1%80%D0%B8%D0%BD%D0%B0%20%D0%98%D0%B2%D0%B0%D0%BD%D0%BE%D0%B2%D0%BD%D0%B0%20(9).pdf)
 - :dancer: В свободное время живу, люблю и дарю [йогу](https://instagram.com/gutmalina), гуляю со своей собакой и занимаюсь [рукотворчеством](https://instagram.com/gutmalina.art)
 
<p padding="0" align="center">~~~~~~~~~~</p>
 

### :hammer: Языки и инструменты: 
<p padding="0"><img src="./image/file_type_css_icon_130661.svg" height="50"/> 
<img src="./image/file_type_html_icon_130541.svg" height="50"/> 
<img src="./image/file_type_js_official_icon_130509.svg" height="50"/> 
<img src="./image/react_original_logo_icon_146374.svg" height="50"/> 
<img src="./image/file_type_vscode_icon_130084.svg" height="50"/> 
<img src="./image/webpack_original_logo_icon_146300.svg" height="48"/> 
<img src="./image/figma_logo_icon_170157.svg" height="46"/>
<img src="./image/mongodb_plain_wordmark_logo_icon_146423.svg" height="52"/>
<img src="./image/Node-JS-01.svg" height="56"/>
<img src="./image/folder_express_icon_161294.svg" height="50"/></p> -->


<p padding="0" align="center">~~~~~~~~~~</p>

### :bar_chart: Статистика: 
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gutmalina&theme=github_dark) 
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gutmalina&theme=github_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gutmalina&theme=github_dark)

<p padding="0" align="center">~~~~~~~~~~</p>
