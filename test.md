#General Guidelines

##File and Directory names
- Hyphenated lowercase (spinal-case)

###Exceptions
- node modules: snakecase (eg. node_modules)
- bower components: snakecase (eg. bower_components)

## Directory Structure
- `.gitignore`
- LICENSE`
- `README.md`
- `Procfile` //Heroku
- `web.js` //Heroku
- `package.json` //Node
- `/docs`
 - `/standard-guidelines`
  - // our standard guidelines (coding, style) across all repos
 - `/custom-guidelines`
  - // guidelines for a specific repo
 - `/challenge-guidelines`
  - // custom guidelines specific for a challenge
- `/node_modules`
 - // dependent node modules
- `/client`
 - //Example page
 - `/manage-challenge`
  - `bower.json`
  - `index.html`
  - `/css`
   - //page specific css
  - `/data`
   - //local files
  - `/img`
   - //non-agent specific images should be directly under /img
   - `/desktop`
   - `/mobile`
   - `/tablet`
  - `/js`
   - `app.js` //module definition and primary entry point 
   - `/controllers`
   - `/directives`
   - `/services`
  - `/templates`
   - // angular template html files

- `/server`
 - // TODO
