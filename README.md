# Schema v.34
Övergripande planering för veckan

##### TypeScript, vecka 2 av 5 (Next.js/React)

## 🎯 Mål för veckan
Efter denna vecka ska du:
1.  Förstå vad ett API är och skillnaderna mellan Rest och GraphQl
2.  Använda Fetch API i next.js
3.  Kunna använda searchParams i next.js
4.  Kunna implementera grundläggande felhantering i en next.js app
    * Kunna göra en try/catch på ett api anrop och följande json() som loggar ett fel
    * Kasta fel från en catch som bubblar upp till en error.tsx fil i din route
    * Göra en notFound() eller redirect när status inte är ok eller om status är 404
    * Testa om datan som du hämtat stämmer med vad du förväntar dig genom att testa om t ex data.id finns eller dylikt, samt hantera om den inte stämmer
    * Göra conditional rendering där du använder && eller ternary för att rendera ut olika tsx beroende på om datan finns eller ej


## 📚 Material
* [Futurama API](https://futuramaapi.com/)
* [Swapi GrapQl](https://graphql.org/swapi-graphql)
* [![Rest vs GraphQl](https://github.com/user-attachments/assets/3702ba6d-5661-4c4d-b71b-e6d5e870c1bf)](https://blog.devops.dev/graphql-vs-rest-navigating-the-evolving-landscape-of-api-design-f543c2038dd1)
* [![Rest vs GraphQl](https://assets.bytebytego.com/diagrams/0036-rest-vs-graphql.png)](https://bytebytego.com/guides/rest-api-vs-graphql/)

### E‑Learning
* [Next.js 14: Foundations (Pluralsight)](https://app.pluralsight.com/library/courses/nextjs-13-fundamentals/table-of-contents)

### YouTube


### Läsning
* [GraphQL vs. REST: A Quick Guide](https://www.cosmicjs.com/blog/graphql-vs-rest-a-quick-guide)
* [GraphQL vs. REST (Postman)](https://blog.postman.com/graphql-vs-rest/)
* Frivilligt om ni vill lära er mer om GrapQl [GraphQL queries](https://graphql.org/learn/queries/)
* [Fetching Data](https://nextjs.org/docs/app/getting-started/fetching-data)
* [Using the Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
* [Rendering with search params](https://nextjs.org/docs/app/getting-started/layouts-and-pages#rendering-with-search-params)
* [Error Handling](https://nextjs.org/docs/app/getting-started/error-handling)

## 🛠️ Övningar
Frivilligt! Här är några förslag till längre tutorials som ni kan följa i helhet eller bara i delar för inspiration. Ta gärna en om ni är lite vilsna eller bara vill testa något nytt.
* [Build A Next.js SaaS From Scratch (ByteGrad)](https://www.youtube.com/watch?v=ERGkwdyjtcM)
* [Next.js Full Stack SaaS Real Estate App | Complete Guide (Sakura Dev)](https://www.youtube.com/watch?v=DEhgtpMxuOQ&list=PLhnVDNT5zYN9ej5u4ftvLYtebI2xVTTyx)
* [Build A Course Platform LMS With Next.js 15, React 19, Stripe, Drizzle, Shadcn, Postgres (Web Dev Simplified)](https://www.youtube.com/watch?v=OAyQ3Wyyzfg)
* [Build a Complete E-Commerce Shop with Next.js 14, Tailwind, React | Full Course 2024 (Josh Tried Coding)](https://www.youtube.com/watch?v=SG82Aqcaaa0)

## 📑 Lektionsrepon
* **Måndag** (Robert) - **APIer:** Olika APier (Rest, GraphQl) teori + demo med webbgränssnitt och ev lite kod demo (post/get)
* **Tisdag** (Robert) - **Repetition:** Måsvingar när, statisk och dynamisk routing (exempel på slugs, demo på intercept routes), props + params, destructuring (nestad), Promise 1
* **Onsdag** (Robert) - **Repetition:** Async/Promise 2 + felhantering del 1, kombinera och transformera data, planeringen framåt
* **Torsdag** (Robert) - **searchParams** (i server) och url state management grund (ev fetch med användning av searchparams)
* **[Fredag]()** (Robert) - **Code review** 
