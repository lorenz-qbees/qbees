## What do i have to do when Windows 10 won't update to Version 2004

**If you have any trouble to install Version 2004 of Windows 10:
here is a workarround for previous Windows 10 versions.**

1. follow the setup guide until the heading "Upgrade to WSL 2". Please skip this part and do the following  instead
2. Check your WSL Ubuntu name: open a windows terminal with **Start** --> **cmd** --> **enter** and type in:

		wsl -l

Result should be something like this:

    Windows-Subsystem für Linux-Distributonen:
    Ubuntu (Standard)

3. Upgrade your WSL
execute this command in your windows terminal (if your distribution name differs, please modify this command to your distribution name from step 2):


		wsl --upgrade Ubuntu

4. Restart your PC and continue with the setup guide
After restarting your PC the WSL should be ready and you can continue with the setup guide at heading "Windows Terminal"

5. Have fun with coding @ lewagon :)
