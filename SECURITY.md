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
      <td style="padding: 8px; border: 1px solid #30363d;"><code>[0F6509BF106F5D44634702BF0CBF48D7BB05537AAE9C71386ABFDFE37F408BA7 (App),   FF374E03CFD55190CBACA8FFE908038D3B3731033A085E553E8DF1309B74F8DA (Public Key)]</code></td>
    </tr>
    <tr>
      <td style="padding: 8px; border: 1px solid #30363d;"><b>Android</b></td>
      <td style="padding: 8px; border: 1px solid #30363d;">ARM64</td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>.apk</code></td>
      <td style="padding: 8px; border: 1px solid #30363d;"><code>[ certificate: ff98ca0d2f0e6ec517e4cc34f14dfd043bea3709d45d8cf1edcb8094fa86f0e2| Filehash:ca02dc1f0b146625b5c012673f589f213ef2995048723bd18e59e508d5f112a5
]</code></td>
    </tr>
  </tbody>
</table>

<hr />

<h3> How to verify</h3>

<h4>Windows (PowerShell):</h4>
<pre><code>Get-FileHash .\Path to your file</code></pre>

<h4>Android (Termux / Linux / SDK):</h4>
<p><b>1. Verify Hash:</b></p>
<pre><code>sha256sum Path to your file</code></pre>
<p><b>2. Verify Developer Signature (Android only):</b></p>
<pre><code>apksigner verify --print-certs "Logger 26.apk"</code></pre>

<hr />
<p><strong>73 de SP9HKA</strong> | <a href="https://github.com/Kambiel5">BielsonSoft on GitHub</a></p>
