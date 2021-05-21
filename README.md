
# ResuMe Nuxt + i18n (Multilanguage) ✨🌍

![locates](./documentation/ResumeLogo.png)

An easy way to **build** you own personal web resume! 💪
### [Check the Demo 💾](https://ivangreve.com/)

## Pre-Requisites 

- Install [NodeJS](https://nodejs.org/es/)


##  How to start? 🥳
1) **Clone** the **repository**
2) **Install** dependencies:
  - `$ npm install`
3) **Build** application:
  - `$ npm run build`
4) **Run** in **dev mode**:
  - `$ npm run dev`


## Configuration ⚙

***You can easily customize the template and the languages!*** 🚀
- To do this, you have to **edit** the **locales** files as you want! 📄

![locates](./documentation/localefiles.jpg)

### Languages Files 🌍
**English**: `./locales/en.json`

**Spanish** `./locales/es.json`

### Add new Language
1) **Create** a new language file in the folder `./locales` :
- **eg.** : `fr.json`

3) You can easily change the actual language by following way:
```html
<div>
	<nuxt-link class="btn btn-light" :to="switchLocalePath('en')">EN</nuxt-link>
	<nuxt-link class="btn btn-light" :to="switchLocalePath('es')">ES</nuxt-link>
	<nuxt-link class="btn btn-light" :to="switchLocalePath('fr')">FR</nuxt-link>
</div>
```

##  Generate static code 🥳
1) In the **root** folder, run the following command:
- `$ npm run generate`
2) All the **generated** code will be apear in the `./dist` folder.

