# Bug_mithdology

/////////////////////

Bug Bounty Hunter Methodology v3
	https://www.youtube.com/watch?v=Qw1nNPiH_Go&t=480s
	
/////////////////

# LEARN SHODAN

# LEARN GOOGLE DOCKES

# LEARN MASSCAN 

# LEARN BRUTESPRAY

# LEARN XMIND

========================

Img of All Methodology

https://raw.githubusercontent.com/axosecurity/Bug_mithdology/main/Screenshot%20from%202022-05-24%2017-33-07.png

-----------------------------------------------

PARTS OF THIS METHODOlogy
	
=DISCOVERING TARGET DOMAIN {	

	1 Discovering IP Space
	
	2 DISCOVERING NEW Targets
	
	3 DOM LINK TOOL

	4 builtwith.com
}

=DISCOVERING TARGET SUBDOMAIN {

video on subdomain_enumaration
https://www.youtube.com/watch?v=e_Gq99CKAys


	1 Amass
	
	2 Subfinder
	
	3 cloudflare_enum

	4 MASSDNS 

	5 Commonspeak 


}

ENUMARATION {

	1 PORT SCANNING #<
	
		1/1 MASSCAN
		
	#>
		
	2 Credential bruteforce #< 
	
		2/1 BruteSpray
		
		2/2 medusa
		
	
	#>

	3 VIsual identification #<
	
		3/1 httpprobe
		
		3/2 EyeWitness
	
	#>

	4 WayBack Enumaration #<
	
		4/1 waybackurl
	
	#>

	5 Xmind 
	[ Mind Mapping Tool]

	6 Platform identification and cve searching #<
		
		6/1 Retire.js 
		
		6/2 wappalyzer
	
		6/3 builtwith.com
		
		6/4 burp-vulners-scanner


	#>
	
	7 Parsing javascript
	
		7/1 js parser
		
		7/3 ScriptHunter
	
		7/4 Js mon
	
		7/5 linkfinder [beetter than js parser ]


	8 Content Discovery
	
		8/1 Gobuster
		
		8/2  RobotsDisallowed
		
		8/3 Content_discovery_all.txt

	9 Parameter Bruthforceing
	
		9/1 parameth

		9/2 List_of_parameter
		
	
	
	10 XSS
		
		10/1 bxxs
		
		10/2 ezxss	


	11 SSRF
	
		cloud_meteadata.txt
	
	
	12 IDOR
	
		12/1 
		
	14 Hashes
		
		14/1 Hash Buster	

	15 Subdomain Take over
		
		15/1 can-i-take-over-xyz
	
	
	16 Robbing Misconfigured 
	
		16/1 S3Scanner	


}












==========================================================================================

		DISCOVERING IP SPACE 
		

1st WEBSITE 
	https://bgp.he.net/

[ JUST SEARCH A KEYWORD and Get your data ]

2nd WEBSITE
	https://whois.arin.net/ui/query.do
	
[ JUST SEARCH A KEYWORD and Get your data ]


3rd WEBSITE
	https://apps.db.ripe.net/db-web-ui/query?bflag=false&dflag=false&rflag=true&searchtext=&source=RIPE
	
[ JUST SEARCH A KEYWORD and Get your data ]





---------------------------------------------------------------------------------


	DISCOVERING NEW TARGETS

	GRAPH IMG OF DISCOVERING NEW TARGETS	
  
https://github.com/axosecurity/Bug_mithdology/blob/main/Screenshot%20from%202022-05-20%2009-53-44.png?raw=true


[USE BURPSUITE SPIDER FOR ThiS LINKED HOST DISCOVERY]
	USE BURPSUITE OLD VERSION FOR SPIDERING THE FUCKING WEBSITE
	


---------------------------------------------------------------------------

	DOM LINK TOOL
	
GITHUB REPO = https://github.com/vysecurity/DomLink

///INFO ABOUT TOOL

	DomLink is a tool that uses a domain name to discover organisation name and associated e-mail 
	address to then find further associated domains.

	This is useful for bug bounty and red team engagements where you need to discover more domains 		 
	associated with the target.

COMAND = 
	python domLink.py -D target.com -o target.out.txt
	
	
	
--------------------------------------------------------------------

	

	builtwith.com

THIS TOOL WILL GIVE YOU ALL INFO OF TECHNOLOGY BACKEND AND FRONTEND

	https://builtwith.com/



---------------------------------------------------------------------------------
/////////////////////  DISCOVERING TARGET SUBDOMAIN \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
---------------------------------------------------------------------------------

	AMASS
	
Github REPOSITORY
	
	https://github.com/OWASP/Amass


-------------------------------------------------------------------

	SUBFINDER

Github REPOSITORY
	
	https://github.com/projectdiscovery/subfinder


---------------------------------------------------------------------

	cloudflare_enum

github Repository
	
	https://github.com/mandatoryprogrammer/cloudflare_enum
	
	
	
-------------------------------------------------------------------------

	MassDns
	
Github Repository
	
	https://github.com/blechschmidt/massdns
	
SUBDOMAIN_LIST
	
	https://gist.github.com/jhaddix/86a06c5dc309d08580a018c66354a056
	
