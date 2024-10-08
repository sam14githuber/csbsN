A newer release of "Amazon Linux" is available.
  Version 2023.4.20240611:
  Version 2023.5.20240624:
  Version 2023.5.20240701:
  Version 2023.5.20240708:
  Version 2023.5.20240722:
  Version 2023.5.20240730:
  Version 2023.5.20240805:
  Version 2023.5.20240819:
  Version 2023.5.20240903:
  Version 2023.5.20240916:
  Version 2023.5.20241001:
Run "/usr/bin/dnf check-release-update" for full release and version update info
   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
Last login: Tue Jun  4 08:46:44 2024 from 18.206.107.27
[ec2-user@ip-172-31-25-25 ~]$ sudo su
[root@ip-172-31-25-25 ec2-user]# sudo yum update
Last metadata expiration check: 6:06:29 ago on Tue Oct  8 03:32:04 2024.
========================================================================================================================================
WARNING:
  A newer release of "Amazon Linux" is available.

  Available Versions:

  Version 2023.4.20240611:
    Run the following command to upgrade to 2023.4.20240611:

      dnf upgrade --releasever=2023.4.20240611

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.4.20240611.html

  Version 2023.5.20240624:
    Run the following command to upgrade to 2023.5.20240624:

      dnf upgrade --releasever=2023.5.20240624

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240624.html

  Version 2023.5.20240701:
    Run the following command to upgrade to 2023.5.20240701:

      dnf upgrade --releasever=2023.5.20240701

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240701.html

  Version 2023.5.20240708:
    Run the following command to upgrade to 2023.5.20240708:

      dnf upgrade --releasever=2023.5.20240708

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240708.html

  Version 2023.5.20240722:
    Run the following command to upgrade to 2023.5.20240722:

      dnf upgrade --releasever=2023.5.20240722

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240722.html

  Version 2023.5.20240730:
    Run the following command to upgrade to 2023.5.20240730:

      dnf upgrade --releasever=2023.5.20240730

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240730.html

  Version 2023.5.20240805:
    Run the following command to upgrade to 2023.5.20240805:

      dnf upgrade --releasever=2023.5.20240805

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240805.html

  Version 2023.5.20240819:
    Run the following command to upgrade to 2023.5.20240819:

      dnf upgrade --releasever=2023.5.20240819

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240819.html

  Version 2023.5.20240903:
    Run the following command to upgrade to 2023.5.20240903:

      dnf upgrade --releasever=2023.5.20240903

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240903.html

  Version 2023.5.20240916:
    Run the following command to upgrade to 2023.5.20240916:

      dnf upgrade --releasever=2023.5.20240916

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240916.html

  Version 2023.5.20241001:
    Run the following command to upgrade to 2023.5.20241001:

      dnf upgrade --releasever=2023.5.20241001

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20241001.html

========================================================================================================================================
Dependencies resolved.
Nothing to do.
Complete!
[root@ip-172-31-25-25 ec2-user]# sudo yum install git -y
Last metadata expiration check: 6:07:36 ago on Tue Oct  8 03:32:04 2024.
Dependencies resolved.
========================================================================================================================================
 Package                           Architecture            Version                                   Repository                    Size
========================================================================================================================================
Installing:
 git                               x86_64                  2.40.1-1.amzn2023.0.3                     amazonlinux                   54 k
Installing dependencies:
 git-core                          x86_64                  2.40.1-1.amzn2023.0.3                     amazonlinux                  4.3 M
 git-core-doc                      noarch                  2.40.1-1.amzn2023.0.3                     amazonlinux                  2.6 M
 perl-Error                        noarch                  1:0.17029-5.amzn2023.0.2                  amazonlinux                   41 k
 perl-File-Find                    noarch                  1.37-477.amzn2023.0.6                     amazonlinux                   26 k
 perl-Git                          noarch                  2.40.1-1.amzn2023.0.3                     amazonlinux                   42 k
 perl-TermReadKey                  x86_64                  2.38-9.amzn2023.0.2                       amazonlinux                   36 k
 perl-lib                          x86_64                  0.65-477.amzn2023.0.6                     amazonlinux                   15 k

Transaction Summary
========================================================================================================================================
Install  8 Packages

Total download size: 7.1 M
Installed size: 34 M
Downloading Packages:
                                                     [===                                             ] ---  B/s |   0  B     --:--(1/8): git-2.40.1-1.amzn2023.0.3.x86_64.rpm       0% [                                                ] ---  B/s |   0  B     --:--(1/8): git-2.40.1-1.amzn2023.0.3.x86_64.rpm                                                             1.1 MB/s |  54 kB     00:00    
