# service-injection-index

Reproduction for https://github.com/emberjs/ember.js/issues/19605

With the service repro at app/services/repro/index.js this message seen

`Assertion Failed: Attempting to inject an unknown injection: 'service:repro'`

Renaming this to `app/services/repro.js` works.