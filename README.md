# metatool

Tool to create metadata reports for collections of video files.
Useful for video post-production departments looking to simplify creating catalogs of video archives.
Works best with reels of raw video and photographs. Supports all formats that Exiftool supports.

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
