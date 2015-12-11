# Crystal Programming Language
## Links
* crystal-lang.org
* play.crystal-lang.org
* github.com/manastech/crystal

## Notes
### Similarities to Ruby
* Syntax is similar
* Same Classes style. Can still Reopen classes to redefine them.

### Differences
* Compiled language (uses LLVM). "crystal build filename.cr -s --release"
* Standard Library (get rid of all the aliases which mean the same)
* Have to use double quotes
* 'accessor' is called 'property'
* Can do methods within parenthesis rather than use blocks (maybe less readable? But more efficient)
* Macros (like C you can configure stuff that triggers on certain builds)
* Can link C libraries
* Regex uses libPCRE

### Includes
* Has a built in testing library called "spec" which is similar to rspec

### Other Notes
* Benchmarks https://github.com/kostya/benchmarks
* Installing: brew install crystal-lang
* Distributed package manager built in
* Web framework: https://github.com/dhruvrajvanshi/Moonshine (Similar to Sinatra), https://github.com/Codcore/amethyst (Similar Rails)
* Libraries: https://crystalshards.herokuapp.com/ | https://github.com/zamith/crystalshards
