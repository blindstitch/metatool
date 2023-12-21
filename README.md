Note: I wrote this in 2014 when working at Vice in my spare time about a month after I started learning python. The code's bad, folks

# metatool

Tool to create metadata reports for collections of video files.
Also collects and stores MD5 hashes of media.

## Usage
 - Organize your video into folders (no video files can be at the top-level).
 - Specify desired file types in the header of the executable.
 - Drag the parent folder into the program's prompts.
 - Follow prompts for CSV or JSON output.
 
## Requires
 - smarnach/pyexiftool
 
## Issues
 - Can break with esoteric file formats.
 - Can break with Unicode metadata (common in archival video sources).

## Todo
 - Create a class wrapper, convert existing classes into methods of the class.
 - Fix Unicode bugs.