(2-3/8): git-core-2.40.1-1.amzn2023.0.3.x86_64.r  0% [                                                ] 1.1 MB/s |  54 kB     00:06(2/8): perl-Error-0.17029-5.amzn2023.0.2.noarch.rpm                                                     1.8 MB/s |  41 kB     00:00    
(3-4/8): git-core-2.40.1-1.amzn2023.0.3.x86_64.r 32% [===============                                 ] 1.6 MB/s | 2.3 MB     00:03(3/8): perl-File-Find-1.37-477.amzn2023.0.6.noarch.rpm                                                  1.3 MB/s |  26 kB     00:00    
(4-5/8): git-core-2.40.1-1.amzn2023.0.3.x86_64.r 68% [================================-               ] 2.1 MB/s | 4.8 MB     00:01(4/8): git-core-2.40.1-1.amzn2023.0.3.x86_64.rpm                                                         32 MB/s | 4.3 MB     00:00    
(5-6/8): git-core-doc-2.40.1-1.amzn2023.0.3.noar 93% [============================================-   ] 2.4 MB/s | 6.6 MB     00:00(5/8): git-core-doc-2.40.1-1.amzn2023.0.3.noarch.rpm                                                     17 MB/s | 2.6 MB     00:00    
(6-7/8): perl-Git-2.40.1-1.amzn2023.0.3.noarch.r 99% [===============================================-] 2.5 MB/s | 7.1 MB     00:00(6/8): perl-Git-2.40.1-1.amzn2023.0.3.noarch.rpm                                                        626 kB/s |  42 kB     00:00    
(7/8): perl-TermReadKey-2.38-9.amzn2023.0.2.x86_ 99% [===============================================-] 2.5 MB/s | 7.1 MB     00:00(7/8): perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64.rpm                                                  1.2 MB/s |  36 kB     00:00    
(8/8): perl-lib-0.65-477.amzn2023.0.6.x86_64.rpm 99% [===============================================-] 2.5 MB/s | 7.1 MB     00:00(8/8): perl-lib-0.65-477.amzn2023.0.6.x86_64.rpm                                                        680 kB/s |  15 kB     00:00    
----------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                    32 MB/s | 7.1 MB     00:00     
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :  [============                                                                                               ]  Preparing        :  [==========================                                                                                 ]  Preparing        :  [=======================================                                                                    ]  Preparing        :  [=====================================================                                                      ]  Preparing        :  [==================================================================                                         ]  Preparing        :  [================================================================================                           ]  Preparing        :  [=============================================================================================              ]  Preparing        :                                                                                                                1/1 
  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [                                                                      ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=                                                                     ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==                                                                    ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===                                                                   ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [====                                                                  ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=====                                                                 ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [======                                                                ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=======                                                               ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [========                                                              ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=========                                                             ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==========                                                            ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===========                                                           ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [============                                                          ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=============                                                         ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==============                                                        ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===============                                                       ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [================                                                      ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=================                                                     ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==================                                                    ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===================                                                   ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [====================                                                  ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=====================                                                 ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [======================                                                ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=======================                                               ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [========================                                              ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=========================                                             ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==========================                                            ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===========================                                           ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [============================                                          ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=============================                                         ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==============================                                        ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===============================                                       ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [================================                                      ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=================================                                     ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==================================                                    ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===================================                                   ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [====================================                                  ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=====================================                                 ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [======================================                                ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=======================================                               ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [========================================                              ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=========================================                             ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==========================================                            ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===========================================                           ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [============================================                          ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=============================================                         ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==============================================                        ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===============================================                       ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [================================================                      ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=================================================                     ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==================================================                    ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===================================================                   ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [====================================================                  ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=====================================================                 ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [======================================================                ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=======================================================               ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [========================================================              ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=========================================================             ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==========================================================            ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===========================================================           ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [============================================================          ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=============================================================         ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==============================================================        ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===============================================================       ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [================================================================      ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [=================================================================     ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [==================================================================    ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===================================================================   ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [====================================================================  ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64 [===================================================================== ]  Installing       : git-core-2.40.1-1.amzn2023.0.3.x86_64                                                                          1/8 
  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [                                                                  ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=                                                                 ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==                                                                ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===                                                               ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [====                                                              ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=====                                                             ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [======                                                            ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=======                                                           ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [========                                                          ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=========                                                         ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==========                                                        ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===========                                                       ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [============                                                      ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=============                                                     ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==============                                                    ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===============                                                   ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [================                                                  ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=================                                                 ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==================                                                ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===================                                               ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [====================                                              ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=====================                                             ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [======================                                            ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=======================                                           ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [========================                                          ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=========================                                         ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==========================                                        ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===========================                                       ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [============================                                      ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=============================                                     ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==============================                                    ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===============================                                   ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [================================                                  ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=================================                                 ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==================================                                ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===================================                               ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [====================================                              ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=====================================                             ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [======================================                            ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=======================================                           ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [========================================                          ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=========================================                         ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==========================================                        ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===========================================                       ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [============================================                      ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=============================================                     ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==============================================                    ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===============================================                   ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [================================================                  ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=================================================                 ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==================================================                ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===================================================               ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [====================================================              ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=====================================================             ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [======================================================            ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=======================================================           ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [========================================================          ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=========================================================         ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==========================================================        ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===========================================================       ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [============================================================      ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [=============================================================     ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [==============================================================    ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [===============================================================   ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [================================================================  ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch [================================================================= ]  Installing       : git-core-doc-2.40.1-1.amzn2023.0.3.noarch                                                                      2/8 
  Installing       : perl-lib-0.65-477.amzn2023.0.6.x86_64 [                                                                      ]  Installing       : perl-lib-0.65-477.amzn2023.0.6.x86_64 [===========================================                           ]  Installing       : perl-lib-0.65-477.amzn2023.0.6.x86_64 [====================================================================  ]  Installing       : perl-lib-0.65-477.amzn2023.0.6.x86_64                                                                          3/8 
  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [                                                                ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [==============                                                  ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [=====================================                           ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [============================================                    ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [===================================================             ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [==========================================================      ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64 [=============================================================== ]  Installing       : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64                                                                    4/8 
  Installing       : perl-File-Find-1.37-477.amzn2023.0.6.noarch [                                                                ]  Installing       : perl-File-Find-1.37-477.amzn2023.0.6.noarch [==========                                                      ]  Installing       : perl-File-Find-1.37-477.amzn2023.0.6.noarch [==============================================================  ]  Installing       : perl-File-Find-1.37-477.amzn2023.0.6.noarch [=============================================================== ]  Installing       : perl-File-Find-1.37-477.amzn2023.0.6.noarch                                                                    5/8 
  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [                                                                 ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [========                                                         ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [=========                                                        ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [==========                                                       ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [===========                                                      ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [============                                                     ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [=============                                                    ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [=============================                                    ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [===================================                              ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [=====================================                            ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [=============================================================    ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch [================================================================ ]  Installing       : perl-Error-1:0.17029-5.amzn2023.0.2.noarch                                                                     6/8 
  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [                                                                      ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [===========                                                           ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [============================================                          ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [============================================================          ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [===============================================================       ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [=================================================================     ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch [===================================================================== ]  Installing       : perl-Git-2.40.1-1.amzn2023.0.3.noarch                                                                          7/8 
  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [                                                                           ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [===                                                                        ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [============                                                               ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [==========================                                                 ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [==============================                                             ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [====================================                                       ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [==========================================                                 ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [===================================================                        ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [========================================================                   ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [============================================================               ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [=============================================================              ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [===============================================================            ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [=========================================================================  ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64 [========================================================================== ]  Installing       : git-2.40.1-1.amzn2023.0.3.x86_64                                                                               8/8 
  Running scriptlet: git-2.40.1-1.amzn2023.0.3.x86_64                                                                               8/8 
  Verifying        : git-2.40.1-1.amzn2023.0.3.x86_64                                                                               1/8 
  Verifying        : git-core-2.40.1-1.amzn2023.0.3.x86_64                                                                          2/8 
  Verifying        : git-core-doc-2.40.1-1.amzn2023.0.3.noarch                                                                      3/8 
  Verifying        : perl-Error-1:0.17029-5.amzn2023.0.2.noarch                                                                     4/8 
  Verifying        : perl-File-Find-1.37-477.amzn2023.0.6.noarch                                                                    5/8 
  Verifying        : perl-Git-2.40.1-1.amzn2023.0.3.noarch                                                                          6/8 
  Verifying        : perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64                                                                    7/8 
  Verifying        : perl-lib-0.65-477.amzn2023.0.6.x86_64                                                                          8/8 
========================================================================================================================================
WARNING:
  A newer release of "Amazon Linux" is available.

  Available Versions:

  Version 2023.4.20240611:
    Run the following command to upgrade to 2023.4.20240611:

      dnf upgrade --releasever=2023.4.20240611

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.4.20240611.html

  Version 2023.5.20240624:
    Run the following command to upgrade to 2023.5.20240624:

      dnf upgrade --releasever=2023.5.20240624

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240624.html

  Version 2023.5.20240701:
    Run the following command to upgrade to 2023.5.20240701:

      dnf upgrade --releasever=2023.5.20240701

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240701.html

  Version 2023.5.20240708:
    Run the following command to upgrade to 2023.5.20240708:

      dnf upgrade --releasever=2023.5.20240708

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240708.html

  Version 2023.5.20240722:
    Run the following command to upgrade to 2023.5.20240722:

      dnf upgrade --releasever=2023.5.20240722

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240722.html

  Version 2023.5.20240730:
    Run the following command to upgrade to 2023.5.20240730:

      dnf upgrade --releasever=2023.5.20240730

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240730.html

  Version 2023.5.20240805:
    Run the following command to upgrade to 2023.5.20240805:

      dnf upgrade --releasever=2023.5.20240805

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240805.html

  Version 2023.5.20240819:
    Run the following command to upgrade to 2023.5.20240819:

      dnf upgrade --releasever=2023.5.20240819

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240819.html

  Version 2023.5.20240903:
    Run the following command to upgrade to 2023.5.20240903:

      dnf upgrade --releasever=2023.5.20240903

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240903.html

  Version 2023.5.20240916:
    Run the following command to upgrade to 2023.5.20240916:

      dnf upgrade --releasever=2023.5.20240916

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20240916.html

  Version 2023.5.20241001:
    Run the following command to upgrade to 2023.5.20241001:

      dnf upgrade --releasever=2023.5.20241001

    Release notes:
     https://docs.aws.amazon.com/linux/al2023/release-notes/relnotes-2023.5.20241001.html

========================================================================================================================================

Installed:
  git-2.40.1-1.amzn2023.0.3.x86_64             git-core-2.40.1-1.amzn2023.0.3.x86_64        git-core-doc-2.40.1-1.amzn2023.0.3.noarch 
  perl-Error-1:0.17029-5.amzn2023.0.2.noarch   perl-File-Find-1.37-477.amzn2023.0.6.noarch  perl-Git-2.40.1-1.amzn2023.0.3.noarch     
  perl-TermReadKey-2.38-9.amzn2023.0.2.x86_64  perl-lib-0.65-477.amzn2023.0.6.x86_64       

Complete!
[root@ip-172-31-25-25 ec2-user]# git --version
git version 2.40.1
[root@ip-172-31-25-25 ec2-user]# ls
[root@ip-172-31-25-25 ec2-user]# mkdir SamikshaMuley
[root@ip-172-31-25-25 ec2-user]# ls
SamikshaMuley
[root@ip-172-31-25-25 ec2-user]# cd SamikshaMuley
[root@ip-172-31-25-25 SamikshaMuley]# git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /home/ec2-user/SamikshaMuley/.git/
[root@ip-172-31-25-25 SamikshaMuley]# git config --global user.name "sam14githuber"
[root@ip-172-31-25-25 SamikshaMuley]# git --global user.email "muleysamiksha14@gmail.com"
unknown option: --global
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]
[root@ip-172-31-25-25 SamikshaMuley]# git config  --global user.email "muleysamiksha14@gmail.com"
[root@ip-172-31-25-25 SamikshaMuley]# git config --global user.name "sam14githuber"
[root@ip-172-31-25-25 SamikshaMuley]# git remote add origin https://github.com/sam14githuber/csbsN.git
[root@ip-172-31-25-25 SamikshaMuley]# cat>home.txt
Hello World

[root@ip-172-31-25-25 SamikshaMuley]# git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.txt

nothing added to commit but untracked files present (use "git add" to track)
[root@ip-172-31-25-25 SamikshaMuley]# git add .
[root@ip-172-31-25-25 SamikshaMuley]# git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   home.txt

[root@ip-172-31-25-25 SamikshaMuley]# git commit -m " my first commit "
[master (root-commit) db5e096]  my first commit
 1 file changed, 2 insertions(+)
 create mode 100644 home.txt
[root@ip-172-31-25-25 SamikshaMuley]# git --log
unknown option: --log
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]
[root@ip-172-31-25-25 SamikshaMuley]# git log
commit db5e0965c677126210f86a92f607c6a5aff2c2ed (HEAD -> master)
Author: sam14githuber <muleysamiksha14@gmail.com>
Date:   Tue Oct 8 10:18:36 2024 +0000

     my first commit
[root@ip-172-31-25-25 SamikshaMuley]# git push -u origin master
Username for 'https://github.com': sam14githuber
Password for 'https://sam14githuber@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/sam14githuber/csbsN.git/'
[root@ip-172-31-25-25 SamikshaMuley]# git push -u origin master
Username for 'https://github.com': sam14githuber
Password for 'https://sam14githuber@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sam14githuber/csbsN.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
[root@ip-172-31-25-25 SamikshaMuley]# ^C
[root@ip-172-31-25-25 SamikshaMuley]# 
