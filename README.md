# MeshWorks Hosts File 2021.
The MeshWorks TLD hosts file.

Many thanks to:

The Island of Sark, Chief Pleas, Post Office, SilverWorks, News Sources and Ferry Services.

Topsham LETS, The Topsham Pound and Topsham Local Exchange.

 http://topsex.topsham/ or https://communities.cyclos.org/topsex/

Steve Black's Hosts File; 
 https://github.com/StevenBlack/hosts


Instructions:
Copy the contents of "hosts.meshworks" file ^^ into your "hosts" file...
... then restart your browser, and visit:
http://meshworks/


Linux / Android / MacOS: /etc/hosts


The command below (*nix only) will add the dotTopsham TLD to the bottom of your hosts file:

sudo cp /etc/hosts /etc/hosts.backup && wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/meshworks-domain-registry/MeshWorks-Main-Grid/main/hosts.meshworks -O ->> /etc/hosts


Windows 10+: C:\Windows\System32\drivers\etc\hosts

The commands below (Win10+ Only) MAY do the job?


set url=https://raw.githubusercontent.com/meshworks-domain-registry/MeshWorks-Main-Grid/main/hosts.meshworks

set file=hosts.meshworks

certutil -urlcache -split -f %url% %file%

echo Done.


The above code may work on Win10+ machines. 
Otherwise you could rename / overwrite your hosts file, and copy the contents of topsham.hosts at the bottom?
... good luck with that.


