Microsoft Windows [Version 10.0.19044.1620]
(c) Microsoft Corporation. All rights reserved.

C:\Users\KIIT>cd Downloads

C:\Users\KIIT\Downloads>ssh -i "Instance.pem" ec2-user@ec2-54-149-180-11.us-west-2.compute.amazonaws.com
Last login: Wed Apr 13 07:11:43 2022 from 49.37.96.170

Last login: Wed Apr 13 07:11:43 2022 from 49.37.96.170

       __|  __|_  )
       _|  (     /   Amazon Linux 2 AMI
      ___|\___|___|

https://aws.amazon.com/amazon-linux-2/
14 package(s) needed for security, out of 17 available
Run "sudo yum update" to apply all updates.
[ec2-user@ip-172-31-5-25 ~]$ sudo vim /etc/yum.repos.d/grafana.repo

[1]+  Stopped                 sudo vim /etc/yum.repos.d/grafana.repo
[ec2-user@ip-172-31-5-25 ~]$ sudo vim /etc/yum.repos.d/grafana.repo

[2]+  Stopped                 sudo vim /etc/yum.repos.d/grafana.repo
[ec2-user@ip-172-31-5-25 ~]$ sudo vi /etc/yum.repos.d/grafana.repo
[ec2-user@ip-172-31-5-25 ~]$ sudo vi /etc/yum.repos.d/grafana.repo

[3]+  Stopped                 sudo vi /etc/yum.repos.d/grafana.repo
[ec2-user@ip-172-31-5-25 ~]$ sudo yum istall grafana
Loaded plugins: extras_suggestions, langpacks, priorities, update-motd
No such command: istall. Please use /bin/yum --help
[ec2-user@ip-172-31-5-25 ~]$ sudo yum install grafana
Loaded plugins: extras_suggestions, langpacks, priorities, update-motd


File contains no section headers.
file: file:///etc/yum.repos.d/grafana.repo, line: 1
']\n'
[ec2-user@ip-172-31-5-25 ~]$ sudo vi /etc/yum.repos.d/grafana.repo
[ec2-user@ip-172-31-5-25 ~]$ sudo yum install grafana
Loaded plugins: extras_suggestions, langpacks, priorities, update-motd
amzn2-core                                                                                                                                           | 3.7 kB  00:00:00
grafana/signature                                                                                                                                    |  454 B  00:00:00
Retrieving key from https://packages.grafana.com/gpg.key
Importing GPG key 0x24098CB6:
 Userid     : "Grafana <info@grafana.com>"
 Fingerprint: 4e40 ddf6 d76e 284a 4a67 80e4 8c8c 34c5 2409 8cb6
 From       : https://packages.grafana.com/gpg.key
Is this ok [y/N]: y
grafana/signature                                                                                                                                    | 3.0 kB  00:00:03 !!!
grafana/primary_db                                                                                                                                   | 132 kB  00:00:00
Resolving Dependencies
--> Running transaction check
---> Package grafana.x86_64 0:8.4.6-1 will be installed
--> Processing Dependency: fontconfig for package: grafana-8.4.6-1.x86_64
--> Processing Dependency: urw-fonts for package: grafana-8.4.6-1.x86_64
--> Running transaction check
---> Package fontconfig.x86_64 0:2.13.0-4.3.amzn2 will be installed
--> Processing Dependency: fontpackages-filesystem for package: fontconfig-2.13.0-4.3.amzn2.x86_64
--> Processing Dependency: dejavu-sans-fonts for package: fontconfig-2.13.0-4.3.amzn2.x86_64
---> Package urw-base35-fonts.noarch 0:20170801-10.amzn2 will be installed
--> Processing Dependency: urw-base35-fonts-common = 20170801-10.amzn2 for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-z003-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-standard-symbols-ps-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-p052-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-nimbus-sans-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-nimbus-roman-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-nimbus-mono-ps-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-gothic-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-d050000l-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-c059-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: urw-base35-bookman-fonts for package: urw-base35-fonts-20170801-10.amzn2.noarch
--> Running transaction check
---> Package dejavu-sans-fonts.noarch 0:2.33-6.amzn2 will be installed
--> Processing Dependency: dejavu-fonts-common = 2.33-6.amzn2 for package: dejavu-sans-fonts-2.33-6.amzn2.noarch
---> Package fontpackages-filesystem.noarch 0:1.44-8.amzn2 will be installed
---> Package urw-base35-bookman-fonts.noarch 0:20170801-10.amzn2 will be installed
--> Processing Dependency: xorg-x11-server-utils for package: urw-base35-bookman-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: xorg-x11-server-utils for package: urw-base35-bookman-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: xorg-x11-font-utils for package: urw-base35-bookman-fonts-20170801-10.amzn2.noarch
--> Processing Dependency: xorg-x11-font-utils for package: urw-base35-bookman-fonts-20170801-10.amzn2.noarch
---> Package urw-base35-c059-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-d050000l-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-fonts-common.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-gothic-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-nimbus-mono-ps-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-nimbus-roman-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-nimbus-sans-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-p052-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-standard-symbols-ps-fonts.noarch 0:20170801-10.amzn2 will be installed
---> Package urw-base35-z003-fonts.noarch 0:20170801-10.amzn2 will be installed
--> Running transaction check
---> Package dejavu-fonts-common.noarch 0:2.33-6.amzn2 will be installed
---> Package xorg-x11-font-utils.x86_64 1:7.5-21.amzn2 will be installed
--> Processing Dependency: libfontenc.so.1()(64bit) for package: 1:xorg-x11-font-utils-7.5-21.amzn2.x86_64
---> Package xorg-x11-server-utils.x86_64 0:7.7-20.amzn2.0.2 will be installed
--> Processing Dependency: libXxf86vm.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXxf86misc.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXt.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXrender.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXrandr.so.2()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXmuu.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXmu.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXinerama.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXi.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXext.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libXcursor.so.1()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libX11.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Processing Dependency: libICE.so.6()(64bit) for package: xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64
--> Running transaction check
---> Package libICE.x86_64 0:1.0.9-9.amzn2.0.2 will be installed
---> Package libX11.x86_64 0:1.6.7-3.amzn2.0.2 will be installed
--> Processing Dependency: libX11-common >= 1.6.7-3.amzn2.0.2 for package: libX11-1.6.7-3.amzn2.0.2.x86_64
--> Processing Dependency: libxcb.so.1()(64bit) for package: libX11-1.6.7-3.amzn2.0.2.x86_64
---> Package libXcursor.x86_64 0:1.1.15-1.amzn2 will be installed
--> Processing Dependency: libXfixes.so.3()(64bit) for package: libXcursor-1.1.15-1.amzn2.x86_64
---> Package libXext.x86_64 0:1.3.3-3.amzn2.0.2 will be installed
---> Package libXi.x86_64 0:1.7.9-1.amzn2.0.2 will be installed
---> Package libXinerama.x86_64 0:1.1.3-2.1.amzn2.0.2 will be installed
---> Package libXmu.x86_64 0:1.1.2-2.amzn2.0.2 will be installed
---> Package libXrandr.x86_64 0:1.5.1-2.amzn2.0.3 will be installed
---> Package libXrender.x86_64 0:0.9.10-1.amzn2.0.2 will be installed
---> Package libXt.x86_64 0:1.1.5-3.amzn2.0.2 will be installed
--> Processing Dependency: libSM.so.6()(64bit) for package: libXt-1.1.5-3.amzn2.0.2.x86_64
---> Package libXxf86misc.x86_64 0:1.0.3-7.1.amzn2.0.2 will be installed
---> Package libXxf86vm.x86_64 0:1.1.4-1.amzn2.0.2 will be installed
---> Package libfontenc.x86_64 0:1.1.3-3.amzn2.0.2 will be installed
--> Running transaction check
---> Package libSM.x86_64 0:1.2.2-2.amzn2.0.2 will be installed
---> Package libX11-common.noarch 0:1.6.7-3.amzn2.0.2 will be installed
---> Package libXfixes.x86_64 0:5.0.3-1.amzn2.0.2 will be installed
---> Package libxcb.x86_64 0:1.12-1.amzn2.0.2 will be installed
--> Processing Dependency: libXau.so.6()(64bit) for package: libxcb-1.12-1.amzn2.0.2.x86_64
--> Running transaction check
---> Package libXau.x86_64 0:1.0.8-2.1.amzn2.0.2 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

============================================================================================================================================================================
 Package                                                    Arch                         Version                                     Repository                        Size
============================================================================================================================================================================
Installing:
 grafana                                                    x86_64                       8.4.6-1                                     grafana                           72 M
Installing for dependencies:
 dejavu-fonts-common                                        noarch                       2.33-6.amzn2                                amzn2-core                        64 k
 dejavu-sans-fonts                                          noarch                       2.33-6.amzn2                                amzn2-core                       1.4 M
 fontconfig                                                 x86_64                       2.13.0-4.3.amzn2                            amzn2-core                       253 k
 fontpackages-filesystem                                    noarch                       1.44-8.amzn2                                amzn2-core                        10 k
 libICE                                                     x86_64                       1.0.9-9.amzn2.0.2                           amzn2-core                        67 k
 libSM                                                      x86_64                       1.2.2-2.amzn2.0.2                           amzn2-core                        39 k
 libX11                                                     x86_64                       1.6.7-3.amzn2.0.2                           amzn2-core                       606 k
 libX11-common                                              noarch                       1.6.7-3.amzn2.0.2                           amzn2-core                       165 k
 libXau                                                     x86_64                       1.0.8-2.1.amzn2.0.2                         amzn2-core                        29 k
 libXcursor                                                 x86_64                       1.1.15-1.amzn2                              amzn2-core                        30 k
 libXext                                                    x86_64                       1.3.3-3.amzn2.0.2                           amzn2-core                        39 k
 libXfixes                                                  x86_64                       5.0.3-1.amzn2.0.2                           amzn2-core                        18 k
 libXi                                                      x86_64                       1.7.9-1.amzn2.0.2                           amzn2-core                        41 k
 libXinerama                                                x86_64                       1.1.3-2.1.amzn2.0.2                         amzn2-core                        14 k
 libXmu                                                     x86_64                       1.1.2-2.amzn2.0.2                           amzn2-core                        72 k
 libXrandr                                                  x86_64                       1.5.1-2.amzn2.0.3                           amzn2-core                        27 k
 libXrender                                                 x86_64                       0.9.10-1.amzn2.0.2                          amzn2-core                        26 k
 libXt                                                      x86_64                       1.1.5-3.amzn2.0.2                           amzn2-core                       177 k
 libXxf86misc                                               x86_64                       1.0.3-7.1.amzn2.0.2                         amzn2-core                        19 k
 libXxf86vm                                                 x86_64                       1.1.4-1.amzn2.0.2                           amzn2-core                        17 k
 libfontenc                                                 x86_64                       1.1.3-3.amzn2.0.2                           amzn2-core                        31 k
 libxcb                                                     x86_64                       1.12-1.amzn2.0.2                            amzn2-core                       216 k
 urw-base35-bookman-fonts                                   noarch                       20170801-10.amzn2                           amzn2-core                       852 k
 urw-base35-c059-fonts                                      noarch                       20170801-10.amzn2                           amzn2-core                       880 k
 urw-base35-d050000l-fonts                                  noarch                       20170801-10.amzn2                           amzn2-core                        75 k
 urw-base35-fonts                                           noarch                       20170801-10.amzn2                           amzn2-core                       7.8 k
 urw-base35-fonts-common                                    noarch                       20170801-10.amzn2                           amzn2-core                        19 k
 urw-base35-gothic-fonts                                    noarch                       20170801-10.amzn2                           amzn2-core                       650 k
 urw-base35-nimbus-mono-ps-fonts                            noarch                       20170801-10.amzn2                           amzn2-core                       797 k
 urw-base35-nimbus-roman-fonts                              noarch                       20170801-10.amzn2                           amzn2-core                       860 k
 urw-base35-nimbus-sans-fonts                               noarch                       20170801-10.amzn2                           amzn2-core                       1.3 M
 urw-base35-p052-fonts                                      noarch                       20170801-10.amzn2                           amzn2-core                       978 k
 urw-base35-standard-symbols-ps-fonts                       noarch                       20170801-10.amzn2                           amzn2-core                        40 k
 urw-base35-z003-fonts                                      noarch                       20170801-10.amzn2                           amzn2-core                       275 k
 xorg-x11-font-utils                                        x86_64                       1:7.5-21.amzn2                              amzn2-core                       103 k
 xorg-x11-server-utils                                      x86_64                       7.7-20.amzn2.0.2                            amzn2-core                       179 k

Transaction Summary
============================================================================================================================================================================
Install  1 Package (+36 Dependent packages)

Total download size: 82 M
Installed size: 262 M
Is this ok [y/d/N]: y
Downloading packages:
(1/37): dejavu-fonts-common-2.33-6.amzn2.noarch.rpm                                                                                                  |  64 kB  00:00:00
(2/37): fontconfig-2.13.0-4.3.amzn2.x86_64.rpm                                                                                                       | 253 kB  00:00:00
(3/37): fontpackages-filesystem-1.44-8.amzn2.noarch.rpm                                                                                              |  10 kB  00:00:00
(4/37): dejavu-sans-fonts-2.33-6.amzn2.noarch.rpm                                                                                                    | 1.4 MB  00:00:00
(5/37): libICE-1.0.9-9.amzn2.0.2.x86_64.rpm                                                                                                          |  67 kB  00:00:00
(6/37): libSM-1.2.2-2.amzn2.0.2.x86_64.rpm                                                                                                           |  39 kB  00:00:00
(7/37): libX11-1.6.7-3.amzn2.0.2.x86_64.rpm                                                                                                          | 606 kB  00:00:00
(8/37): libX11-common-1.6.7-3.amzn2.0.2.noarch.rpm                                                                                                   | 165 kB  00:00:00
(9/37): libXau-1.0.8-2.1.amzn2.0.2.x86_64.rpm                                                                                                        |  29 kB  00:00:00
(10/37): libXcursor-1.1.15-1.amzn2.x86_64.rpm                                                                                                        |  30 kB  00:00:00
(11/37): libXext-1.3.3-3.amzn2.0.2.x86_64.rpm                                                                                                        |  39 kB  00:00:00
(12/37): libXi-1.7.9-1.amzn2.0.2.x86_64.rpm                                                                                                          |  41 kB  00:00:00
(13/37): libXfixes-5.0.3-1.amzn2.0.2.x86_64.rpm                                                                                                      |  18 kB  00:00:00
(14/37): libXinerama-1.1.3-2.1.amzn2.0.2.x86_64.rpm                                                                                                  |  14 kB  00:00:00
(15/37): libXmu-1.1.2-2.amzn2.0.2.x86_64.rpm                                                                                                         |  72 kB  00:00:00
(16/37): libXrandr-1.5.1-2.amzn2.0.3.x86_64.rpm                                                                                                      |  27 kB  00:00:00
(17/37): libXrender-0.9.10-1.amzn2.0.2.x86_64.rpm                                                                                                    |  26 kB  00:00:00
(18/37): libXt-1.1.5-3.amzn2.0.2.x86_64.rpm                                                                                                          | 177 kB  00:00:00
(19/37): libXxf86misc-1.0.3-7.1.amzn2.0.2.x86_64.rpm                                                                                                 |  19 kB  00:00:00
(20/37): libXxf86vm-1.1.4-1.amzn2.0.2.x86_64.rpm                                                                                                     |  17 kB  00:00:00
(21/37): libfontenc-1.1.3-3.amzn2.0.2.x86_64.rpm                                                                                                     |  31 kB  00:00:00
(22/37): libxcb-1.12-1.amzn2.0.2.x86_64.rpm                                                                                                          | 216 kB  00:00:00
(23/37): urw-base35-bookman-fonts-20170801-10.amzn2.noarch.rpm                                                                                       | 852 kB  00:00:00
(24/37): urw-base35-c059-fonts-20170801-10.amzn2.noarch.rpm                                                                                          | 880 kB  00:00:00
(25/37): urw-base35-d050000l-fonts-20170801-10.amzn2.noarch.rpm                                                                                      |  75 kB  00:00:00
(26/37): urw-base35-fonts-20170801-10.amzn2.noarch.rpm                                                                                               | 7.8 kB  00:00:00
(27/37): urw-base35-fonts-common-20170801-10.amzn2.noarch.rpm                                                                                        |  19 kB  00:00:00
(28/37): urw-base35-nimbus-mono-ps-fonts-20170801-10.amzn2.noarch.rpm                                                                                | 797 kB  00:00:00
(29/37): urw-base35-gothic-fonts-20170801-10.amzn2.noarch.rpm                                                                                        | 650 kB  00:00:00
(30/37): urw-base35-nimbus-roman-fonts-20170801-10.amzn2.noarch.rpm                                                                                  | 860 kB  00:00:00
(31/37): urw-base35-nimbus-sans-fonts-20170801-10.amzn2.noarch.rpm                                                                                   | 1.3 MB  00:00:00
(32/37): urw-base35-p052-fonts-20170801-10.amzn2.noarch.rpm                                                                                          | 978 kB  00:00:00
(33/37): urw-base35-standard-symbols-ps-fonts-20170801-10.amzn2.noarch.rpm                                                                           |  40 kB  00:00:00
(34/37): urw-base35-z003-fonts-20170801-10.amzn2.noarch.rpm                                                                                          | 275 kB  00:00:00
(35/37): xorg-x11-font-utils-7.5-21.amzn2.x86_64.rpm                                                                                                 | 103 kB  00:00:00
(36/37): xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64.rpm                                                                                           | 179 kB  00:00:00
warning: /var/cache/yum/x86_64/2/grafana/packages/grafana-8.4.6-1.x86_64.rpm: Header V4 RSA/SHA256 Signature, key ID 24098cb6: NOKEY      ]  17 MB/s |  71 MB  00:00:00 ETA
Public key for grafana-8.4.6-1.x86_64.rpm is not installed
(37/37): grafana-8.4.6-1.x86_64.rpm                                                                                                                  |  72 MB  00:00:02
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                                                        35 MB/s |  82 MB  00:00:02
Retrieving key from https://packages.grafana.com/gpg.key
Importing GPG key 0x24098CB6:
 Userid     : "Grafana <info@grafana.com>"
 Fingerprint: 4e40 ddf6 d76e 284a 4a67 80e4 8c8c 34c5 2409 8cb6
 From       : https://packages.grafana.com/gpg.key
