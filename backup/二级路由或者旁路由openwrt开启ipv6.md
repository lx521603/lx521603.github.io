配置/etc/config/dhcp

config dhcp 'wan6' ##旁路由lan6
	option dhcpv6 'relay'
	option ra 'relay'
	option ndp 'relay'
	option master '1'
	option interface 'wan6'

