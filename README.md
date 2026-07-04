<p align="center">
<img src="https://i.imgur.com/REPLACE_WITH_YOUR_BANNER.png" alt="Identity Governance"/>
</p>

<h1>Entra ID — Identity Governance (SC-300 Lab 5)</h1>
Configure Privileged Identity Management, access reviews, and entitlement management. Maps to SC-300 Domain 4 (20–25%).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Entra ID (P2 required)
- Privileged Identity Management, Access Reviews, Entitlement Management

<h2>Operating Systems Used</h2>

- Windows 11 (browser-based)

<h2>List of Prerequisites</h2>

- A developer tenant with E5 / Entra ID P2
- Privileged Role Administrator access

<h2>Configuration Steps</h2>
<ol>
  <li><strong>Configure PIM</strong> — make a user <em>eligible</em> for a role; in role settings require approval + MFA + justification on activation.</li>
  <li><strong>Create an access review</strong> — monthly review of a privileged role; assign the business owner as reviewer.</li>
  <li><strong>Build an access package</strong> — Entitlement management &rarr; create a catalog and publish an access package with an approval policy.</li>
  <li><strong>Add terms of use</strong> — upload a PDF and require it via a Conditional Access grant control.</li>
</ol>

<h2>Key Concepts Demonstrated</h2>

- Eligible is not active — PIM activates just-in-time, time-boxed.
- Access reviews close the loop by having owners re-attest access.

<h2>Lessons Learned</h2>

- Reducing standing admins (e.g., 7 Global Admins to 1 via PIM) is a measurable, resume-worthy win.
- Owners, not IT, should review access so attestation scales.
