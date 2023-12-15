# Incident Report

<table>
  <thead>
    <tr>
      <th>Incident Report</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <h3>Summary</h3>
        <p>
          This morning, our company experienced a DDoS attack that compromised the internal network for approximately two hours. This attack flooded our system with ICMP packets which caused our network to stop responding to regular traffic.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h3>Identify</h3>
        <p>
          After discovering the security incident, the cybersecurity team of the company initiated an investigation. Their findings revealed that an unauthorized individual had launched an extensive barrage of ICMP pings into the company's network by exploiting an inadequately configured firewall. This vulnerability enabled the attacker to overpower the company's network by executing a distributed denial of service (DDoS) assault.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h3>Protect</h3>
        <p>
          The cybersecurity team implemented a series of measures in response to the security event. Firstly, they established a new firewall rule that limits the rate of incoming ICMP packets. This restriction aimed to prevent overwhelming influxes of ICMP traffic. Additionally, the team incorporated source IP address verification on the firewall, which enabled them to identify and block any incoming ICMP packets with spoofed IP addresses.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h3>Detect</h3>
        <p>
          To enhance security measures, the cybersecurity team implemented source IP address verification on the firewall, effectively scrutinizing incoming ICMP packets for any signs of spoofed IP addresses. This configuration ensured that only legitimate and authorized IP addresses were allowed through. Furthermore, they deployed network monitoring software that actively detected and identified any irregular traffic patterns, enabling swift identification and response to potential threats.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h3>Recover</h3>
        <p>
          The cybersecurity team will take measures to isolate affected systems, effectively preventing any further disruption to the network. They will make diligent efforts to restore any critical systems and services that were disrupted as a result of the event. Subsequently, the team will conduct a thorough analysis of network logs to identify any indications of suspicious or abnormal activity.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <h3>Respond</h3>
        <p>
          The implementation of network monitoring software was carried out to detect any abnormal traffic patterns. This software will continuously monitor the network, promptly identifying any unusual or suspicious activity that could indicate a security breach.
        </p>
      </td>
    </tr>
  </tbody>
</table>
