<h1>IP Geolocation API</h1>
Provides the ability to get the location of an IP address.<br><br>
<table style="width: 90%; margin-left: auto; margin-right: auto;">
<tr>
<td>
<table style="height: 32px; padding: 5px; border: 1px solid #1086E8; color: #999; border-radius: 3px; padding: 0px; font: 14px Tahoma, Arial, sans-serif;">
<tr>
<td style="width: 95px; border: 1px solid #1086E8; border-radius: 3px; background: #fff; padding: 3px; color: #1086E8;">Base API Url: </td>
<td style="font: 13px Tahoma, Arial, sans-serif; padding-left: 4px; padding-right: 123px;">http://api.sgsites.net/</td>
</tr>
</table>
</td><td>
<table style="height: 32px; padding: 5px; border: 1px solid #1086E8; color: #999; border-radius: 3px; padding: 0px; font: 14px Tahoma, Arial, sans-serif;">
<tr>
<td style="width: 95px; border: 1px solid #1086E8; border-radius: 3px; background: #fff; padding: 3px; color: #1086E8;">Secure API Url: </td>
<td style="font: 13px Tahoma, Arial, sans-serif; padding-left: 4px; padding-right: 123px;">https://sgsites.net/api/</td>
</tr>
</table>
</td></tr>
</table>
<br><br>
<table style="height: 32px; padding: 5px; border: 1px solid #1086E8; color: #999; border-radius: 3px; padding: 0px; font: 14px Tahoma, Arial, sans-serif; width: 90%; margin-left: auto; margin-right: auto;">
<tr>
<td style="width: 95px; border: 1px solid #1086E8; border-radius: 3px; background: #fff; padding: 3px; color: #1086E8;">Prefix: </td>
<td style="font: 13px Tahoma, Arial, sans-serif; padding-left: 4px; padding-right: 123px;">geolocation/ [GET: { <b style="color: #0ED62C;">Optional:</b> <u style="color: #0fb4e7; text-decoration: none;">IP</u> }]</td>
</tr>
</table><br><br>
<h2>GET values</h2>
<table style="width: 90%; margin-left: auto; margin-right: auto;">
<tr>
<td style="width: 250px;">[ IP ]</td>
<td>Optional attribute. The following GET value specifies the IP address, for which SGSITES will make a lookup. If left blank, SGSITES will use the remote IP address. <i>Note: Information for private IPs and localhost IPs cannot be retrieved.</i></td>
</tr>
</table><br><br>
<h2>Output</h2>
The service will output as a xml document and will return a &lt;error&gt; tag with description on error.<br><br>
<h2>Example</h2>
With the following example, we will retrieve information about 204.202.20.2:<br>
<a href="http://api.sgsites.net/geolocation/?IP=204.202.20.2" target="_blank">http://api.sgsites.net/geolocation/?IP=204.202.20.2</a>.<br><br>
<h2>Limitations</h2>
Access to this API is provided unrestricted, without the use access tokens. Unlimited requests are served.<br><br>
<h2>Copyright</h2>
Attribution to the SGSITES Technologies or to the EOHP Corporation is required in accordance with the Terms of Use. The service can be used for informational purposes only.
