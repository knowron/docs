# Agentic Workflows

An agentic workflow teaches the KNOWRON Assistant how your team handles one specific task: when it comes up, what to clarify, where to look and what the result should be.

Think of it as the playbook you give a new colleague. The assistant recognizes when a question needs a workflow and follows it. Users just ask, as always.

Part of Assistant 3.0 and included for all clients at no extra cost. You define the task, our Customer Success team builds the workflow with you.

## How it works

!!! example "Example: making sure it's the right machine before ordering spare parts"

    A client's machines share many similar spare parts, so a short question could easily be answered from the wrong machine. Together with Customer Success, they created a workflow that first makes sure the user is looking at the right machine, then searches only its documents.

<div class="kn-chat">
  <div class="kn-user"><p>Spare part number for the dosing pump?</p></div>
  <div class="kn-bot">
    <p class="kn-status"><span class="kn-num">1</span> Spare part request recognized</p>
    <div class="kn-card">
      <p class="kn-question"><span class="kn-num">2</span> Spare parts lists differ by machine. Which one is it?</p>
      <ul class="kn-options">
        <li>MX-200</li>
        <li class="kn-selected">MX-300</li>
        <li>MX-350</li>
        <li class="kn-other">Something else…</li>
      </ul>
    </div>
  </div>
  <div class="kn-bot">
    <p class="kn-status"><span class="kn-num">3</span> Searching only MX-300</p>
    <p><strong>Dosing pump, MX-300</strong><br>Part number: 30-4471-02</p>
    <p class="kn-source"><span class="kn-dot">●</span> 1 source: MX-300 spare parts list</p>
  </div>
</div>

1. **Recognizes the task.** A spare part request, not a general question.
2. **Asks only when it matters.** One question, three suggestions, one tap.
3. **Searches the right documents.** The answer comes with its source.

On a year of real questions from one client, it would have asked back in 4 out of 100.

## What a workflow defines

| | Example: spare parts |
|---|---|
| **When it applies** | Someone asks for a spare part |
| **What to clarify** | The machine, if unclear |
| **Where to look** | Only that machine's spare parts lists |
| **The result** | Part number, with source |
| **What to avoid** | Interrupting troubleshooting |

## Ideas

- **Service:** identify the exact model, diagnose recurring faults, decode part numbers
- **Production:** shift handovers, safety checks before maintenance, changeover checklists
- **Support:** answer spare part requests with the exact part number
- **Your customers:** find the right manual for their model

Good candidates repeat often, follow the same steps and depend on details people forget to mention.

## How you get one

1. You pick a task and book a meeting with Customer Success.
2. We build and test the workflow with you. Expect about a week from your first request to go-live.
3. Your users find it in the assistant. We maintain it.

!!! tip "What helps us most"

    Write down how someone on your team does the task today, step by step, in plain text. It doesn't need to be polished. We take it from there.

## For admins

**Where do I see workflows?** In the chat, whenever the assistant uses one. For an overview of your active workflows, ask Customer Success.

**How do I change a workflow?** Talk to Customer Success. Workflows can't be edited in the chat.

**Who can see a workflow?** It follows the same visibility rules as your documents: internal, customer or public.

**Which knowledge does it use?** Only your KNOWRON knowledge base, not the internet.

**Which languages?** All of them. Users can ask in any language they use KNOWRON in.

**Can workflows do more?** Ask us about expanding the possibilities.

Contact your Customer Success manager at [support@knowron.com](mailto:support@knowron.com) to find your first workflows.
