v1.0.2, 2016-04-26 ([changes](https://github.com/sparkapi/sparkql/compare/v1.0.1...v1.0.2))
-------------------
  * [IMPROVEMENT] Support for new range() function for character ranges

v1.0.1, 2016-02-24 ([changes](https://github.com/sparkapi/sparkql/compare/v1.0.0...v1.0.1))
-------------------
  * [IMPROVEMENT] Support scientific notation for floating point numbers

v1.0.0, 2016-02-11 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.23...v1.0.0))
-------------------
  * [IMPROVEMENT] function support for fields (delayed resolution). Backing systems must
    implement necessary function behaviour.
  * Drop support for ruby 1.8.7. Georuby dropped support several years back and
    this drop allows us to pick up newer update allows us to stay in sync with
    that gems development

v0.3.24, 2016-01-05 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.23...v0.3.24))
-------------------

  * [BUGFIX] Support opening Not operator for "Not (Not ...)" expressions.

v0.3.23, 2015-10-09 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.22...v0.3.23))
-------------------

  * [IMPROVEMENT] Add regex function for character types

v0.3.22, 2015-10-09 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.21...v0.3.22))
-------------------

  * [IMPROVEMENT] Record sparkql and nested errors for fields that embed sparkql

v0.3.21, 2015-09-24 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.20...v0.3.21))
-------------------

  * [IMPROVEMENT] Record token index and current token in lexer, for error reporting

v0.3.20, 2015-04-14 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.18...v0.3.20))
-------------------

  * [BUGFIX] Allow seconds for ISO-8601

v0.3.18, 2015-04-10 ([changes](https://github.com/sparkapi/sparkql/compare/v0.3.17...v0.3.18))
-------------------

  * [BUGFIX] Better support for ISO-8601
