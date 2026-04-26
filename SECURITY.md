<h2> Trust & Security (Verification Required)</h2>

<p><strong>Do not trust third-party mirrors.</strong> To ensure your QRZ credentials and logs remain secure, verify the integrity of your download.</p>

<table style="width:100%; border: 1px solid #30363d; border-collapse: collapse;">
  <thead>
    <tr style="background-color: #161b22;">
      <th style="padding: 8px; border: 1px solid #30363d;">Platform</th>
      <th style="padding: 8px; border: 1px solid #30363d;">Target Arch</th>
      <th style="padding: 8px; border: 1px solid #30363d;">File Type</th>
      <th style="padding: 8px; border: 1px solid #30363d;">SHA-256 Checksum</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px; border: 1px solid #30363d;"><b>Windows 10 Mobile</b></td>
      <td style="padding: 8px; border: 1px solid #30363d;">Fat Binary (ARM/x86)</td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>.appxbundle</code></td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>[TBA]</code></td>
    </tr>
    <tr>
      <td style="padding: 8px; border: 1px solid #30363d;"><b>Android</b></td>
      <td style="padding: 8px; border: 1px solid #30363d;">ARM64</td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>.apk</code></td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>[TBA]</code></td>
    </tr>
  </tbody>
</table>

<hr />

<h3> How to verify</h3>

<h4>Windows (PowerShell):</h4>
<pre><code>Get-FileHash .\Logger26_v1.0_arch.appxbundle</code></pre>

<h4>Android (Termux / Linux / SDK):</h4>
<p><b>1. Verify Hash:</b></p>
<pre><code>sha256sum Logger26.apk</code></pre>
<p><b>2. Verify Developer Signature (BielsonSoft):</b></p>
<pre><code>apksigner verify --print-certs "Logger 26.apk"</code></pre>

<hr />
<p><strong>73 de SP9HKA</strong> | <a href="https://github.com/Kambiel5">BielsonSoft on GitHub</a></p>
