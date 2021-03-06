Connect to Bexio via Curl

### Usage

#### Composer
First add the following to your `composer.json` file:
```json
"require": {
  "srag/bexiocurl": ">=0.1.0"
},
```

And run a `composer install`.

If you deliver your plugin, the plugin has it's own copy of this library and the user doesn't need to install the library.

Tip: Because of multiple autoloaders of plugins, it could be, that different versions of this library exists and suddenly your plugin use an older or a newer version of an other plugin!

So I recommand to use [srag/librariesnamespacechanger](https://packagist.org/packages/srag/librariesnamespacechanger) in your plugin.

### Requirements
* PHP >=7.0

### Adjustment suggestions
* Adjustment suggestions by pull requests
* Adjustment suggestions which are not yet worked out in detail by Jira tasks under https://jira.studer-raimann.ch/projects/LBEXIOCURL
* Bug reports under https://jira.studer-raimann.ch/projects/LBEXIOCURL
* For external users you can report it at https://plugins.studer-raimann.ch/goto.php?target=uihk_srsu_LBEXIOCURL
