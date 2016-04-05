#c02-edit-profile.sh.md




This bash file auto loads ~/.profile which is a bash file that runs before any terminal or other bash program.

the command is 

sudo nano ~/.profile


and to exit you must ctrl-X and the y


Any command here will run every time a terminal is opened.

An example of a command you may want to put at the bottom of the file is


export INDEXFILE=/home/ubuntu/workspace/index.html

changed for a new location to the index.html file or to change the name of the file. This file is auto-updated with your Android Apps .apk file.



to set your timezone just put one of these commands in the ~/.profile at the bottom of the file



export TZ=Africa/Abidjan	
export TZ=Africa/Cairo	
export TZ=Africa/Johannesburg	
export TZ=Africa/Khartoum	
export TZ=Africa/Lagos	
export TZ=Africa/Maputo	
export TZ=Africa/Nairobi	
export TZ=Africa/Tripoli	
export TZ=America/Adak	
export TZ=America/Anchorage	
export TZ=America/Argentina/Cordoba	
export TZ=America/Argentina/Jujuy	
export TZ=America/Argentina/Mendoza	
export TZ=America/Atikokan	
export TZ=America/Chicago	
export TZ=America/Curacao	
export TZ=America/Denver	
export TZ=America/Detroit	
export TZ=America/Edmonton	
export TZ=America/Halifax	
export TZ=America/Havana	
export TZ=America/Indiana/Knox	
export TZ=America/Jamaica	
export TZ=America/Kentucky/Louisville	
export TZ=America/Los_Angeles	
export TZ=America/Manaus	
export TZ=America/Mazatlan	
export TZ=America/Mexico_City	
export TZ=America/New_York	
export TZ=America/Noronha	
export TZ=America/Panama	
export TZ=America/Phoenix	
export TZ=America/Port_of_Spain	
export TZ=America/Regina	
export TZ=America/Rio_Branco	
export TZ=America/Santiago	
export TZ=America/Sao_Paulo	
export TZ=America/St_Johns	
export TZ=America/Tijuana	
export TZ=America/Toronto	
export TZ=America/Vancouver	
export TZ=America/Whitehorse	
export TZ=America/Winnipeg	
export TZ=Asia/Ashgabat	
export TZ=Asia/Bangkok	
export TZ=Asia/Dhaka	
export TZ=Asia/Dubai	
export TZ=Asia/Ho_Chi_Minh	
export TZ=Asia/Hong_Kong	
export TZ=Asia/Jerusalem	
export TZ=Asia/Kathmandu	
export TZ=Asia/Kolkata	
export TZ=Asia/Macau	
export TZ=Asia/Makassar	
export TZ=Asia/Nicosia	
export TZ=Asia/Qatar	
export TZ=Asia/Riyadh	
export TZ=Asia/Seoul	
export TZ=Asia/Shanghai	
export TZ=Asia/Singapore	
export TZ=Asia/Taipei	
export TZ=Asia/Tehran	
export TZ=Asia/Thimphu	
export TZ=Asia/Tokyo	
export TZ=Asia/Ulaanbaatar	
export TZ=Asia/Urumqi	
export TZ=Atlantic/Faroe	
export TZ=Atlantic/Reykjavik	
export TZ=Australia/Adelaide	
export TZ=Australia/Brisbane	
export TZ=Australia/Broken_Hill	
export TZ=Australia/Darwin	
export TZ=Australia/Hobart	
export TZ=Australia/Lord_Howe	
export TZ=Australia/Melbourne	
export TZ=Australia/Perth	
export TZ=Australia/Sydney	
export TZ=Europe/Belgrade	
export TZ=Europe/Chisinau	
export TZ=Europe/Dublin	
export TZ=Europe/Helsinki	
export TZ=Europe/Istanbul	
export TZ=Europe/Lisbon	
export TZ=Europe/London	
export TZ=Europe/Moscow	
export TZ=Europe/Oslo	
export TZ=Europe/Prague	
export TZ=Europe/Rome	
export TZ=Europe/Warsaw	
export TZ=Europe/Zurich	
export TZ=Pacific/Auckland	
export TZ=Pacific/Chatham	
export TZ=Pacific/Chuuk	
export TZ=Pacific/Easter	
export TZ=Pacific/Guam	
export TZ=Pacific/Honolulu	
export TZ=Pacific/Kwajalein	
export TZ=Pacific/Pago_Pago	
export TZ=Pacific/Pohnpei	


