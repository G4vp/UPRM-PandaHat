<h1>UPRM-PandaHat</h1>
<h2>Lab 1: Exploiting a Smart Plug</h2>
------------------------------
<h3>Description: </h3>
<p> In this lab, we are going to exploit an Orvibo Smart plug,
using mobile application reversing, native library analysis and
network traffic capturing techniques.

Mobile applications for loT devices are often riddled with a
number of security issues, which when identified and exploit-
ed can lead to the complete takeover of the loT device.
We will start by reverse engineering the Android mobile ap-
plication of the Orvibo Smart Plug using JADX which will help
us understand how the application work behind the scenes,
as well as to find the encryption type and encryption key
used by the application and device to encrypt and decrypt
the initial commands.

Once we have identified the encryption type and key, we
will then set up a hotspot to capture the traffic between the
mobile application, device and the remote endpoint using
Wireshark. This step will also allow us to obtain the unique
device key used for the device control commands.
Finally, we will use a custom script to control the device using
the obtained information. </p>

<h3>Lab Steps</h3>
<ol>
<li>
  <h4>Reverse Engineering the mobile Application</h4>
  <p>Utilized JADX to navigate the Android application source code to find where the encryption key is located.
Jadx Command: $ jadx-gui homemate.apk</p>
</li>
<li>
  <h4>Network traffic sniffing:</h4>
    <p>
    blablabla*algo que diria chatgpt* bla bla
  </p>
 </li>
<li>
    <h4>Exploiting Smart Plug</h4>
  <p>
    blablabla*algo que diria chatgpt* bla bla
  </p>
 </li>
</ol>
