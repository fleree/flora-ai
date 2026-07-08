# IF YOU USE LINUX READ THIS CAREFULLY
--------------------------------------

Linux does not automatically create a start menu icon that means you will need to run the following command if you want a start menu icon
-
`mkdir -p ~/Applications`

`mv ~/flora-app/dist/Flora-1.3.2.AppImage ~/Applications/`

`chmod +x ~/Applications/Flora-1.3.2.AppImage`

`ln -sf ~/Applications/Flora-1.3.2.AppImage ~/Applications/Flora.AppImage`


[NOTE]
Don't worry about the version number in the command AND DO NOT CHANGE THAT NUMBER otherwhise it will not work.
