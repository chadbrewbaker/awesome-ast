# Awesome AST#
A curated list of tools for Abstract Syntax Tree processing.



## Contents ##




#Specific Languages
* [Bash](#bash)
* [C/C++](#c/c++)
* [CSharp](#csharp)
* [CSV](#csv)
* [English](*english)
* [Go](#go)
* [Generic](#generic)
* [Java](#java)
* [Javascript](#javascript)
* [JSON](#json)
* [PHP](#php)
* [Python](#python)
* [Haskell](#haskell)
<!--- * [R](#) -->
* [Scala](#scala)
* [SMT-LIB](#smt-lib)
* [SQL](#sql)
* [XML/HTML](#xml/html)


## Bash ##
https://github.com/idank/bashlex
## C/C++ ##
http://clang.llvm.org/docs/LibASTMatchersReference.html?
http://stackoverflow.com/questions/18560019/how-to-view-clang-ast
~~~bash
clang -emit-ast hello.c  #binary output to hello.ast
clang-check -ast-dump hello.c
~~~
[Clang AST Matchers](http://clang.llvm.org/docs/LibASTMatchersReference.html)



## CSharp ##
[Roslyn HOWTO](http://blog.ptsecurity.com/2016/06/theory-and-practice-of-source-code.html)

## CSV ##
[Papa Parse](http://papaparse.co)m

## English ##
[write-good (javascript)](https://github.com/btford/write-good)

[NLTK (Python)](http://www.nltk.org)

## Excel ##

## Haskell ##
[haskell-tools-ast](https://hackage.haskell.org/package/haskell-tools-ast)
[haskell-src-exts](https://hackage.haskell.org/package/haskell-src-exts-1.18.0)
[GHC API](https://ghc.haskell.org/trac/ghc/wiki/GhcApi)
[GHC tutorial](http://www.stephendiehl.com/posts/ghc_02.html)
[ghc-dump-tree](https://github.com/edsko/ghc-dump-tree)
[ghc-viz](http://felsin9.de/nnis/ghc-vis/#basic-usage)
[prof2dot](https://hackage.haskell.org/package/prof2dot)
[Glance](https://github.com/rgleichman/glance)

## Generic ##
[Atomist rug](https://github.com/atomist/rug)
[ANTLR](http://www.antlr.org)
[ANTLR command line](https://theantlrguy.atlassian.net/wiki/pages/viewpage.action?pageId=2687267)

[Bison](http://savannah.gnu.org/projects/bison/)
[Flex](https://www.gnu.org/software/flex/)


[Nom Parser Combinator](https://github.com/Geal/nom)

[Treetop](https://github.com/nathansobo/treetop/tree/master)
[Tree Sitter](https://tree-sitter.github.io/tree-sitter/)
[Tree Sitter Talk](https://www.youtube.com/watch?v=0CGzC_iss-8)



[JetBrainst GrammarKit](https://plugins.jetbrains.com/idea/plugin/6606-grammar-kit)

[Gramtest BNF generator](https://github.com/codelion/gramtest)
[Rubular Ruby Regexp](http://rubular.com)
[Mr Data Converter CSV,JSON,Excel,..](https://shancarter.github.io/mr-data-converter/)

[Hammer secure parser generator](https://github.com/UpstandingHackers/hammer)
[Parsing Expression Grammar Template Library](https://github.com/taocpp/PEGTL)

## Go ##
[ast](https://golang.org/pkg/go/ast/)






## Java ##

* [javaparser](https://github.com/javaparser/javaparser)
* [Spoon](https://github.com/INRIA/spoon)
* [Apache Commons-lang](https://commons.apache.org/proper/commons-lang/)
* [JetBrains JDKLangTools](https://github.com/JetBrains/jdk8u_langtools/blob/master/src/share/sample/javac/processing/src/CheckNamesProcessor.java)
* [JetBrains uast](https://github.com/JetBrains/uast)
* [JetBrains IntelliJ](https://github.com/JetBrains/intellij-community)
* [JetBrains IntelliJ Plugin HOWTO](http://www.jetbrains.org/display/IJOS/Writing+Plug-ins)




## Javascript ##
[ESPrima](http://esprima.org)
[uglifyjs parser](http://lisperator.net/uglifyjs/parser)
[Babel](https://github.com/babel/babel)
[Recast](https://github.com/benjamn/recast)

## JSON ##
[ast-match](https://www.npmjs.com/package/ast-match)
[Rapid JSON](https://github.com/Tencent/rapidjson)
[sajson](https://github.com/chadaustin/sajson)



## Python  ##
[ast](https://docs.python.org/2/library/ast.html)
[python-skeletons](https://github.com/JetBrains/python-skeletons)

## Ruby ##
~~~bash
ruby --dump parsetree foo.rb
ruby --dump insns foo.rb
~~~
~~~ruby
RubyVM::InstructionSequence
~~~
[ruby\_parser](https://github.com/seattlerb/ruby_parser)
[sorerer](https://github.com/jimweirich/sorcerer)


## Scala ##
[scalac](http://lampsvn.epfl.ch/trac/scala/browser/scala/trunk/src/compiler/scala/tools/nsc/ast/parser)
[Scala AST reference](https://github.com/wolfe-pack/wolfe/wiki/Scala-AST-reference)

## SMT-LIB ##
[smt-lib (Haskell)](http://hackage.haskell.org/package/smt-lib)
[sbv (Haskell)](http://leventerkok.github.io/sbv/)
[smt-kit](http://ahorn.github.io/smt-kit/)
[nsolv](https://github.com/delcypher/nsolv)
[ddsmt](http://fmv.jku.at/ddsmt/)

## SQL ##
https://github.com/codeschool/sqlite-parser
https://github.com/lfittl/pg_query



## XML/HTML ##
nokogiri
xslt

## Talks ##
[Polyhedral Analysis](http://www.pollylabs.org/education.html)
[Hiking Through The Javascript Forest](https://channel9.msdn.com/Blogs/seattlejs/2016-01-14-02)
[The Hidden Benefits of Static Analysis](https://www.youtube.com/watch?v=3ZqTvexCtZM)
[ASTs for Beginners](https://www.youtube.com/watch?v=CFQBHy8RCpg)
