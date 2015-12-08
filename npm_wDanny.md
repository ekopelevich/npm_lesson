# npm with Danny - 2015-12-08 (TUE d0??)

### What are some reasons to use npm?
* task runner
* use existing modules
* share modules


### What is npmjs.org? (list of 2 to 3 things)
* repo of modules
* npm documentation and examples


### What are some npm commands for maintaining package dependencies?
* npm root ?
* npm bin ?
* npm install
* npm init ?
* npm remove
* npm update
* npm outdated -- look this up

### What are the benefits of Semantic Versioning?

* Distinguishing between major releases, new features and patches
* 1.X.X - Breaking API change (major)
* X.1.X - Additional API or improvement (minor)
* X.X.1 - Bugfix (patch)
* X.X.X.1 - pre-release tag (alpha)
* Minor and patch always have to be backwards compatible

#### Example: Select only versions with major version of 4
* 4
* 4.x
* 4.*
* ^4
* ^4.0
* ^4.0.0
* ~4
* >=4 <5

#### Checklist 
-[ ] Look at SemVer Check on GitHub


### What are some package.json fields?

* "name": 
* "version"
* "private"
* "scripts"
* "dependencies"
* "author"
* "license"
* "git repo"

###How do you use npm as a task runner?

* You can do built-in (test) or arbitrary (custom) tasks. 
* When you want to go outside of the built-in tasks you can create your own. You can name these tasks whatever you want, but you must use the __run__ command to set them going.

### npm install flags

* -g //global
* -S or --save //save dependency
* -D or --save-dev // save dev dependency
* -O or --save-optional //??

The only way to get dev dependencies is if you are in the dev folder and enter "npm install"

### npm list 
See all installed modules






