### Running

Run the presentation by using the `npm start` command

### Generating PDF
Reveal.js itself has print/PDF support, but then the style is different from the real presentation.

####
Decktape seems to give nicer results. In order to run [decktape](https://github.com/astefanutti/decktape) do the following:
* `npm install decktape`
*  `./node_modules/decktape/decktape.js --size 1920x1200 reveal http://localhost:8001/ practical-security.pdf`
