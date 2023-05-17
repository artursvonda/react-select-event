## 1.0.0 (2023-05-17)


### ⚠ BREAKING CHANGES

* - `create`'s third parameter has been moved to a `config` object.
  `selectEvent.create(input, "value", /Generate/)` needs to be updated
  to: `selectEvent.create(input, "value", { createOptionText: /Generate/ })`.

### Bug Fixes

* update spelling of license file ([0bd5ba2](https://github.com/lokalise/react-select-event/commit/0bd5ba2da98065a438dcde2f8f946f295d6190f5))


* [BREAKING] Add support for dropdowns rendered in a portal ([17ac6b3](https://github.com/lokalise/react-select-event/commit/17ac6b3cc2f5f9b95eeed1dab647014bd8aa2ffa))


### Code Refactors

* add automatic release ([#1](https://github.com/lokalise/react-select-event/issues/1)) ([c3343ae](https://github.com/lokalise/react-select-event/commit/c3343aeed552127d4039a81f40fd230f0a8ccda6))
