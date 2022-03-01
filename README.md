<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="100" src="https://vuejs.org/images/logo.png" alt="Vue logo"></a></p>
<h1 align="center" id="heading">Window Configurator</h1>

> This application is created to prove development skills. It implements a simple window configurator where you can customize product base on dimensions and price.

<p align="center">
  <br>
  <img alt="heading_logo" src="https://i.ibb.co/R6RvBvd/274728408-680107833427640-4031198912208846499-n.png" width="600" />
</p>

## Table of Contents
* [1. Build Setup](#1-build-setup)
* [2. Features](#2-features)
* [3. Other informatioons](#3-other-information)
* [4. Todo](#4-todo)

## 1. Build Setup

``` bash
# install dependencies
npm install

# serve with vue-cli at localhost:8080
npm run serve

# build for production with minification
npm run build

```

## 2. Features

- Form with inputs that takes customer preferences
  - Price per square meter
  - Width
  - Height
  - Wall (background) color
- Visualization
  - It's rendering background in chosen color
  - Auto refresh
  - Random image from Pexels api
  - Adjust window size to chosen dimensions
  - Ability to export visualization to png file
- Computed price 
    - base on customer input it counts total price
    - auto refresh on change

## 3. Used technologies
- Vue 2
- Axios
- Vue-konva
- Vuetify
- Sass
- JavaScript

## 4. TODO

- [ ] Limitation that not allows to set width of window more than wall - 50cm
- [ ] Fix exporting visualisation to png (to base)
- [ ] Create button that opens dialog with contact form
- [ ] App state saved in local storage
- [ ] Button - clear storage
- [ ] Image expand, should uncover on changing width
- [x] Add in readme section about used technologies
