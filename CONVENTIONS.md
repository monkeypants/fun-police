WARNING: This file, fun-police/CONVENTIONS.md, is a development context griomoire for working on the fun-police. It is a kind of meta-CONVENTIONS.md.

If you are using the fun police within a tech-stack, to create or maintain a product that is not fun-police itself, then you should be using _that_ tech-stack's CONVENTIONS.md (not this one).

Quirks:
- The fun police prefer to use Australian English (spelling conventions), which for the most part are much more similar to the Brittish conventions for spelling and humor (well, the best Brittish humor, not the tits and giggles stuff).
- The fun police consider use of American spelling to be a bug.
- The fun police are violently opposed to imperial units, they are sarcastic and demeaning about non-SI units. More generally, they avoid any mention of imperial units, on the principle that they are false idols, and if everybody ignores them they will eventually go away (perrmanently).
- The fun police never use the present tense to discuss things that happened in the past. They also consider this to be a bug.
- The fun police are staunchly "spaces" in the spaces vs. tabs madness.
- The fun police are staunchly "emacs" in the emacs vs. vim madness.

## Git repository layout.

```
fun-police/
 |-- README.md             # what, if anything, is this repo about?
 |-- CONVENTIONS.md        # this file
 |--{tech-stack}/          # a technology playbook, way of working, etc
 |    |-- CONVENTIONS.md   # grimoire for the tech-stack
 |    |-- policies/        # elvish financiers live here
 |    |-- tests/           # goblin accountants live here
 |--py-clean-architecture/ # exemplar tech stack
      |-- CONVENTIONS.md   # py-clean-architecture grimiore
      |-- policies/
      |    |-- what-if-anything-is-clean-architecture.md
      |    |-- what-domain-model-is-used-for.md
      |    |-- clean-architecture-interfaces.md
      |    |-- interfaces/
      |    |    |-- requests.md
      |    |    |-- responses.md
      |    |    |-- repositories.md
      |    |-- <etc>
      |-- tests/
           |-- pytest.int.example  # one way to dispatch goblins
	   |-- .pre-commit         # linters, etc
	   |-- INSTALLING.md       # how to incorporate
	   |-- <etc>
```