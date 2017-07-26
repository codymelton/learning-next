Left off at https://learnnextjs.com/excel/static-html-export

To create a Next.js project create the directory of the project.

yarn add react react-dom next express

add the following in your package.json:

"scripts": {
  "dev": "next"
},

make  a pages directory in your root directory

inside that directory add an index.js file.  

add...

const Index =  () => (
  <div>
    <p>Hello from index.</p>
  </div>
)

in terminal run yarn run dev

Localhost:3000 should now work.

^^^STYLE^^^
When using the Link component in next styling must be done inline with the underlying component.
When using link you can place anything inside of it as long as it accepts and onClick prop.

^^^Directory structure^^^
only required directory is the pages directory in root.  Components directory can
be named whatever you would like.  You can create a component inside the pages directory if it needs a direct URL.
