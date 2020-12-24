# Alpine Hotwire Turbo Adapter

`alpine-hotwire-turbo-adapter` allows you to add support for Alpine.js to your Hotwire Turbo powered apps.
It handles Hotwire Turbo events to properly clean up the DOM from Alpine generated code when navigating between pages.

## Install

### From CDN

```
<script src="https://cdn.jsdelivr.net/npm/alpine-hotwire-turbo-adapter@0.1.0/dist/alpine-hotwire-turbo-adapter.min.js" defer></script> 
```

### From NPM
 Install the package
```bash
npm i alpine-hotwire-turbo-adapter
```
Include it in your script along with Alpine JS.
```javascript
import 'alpine-hotwire-turbo-adapter'
import 'alpinejs'
```
