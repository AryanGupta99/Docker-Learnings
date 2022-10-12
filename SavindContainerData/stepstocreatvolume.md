-> Create a volume by using the commmand:
: docker volume create "volume-name"
-> start and stop the container again to see if the volume is actually working or not
->start the container again but with the -v flag to actually mount the volume
-> you can also inspect the volumes by command:
: docker volume inspect "volume-name"

------------------------------------------------------
->bind mounts
:this is type of volume where you can control the data however you want
:you can provide own choice of path
:you can also maintain the file system changes
:bind mount is used in development workflow bcoz there will be multiple databases integrated in applicatin and you have to send data to every where.

