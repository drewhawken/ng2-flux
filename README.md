[![dependency status](https://img.shields.io/david/mjw56/ng2-flux.svg)](https://david-dm.org/mjw56/ng2-flux)
[![devDependency Status](https://david-dm.org/mjw56/ng2-flux/dev-status.svg)](https://david-dm.org/mjw56/ng2-flux#info=devDependencies)

ng2-flux
========

## Usage:

```bash
make
```

open your browser to ```http://localhost:3000```

## About

Scrapes live NY Times data, which is fetched from server and displayed onto the UI using Angular 2 components.

Uses the flux architecture to retrieve data via actions and pipe that data through the dispatcher to a store
which then notifies the parent Angular component that it has updated data. The parent Angular component then queries
the store for this new data, and the new data is then passed the parent who then passes it to it's children.

![screen](/media/screen.gif)

## Tech Used

- [Angular 2](https://github.com/angular/angular)
- [Component Router](https://github.com/angular/router)
- [Flux](https://github.com/facebook/flux)
- [Firebase](https://www.npmjs.com/package/firebase)
- [Webpack](https://github.com/webpack/webpack)
- [FluxRecorder](https://github.com/nextminds/FluxRecorder)

## Contributing

PR's + Issues are welcome!

## TODO

- [ ] Make fetching smarter

## Thanks

Thanks to the folks at [AngularClass](https://github.com/angular-class) for the [webpack-starter](https://github.com/angular-class/angular2-webpack-starter) inspiration.

## License

MIT
