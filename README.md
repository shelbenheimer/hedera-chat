[Hedera Chat]

[Description]
This is a simple LAN oriented TCP chat server that utilises the built-in 'Winsock' API offered by Windows. This was a personal project of mine that I took an interest in recently as I have dabbled with networking in the past. I worked on this application for roughly a week and encountered many issues which gave me a multitude of opportunities to learn, I really enjoyed solving these.

[Bugs]
I understand that this program has bugs and I will potentially release an updated version to address these issues, if you find any of these issues please report them so I can inspect them further.

[Installation]
The client application and config file must be included in the same directory as they are associated with one another - this allows for you to create and load your own server address configurations. The server has no special requirements and, as long as your system has 'Winsock', should work as intended. If you wish to connect to someone outside of your local network, I would suggest using Hamachi to create a virtual private network, the IP will then be the IPv4 of the host who is running the included server tool. By default, this application utilises port [80].
