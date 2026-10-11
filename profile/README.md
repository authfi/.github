# AuthFI

**The identity provider for people and AI agents, enforced where the work runs.**

AuthFI signs in your staff and your customers, gives every AI agent its own identity, limits and off switch, and enforces what each service and agent may reach in the Linux kernel of your own machines, with no change to your applications.

| | |
| --- | --- |
| **Website** | [authfi.io](https://authfi.io) |
| **Documentation** | [authfi.io/docs](https://authfi.io/docs/) |
| **Pricing** | [authfi.io/pricing](https://authfi.io/pricing) |
| **Service status** | [status.authfi.io](https://status.authfi.io) |

## What it does

- **Single sign-on and customer identity** over OpenID Connect and SAML 2.0, with SCIM provisioning, passkeys and multi-factor authentication.
- **AI Auth**: authentication and authorization for AI agents, built on OAuth. An agent holds its own key, has permissions with limits, and can be made to wait for a person's approval.
- **MCP gateway**: one endpoint for every tool an agent calls, with a grant per tool.
- **Zero-Code**: sign-in and access rules in front of services on Kubernetes, enforced with eBPF, with nothing added to the services.

## Talk to us

- **Questions, ideas and feedback**: [Discussions](https://github.com/authfi/.github/discussions)
- **A security weakness**: please do not post it publicly. See the [security policy](https://github.com/authfi/.github/blob/main/SECURITY.md).
