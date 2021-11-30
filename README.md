# graylog
Graylog materials

<B>NGINX</B><BR>
Complete host file to add SSL layer to your Graylog GUI <BR>
Add server name to your graylog server in /etc/hosts and to your local machine<BR>
Or add into your network DNS service.<BR>

Remember to setup proper cert and key file here:<BR>
  ssl_certificate /etc/ssl/certs/graylog/graylog.crt;<BR>
  ssl_certificate_key /etc/ssl/certs/graylog/graylog.key;<BR>

  
  <B>GROK PATTERNS for Suricata</B><BR>
  Add data from grok_patterns_suricatra to your graylog config in GROK PATTERNS<BR>
  <BR>
