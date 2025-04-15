
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

<h2>Contact Information</h2>
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Email address</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Shubham Prasad</td>
      <td>shubham.prasad.snaatak@mygurukulam.co</td>
    </tr>
  </tbody>
</table>

<h2>References</h2>
<table>
  <thead>
    <tr>
      <th>Links</th>
      <th>Descriptions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.jenkins.io/doc/book/installing/linux/#debianubuntu" target="_blank">Jenkins Installation Guide</a></td>
      <td>Document format followed from this link</td>
    </tr>
    <tr>
      <td><a href="https://amplifi.com/user-guide/FAQs.html" target="_blank">Amplifi FAQs</a></td>
      <td>Documentation referred for the table of contents to be included</td>
    </tr>
    <tr>
      <td><a href="https://thecontentauthority.com/blog/introduction-vs-overview" target="_blank">Introduction vs Overview</a></td>
      <td>This link explains the difference between Overview & Intro</td>
    </tr>
  </tbody>
</table>

<h2>Pages: 3</h2>

<h3>Find a page…</h3>
<ul>
  <li>Home</li>
  <li>Application Template</li>
  <li>Purpose</li>
  <li>Pre-requisites</li>
  <li>System Requirements</li>
  <li>Dependencies
    <ul>
      <li>Build time Dependency</li>
      <li>Run time Dependency</li>
      <li>Other Dependency</li>
    </ul>
  </li>
  <li>Important Ports</li>
  <li>Others</li>
  <li>Architecture</li>
  <li>Dataflow Diagram</li>
  <li>Step-by-step installation of [application]
    <ul>
      <li>Step1: Installation of software Dependencies
        <ul>
          <li>Build Dependency</li>
          <li>Run time Dependency</li>
          <li>Other Dependency</li>
        </ul>
      </li>
      <li>Step2: Build/Artifact Generation</li>
      <li>Step3: Application Deployment</li>
    </ul>
  </li>
  <li>Monitoring
    <ul>
      <li>Metrics</li>
      <

