# Extended Answers

Extended Answers allows the KNOWRON assistant to respond to questions that are not covered anywhere in your organization's documentation, drawing on general knowledge the way a general-purpose AI assistant would. It is an opt-in feature and is disabled by default for all clients.

!!! info "Enabled by KNOWRON"
    Extended Answers must be activated at the client level by the KNOWRON team before it is available in your environment. To request activation, contact your KNOWRON account manager or [support@knowron.com](mailto:support@knowron.com).

## How It Works

Your documentation always takes precedence. Extended Answers only activates when the assistant finds no relevant content in the knowledge base. If your organization defines a concept differently from its common usage, your definition is used and Extended Answers does not activate for that topic.

When a user submits a query, the flow is as follows:

1. The assistant searches the knowledge base first.
2. If relevant documentation exists, it is used to generate the answer — Extended Answers does not activate.
3. If no relevant documentation is found and Extended Answers is enabled, the user is prompted to confirm whether they want a response based on general knowledge.
4. If the user confirms, the answer is generated and **clearly labeled as not sourced from the organization's knowledge base**.
5. If the user declines, no answer is generated.

This label is always present on Extended Answers responses and cannot be disabled, so users are never in doubt about where the information comes from.

<p align="center"><img src="https://i.imgur.com/Y3uLVL3.gif" width="80%"></p>

## Activation and Consent

Two independent conditions must be met before any Extended Answer can be generated:

**1. Client-level enablement**

The feature must be enabled at the client level before it is available to any user. When it is not enabled, no user in that environment can access Extended Answers regardless of their personal settings.

**2. Per-query user confirmation**

Even when the feature is enabled, the user is prompted every time the assistant would generate an Extended Answer. The user must actively confirm before a response is produced.

## User Preferences

Users who prefer not to be prompted on every query can pre-authorize Extended Answers from their profile screen in the Native Assistant. When this preference is set, the assistant generates Extended Answers automatically without prompting, for as long as the preference is active.

This preference can be revoked at any time from the profile screen, after which the assistant resumes prompting on each applicable query.

!!! note
    Client-level settings always take precedence over personal preferences. If Extended Answers is disabled at the client level, user preferences have no effect.

## Related pages

- [AI-generated Answers](answers.en.md)
- [Ask Assistant](ask_assistant.en.md)
- [Search](search.en.md)
