# AI Security "Opportunities" 😈

**Guardrails, Sandboxes, and Keeping Your Agents on a Leash**

A presentation on AI security for the [Drupal AI Learners Club](https://luma.com/drupal-ai) by Marlene Wanberg, originally given on May 18, 2026.

## View the slides

**[View slides in your browser](https://mwanberg.github.io/ai-learners-security-talk/)** | **[Download as PDF](https://mwanberg.github.io/ai-learners-security-talk/slides.pdf)**

## Topics covered

- Deterministic vs. probabilistic systems and why AI security is different
- The Three S's framework (Social Engineering, Sniffing, Sending)
- Real-world AI agent incidents
- Prompt injection, slopsquatting, and MCP server risks
- Container strategies for Drupal/DDEV development
- Secrets management, permissions, and monitoring
- Practical steps you can take today

## Running locally

```bash
# Preview with live reload
npx @marp-team/marp-cli -s .

# Export to PDF
npx @marp-team/marp-cli slides.md --pdf
```

## Resources from the talk

- Randy Fay's DDEV container notes (presented during this talk):
  https://rfay.github.io/ai-security-notes/
- Anthropic devcontainer docs:
  https://code.claude.com/docs/en/devcontainer
- FreelyGive/ddev-claude-code:
  https://github.com/FreelyGive/ddev-claude-code
- makraz/ddev-claude:
  https://github.com/makraz/ddev-claude

### Frameworks & Concepts

- Fabian Franz, "Three S's":
  https://www.tag1.com/blog/how-to-think-about-ai-agent-security/
- Fabian Franz, follow-up article "Structure is Freedom":
  https://www.tag1.com/blog/structure-is-freedom-ai-agent-security/
- IBM AI agent security videos:
  https://www.youtube.com/watch?v=UMYtqHptYvA
- OWASP GenAI Security Project:
  https://genai.owasp.org/

### Tools & Setup

**Container setup:**
- Anthropic: <https://code.claude.com/docs/en/devcontainer>
  - Referenced 3-file starterkit files: <https://github.com/anthropics/claude-code/tree/main/.devcontainer>
- How to set up VS Code: <https://code.visualstudio.com/docs/devcontainers/create-dev-container>
- Docker sandboxes: <https://docs.docker.com/ai/sandboxes/>

**DDEV approaches:**
- [e0ipso/ddev-assistant-claude](https://github.com/e0ipso/ddev-assistant-claude)
- [FreelyGive/ddev-claude-code](https://github.com/FreelyGive/ddev-claude-code)
- [makraz/ddev-claude](https://github.com/makraz/ddev-claude)

## Credits

Illustrations generated with Google Gemini. Slides built with [Marp](https://marp.app/). Typography: [Newsreader](https://github.com/productiontype/Newsreader) and [Source Sans 3](https://github.com/adobe-fonts/source-sans), both under the SIL Open Font License.