Is this ok [y/N]: y
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : libICE-1.0.9-9.amzn2.0.2.x86_64                                                                                                                         1/37
  Installing : fontpackages-filesystem-1.44-8.amzn2.noarch                                                                                                             2/37
  Installing : urw-base35-fonts-common-20170801-10.amzn2.noarch                                                                                                        3/37
  Installing : dejavu-fonts-common-2.33-6.amzn2.noarch                                                                                                                 4/37
  Installing : dejavu-sans-fonts-2.33-6.amzn2.noarch                                                                                                                   5/37
  Installing : fontconfig-2.13.0-4.3.amzn2.x86_64                                                                                                                      6/37
  Installing : libSM-1.2.2-2.amzn2.0.2.x86_64                                                                                                                          7/37
  Installing : libfontenc-1.1.3-3.amzn2.0.2.x86_64                                                                                                                     8/37
  Installing : 1:xorg-x11-font-utils-7.5-21.amzn2.x86_64                                                                                                               9/37
  Installing : libXau-1.0.8-2.1.amzn2.0.2.x86_64                                                                                                                      10/37
  Installing : libxcb-1.12-1.amzn2.0.2.x86_64                                                                                                                         11/37
  Installing : libX11-common-1.6.7-3.amzn2.0.2.noarch                                                                                                                 12/37
  Installing : libX11-1.6.7-3.amzn2.0.2.x86_64                                                                                                                        13/37
  Installing : libXext-1.3.3-3.amzn2.0.2.x86_64                                                                                                                       14/37
  Installing : libXrender-0.9.10-1.amzn2.0.2.x86_64                                                                                                                   15/37
  Installing : libXt-1.1.5-3.amzn2.0.2.x86_64                                                                                                                         16/37
  Installing : libXmu-1.1.2-2.amzn2.0.2.x86_64                                                                                                                        17/37
  Installing : libXrandr-1.5.1-2.amzn2.0.3.x86_64                                                                                                                     18/37
  Installing : libXxf86misc-1.0.3-7.1.amzn2.0.2.x86_64                                                                                                                19/37
  Installing : libXinerama-1.1.3-2.1.amzn2.0.2.x86_64                                                                                                                 20/37
  Installing : libXi-1.7.9-1.amzn2.0.2.x86_64                                                                                                                         21/37
  Installing : libXxf86vm-1.1.4-1.amzn2.0.2.x86_64                                                                                                                    22/37
  Installing : libXfixes-5.0.3-1.amzn2.0.2.x86_64                                                                                                                     23/37
  Installing : libXcursor-1.1.15-1.amzn2.x86_64                                                                                                                       24/37
  Installing : xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64                                                                                                          25/37
  Installing : urw-base35-z003-fonts-20170801-10.amzn2.noarch                                                                                                         26/37
  Installing : urw-base35-p052-fonts-20170801-10.amzn2.noarch                                                                                                         27/37
  Installing : urw-base35-nimbus-roman-fonts-20170801-10.amzn2.noarch                                                                                                 28/37
  Installing : urw-base35-c059-fonts-20170801-10.amzn2.noarch                                                                                                         29/37
  Installing : urw-base35-d050000l-fonts-20170801-10.amzn2.noarch                                                                                                     30/37
  Installing : urw-base35-nimbus-mono-ps-fonts-20170801-10.amzn2.noarch                                                                                               31/37
  Installing : urw-base35-bookman-fonts-20170801-10.amzn2.noarch                                                                                                      32/37
  Installing : urw-base35-nimbus-sans-fonts-20170801-10.amzn2.noarch                                                                                                  33/37
  Installing : urw-base35-standard-symbols-ps-fonts-20170801-10.amzn2.noarch                                                                                          34/37
  Installing : urw-base35-gothic-fonts-20170801-10.amzn2.noarch                                                                                                       35/37
  Installing : urw-base35-fonts-20170801-10.amzn2.noarch                                                                                                              36/37
  Installing : grafana-8.4.6-1.x86_64                                                                                                                                 37/37
