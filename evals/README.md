# Evaluation cases

These are maintenance inputs, not runtime references. Do not load them during
ordinary use of the skill.

- `routing.json`: classify each request from skill descriptions alone. Required
  routes must be present; forbidden routes must be absent. PR workflow cases
  must retain their domain orchestrator even if it later loads `stop-bullshit`.
  The tone-only negative checks that `stop-bullshit` stays out; it does not
  require a particular style-editing skill. The separate humanizer collision
  case tests that adjacent route.
- `behavior.json`: apply `SKILL.md` to each fictional fixture without running
  commands, accessing external services, or editing the reviewed material.
  Return separate findings for `material` and `response`, a concise corrected
  response, and any unresolved premise. Grade against `expected`, which must be
  withheld from the agent handling the fixture.

Use fresh sessions in each supported runtime. Record actual model, routing
failures, missed corrections, and false positives. Check whether the installed
skill is discoverable separately from classification against a supplied catalog.
These fixtures test specified behaviors; passing them does not establish general
truthfulness or quantify improvement over an agent without the skill.
