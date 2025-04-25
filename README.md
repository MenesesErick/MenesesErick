### 🌟 Hey! I’m Erick! 😊  


---

## ⭐ GitHub Stats
<table>
  <tr>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api?username=MenesesErick&theme=dark&hide_border=false&include_all_commits=true"
        alt="Github Stats"
      />
    </td>
    <td>
      <img
        align="left"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=MenesesErick&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact"
        alt="Github Stats"
      />
    </td>
  </tr>
</table>

---
 ![Streak](https://streak-stats.demolab.com/?user=MenesesErick&theme=algolia)

 ## Techs:
    
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>
 
    
```tsx
// pages/index.tsx (Next.js)
import { useEffect, useState } from 'react';

export default function Home() {
  const [message, setMessage] = useState<string>('');

  useEffect(() => {
    fetch('/api/message')
      .then(res => res.json())
      .then(data => setMessage(data.message));
  }, []);

  return <h1>{message}</h1>;
}

// pages/api/message.ts (Next.js API route)
export default function handler(req, res) {
  res.status(200).json({ message: 'João with React + Node.js magic!' });
}

```
