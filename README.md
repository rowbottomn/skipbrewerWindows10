# Skip Brewer Windows 10 Image
Local Policy - Security Options
1	Accounts: Guest account status	Disabled
2	Devices: Prevent users from installing printer drivers	Enabled
3	Devices: Restrict CD-ROM access to locally logged-on user only	Enabled
4	Interactive logon: Do not display last user name	Enabled
Account Policies - Account Lockout Policy
5	Account lockout threshold	Any value from 3 to 10
Account Policies - Password Policy
6	Enforce password history	Any value from 3 to 20
7	Minimum password age	Any value from 3 to 10
8	Minimum password length	Any value from 5 to 14
9	Password must meet complexity requirements	Enabled
Installed Programs
10	Core FTP Server	Uninstall Core FTP Server
11	MediaMonkey 4.1	Uninstall MediaMonkey 4.1
Users
12	Administrator	Account is disabled:True
13	Charlie Brown	Password never expires:False
14	Guest	Account is disabled:True
15	Linus	User must change password
16	Lucy	User must change password
17	Marcie	Account is disabled:True
18	Peppermint Patty	User must change password
19	Peppermint Patty	Account is disabled:False
20	Red Baron	Account is disabled:True
21	Schroeder	Account is disabled:False
22	Snoopy	User must change password
Groups
23	Administrators	Administrator
Snoopy
Peppermint Patty
Shares
24	Users	Stop sharing C:\Users
Firewall Profiles
25	Private Profile	Firewall State: On
26	Public Profile	Firewall State: On
Services
27	IP Helper	Stopped - Disabled
28	Microsoft FTP Service	Stopped - Disabled
29	Remote Desktop Services	Running - Automatic
30	RIP Listener	Stopped - Disabled
31	SNMP Service	Stopped - Disabled
32	Windows Event Log	Running - Automatic
Other
33	Remote Desktop	Allow connections only from computers running Remote Desktop with Network Level Authentication (more secure)
