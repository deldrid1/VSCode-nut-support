# VSCode-Squirrel-Support

This Extension adds support for the [Squirrel Programming Language](http://www.squirrel-lang.org/) (specifically [Electric Imp flavored Squirrel](https://electricimp.com/docs/squirrel/learningsquirrel/)) and its associated .nut files.

From the author of Squirrel:
> "Squirrel is a high level imperative, object-oriented programming language, designed to be a light-weight scripting language that fits in the size, memory bandwidth, and real-time requirements of applications like video games" (or in Electric Imp's case, embedded ARM microcontrollers).

## Snippets

* **class** - class definition
* **constr** - constructor definition
* **for** - for (_initialize_; _max_; _evaluate_) { }
* **foreach** - foreach (_element_ in _collection_)
* **func** - function _name_(_args_) { }
* **if** - if (_statement_) { }
* **l** - local _variable_
* **[The Complete imp API](https://electricimp.com/docs/api/complete/)** - Up to date as of Nov 7, 2016 (impOS [Release 34](https://electricimp.com/docs/releasenotes/releases/release34/))

# Contributions
- the .tmLanguage grammar file is based off of https://github.com/electricimp/ElectricImp-Sublime with some minor fixes per https://github.com/babel/babel-sublime/commit/9c7d32faecbf53e8984d7ab743f7408032286c44	sublime-completions
- the native Squirrel snippets are originally from https://github.com/robmerrell/squirrel-tmbundle
