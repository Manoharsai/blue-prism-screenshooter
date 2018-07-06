# Screenshooter for Blue Prism
Screenshooter for Blue Prism: An object that takes screenshots (screen captures) using [Blue Prism](https://www.blueprism.com), and is intended as a workaround for the deficient Screen Capture-functionality. This is in particular useful for taking screenshots before triggering *Exceptions*.
The object can be used by both Processes and Objects.

## Save location
When the object's *Take Screenshot*-action is called, it saves a screenshot of the primary screen as PNG files in the TEMP directory (Typically, this is the user's `AppData\Local\Temp` directory, and can be found pressing Windows+R and typing *%TEMP%*).
The files are named *Blue Prism TIMESTAMP.png*

## Disclaimer
Remember to clean up your screenshots, as they may contain confidential information. I do not take responsibility if anything goes wrong.

[Kristian Risager Larsen](https://kristianrisagerlarsen.dk), [Silkeborg Kommune](http://silkeborg.dk), July 2018
