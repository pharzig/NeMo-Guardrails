# Documentation

The documentation is divided into the following sections:

* [Getting Started](#getting-started)
* [Examples](#examples)
* [User Guide](#user-guide)
* [Architecture Guide](#architecture-guide)
* [Security Guidelines](./security/guidelines.md)

## Getting Started

The getting started section covers two topics:

* [Installation Guide](./getting_started/installation-guide.md): This guide walks you through the process of setting up an environment to run Guardrails. It also showcases the various ways in which you can interact with the bot.
* [The "Hello World" example](./getting_started/hello-world.md): This example walks you through setting up basic rails along with peeling some layers for the Guardrail runtime to explain how the rails work.

## Examples

Five reference examples are provided as a general demonstration for building different types of rails:

* [Topical Rail](../examples/topical_rail/README.md): Making the bot stick to a specific topic of conversation.
* [Moderation Rail](../examples/moderation_rail/README.md): Moderating a bot's response.
* [Fact Checking and Hallucination Rail](../examples/grounding_rail/README.md): Ensuring factual answers.
* [Secure Execution Rail](../examples/execution_rails/README.md): Executing a third-party service with LLMs.
* [Jailbreaking Rail](../examples/jailbreak_check/README.md): Ensuring safe answers despite malicious intent from the user.

**Note:** These examples are meant to showcase the process of building rails, not as out-of-the-box safety features. Customization and strengthening of the rails is highly recommended.

## User Guide

The user guide covers the core details of the Guardrails toolkit and how to configure and use different features to make your own rails.

* [Colang Language Guide](./user_guide/colang-language-syntax-guide.md): Learn about Colang, the language at the heart of NeMo Guardrails!
* [Colang Syntax Reference Guide](./user_guide/colang-syntax-reference.md): General keyword ledger.
* [Guardrails Configuration Guide](./user_guide/configuration-guide.md): Learn how to do general configurations such as adding a system prompt!
* [Python API](./user_guide/python-api.md): Explore the Python API for Guardrails!
* [Integration with LangChain](./user_guide/integration-with-langchain.md): Integrate Guardrails in your existing LangChain-powered app or bring your preferred Chains to Guardrails!
* [Server Guide](./user_guide/server-guide.md): General explanation for the Guardrails Servers.
* [Interface Guide](./user_guide/server-guide.md): Learn the different ways in which to interact with the bot!

The following guides explain in more details various specific topics:

* [Extract User Provided Values](./user_guide/advanced/extract-user-provided-values.md): Learn how to extract user-provided values like a name, a date or a query.

## Architecture Guide

This guide sheds more light on the infrastructure details and the execution flow for a query when the runtime is used:

* [Via an API (Server-less)](./architecture/README.md#the-guardrails-process): Learn how the Guardrails runtime works under the hood!

* [Request is sent to a Colang server (Server Arch)](./architecture/README.md#server-architecture): Understand the architecture of the Guardrails server!
