
# data-driven-jmeter-rest-api-test
A simple data-driven approach for using jmeter to write api test


## JMeter Testtrecorder
- https://jmeter.apache.org/usermanual/jmeter_proxy_step_by_step.html

# mock server
Using [JSON-Server](https://github.com/typicode/json-server) to get a full fake REST API.You could also use your application APIs if you have.

<pre><code>  npm i json-server </pre></code>
Once JSON-Server installed, start the server using below command:
<pre><code>json-server --watch db.json</pre></code>

# test secnario in csv
<img src="resources/data.png">

# test script in jmeter
<img src="resources/result.png">

