Code created to perform the registration of hosts in the centreon monitoring system version 22.10.0, it was necessary to do it this way because the old version of the system was very old and there was no tool available to perform the migration of hosts officially, so I I accessed the centreon server through winscp, and looked for the hosts.cfg file and exported it to my machine. I opened that file and deleted unnecessary information with notepad++. Leaving the file in the complementary file format, once that was done, it was just running the code.