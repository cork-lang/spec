# spec
A description and specification for the Cork programming language.

# Why a new Programming Language?
*Groan*.
How many more of these things do we need? Personally, I thought
that Google's [Dart](https://dartlang.org) had solved all of my
problems. It is a single language that I can use on both the client and
server. Hooray, right?

Unfortunately, there are several problems with Dart.

First and foremost, it was originally designed to completely replace
JavaScript, and a lot of the language design decisions were made with that
goal in mind. This means that until recently, Dart had no *real* type
system, although type annotations combined with static analysis made
development more productive.

Another thing is that although Dart is capable of running on the server
side, server-side Dart really has not gotten any love from Google. I don't
think that it ever will. There is *huge* potential for using the same
language throughout your entire Web stack, and I really don't understand
why that's not pushed harder. Dart full-stack is *far* preferable to
JavaScript full-stack. It's not even debatable.

Dart also lacks any sort of built-in serialization to/from Dart types to
raw data formats, such as JSON. JavaScript does not have this problem,
because it is reflective by nature. However, the lack of convenient solutions
means more boilerplate code when starting a Dart project.

Perhaps the most important problem is that the direction of Dart's
development is entirely swayed by Google's needs. This is great if you
work for Google, but most of us do not. It is hard to push Dart to the rest
of the community, when to the outside world, it for the most seems like
a Google-centric project. Of course, I still have the highest of hopes for
Dart. Hopefully Dart 2.0 will come around to change all the above complaints,
and render Cork obsolete. But until then...

# What is Cork?
Cork is a statically-typed language that can compile to JavaScript, or run on the server
side. Just like in Dart, Cork can be tree-shaken before compilation.

Cork supports the following:
* Incremental Compilation
* Hot Reloading
* Highly Modular
* Object-oriented
* Serialization

Cork aims to be more lightweight than Dart, so that compilation to JavaScript will be much
faster.

It should also be easy to incorporate existing JavaScript or Dart code.

# Specification
Proceed to the [next page](spec/README.md).