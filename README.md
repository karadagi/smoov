# Running a Local Server for Your Three.js Project

If you have **Node.js** installed (which you probably do, since you used
`npm` or `npx` before), just open a terminal inside your project folder
(the one containing your `index.html`) and run:

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

Your `bundle.js`, `models/motorBike.obj`, and textures will now load
fine.
