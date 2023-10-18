# Luau Research Papers

[Bibiography](luau.bib), [Repo](https://github.com/luau-lang/research)

## HATRA'21: Position Paper: Goals of the Luau Type System

Authors: Lily Brown, Andy Friesen, Alan Jeffrey

Luau is the scripting language that powers user-generated experiences on the Roblox platform. It is a statically- typed language, based on the dynamically-typed Lua language, with type inference. These types are used for providing editor assistance in Roblox Studio, the IDE for authoring Roblox experiences. Due to Roblox’s uniquely heterogeneous developer community, Luau must operate in a somewhat different fashion than a traditional statically-typed language. In this paper, we describe some of the goals of the Luau type system, focusing on where the goals differ from those of other type systems.

[Paper](hatra21/hatra21.pdf), [Slides](hatra21/talk.pdf), [Video](https://www.youtube.com/watch?v=nziiBPtB0eQ)

## HATRA'23: Goals of the Luau Type System, Two Years On

Authors: Lily Brown, Andy Friesen, Alan Jeffrey

In HATRA 2021, we presented The Goals Of The Luau Type System, describing the human factors of a type system for a language with a heterogeneous developer community. In this extended abstract we provide a progress report, focusing on the unexpected aspects: semantic subtyping and type error suppression.

[Paper](hatra23/hatra23.pdf), [Slides](hatra23/talk.pdf)

## Draft Manuscript: Towards an Unsound But Complete Type System

Authors: Lily Brown, Andy Friesen, Alan Jeffrey, Vighnesh Vijay

In HATRA 2021, we presented The Goals Of The Luau Type System, describing the human factors of a type system for a language with a heterogeneous developer community. One of the goals was the design of type system for bug detection, where we have high confidence that type errors identify gen- uine software defects, and that false positives are minimized. Such a type system is, by necessity, unsound, but we can ask instead that it is complete. This paper presents a work- in-progress report on the design and implementation of the new unsound type system for Luau.

[Paper](incorrectness24/incorrectness24.pdf)
