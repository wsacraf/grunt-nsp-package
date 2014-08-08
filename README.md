# grunt-nsp-package

Audits your package.json file against the nodesecurity.io API for validation that dependencies or dependencies of dependencies are not vulnerable to known vulnerabilities.

# Installation

    $ npm install grunt-nsp-package --save-dev

# Usage

Add this line to your project's grunt.js gruntfile:
```js
grunt.loadNpmTasks('grunt-nsp-package');
```

Then use the task `validate-package` build tasks eg.
```js
grunt.registerTask("default", 'validate-package');
```

# License

MIT

# Badges

[![Build Status](https://secure.travis-ci.org/nodesecurity/grunt-nsp-package.svg)](http://travis-ci.org/nodesecurity/grunt-nsp-package)
[![Dependency Status](https://david-dm.org/nodesecurity/grunt-nsp-package.png)](https://david-dm.org/nodesecurity/grunt-nsp-package)
