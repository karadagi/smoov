# Running a Local Server

If you have **Node.js** installed, just open a terminal inside your project folder
(the one containing `index.html`) and run:

``` bash
npx http-server .
```

------------------------------------------------------------------------

Or if that package isn't installed yet:

``` bash
npm install -g http-server
http-server .
```

------------------------------------------------------------------------

Then open the URL it prints --- usually:

👉 <http://127.0.0.1:8080> or <http://localhost:8080>

`bundle.js`, `models/motorBike.obj`, and textures will now load fine.
