# LearningCourses

### Setup instruction

1. Clone the project
`````
git@github.com:Arunpandey73/LearningCourse.git

``````
2. Move into the directory

```````
cd LearningCourse

````````

3. Install dependencies

``````
npm i

``````

4. run the server

```````````
npm run dev

```````````

### Setup instruction for tailwind

[Tailwind official instruction doc](https://v3.tailwindcss.com/docs/installation)

1. Install tailwindcss

``````````
npm install -D tailwindcss@3

``````````

2. Create tailwind config file

`````````
npx tailwindcss init

``````````

3. Add file extensions to tailwind config file in the contents propary

```````````
"./src/**/*.{html,js,jsx,ts,,tsx}"

```````````

4. Add the Tailwind directives at the top the `index.css` file

`````````````
@tailwind base;
@tailwind components;
@tailwind utilities;

````````````````

### Adding plugins and dependencies

````````````````````

npm i @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp

````````````````````

### Configure auto import sort eslin

1. Install simple import sort

```````````````````
npm i eslint-plugin-simple-import-sort

````````````````````

2. Add rule in `.eslint.cjs`

````````````````
'simple-import-sort/imports':'error'

`````````````````
3. Add simple import sort plugin in `.eslint.cjs`

```````````
plugins: [..., 'simple-import-sort']

``````````

4. To enable auto import sort on file save in vsCode

  - Open `Setting.json`
  - add the following config

  `````````````````
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  }

  ```````````````````

  