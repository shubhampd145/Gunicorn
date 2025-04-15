
<h1>Standard Operating Procedure (SOP) for Gunicorn Installation & Setup</h1>

<table>
  <thead>
    <tr>
      <th>Author</th>
      <th>Created on</th>
      <th>Version</th>
      <th>Internal-Reviewer</th>
      <th>L0-Reviewer</th>
      <th>L1-Reviewer</th>
      <th>L2-Reviewer</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Shubham</td>
      <td>15-04-25</td>
      <td>version 1</td>
      <td>Komal Jaiswal</td>
      <td>Gaurav Singla</td>
      <td>Rahul Gupta</td>
      <td>Mahesh Kumar</td>
    </tr>
  </tbody>
</table>

<h2>Purpose:</h2>
<p>This document provides a step-by-step guide to install and configure Gunicorn (Green Unicorn), a production-grade WSGI server for Python applications.</p>

<h2>1. Prerequisites</h2>
<ul>
  <li>A Linux-based system (Ubuntu/Debian/CentOS recommended)</li>
  <li>Python 3.6+ installed</li>
  <li>pip (Python package manager)</li>
  <li>A Python web application (Flask/Django/FastAPI, etc.)</li>
</ul>

<h2>2. Installation Steps</h2>

<h3>Step 1: Update System Packages</h3>
<pre><code>sudo apt update && sudo apt upgrade -y  # For Debian/Ubuntu

</code></pre>

<h3>Step 2: Install Python & pip (if not installed)</h3>
<pre><code>sudo apt install python3 python3-pip python3-venv -y  # Debian/Ubuntu

</code></pre>

<h3>Step 3: Create a Virtual Environment (Recommended)</h3>
<pre><code>python3 -m venv myenv
source myenv/bin/activate  # Activate the virtual environment
</code></pre>

<h3>Step 4: Install Gunicorn</h3>
<pre><code>pip install gunicorn
</code></pre>

<p><strong>Verify installation:</strong></p>
<pre><code>gunicorn --version
</code></pre>
