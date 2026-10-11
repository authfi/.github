<p align="center">
  <a href="https://authfi.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/header-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/header-light.png" alt="AuthFI: the identity provider for people and AI agents" width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://authfi.io"><b>Website</b></a> &nbsp;·&nbsp;
  <a href="https://authfi.io/docs/"><b>Documentation</b></a> &nbsp;·&nbsp;
  <a href="https://authfi.io/pricing"><b>Pricing</b></a> &nbsp;·&nbsp;
  <a href="https://authfi.io/compare"><b>Compare</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/orgs/authfi/discussions"><b>Discussions</b></a>
</p>

<h3 align="center">Sign in your people. Give every AI agent an identity, limits and an off switch.<br>Enforce it where the work runs.</h3>

<br>

<p align="center">
  <a href="https://authfi.io/ai-auth">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/ai-auth-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/ai-auth-light.png" alt="AI Auth: every AI agent gets an identity, limits and an off switch. The agent holds its own key, permissions carry limits, and a sensitive action waits for a named person to approve it." width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://authfi.io/solutions/tool-gateway">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/mcp-gateway-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/mcp-gateway-light.png" alt="MCP gateway: one endpoint for every tool your agents call. A grant per tool, arguments checked on every call, and the tool's own credential stays in the gateway." width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://authfi.io/zero-code">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/zero-code-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/zero-code-light.png" alt="Zero-Code: sign-in and enforcement with no change to your code. One install on a cluster, enforced with eBPF in the Linux kernel." width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://authfi.io/platform">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/identity-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/identity-light.png" alt="Identity provider: one identity provider for staff, customers and devices. Single sign-on over OpenID Connect and SAML 2.0 with SCIM, passkeys and multi-factor authentication on every plan, hosted sign-in under your brand." width="100%">
    </picture>
  </a>
</p>

## Build with AuthFI

<p align="center">
  <a href="https://authfi.io/docs/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/sdks-dark.png">
      <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/sdks-light.png" alt="SDKs in seven languages, a signed Helm chart, a Terraform provider and skills for coding agents." width="100%">
    </picture>
  </a>
</p>

**SDKs.** Each one signs people in, verifies tokens and calls the AuthFI APIs, in the idiom of its language.

| Language | Repository |
| --- | --- |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/nodejs.svg" alt="" height="20" align="top"> &nbsp;Node.js | [authfi/authfi-nodejs-sdk](https://github.com/authfi/authfi-nodejs-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/python.svg" alt="" height="20" align="top"> &nbsp;Python | [authfi/authfi-python-sdk](https://github.com/authfi/authfi-python-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/go.svg" alt="" height="20" align="top"> &nbsp;Go | [authfi/authfi-go-sdk](https://github.com/authfi/authfi-go-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/java.svg" alt="" height="20" align="top"> &nbsp;Java | [authfi/authfi-java-sdk](https://github.com/authfi/authfi-java-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/csharp.svg" alt="" height="20" align="top"> &nbsp;.NET | [authfi/authfi-dotnet-sdk](https://github.com/authfi/authfi-dotnet-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/php.svg" alt="" height="20" align="top"> &nbsp;PHP | [authfi/authfi-php-sdk](https://github.com/authfi/authfi-php-sdk) |
| <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/ruby.svg" alt="" height="20" align="top"> &nbsp;Ruby | [authfi/authfi-ruby-sdk](https://github.com/authfi/authfi-ruby-sdk) |

**Kubernetes.** <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/helm.svg" alt="" height="18" align="top"> The [authfi-ebpf-agent Helm chart](https://artifacthub.io/packages/helm/authfi-ebpf-agent/authfi-ebpf-agent) installs Zero-Code on a cluster. It is published on Artifact Hub by a verified publisher and signed with cosign.

In the console, open **Connect cluster**, copy the one-time token, then:

```sh
helm install authfi-ebpf-agent oci://ghcr.io/authfi/charts/authfi-ebpf-agent \
  --set authfi.issuerUrl=https://<your-project>.authfi.io \
  --set authfi.connectToken=<token from the console>
```

**Infrastructure as code.** <img src="https://raw.githubusercontent.com/authfi/.github/main/profile/assets/langs/terraform.svg" alt="" height="18" align="top"> [terraform-provider-authfi](https://github.com/authfi/terraform-provider-authfi) manages applications, connections, roles and policies from Terraform.

**Skills for coding agents.** [authfi-skills](https://github.com/authfi/authfi-skills) teaches an AI coding agent how to integrate AuthFI: written in the Open Knowledge Format, so any agent that reads Markdown can use them.

## Start in ten minutes

| You want to | Start here |
| --- | --- |
| Sign people in to your application | [Add sign-in to an app](https://authfi.io/docs/quickstart/sign-in) |
| Give an AI agent its own identity | [Give an AI agent an identity](https://authfi.io/docs/quickstart/agent) |
| Control which tools an agent can call | [Connect an agent to tools](https://authfi.io/docs/quickstart/mcp) |
| Protect a service without changing it | [How Zero-Code works](https://authfi.io/docs/zero-code/overview) |
| Compare with Auth0, Okta and Microsoft Entra | [The comparison, with sources](https://authfi.io/compare) |

## Built on open standards

OAuth 2.0 · OpenID Connect · SAML 2.0 · SCIM 2.0 · WebAuthn · OpenID CIBA · Model Context Protocol · eBPF

## Talk to us

- **Questions, ideas and feedback:** join the [community discussions](https://github.com/orgs/authfi/discussions). The people who build AuthFI read every post.
- **Early-stage company?** See the [startup program](https://authfi.io/startups).
- **Found a security weakness?** Please do not post it publicly. Follow the [security policy](https://github.com/authfi/.github/blob/main/SECURITY.md).

<p align="center"><sub>AuthFI is <b>Auth</b>entication <b>F</b>rom <b>I</b>ndia · <a href="https://authfi.io/about">About the company</a></sub></p>
