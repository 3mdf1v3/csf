# namedCsfPost
	ConfigServer Security & Firewall custom files
# Install
	cd /etc/csf
	git clone https://github.com/3mdf1v3/csfCustom.git
  	vim csf.allow
	    [...]
	    Include /etc/csf/csf.custom/csf.cloudflare
	    [...]
	csf -r
