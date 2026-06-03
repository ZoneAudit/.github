# ZoneAudit™

**Global attack surface management and actionable domain intelligence.**

ZoneAudit™ provides high-velocity telemetry collection and engineering-led analysis to maintain a continuous, validated map of your digital perimeter. The ecosystem is designed to bridge the gap between raw network data and operational clarity.

---

### Ecosystem and core projects

<table>
  <tr>
    <td width="45%" valign="top">
      <img src="assets/community-card-portrait.svg" width="100%" alt="ZoneAudit™ Community Edition" /><br/>
      <br/>
      <b>ZoneAudit™ Community Edition</b><br/>
      Tactical discovery of core digital perimeters with high-velocity Go telemetry.<br/>
      <br/>
      <a href="https://github.com/ZoneAudit/zoneaudit-cli"><b>Explore the CLI →</b></a>
    </td>
    <td width="10%"></td>
    <td width="45%" valign="top">
      <img src="assets/enterprise-card-portrait.svg" width="100%" alt="ZoneAudit™ Enterprise" /><br/>
      <br/>
      <b>ZoneAudit™ Enterprise</b><br/>
      Drive operational clarity with the active DeepScan™ engine and intelligence pipeline.<br/>
      <br/>
      <a href="https://zoneaudit.com"><b>Join the waitlist →</b></a>
    </td>
  </tr>
</table>

---

### Data to insight flow

```mermaid
graph TD
    subgraph collection [Telemetry collection]
        direction TB
        A[zoneaudit-cli]
        B[DeepScan Agent™]
    end

    subgraph engine [Intelligence engine]
        direction TB
        E(DeepScan™ engine)
        F(AI discovery and triage)
    end

    subgraph output [Operational clarity]
        direction TB
        G[DeepScan Intelligent Insight™]
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

ZoneAudit™ is built on a foundation of open telemetry. We believe that mapping the digital perimeter should be accessible, high-velocity, and community-driven.

- **Contribute**: We welcome pull requests for the [zoneaudit-cli](https://github.com/ZoneAudit/zoneaudit-cli), especially for new heuristics and scanning optimisations.
- **Heuristics**: Help us engineer new ways to spot orphaned infrastructure and misconfigured records.
- **Feedback**: Open an issue to discuss architectural improvements or feature requests.

---

### Connect with us

- **Website**: [zoneaudit.com](https://zoneaudit.com)
- **LinkedIn**: [ZoneAudit on LinkedIn](https://www.linkedin.com/company/zoneaudit)
- **Engineering**: A [CobraSphere](https://github.com/CobraSphere) technical excellence initiative.

---

_Built with precision in the United Kingdom._
