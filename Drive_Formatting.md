# HOW TO FORMAT A DRIVE USING THE COMMAND PROMPT

# THE STEPS INVOLVE ARE AS FOLLOWS

- Insert the drive to your pc and check the volume label and size 

- Open Command Prompt (Optional: Run it as Administrator)

- Enter the following Command in the Command Prompt

    - type _diskpart_ and press enter (if a dialog box appear select _OK_)

- Now you should see Diskpart as your prompt

- Enter the following commands in the diskpart

    - _list disk_ (this command shows you all the physical disk that are connected to your pc)

    - _list vol_ (this command shows you all the volumes in your pc. check the volume number of the drive you wish to format)

    - _select vol 1_ (i am selecting volume 1 because that the volume index of my drive)

    - _list vol_ (now you should see _*_ attached to the selected volume)

    - _format fs=ntfs quick_ (this command will format the selected volume, this _fs=ntfs_ set the file system to __ntfs__ and this _quick_ makes the format to run faster)

    - When completed, you should see a Success message (You drive should be formated now)

#   I HOPE IT IS HELPFUL 

#   THANK YOU FOR TAKING SOME TIME TO READ THIS,.