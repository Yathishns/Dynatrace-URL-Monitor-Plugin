<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>URL Monitor Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>URL Monitor Plugin</h1>
    <div class="section-2"  id="103907986_URLMonitorPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
    </p>
    <div class="confbox admonition admonition-info">
    <p>
Since dynaTrace 4.2 the URL Monitor Plugin that shipped with the product is no longer officially supported. Continued development of this plugin will be done through the Community    </p>
    </div>
    <p>
This plugin extends the <a href="https://community/display/DOCDT55/URL+Monitor">dynaTrace URL Monitor</a> plugin and allows specifying a timeout for connectionsIt's based on a post from the <a href="https://community/pages/viewpage.action?pageId=102269277">dynaTrace Forum</a>.    </p>
    </div>
    <div class="section-2"  id="103907986_URLMonitorPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_121569746_1_com.dynatrace.diagnostics.plugins.UrlPlugin_5.0.0.3773.jar">com.dynatrace.diagnostics.plugins.UrlPlugin_5.0.0.3773.jar</a><br/><a href="attachments_104136856_1_com.dynatrace.diagnostics.plugins.UrlPlugin_4.2.0.3154.jar">com.dynatrace.diagnostics.plugins.UrlPlugin_4.2.0.3154.jar</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Robert K&uuml;hn, T-Systems Multimedia Solutions GmbH    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.2+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    
    <div class="section-2"  id="103907986_URLMonitorPlugin-ProvidedMeasures"  >
        <h2>Provided Measures</h2>
    
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
ConnectionCloseDelay    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Required time to close the server connection.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
ConnectionTimedOut    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1 if the connection timed out, 0 otherwise.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
ContentVerified    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1 if content verification was successful, 0 if not, no value is provided if content verification is disabled.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FirstResponseDelay    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Time elapsed between sending the URL request and receiving the first byte of the response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
HeaderSize    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Size of the response header    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
HostReachable    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1 if the HTTP server sent a response in time, 0 if not.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
HttpStatusCode    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The HTTP status code received from the server mapped to a number.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
ResponseCompleteTime    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Time elapsed between sending the URL request and receiving the last byte of the response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
ResponseSize    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Size of the HTTP response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
SocketTimedOut    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Socket Timeout = 1, otherwise 0.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Throughput    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Average network throughput achieved during retrieval of HTTP response.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="103907986_URLMonitorPlugin-Configuration"  >
        <h2>Configuration</h2>
    <p>
Please see the dynaTrace documentation (    </p>
    <p>
<a href="https://community/display/DOCDT50/URL+Monitor">URL Monitor</a>    </p>
    <p>
) for a description of configuration options. Additional configuration options for this version are:    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Socket Timeout    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
long    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
the socket timeout in ms    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Connection Timeout    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
long    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
the connection timeout in ms    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="103907986_URLMonitorPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the dynaTrace documentation:    </p>
    <p>
<a href="https://community/display/DOCDT50/Plugin+Management">Plugin Management</a>    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
