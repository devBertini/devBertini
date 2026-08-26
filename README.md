
**[XTant](https://github.com/devBertini/xtant)** is a local autonomous coding platform that runs on
one 8 GB laptop GPU. A card on a board becomes a plan the architect model must emit under a GBNF
grammar. The plan becomes a contract whose acceptance criteria are real commands, proven to fail
before any work starts. The developer model implements it inside a Docker sandbox that runs
unprivileged and offline. Neither model ever rules on its own work: deterministic gates do, and only
a human closes a card.

That separation stopped being theoretical the day the developer model, told to make
`node --test test/total.test.js` pass, rewrote `test/total.test.js` instead and turned every gate
green against its own edit. The plan linter now refuses a criterion that judges a file the same plan
is allowed to change, before a container is ever started.

**The part of it I am proudest of is the part that ships switched off.**

> Injecting a written skill into the developer's prompt was supposed to help. Measured over 54
> paired runs (nine tasks, six samples each, same GPU, same model, same seed, the 430-token skill
> the only variable), correctness fell **66.7% → 55.6%** and format adherence **98.1% → 68.5%**. The
> mechanism is finished and tested. `skills.roots` ships empty, because turning it on needs a number
> it does not have.

Also here: the sites for four iOS apps whose whole pitch is that nothing leaves the phone, and the
VS Code extension XTant grew out of.

[LinkedIn](https://www.linkedin.com/in/claudio-bertini/)

