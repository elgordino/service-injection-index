# service-injection-index

Reproduction for https://github.com/emberjs/ember.js/issues/19605

It fails with the service at `app/services/repro/index.js` with this error

`Assertion Failed: Attempting to inject an unknown injection: 'service:repro'`

Move it to `app/services/repro.js` and the app will boot.