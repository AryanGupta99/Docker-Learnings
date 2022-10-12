-> Create a volume by using the commmand:
: docker volume create "volume-name"
-> start and stop the container again to see if the volume is actually working or not
->start the container again but with the -v flag to actually mount the volume
-> you can also inspect the volumes by command:
: docker volume inspect "volume-name"