### NOT starting on installation, please execute the following statements to configure grafana to start automatically using systemd
 sudo /bin/systemctl daemon-reload
 sudo /bin/systemctl enable grafana-server.service
### You can start grafana-server by executing
 sudo /bin/systemctl start grafana-server.service
POSTTRANS: Running script
  Verifying  : urw-base35-z003-fonts-20170801-10.amzn2.noarch                                                                                                          1/37
  Verifying  : 1:xorg-x11-font-utils-7.5-21.amzn2.x86_64                                                                                                               2/37
  Verifying  : urw-base35-p052-fonts-20170801-10.amzn2.noarch                                                                                                          3/37
  Verifying  : urw-base35-nimbus-roman-fonts-20170801-10.amzn2.noarch                                                                                                  4/37
  Verifying  : fontpackages-filesystem-1.44-8.amzn2.noarch                                                                                                             5/37
  Verifying  : libxcb-1.12-1.amzn2.0.2.x86_64                                                                                                                          6/37
  Verifying  : libXrandr-1.5.1-2.amzn2.0.3.x86_64                                                                                                                      7/37
  Verifying  : xorg-x11-server-utils-7.7-20.amzn2.0.2.x86_64                                                                                                           8/37
  Verifying  : libX11-1.6.7-3.amzn2.0.2.x86_64                                                                                                                         9/37
  Verifying  : urw-base35-c059-fonts-20170801-10.amzn2.noarch                                                                                                         10/37
  Verifying  : libXcursor-1.1.15-1.amzn2.x86_64                                                                                                                       11/37
  Verifying  : urw-base35-d050000l-fonts-20170801-10.amzn2.noarch                                                                                                     12/37
  Verifying  : libXxf86misc-1.0.3-7.1.amzn2.0.2.x86_64                                                                                                                13/37
  Verifying  : libX11-common-1.6.7-3.amzn2.0.2.noarch                                                                                                                 14/37
  Verifying  : dejavu-fonts-common-2.33-6.amzn2.noarch                                                                                                                15/37
  Verifying  : urw-base35-fonts-common-20170801-10.amzn2.noarch                                                                                                       16/37
  Verifying  : libXau-1.0.8-2.1.amzn2.0.2.x86_64                                                                                                                      17/37
  Verifying  : libfontenc-1.1.3-3.amzn2.0.2.x86_64                                                                                                                    18/37
  Verifying  : libSM-1.2.2-2.amzn2.0.2.x86_64                                                                                                                         19/37
  Verifying  : urw-base35-fonts-20170801-10.amzn2.noarch                                                                                                              20/37
  Verifying  : libXrender-0.9.10-1.amzn2.0.2.x86_64                                                                                                                   21/37
  Verifying  : urw-base35-nimbus-mono-ps-fonts-20170801-10.amzn2.noarch                                                                                               22/37
  Verifying  : dejavu-sans-fonts-2.33-6.amzn2.noarch                                                                                                                  23/37
  Verifying  : fontconfig-2.13.0-4.3.amzn2.x86_64                                                                                                                     24/37
  Verifying  : urw-base35-bookman-fonts-20170801-10.amzn2.noarch                                                                                                      25/37
  Verifying  : libXt-1.1.5-3.amzn2.0.2.x86_64                                                                                                                         26/37
  Verifying  : libXmu-1.1.2-2.amzn2.0.2.x86_64                                                                                                                        27/37
  Verifying  : libXinerama-1.1.3-2.1.amzn2.0.2.x86_64                                                                                                                 28/37
  Verifying  : urw-base35-nimbus-sans-fonts-20170801-10.amzn2.noarch                                                                                                  29/37
  Verifying  : libXi-1.7.9-1.amzn2.0.2.x86_64                                                                                                                         30/37
  Verifying  : libXxf86vm-1.1.4-1.amzn2.0.2.x86_64                                                                                                                    31/37
  Verifying  : libXext-1.3.3-3.amzn2.0.2.x86_64                                                                                                                       32/37
  Verifying  : grafana-8.4.6-1.x86_64                                                                                                                                 33/37
  Verifying  : urw-base35-standard-symbols-ps-fonts-20170801-10.amzn2.noarch                                                                                          34/37
  Verifying  : libXfixes-5.0.3-1.amzn2.0.2.x86_64                                                                                                                     35/37
  Verifying  : libICE-1.0.9-9.amzn2.0.2.x86_64                                                                                                                        36/37
  Verifying  : urw-base35-gothic-fonts-20170801-10.amzn2.noarch                                                                                                       37/37

