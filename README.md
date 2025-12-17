# voxelo

web replicube recreation, voxelo

link: https://qaptivator.github.io/voxelo/

# description

replicube is a fun little procedural voxel game, where using lua you make simple control flows to render out cubes (either empty or with a color). i found it cool on how it trains you to make code for every cube (kind of like an introduction to shaders), so i made my own recreation. i also had a fun time forcing myself to use vanilla js and html. alpine js was also REALLY awesome, since its basically vue but usable literally anywhere. this took me a couple of days to make, and gemini ai helped me out a lot.

play this game [here](https://qaptivator.github.io/voxelo/), or simply clone this repository and open `index.html` in your browser. *p.s. it works offline too!*

# todo

- [ ] save code to localstorage
- [ ] add small documentation tab
- [ ] add a header with the title (voxelo), tabs, link to this github repo, and so on
- [ ] maybe make a tutorial
- [ ] add a color chart below the code
- [ ] add side by side layout
- [ ] add full support for mobile
- [ ] add the cross section dragables
- [ ] add coordinates to each of the 4 axis by remaking AxesHelper from scratch
- [ ] move the Y line of the axes helper from the origin to the tip of Z axis

# credits

- [Replicube](https://store.steampowered.com/app/3401490/Replicube/) (a steam game)
- [Alpine.js](https://github.com/alpinejs/alpine) (for the awesome reactivity system)
- [Three.js](https://github.com/mrdoob/three.js) (for the 3D cube rendering part)
- [Fengari](https://github.com/fengari-lua/fengari) (for running lua fully in the browser, i used fengari-web)
- [UNPKG](https://unpkg.com/) (for giving me the `.min.js` files for the libraries, so i can make this project fully portable and able to work offline)
