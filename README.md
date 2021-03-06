# HULK v2 - HTTPS Unbearable Load King
-----------------------------------------------------------------------------------------------
## Introduction:

 > This script is a *Denial of Service* tool that can put heavy load on HTTPS servers,
 > in order to bring them to their knees, by exhausting the resource pool.
 > Its is meant for research purposes only and any malicious usage of this tool is prohibited.
 > **The authors aren't to be held responsible for any consequence of usage of this tool.**

 Authors : **Hyperclaw79**, *version 2.0*; **Barry Shteiman** , *version 1.0*

 ### Notes: 
     * Edited and improved by Hyperclaw79 for smoother working and PY3+ compatibility.
     * Works for Python 3.5. No backward compatiblity.
 
 Run `pip install -r requirements.txt` before starting this script.

-----------------------------------------------------------------------------------------------

## Edits: 
        1)Syntax Corrections.
        2)Replaced urllib2 module with requests module.
        3)Replaced support for Http with support for Https.
        4)Added more HTTP Status Error Codes for detection and control.
        5)Randomized buildblock size a bit more.
        6)Deprecated 'safe'.
        7)Improved Documentation.
        8)Payload Obfuscation.
        9)Converted global variables to class variables.
        10)Replaced Threading with Multiprocessing.
        11)Introduced Shared Memory for interprocess communication. 
        12)Performed other performance tweaks.

-------------------------------------------------------------------------------------------------
## License

HULK v2 is a Python 3 compatible Denial of Service Script. Original script was created by Barry Shteiman. You can use that one if you have Python 2. Here's the [link:] (http://www.sectorix.com/2012/05/17/hulk-web-server-dos-tool/) 

Using a GNU license cause there was no mention about any license used by Barry. Feel free to modify and share it, but leave some credits to us both and don't hold us liable.
