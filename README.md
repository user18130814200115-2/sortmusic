# sortmusic
A shell script to sort all of your .mp3 files.  
This script will sort music based on ID3 tags in ./artist/album/title.mp3. The scripts speed will depend on your hardware (mainly drive and processor speed) but for me it sorted over 1000 files (11.4 GB) in a little over 15 seconds.

# dependencies
id3

# usage
Simply run `sortmusic` in a directory with all the mp3 files you wish to sort.   
My files were parialy sorted already, so I used `find / -iname "*.mp3" -exec mv {} ~/Music \` to move all my mp3 files to the ~/Music folder beforehand. From there the script sorted them.
