---
title: Agent World
type: definition
---

An Agent World is a [[is_a:Computation]] that communicates with one or more [[uses:Agent]]s.

For each time step, it might compute something like:

```rust
type World := { state: WorldState, agents: List<AgentState> };
let update_world : { world: World } -> World := {
	let messages := world.state.get_messages_for_agents();
	// receive updates from agents
	let updates := world.agents.join(messages).foreach{apply}.collect{List};
	// use the updates to update the world and generate new messages for the agents
	{...}
};
```