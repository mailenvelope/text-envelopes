text-envelopes
==============

Excutables and the sources are currently available for download on  http://www.unchartedcharters.com
Two .avi samples are on Youtube: https://www.youtube.com/watch?v=uLiNYzG81MA and 
https://www.youtube.com/watch?v=QcRm3X3qA1A

This GitHub repository serves as a stub.

    What is CuttleFish?
    ===================
    CuttleFish is a sinple programm that makes text messages unreadable to humans.
    CuttleFish does not use encryption. All it does is turn your messages into
    what looks like gibbersish. It then puts this gibberish into a common file
    format, which serves as an "envelope" if you will. If a human opens such a 
    file in a standard program, he or she will see "garbage".
    
    This works also for many automated message scanners. Simple-minded scanners
    will "think" you made a mistake and created a bad file. 
    
    If you need strong privacy, encrypt your messages. You can put "ASCII armored"
    encrypted messages into a CuttleFish envelope, too.


    How to:
    ======
    Enter or paste message text into this editor.
    
    Select a File Format from the dropdown. Saving or opening a file will 
    always use the currently selected File Format.
    
    The following formats are supported
    ===================================
    "PDF .pdf": a file in portable document (pdf) format.
    
    "QR code .png": a Quick Response code .png file. Limit of 4200 characters.
    
    ".wav audio": a Wave audio file. Use CuttleFish to open a .wav message file.
    
    ".avi movie": the text is saved as a .avi movie and is displayed as a pink
    bouncy ball in case you play the movie in a movie player.
    WARNING: The format of avi rendering changed with v. 1.1. Previous avis
    will not be decoded correctly.
    Configure the bouncy image to "pacman"  by changing the aviBlip "star" to
    pacman.
    Configure a footer image by replacing the existing footer.png. The new footer
    image should be at least 500 pixels wide and 200 high. If it is higher, it
    will automatically scroll upwards.
    
    "plain .png image": the message is saved in a plain image file.    
    
    "empty .xml file": saves the message in "metadata" of an .xml file. The file
    is filled with unrelated text from a default template. Anybody reading the
    text will only see the adventures of Huck Finn. You can replace this file,
    which is an equivalent of "packing peanuts".
        
    "javascript .html": saves the message in the javascript section of an html file. 
    You can replace the default file with any file that has a javascript section.
    
    ".asp vb html": saves the message in an html file that has a Microsoft asp 
    vb script section.  You can replace the default file with any file that has such a section.
    
    "Java .jar file": saves the message in a Java (tm) .jar file. A template jar is 
    included in the package. You can replace it with any other .jar, but your
    replacement must have a manifest file with a "Main-class" enty.
 
    "DNA sequence .txt": turns your message into a "DNA sequence" using only the four
    basic building blocks ACGT. Mimicking of one or more common scientific formats 
    will be added.
    
    [experimental] "CSS stylesheet .css": saves in a cascading stylesheet. This is a very rudimentray 
    implementation, really a proof of concept. You should change the source code CSSHandling
    class to get a good implementation.
       
    Save
    ====
    Save the contents of the editor window into one of the "envelope file" formats.
    
    Open
    ====
    Open an envelope file and read the contents into the editor window. If the window remains empty, check the File Format
    setting.
    
    Recipients of any of these files need CuttleFish to extract the message.
