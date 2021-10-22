# Hulu Clone with nextjs and tailwindcss

1. Install nextjs
   1. npx create-next-app
2. Install tailwindcss
   1. npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
   2. create the tailwindcss config files with npx tailwindcss init -p
   3. add the jit mode into the tailwind.config.js and add the purge directories
   4. include the tailwindcss directives into the globalcss file
3. Remove the extra code from index.js of pages folder
4. Create the Header
   1. create Header.js file inside the components folder created inside root of the project
   2. create the HeaderItem.js file inside components folder
5. Install heroicons
   1. npm install @heroicons/react
   2. implement the heroicons into the header part
6. Create Navbar
   1. create the Nav.js inside the components folder
   2. create the requests.js files inside utils folder created at the root level of project
   3. import the request and loop through and display the title of each request as the navbar links
   4. create .env.local file inside the root level of project
7. Add tailwind-scrollbar-hide
   1. require this plugin into the tailwind.config.js file into the plugin array
8. Create the Results part
   1. create the Results.js inside components
   2. get the results from the tmdb inside the home page as SSR props
   3. send to Results.js
   4. From there get the results and loop through each result and send each result to each thumbnail component
   5. create Thumbnail.js inside component folder
   6. get the result and populate
   7. add animation for each thumbnail upon page load or reload
   8. add package for thumbnail animation npm i react-flip-move
