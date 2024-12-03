# The Fun Police Are Here To Help

This is the fun name for the fun job
of Software Architecture Compliance.

These are the moving parts in this repository:

```
fun-police/
 |-- {tech-stack}/
 |   |-- tests/         # Architectural Compliance unittests
 |   |-- policies/      # The Rules, in plain english
 |   |-- CONVENTIONS.md # Semantic entry point for context injection
 |-- README.md          # For when you need to understand the fun police
```

However, this is how it looks when you deploy the fun police in your repository:

```
repo/
 |-- some/
     |-- path/
         |--.fun_police/
         |   |-- CONVENTIONS
         |   |-- tests/
         |   |-- other_files...
         |-- your files, policed by the fun police
         |-- subdirs/
             |-- also
```
## Analogy for explaining the Fun Police

The management analogy is Accounting and Finance.
The difference between these two things is that
accounting is about the past (historical facts),
and finance is about the future (sensible guessing).
The fun police cover both responsibilities.
The accountant (test suite) runs _after_ code is written,
and the financiers (policies) are evaluated _before_.

The executive analogy is a high performance race car.
Software Architecture Policies are the engine
that accelerates the creation of high-quality software
(`hands waive furiously`).
Architecture compliance unittests are the brakes
that quickly and effectively keep the race car
on the track when it suddenly needs to change
its speed and direction.

You need a good balance of both to minimise your lap times.

### Policies Accelerate Delivery

CONVENTIONS.md is an idiom, a grimoire of policies
for telling your AI code generator HOW you want it to work.
A fun police CONVENTIONS.md file is exactly one of those,
with the intent that the spell help the tool
to load the right policy at the right time.

Policy filenames should also help that process,
because they might help the tools,
and they will definitely help the humans
to locate relevant policies when they need them.
Humans can, of course, manually add selected policies
to their development context, when they are relevant
to the heuristic they are using for the task at hand.

If this is working well, the AI coding tools will load
the right policies into their context at the right time.
This will mean that:
- The code they generate is more likely pass the unittests "first time".
- Contextual queues about the code will be provided which compliments the code generration tools internal mechanism for choosing what code to load into context.

The policies accelerate work by telling developers
(human and AI) how to write code "correctly".
They are soothsaying financier elves,
not grumbling goblin accountants.


### Compliance Tests trap mistakes quickly.

Linters are part of the fine-grained code quality system,
that prevent mythologically bad wastes of effort;
like the tabs vs. spaces war (spaces won)
and vim vs. emacs (the Korean War-esque draw
of the software world).

The architectural compliance tests would almost be
_unreasonably restrictive_ if it wasn't for the fact that
AI code generation tools are so _unreasonably effective_.
The two must be in ballance, they must be maintained together.

### Tech-stacks are playbooks 

Different tech-stacks have different CONVENTIONS.md;
A developer needs to choose the right conventions
for the tech stack that they are using,
so their coding assistant can discover and load
the right policies.

Those pollicies will work hand in glove with
specific architecure requirements,
and specific test suites.
They should be a cohesive bundle,
part of the same ying-yang system;
a self-contained, stand alone product.
It's why the fun-police need to exist.
