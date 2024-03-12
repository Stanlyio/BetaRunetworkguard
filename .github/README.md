<h1 align="center">Бета (СУРРОГАТ)</h1>

<p align="center">
<b><i>от материнки</i></b>
<br />
<b>🌐 <a href="https://digital-defense.io/">digital-defense.io</a></b><br />
<br />
<a href="https://personal-security-checklist.as93.net"><img src="https://i.ibb.co/Rb6P6h6/shield.png" width="64" /><br /></a>
<br />
<kbd><br />👉 <a href="https://github.com/Lissy93/personal-security-checklist/blob/HEAD/CHECKLIST.md"><b>Read the Checklist</b></a> 👈<br /><br /></kbd>
<br />
</p>

<details>
    <summary><b>Contents</b></summary>
    
- [The Checklist](#the-checklist)
- [The Website](#the-website)
- [The API](#the-api)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

</details>

---

## The Checklist

You can view the full checklist in [`CHECKLIST.md`](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/CHECKLIST.md)

---

## The Website

The easiest method for consuming the checklist is via our website, at: **[digital-defense.io](https://digital-defense.io/)**

Here you can browse lists, filter by your threat model and tick items off once complete (plus, there's pretty charts to make you feel good about your progress ☺️).

<p align="center">
<img width="600" src="https://i.ibb.co/jzKn05H/digital-defense.png" />
</p>

### About
The source for the website is in [`web/`](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/web).<br />
The site is built with Qwik, using TypeScript and some components from DaisyUI.

### Developing
To run the app locally, or to make code changes, you'll need Node and Git installed.

1. Grab the code: `git@github.com:Lissy93/personal-security-checklist.git`
2. Navigate into source: `cd personal-security-checklist/web`
3. Install dependencies: `yarn`
4. Start the development server: `yarn dev`

Alternatively, just open this repo is Code Spaces, where everything is already configured and ready to go.

### Deploying
To deploy the app, follow the developing steps above, then run `yarn build.static`. You can then deploy it by copying the `dist/` directory to any CDN, web server or static hosting provider of your choice.

Alternatively, fork the repo and import into your providers dashboard. Or use the link below for an easy 1-click deploy 😉

---

## The API

We also make all the data available via a free API, which you can use however you wish.

### Usage
All endpoints are documented in our OpenAPI spec, you can view these and try them out via our [Swagger docs]().

Base: digital-defense.io/api

/api/checklists
/api/checklists/[name-or-index]
/api/checklists/[name]/[point-index]
/api/search/[searchterm]


### Developing

### Deploying

