# Dev Talent

A website was created for a fictitious HR consulting company called: devTalent.

This "fake" recruiting agency specialized in sourcing IT profiles, gave me the task of developing their site with the intention of modernizing their current online presence.


## Some of their needs as "clients" are:

- Show their services to potential companies that need to hire new Human Resources.

- Detail active job offers on the site.

- Get in touch with new Devs who are looking for a job.

- Contemplate the development of a "blog" section within the project.


## Some technical requirements for the development of the challenge:

- Good SEO practices.

- Mobile first experience

- Good site performance

- Take accessibility into account.

---

## Technologies

📝 [**Astro**](https://astro.build/) -> As main framework

📝 [**Content Collections by Astro**](https://docs.astro.build/en/guides/content-collections/) -> To manage the blog articles and the job offers section

📝 [**View Transitions by Astro**](https://docs.astro.build/en/guides/view-transitions/) 

📝 [**React**](https://react.dev/) -> As support for some interactive components

📝 [**Tailwind CSS**](https://tailwindcss.com/) -> For the styles

📝 [**Astro Icons**](https://www.astroicon.dev/) -> For icons

📝 Figma -> For layouts


---

## 🚀 Project structure 

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for .astro or .md files in the src/pages/ directory. Each page is exposed as a route based on its file name.

There's nothing special about src/components/, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the public/ directory.

---

## 🧞 Comamands

All commands are run from the root of the project, from a terminal:

| Command	| Action |
| ------- | ------ |
| npm install	| Installs dependencies |
| npm run dev	| Starts local dev server at localhost:4321 |
| npm run build	| Build your production site to ./dist/ |
| npm run preview	| Preview your build locally, before deploying |
| npm run astro ...	| Run CLI commands like astro add, astro check |
| npm run astro -- --help	| Get help using the Astro CLI |

---

## How the project was created?

`npm create astro@latest`
