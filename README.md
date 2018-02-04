# tftpd64
  
## what is it?
tftpd64 is an IPv6 and IPv4 server application for many protocols: DNS, DHCP, SNTP, TFTP, and Syslog  
  
tftpd64 is also a capable TFTP client  
  
## where to download?
https://github.com/peacepenguin/tftpd64/releases  
  
## where is the official source?
This is an unofficial home for tftpd64 since the codeplex hosting site was shutdown and the original author has not yet made a new public repository for source or binary downloads of the latest versions as were found on codeplex. The entire codeplex archive bundle is still available, but unknown for how much longer.  
  
tftpd64 was/is created by:  
Philippe Jounin   
http://tftpd32.jounin.net/tftpd32_download.html  
   
Copied source from Archived CodePlex site:  
https://archive.codeplex.com/?p=tftpd64  
  
## License  
"Tftpd32 and Tftpd64 are released under the European Union Public License" -from original homepage.  
  
2. Scope of the rights granted by the Licence (European Union Public License)  
The Licensor hereby grants You a world-wide, royalty-free, non-exclusive, sub- licensable licence to do the following, for the duration of copyright vested in the Original Work: 
use the Work in any circumstance and for all usage, 
reproduce the Work, 
modify the Original Work, and make Derivative Works based upon the Work, 
communicate to the public, including the right to make available or display the Work or copies thereof to the public and perform publicly, as the case may be, the Work, 
distribute the Work or copies thereof, 
lend and rent the Work or copies thereof, sub-license rights in the Work or copies thereof 

## Original README.txt from codeplex source archive:
This is the complete source code for Tftpd32 and Tftpd64, the industry standard TFTP server.  
  
The code has been splitted into 2 parts :   
  - the GUI management  
  - the background process  
  
They communicate together by messages sent through a TCP socket. In addition to separate processing and display, this allow a remote monitoring for the service edition.  
  
_common and _libs directories contains files which belongs to both parts.  
GUI processing is in the _gui directory.  
Demon and background processing is found into _services directory.  
Initializations are in the _main directory  
  
tftpd32.sln and .vcxproj files are the project files necessary for building the executables.  
  
All code is released under the European Public License, which is compatible with the GPLv2.  
  
### Copyright notice from original author:
TFTPD32 and TFTPD64 are copyrighted 1998-2017 by Philippe Jounin (philippe@jounin.net) and released under the European Union Public License 1.1 (see either the help file or the file EUPL-EN.pdf for the full text of the license)  
  
Official site: http://tftpd32.jounin.net  
  
Tftpd32 and Tftpd64 use the following copyrights or contributions  
  - MD5 part is from RSA Data Security  
  - IP checksum computation is from Mike Muss  
  - DHCP lease persistance is from Nick Wagner   
  - DHCP opts 82, 42 and 120 from Jesus Soto  
  - DHCP header file from The Internet Software  
    Consortium  
  



