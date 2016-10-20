## Photoswipe library wrapper for Frappe

A Frappe wrapper to the js photo library Photoswipe: https://github.com/dimsemenov/photoswipe

#### Installation

```bash
bench get-app lib_photoswipe git@github.com:DigiThinkIT/lib_photoswipe.git
bench --site [your site] install-app lib_photoswipe
```

Restart frappe and clear cache

```bash
bench restart && bench clear-cache
```

#### Usage

Right now this wrapper only loads the js, css and default skin css. You must build the gallery html skeleton and js which drives it on a per use case. Doctypes to drive galleries will be added in the future.

#### License

MIT
