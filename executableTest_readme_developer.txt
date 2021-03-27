in command prompt use:

	pyinstaller --onefile -w --icon=image.ico -n specified_name.py program_code.py

(--onefile makes just one output executable and -w stops the 
command prompt from coming up; don't use it if command prompt 
is intended; -n is only necessary as a workaround for avoiding
a weird icon caching problem I couldn't fix where pyinstaller uses
previous icons for your current executable)

then you can change the icon using windows