COMAND FOR DOWNLOAD SUBDOAMIN_BIGGEST LIST

wget https://gist.githubusercontent.com/jhaddix/86a06c5dc309d08580a018c66354a056/raw/96f4e51d96b2203f19f6381c8c545b278eaa0837/all.txt 


	
---------------------------------------------------------------------------------------------	
	
	Commonspeak
	
Github REPO
	
	https://github.com/pentester-io/commonspeak.git
	
video for learning
	
	https://www.youtube.com/watch?v=GxkuBFUfnL8&t=223s
	
	https://www.youtube.com/watch?v=QGbTaxtEQlg&t=5s
	
	
	
--------------------------------------------------------------------------------------
////////////////// PORT SCANNEING \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
-------------------------------------------------------------------------------------
	
	 MASSCAN
	
IMG =
https://github.com/axosecurity/Bug_mithdology/blob/main/Screenshot%20from%202022-05-22%2021-35-03.png?raw=true

github REPOsitory =
	https://github.com/robertdavidgraham/masscan
	

-------------------------------------------------------------------------------------------

	Httpprobe
	
github =
	https://github.com/tomnomnom/httprobe
	
--------------------------------------------------------------------------------------------

	EyeWitness
	
github =
	https://github.com/FortyNorthSecurity/EyeWitness
	

------------------------------------------------------------------------------------------

	WayBackUrl
	
IMG= 

https://github.com/axosecurity/Bug_mithdology/blob/main/Screenshot%20from%202022-05-22%2022-21-33.png?raw=true

Github = 

https://github.com/tomnomnom/waybackurls	
	
youtube =

https://www.youtube.com/watch?v=-zsYi0_xWbo


-----------------------------------------------------------------------------------------------

	Xmind	
	
installtion
	
	sudo snap install xmind

website 

	https://www.xmind.net/
	
yt
	https://www.youtube.com/watch?v=7HG-p6843Sg
	
	
	
	
-----------------------------------------------------------------------------------------------

	Retire.js

github =
	
	https://github.com/portswigger/retire-js
	
	https://github.com/retirejs/retire.js/
	
video =

https://www.youtube.com/watch?v=exZrQCAMV-I

https://www.youtube.com/watch?v=_EKQScey6nk
	
	
	
---------------------------------------------------------------------------------------

	wappalyze
	
video 

https://www.youtube.com/watch?v=OQMtMchO0NM	

github 

https://github.com/wappalyzer/wappalyzer	
	
--------------------------------------------------------------------------------------	
	
	burp-vulners-scanner
	
github 

https://github.com/vulnersCom/burp-vulners-scanner


---------------------------------------------------------------------------------------
/////////////// Parseing Javascript \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
-------------------------------------------------------------------------------------
	Js parser
	
github 

https://github.com/vulnersCom/burp-vulners-scanner

video 

https://www.youtube.com/watch?v=vUrx113ZtEw	


-----------------------------------------------------------------------------	

	Script Hunter
	
github 

https://github.com/robre/scripthunter

	
	
-------------------------------------------------------------------------------

	JSMON
	
github 
 
https://github.com/robre/jsmon


----------------------------------------------------------------------------

	LinkFinder
	
github 

https://github.com/GerbenJavado/LinkFinder



----------------------------------------------------------------------------
////////////////// Content Discovery \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
*------------------------------------------------------------------------------

	Gobuster
	
github 

https://github.com/OJ/gobuster.git

----------------------------------------------------------------------------------

	 RobotsDisallowed
	 
github 

https://github.com/danielmiessler/RobotsDisallowed


----------------------------------------------------------------------------------

	content_discovery_all.txt
	
github

https://gist.github.com/jhaddix/b80ea67d85c13206125806f0828f4d10


-----------------------------------------------------------------------------------
///////////////// Parameter BrutForceing \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
-------------------------------------------------------------------------------------

	parameth
	
github 

https://github.com/maK-/parameth

----------------------------------------------------------------------------------

	List_of_parameter
	
github 

https://github.com/PortSwigger/backslash-powered-scanner/blob/master/resources/params

-------------------------------------------------------------------------------------
////////////////////// XSS \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
--------------------------------------------------------------------------------------

	bXSS
	
github 

https://github.com/LewisArdern/bXSS

------------------------------------------------------------------------------------------

	ezXSS
	
github 

https://github.com/ssl/ezXSS

------------------------------------------------------------------------------------
/////////////////////// SSRF \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
-----------------------------------------------------------------------------------

	Cloud_metadata.txt
	
github

https://gist.github.com/jhaddix/78cece26c91c6263653f31ba453e273b

-----------------------------------------------------------------------------------

	Hash Buster
	
github

https://github.com/s0md3v/Hash-Buster


--------------------------------------------------------------------------
///////////// Sub-Domain-Take-Over\\\\\\\\\\\\\\\\\\\\\\\\\\\
------------------------------------------------------------------------

	can-i-take-over-xyz
	
github

https://github.com/EdOverflow/can-i-take-over-xyz


-----------------------------------------------------------------------------

	S3Scanner
	
github 

https://github.com/sa7mon/S3Scanner














































