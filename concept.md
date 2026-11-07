# Conceptualization 

### Goal
Show how hidden text in phishing emails hijacks AI email assistants, then demonstrate a defense.
Scope note: Version 1 demonstrates the attack and the defense together; the side-by-side output difference is the proof of concept.

### Deliverables (Version 1)

###### 1. Reusable Code Repository — GitHub
* Source code, dependency definitions, and configuration examples.
* Public repository that others can inspect, modify, and reuse.

###### 2. Deployed Demonstration — Cloudflare
* Publicly accessible, read-only interface for testing predefined prompt-injection scenarios.
* Six synthetic phishing emails are seeded in advance through Cloudflare Email Routing and stored for the demo. The public interface cannot receive or accept new email.
* Side-by-side comparison of vulnerable and defended AI outputs for the same email, model and system prompt.
* Appropriate usage limits (rate limiting per visitor) and security isolation (no real inboxes, no user-supplied content).

###### 3. Project Documentation — GitHub
* Installation and usage instructions.
* Technical decisions and their rationale.
* Development methodology, testing results, and limitations.

###### 4. Design and Architecture
* High-Level Design (HLD) document.
* Architecture diagrams illustrating components and data flows.
* Security boundaries and interactions between email content, processing pipelines, and the AI model.

###### 5. Deployable Package — GitHub Releases
* Versioned release containing the required application files and deployment configuration.
* Installation and deployment scripts or instructions.
* Configuration templates without embedded secrets.
* Instructions enabling others to deploy their own instances using their API credentials.


