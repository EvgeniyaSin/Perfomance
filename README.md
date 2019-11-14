# How to create a new Test Plan.
1. Check that the Java is installed.
2. Run the jmeter.bat.
3. Create a Thread Group. Using Thread Group, you can control the number of threads, the time to start all threads, and the number of loops.
4. Add HTTP Request Defaults config element. Set default values for HTTP Request controllers using HTTP Request Defaults in your software load test plan. Let's say, You have a software load test plan with 10 HTTP requests and all requests are being sent to the same server.
 4.1. Enter demo.nopcommerce.com in the Server name or IP box. 
 4.2. Enter 8080 in the Port box. 
 4.3. Enter / in the Path box. 
5. Add Recording controller. The Recording Controller is a place holder indicating where the proxy server should record samples to.
6. Add HTTP Cookie Manager config element. It stores and sends cookies just like a web browser. If you have an HTTP Request and the response contains a cookie, the Cookie Manager automatically stores that cookie and will use it for all future requests to that particular web site.
7. Add HTTP(S) Test Script Recorder Non-test elements. The HTTP(S) Test Script Recorder allows JMeter to intercept and record your actions while viewing a web application using a normal browser.
 7.1. Enter 8080 in the Port box.
8. Set IP=127.0.0.1 and port=8080 in the Settings of the FireFox
9. Click the Record button on the HTTP(S) Test Script Recorder screen in the Jmeter.
10. Follow the necessary steps on the site.
11. Stop recording.
JMeter created a test plan for the steps taken on the site. By changing the settings in JMeter, you can send requests to the site, manage the number of users, etc.

# How to run existing Test Plan in the JMeter.
1. Add the MQA_Yevheniia_Syniavska.jmx file to the .../apache-JMeter/bin.
2. Open the MQA_Yevheniia_Syniavska.jmx in the JMeter.
3. Click the Start button to pass the test plan.
