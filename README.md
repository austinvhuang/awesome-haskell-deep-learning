# Awesome Haskell Deep Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/avctrh/awesome-haskell-deep-learning)

In the tradition of "awesome" (curated) lists, this is a list of references and code for doing deep learning (and adjacent/related topics) in Haskell.

- 2019 | [A Functional Reboot for Deep Learning (BOB 2019 Talk)](https://github.com/conal/talk-2018-deep-learning-rebooted) | Conal Elliott

- 2019 | [Keynote: Automatic Diferentiation for Dummies (talk)](https://www.youtube.com/watch?v=FtnkqIsfNQc) | Simon Peyton Jones

- 2018 | [NPFL Numerical Programming in Functional Languages (ICFP Session) 2018 Playlist](https://www.youtube.com/watch?v=0SUvyhbFjeg&list=PLnqUlCo055hWb33k7lJ16TZpG6ZYTOmWj) | Multiple Presenters

- 2018 | [Not-o-matic Differentiation](https://ajknapp.github.io/2018/08/14/notomatic-differentiation.html) | Andrew Knapp

- 2018 | [Hasktorch v0.0.1](https://medium.com/@stites/hasktorch-v0-0-1-28d9ab270f3f) | Sam Stites

- 2018 | [The Simple Essence of Automatic Differentiation (talk)](https://www.youtube.com/watch?v=ne99laPUxN4) | Conal Elliott

- 2018 | [The Simple Essence of Automatic Differentiation](http://conal.net/papers/essence-of-ad/essence-of-ad-icfp.pdf) | Conal Elliott

- 2018 | [A Purely Functional Typed Approach to Trainable Models ](https://blog.jle.im/entry/purely-functional-typed-models-1.html) | Justin Le

- 2018 | [Introducing the backprop library](https://blog.jle.im/entry/introducing-the-backprop-library.html) | Justin Le

- 2017 | [Backprop as Functor: A compositional perspective on supervised
  learning](https://arxiv.org/abs/1711.10455) | Brendan Fong, David I. Spivak,
  Rémy Tuyéras

- 2017 | [Haskell and AI (multi-part series covering Tensorflow)](https://mmhaskell.com/haskell-ai/) | James Bowen

- 2017 | [Backpack for deep learning](http://blog.ezyang.com/2017/08/backpack-for-deep-learning/) | Kaixi Ruan

- 2017 | [DeepDarkFantasy: A Programming Language for Deep Learning](https://github.com/ThoughtWorksInc/DeepDarkFantasy) | Marisa Kirisame

- 2017 | [Deep Learning, from a Programming Language Perspective](https://marisa.moe/2017/DLPL/) | Marisa Kirisame

- 2016 | [Computing symbolic gradient vectors with plain Haskell](http://blog.aloni.org/posts/symbolic-gradients-with-plain-haskell/) | Dan Aloni

- 2016 | [Practical Dependent Types in Haskell (Part 2): Existential Neural Networks and Types at Runtime](https://blog.jle.im/) | Justin Le

- 2016 | [Practical Dependent Types in Haskell (Part 1): Type-Safe Neural Networks](https://blog.jle.im/entry/practical-dependent-types-in-haskell-1.html) | Justin Le

- 2016 | [Reverse-Mode Automatic Differentiation in Haskell Using the Accelerate Library (CS240h project)](http://www.scs.stanford.edu/16wi-cs240h/projects/bradbury_kathawala.pdf) | James Bradbury, Farhan Kathawala

- 2015 | [Neural Networks, Types, and Functional Programming](http://colah.github.io/posts/2015-09-NN-Types-FP/) | Christopher Olah

- 2014 | [Get a Brain](https://crypto.stanford.edu/~blynn/haskell/brain.html) | Ben Lynn

- 2013 | [Backpropogation is Just Steepest Descent with Automatic Differentiation](https://idontgetoutmuch.wordpress.com/2013/10/13/backpropogation-is-just-steepest-descent-with-automatic-differentiation-2/) | Dominic Steinitz

## Haskell Packages

### Packages Under Active Development

- [backprop](http://hackage.haskell.org/package/backprop) - Automatic
  heterogeneous back-propagation that can be used either implicitly (in the
  style of the ad library) or using explicit graphs built in monadic style.|
  [Justin Le](https://github.com/mstksg) 
- [backprop-hmatrix](http://hackage.haskell.org/package/backprop) - Automatic
  heterogeneous back-propagation that can be used either implicitly (in the
  style of the ad library) or using explicit graphs built in monadic style. |
  [Justin Le](https://github.com/mstksg)
- [diffhask](https://github.com/o1lo01ol1o/diffhask) -
  DSL for forward and reverse mode automatic differentiation via a version of 
  operator overloading. Port of DiffSharp to Haskell; currently a work in 
  progress. | [Tim Pierson](https://github.com/o1lo01ol1o)
- [funn](https://github.com/nshepperd/funn) - This is an experimental library
  exploring a combinator approach for building and training neural networks in
  haskell. | [Neil Shepperd](https://github.com/nshepperd)
- [grenade](https://github.com/HuwCampbell/grenade) - Grenade is a composable,
  dependently typed, practical, and fast recurrent neural network library for
  concise and precise specifications of complex networks in Haskell. | [Huw
  Campbell](https://github.com/HuwCampbell)
- [gym-http-api](https://github.com/openai/gym-http-api) This project provides a
  local REST API to the gym open-source library, includes a Haskell client by
  [Sam Stites](https://github.com/stites)
- [hasktorch](https://github.com/hasktorch/hasktorch) Tensors and neural networks
  in Haskell, leverages the C backend libraries shared by Torch and PyTorch.
  Also uses [backpack](https://ghc.haskell.org/trac/ghc/wiki/Backpack) and
  [backprop](https://blog.jle.im/entry/introducing-the-backprop-library.html) 
  to define a high level differentiable programming API. |
  [Sam Stites](https://github.com/stites) and 
  [Austin Huang](https://github.com/austinvhuang)
- [hnn](http://hackage.haskell.org/package/hnn) - A neural network library
  implemented purely in Haskell, relying on the hmatrix library. | [Alp
  Mestan](https://github.com/alpmestan)
- [rc](http://hackage.haskell.org/package/rc) - Reservoir computing library. 
  | [Bogdan Penkovsky](https://github.com/masterdezign)
- [tensorflow](https://github.com/tensorflow/haskell) - The tensorflow-haskell
  package provides Haskell bindings to TensorFlow. | [Judah
  Jacobson](https://github.com/judah) and [Greg
  Steuk](https://github.com/blackgnezdo)
- [TypedFlow](https://github.com/GU-CLASP/TypedFlow) - TypedFlow is a typed,
  higher-order frontend to TensorFlow and a high-level library for
  deep-learning. Generates python. | [Jean-Philippe
  Bernardy](https://github.com/jyp)

### Legacy Packages

- [convoluted](https://github.com/jonascarpay/convoluted) - Dependently typed
  convolutional neural networks in pure Haskell. Uses the repa library for
  high-performance arrays, with a static wrapper that ensures networks are valid
  at compile-time. | [Jonas Carpay](https://github.com/jonascarpay)
- [deeplearning-hs](https://hackage.haskell.org/package/deeplearning-hs)
- [dnngraph](https://github.com/ajtulloch/dnngraph)
- [lambdanet](https://hackage.haskell.org/package/LambdaNet)
- [neural](http://hackage.haskell.org/package/neural) - The goal of neural is to
  provide a modular and flexible neural network library written in native
  Haskell. | [Lars Brünjes](https://github.com/brunjlar)

## Related Topics & Links

- [Chris Olah's blog](http://colah.github.io/archive.html)
- [dataHaskell site](http://www.datahaskell.org/) and [gitter chat](https://gitter.im/dataHaskell/Lobby)
- [idontgetoutmuch blog](https://idontgetoutmuch.wordpress.com/)
- [Justin Le's blog](https://blog.jle.im/)
- [Monday Morning Haskell](https://mmhaskell.com/)

## Contribution

Feel free to send a pull request.
