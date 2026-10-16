# Model, harness and app

The model interprets the available context and produces responses or requests to use tools. The harness is the runtime around it: it assembles context, dispatches tools under the applicable policy, returns results and maintains the session. The app is the interface you use to direct and inspect the work.

## The loop in our course
1. Your task, selected source files and applicable instructions form the working context.
2. The model proposes the next response or tool call.
3. The runtime applies the relevant approval and execution policy and dispatches the tool.
4. The result returns as context for the next step. The loop can continue or end.
5. You inspect the output and trace important claims back to sources.

Changing the model alone cannot supply a missing source file or authorize a connection. When a result is wrong, check the inputs, instructions, available tools and evidence as well as the model choice.

The illustration is a simplified teaching model. Plan, execute and reflect describe the feedback loop; they are not three literal software modules. Tool access and sandbox enforcement depend on configuration and environment. The model's separate position in the image distinguishes responsibility, not physical hosting.

## Open-source scope and sources
OpenAI publishes the CLI, SDK, app-server and core runtime source. This does not imply publication of model weights or every product surface.

- [Open-source components](https://learn.chatgpt.com/docs/open-source)
- [App-server interface](https://learn.chatgpt.com/docs/app-server)
- [Core runtime](https://github.com/openai/codex/blob/3ee47c10513f1bb57d869ea650aba28638e3d11c/codex-rs/core/README.md)
- [Model and tool loop](https://github.com/openai/codex/blob/3ee47c10513f1bb57d869ea650aba28638e3d11c/codex-rs/core/src/session/turn.rs)
- [Tool approvals and sandbox orchestration](https://github.com/openai/codex/blob/3ee47c10513f1bb57d869ea650aba28638e3d11c/codex-rs/core/src/tools/orchestrator.rs)
- [Conversation history](https://github.com/openai/codex/blob/3ee47c10513f1bb57d869ea650aba28638e3d11c/codex-rs/core/src/context_manager/history.rs)

Source repository snapshot: 3ee47c10513f1bb57d869ea650aba28638e3d11c.
