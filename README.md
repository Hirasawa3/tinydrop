tinydrop is a Python2 socket based payload dropper.
	Features?
		Modularity of tinydrop is my top priority. There are other default features in tinydrop...
		such as spawning bash shells and transferring files.
	Payloads?
		All payloads are encoded in hex and sent to the target socket in hex.
		Any module is a executable Linux file, such as a Python script or a bash script.
		Hex encoding makes it easier for modules to be shared and to be sent across sockets.
		You are obliged to make your own modules, and in no way should you have to share them with me.
	Requirements?
		Python2,
		dos2unix (http://linuxcommand.org/man_pages/dos2unix1.html),
		sudo or direct root access (required for elevated actions)
