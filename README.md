**Agents bullshit too much.**

`stop-bullshit` is an agent skill for catching unsupported claims,
evasions, and reasoning that sounds convincing without establishing its point.
Its final check examines both the material and the agent's own response. Use it
when a user signals "stop bullshitting me" to find and correct the underlying
failure, rather than merely soften the answer.

Inspired by and written under the influence of Harry G. Frankfurt's
[*On Bullshit*](https://en.wikipedia.org/wiki/On_Bullshit) (Princeton University
Press, 2005; first published as an essay in 1986;
[essay text](https://www.maieutiek.nl/wp-content/uploads/2020/02/on-bullshit.pdf)).

Install this repository as a directory named `stop-bullshit` in your runtime's
configured skill location. Invoke `stop-bullshit`, or have a workflow load
[SKILL.md](SKILL.md) before delivery. For continuous vigilance, keep its core
discipline—answer the actual question and match claims to evidence—in your
always-loaded instructions.

[Evaluation cases](evals/README.md) cover routing and correction behavior.
