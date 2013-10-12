What This Is
------------

Just somebody that wanted to checkout the code.


How To Run
----------

```
git clone git@github.com:STRML/Healthcare.gov-Marketplace.git
cd Healthcare.gov-Marketplace
npm install -g grunt
npm install
npm start
```

Tests
-----

There are no actual tests at this time. 


TODO
----

* ~~Redirect API calls to their actual destination so this fork works~~
* Add any missing JS/CSS from other sections of the site
* Add unit tests and TravisCI integration
* Pass JSHint (good luck)


Contributing
------------

If healthcare.gov frustrates you, please contribute! My hope is that this repository becomes large enough
to attract some real attention, not just from CGI Federal but from Health & Human Services. They have been thoroughly
embarassed by this boondoggle and with luck will be looking for a way to reform the system and save face.

See the TODO list above.

While the existing source does not pass jshint, please make sure that any contributions do (we have to start somewhere).
Unit tests would be greatly appreciated. Please place them inside the `test/` folder, prefixed by unit test framework
(qunit, jasmine). Please just make sure they pass, and feel free to use your favorite test framework. I will take care
of wiring them into Grunt and TravisCI.

Development
-----------

If you want to run without minification for development, use `grunt develop`.
