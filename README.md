## Synopsis

A simple Unix shell script example to start, stop, restart, and check status of NodeJS forever tool that ensures that a given script runs continuously.

## Installation

You would need to install forever tool globally: 
<div class="highlight highlight-source-shell"><pre>  $ [sudo] npm install forever -g</pre></div>

Place the script into <strong>init.d</strong> directory. 

Update reference according to your system and project setup: 

<h3>Variables</h3>
<pre>
<code>
NAME="myapp"                                Application name
APP_DIRECTORY=/var/www/html/myapp.com       Application directory path to start file
APP_START=server.js                         Application start file name
</code>
</pre>

## Usage

To start the service:
<div class="highlight highlight-source-shell"><pre>  $ [sudo] /etc/init.d/foreverdaemon start</pre></div>

To stop the service:
<div class="highlight highlight-source-shell"><pre>  $ [sudo] /etc/init.d/foreverdaemon stop</pre></div>

To restart the service:
<div class="highlight highlight-source-shell"><pre>  $ [sudo] /etc/init.d/foreverdaemon restart</pre></div>

To get the status:
<div class="highlight highlight-source-shell"><pre>  $ [sudo] /etc/init.d/foreverdaemon status</pre></div>

## License

<a id="user-content-license-mit" class="anchor" href="#license-mit" aria-hidden="true"><span class="octicon octicon-link"></span></a>
License: MIT
