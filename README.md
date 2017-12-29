# Minimal React Boilerplate
## How to set up locally
### Production build
1. Clone the repo
```shell
git clone https://github.com/prajapati-parth/minimal-react-boilerplate.git
```
2. Install dependencies
```shell
cd minimal-react-boilerplate
npm install
```
3. Build output bundle
```
npm run build
```
4. Open `index.html` in browser
### Development build
1. Follow steps 1 and 2 from above.
2. Change script `src` in `index.html`
```html
<script src="./bundle.js" type="text/javascript"></script>
```
3. Start `webpack-dev-server` for live reload
```
npm run dev
```
4. Browse `http://localhost:9000`