ILOVEYOU, sometimes referred to as Love Bug or Love Letter for you, was a computer worm that infected over ten million Windows personal computers on and after 5 May 2000. It started spreading as an email message with the subject line "ILOVEYOU" and the attachment "LOVE-LETTER-FOR-YOU.TXT.vbs."[1] At the time, Windows computers often hid the latter file extension ("VBS," a type of interpreted file) by default because it is an extension for a file type that Windows knows, leading unwitting users to think it was a normal text file. Opening the attachment activates the Visual Basic script. First, the worm inflicts damage on the local machine, overwriting random files (including Office files and image files; however, it hides MP3 files instead of deleting them), then, it copies itself to all addresses in the Windows Address Book used by Microsoft Outlook, allowing it to spread much faster than any other previous email worm.

Onel de Guzman, a then-24-year-old resident of Manila, Philippines, created the malware. Because there were no laws in the Philippines against making malware at the time of its creation, the Philippine Congress enacted Republic Act No. 8792, otherwise known as the E-Commerce Law, in July 2000 to discourage future iterations of such activity. However, the Constitution of the Philippines bans ex post facto laws, and as such de Guzman could not be prosecuted.

## Creation

De Guzman, who was poor and struggling to pay for Internet access at the time, created the computer worm intending to steal other users' passwords, which he could use to log in to their Internet accounts without needing to pay for the service. He justified his actions on his belief that Internet access is a human right and that he was not actually stealing.

The worm used the same principles that de Guzman had described in his undergraduate thesis at AMA Computer College. He stated that the worm was very easy to create, thanks to a bug in Windows 95 that would run code in email attachments when the user clicked on them. Originally designing the worm to only work in Manila, he removed this geographic restriction out of curiosity, which allowed the worm to spread worldwide. De Guzman did not expect this worldwide spread.

## Description

On the machine system level, ILOVEYOU relied on the scripting engine system setting (which runs scripting language files such as .vbs files) being enabled and took advantage of a feature in Windows that hid file extensions by default, which malware authors would use as an exploit. Windows would parse file names from right to left, stopping at the first period character, showing only those elements to the left of this. The attachment, which had two periods, could thus display the inner fake "TXT" file extension. True text files are considered to be innocuous as they are incapable of running arbitrary code. The worm used social engineering to entice users to open the attachment (out of actual desire to connect or simple curiosity) to ensure continued propagation. Systemic weaknesses in the design of Microsoft Outlook and Microsoft Windows were exploited to allow malicious code capable of gaining complete access to the operating system, secondary storage, and system and user data in, simply through unwitting users clicking on an icon.

Taken from https://en.wikipedia.org/wiki/ILOVEYOU