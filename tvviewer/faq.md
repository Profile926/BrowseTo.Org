# TV Viewer FAQ
The TV Viewer main page is [here](https://github.com/Profile926/BrowseTo.Org/blob/main/README.md)

Frequent Asked Questions
Q: I do not hear sound.
A: This program is optimized for cards that use a separate sound card for sound capture. So your input should be connected to your sound card as well. To hear sound, just turn up the volume bar in the normal volume mixer program you use. Usually sound is connected to the 'line-in' of your sound card.

Q: TV Viewer does not save my input settings.
A: TV Viewer tries to save the input settings, but this is not supported by all drivers / capture cards. Usually a separate program is provided by the card manufacturer that saves the default input settings. If this is not the case, you can try to use Vidcap to save the default input setting. Vidcap uses a different API, that has better support for saving the input settings.

- Q: Can I make the program start full-screen using a command-line argument?
- A: Yes, just add the command line argument "/s".

- Q: I have a Studio DC10+ under Windows XP and the performance and/or image quality is poor.
- A: TV Viewer works fine under Windows XP, however the drivers (August 2002) for the DC10+ for Windows XP are beta and of poor quality. Please wait until Pinnacle releases new drivers. You can use the free trial version to experiment if the program works ok on your system.

- Q: My capture card is not detected by the program, what do I do?
- A: If the capture card is not supported by TV Viewer (See list on main page) there is little that you can do. However if that card is supported, make sure that you are using the latest drivers for your card. If you have a combo card (Graphics card with video in/out), make sure that you download drivers that also support the video in/out of your card, some drivers only support the graphics part of your card.

- Q: I am using a Studio DC10+ and full screen display freezes or is severely garbled (Windows 9x).
- A: Try setting the 'capture' resolution to low-resolution. (Available in Options->Video Format). Also make sure squeezing is enabled under Options->Video Display. (Note: Some users claim that disabling squeezing helps, so try both settings)

- Q: I am using a Studio DC10+ and when I set the 'capture' resolution or other settings, they are not saved. (Windows 9x)
- A: Run the VidCap program supplied with the DC10+. (Available under Start->Programs->Studio DC10+->Tools). Set the settings in this program, and they will be saved and used by TV Viewer.

- Q: I am using a Studio DC10+ and when I resize the TV Viewer window, or go to full screen, the size of the video display does not increase. (Windows 9x)
- A: Run the Studio DC10+ configuration (Available under Start->Programs->Studio DC10+->Tools) and make sure DDraw Overlay surface is checked.

- Q: I am using a Matrox graphics card, and I only see anything when I am in 24-bit or 32-bit color.
- A: This is a Matrox driver issue. 32-bit color is recommend, as Matrox 3D acceleration does not work in 24-bit mode.
