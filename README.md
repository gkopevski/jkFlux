# jkFlux
Wrapper of Flux framework for usage in any front-end framework

**Install**
```sh
npm i
webpack
```

**Usage**
```sh
import jkFlux from "../src/jkFlux";
const dispatcher = new jkFlux.Dispatcher();
dispatcher.dispatch('action:actionName', {payloadObject});
```