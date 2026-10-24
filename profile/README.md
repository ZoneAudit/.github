# ZoneAudit™

**Domain and attack surface intelligence from public records.**

ZoneAudit reads a domain's public records, such as DNS, certificates and registration data, and turns them into findings an organisation can act on. The open source Community Edition CLI is available now. ZoneAudit Enterprise is preparing to launch.

---

### Ecosystem and core projects

<table>
  <tr>
    <td width="45%" valign="top">
      <img src="assets/community-card-portrait.svg" width="100%" alt="ZoneAudit Community Edition" /><br/>
      <br/>
      <b>ZoneAudit Community Edition</b><br/>
      Read-only checks of a domain's public footprint, written in Go and open source.<br/>
      <br/>
      <a href="https://github.com/ZoneAudit/zoneaudit-cli"><b>Explore the CLI →</b></a>
    </td>
    <td width="10%"></td>
    <td width="45%" valign="top">
      <img src="assets/enterprise-card-portrait.svg" width="100%" alt="ZoneAudit Enterprise" /><br/>
      <br/>
      <b>ZoneAudit Enterprise</b><br/>
      Prioritised, evidenced reports from passive public records, with no probing. Preparing to launch.<br/>
      <br/>
      <a href="https://zoneaudit.com/en-gb/access"><b>Request access →</b></a>
    </td>
  </tr>
</table>

---

### Data to insight flow

The Enterprise analysis and report stages are in development.

```mermaid
graph TD
    subgraph collection [Public record collection]
        direction TB
        A[zoneaudit-cli]
        B[DeepScan™ Agent]
    end

    subgraph engine [Analysis]
        direction TB
        E(DeepScan engine)
        F(Prioritisation and triage)
    end

    subgraph output [Report]
        direction TB
        G[DeepScan Intelligent Insight]
    end

    collection --> engine
    engine --> output

    %% Styling
    style G fill:#fefefe,stroke:#333,stroke-width:2px
    style E fill:#f5f5f5,stroke:#333
    style F fill:#f5f5f5,stroke:#333
    style collection fill:none,stroke:#ddd,stroke-dasharray: 5 5
    style engine fill:none,stroke:#ddd,stroke-dasharray: 5 5
    style output fill:none,stroke:#ddd,stroke-dasharray: 5 5
```

---

### Open source and community

The ZoneAudit Community Edition CLI is open source under the MIT licence. Anyone can run it against a domain they own or are authorised to assess.

- **Contribute.** Pull requests for the [zoneaudit-cli](https://github.com/ZoneAudit/zoneaudit-cli) are open, especially for new checks and performance improvements.
- **Checks.** New ways to spot orphaned infrastructure and misconfigured records are welcome.
- **Feedback.** Open an issue to discuss design improvements or feature requests.

---

### Connect with us

- **Website.** [zoneaudit.com](https://zoneaudit.com)
- **LinkedIn.** [ZoneAudit on LinkedIn](https://www.linkedin.com/company/zoneaudit)
- **Engineering.** Built by [CobraSphere](https://github.com/CobraSphere).

---

_Made in the United Kingdom._
