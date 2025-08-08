1.Open Firewall Settings
 • Press Win + R, type control firewall.cpl, hit Enter.
 • Click "Advanced settings" on the left to open Windows Defender Firewall with Advanced Security.
2. View Current Rules
 • In the left panel, click Inbound Rules and Outbound Rules.
 • These list all active rules.
3. Block Inbound Traffic on Port 23
(nmap)
 • Click Inbound Rules > New Rule...
 • Choose Port, then Next.
 • Select TCP and Specific local ports: enter 23 
 • Choose Block the connection, click Next.
 • Apply to all profiles (Domain, Private, Public).
 • Name the rule (e.g. Block Telnet) and click Finish.
4. Test the Rule
5. Remove the Rule
 • Go back to Inbound Rules.
 • Find your Block Telnet rule.
 • Right-click and Delete it.