Installed:
  grafana.x86_64 0:8.4.6-1

Dependency Installed:
  dejavu-fonts-common.noarch 0:2.33-6.amzn2                                                dejavu-sans-fonts.noarch 0:2.33-6.amzn2
  fontconfig.x86_64 0:2.13.0-4.3.amzn2                                                     fontpackages-filesystem.noarch 0:1.44-8.amzn2
  libICE.x86_64 0:1.0.9-9.amzn2.0.2                                                        libSM.x86_64 0:1.2.2-2.amzn2.0.2
  libX11.x86_64 0:1.6.7-3.amzn2.0.2                                                        libX11-common.noarch 0:1.6.7-3.amzn2.0.2
  libXau.x86_64 0:1.0.8-2.1.amzn2.0.2                                                      libXcursor.x86_64 0:1.1.15-1.amzn2
  libXext.x86_64 0:1.3.3-3.amzn2.0.2                                                       libXfixes.x86_64 0:5.0.3-1.amzn2.0.2
  libXi.x86_64 0:1.7.9-1.amzn2.0.2                                                         libXinerama.x86_64 0:1.1.3-2.1.amzn2.0.2
  libXmu.x86_64 0:1.1.2-2.amzn2.0.2                                                        libXrandr.x86_64 0:1.5.1-2.amzn2.0.3
  libXrender.x86_64 0:0.9.10-1.amzn2.0.2                                                   libXt.x86_64 0:1.1.5-3.amzn2.0.2
  libXxf86misc.x86_64 0:1.0.3-7.1.amzn2.0.2                                                libXxf86vm.x86_64 0:1.1.4-1.amzn2.0.2
  libfontenc.x86_64 0:1.1.3-3.amzn2.0.2                                                    libxcb.x86_64 0:1.12-1.amzn2.0.2
  urw-base35-bookman-fonts.noarch 0:20170801-10.amzn2                                      urw-base35-c059-fonts.noarch 0:20170801-10.amzn2
  urw-base35-d050000l-fonts.noarch 0:20170801-10.amzn2                                     urw-base35-fonts.noarch 0:20170801-10.amzn2
  urw-base35-fonts-common.noarch 0:20170801-10.amzn2                                       urw-base35-gothic-fonts.noarch 0:20170801-10.amzn2
  urw-base35-nimbus-mono-ps-fonts.noarch 0:20170801-10.amzn2                               urw-base35-nimbus-roman-fonts.noarch 0:20170801-10.amzn2
  urw-base35-nimbus-sans-fonts.noarch 0:20170801-10.amzn2                                  urw-base35-p052-fonts.noarch 0:20170801-10.amzn2
  urw-base35-standard-symbols-ps-fonts.noarch 0:20170801-10.amzn2                          urw-base35-z003-fonts.noarch 0:20170801-10.amzn2
  xorg-x11-font-utils.x86_64 1:7.5-21.amzn2                                                xorg-x11-server-utils.x86_64 0:7.7-20.amzn2.0.2

Complete!
[ec2-user@ip-172-31-5-25 ~]$ sudo systemctl start grafana-server
[ec2-user@ip-172-31-5-25 ~]$ sudo systemctl enable grafana-server
Created symlink from /etc/systemd/system/multi-user.target.wants/grafana-server.service to /usr/lib/systemd/system/grafana-server.service.
