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