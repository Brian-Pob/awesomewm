*Last updated: 2020-05-14*


I used the Awesome edition of Manjaro for this.

To install all the dependencies from the text file, do 
`sudo pacman -Syu - < pkglist.txt`

I am not putting a lot of effort into this right now lol.

## Known Issues
* When AwesomeWM is restarted, VolumeIcon will create another instance in systray. `awful.spawn.single_instance("volumeicon")` does not seem to work
