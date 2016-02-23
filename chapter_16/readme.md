#Do More Add the * to your deck of flash cards. On the back write: "matches anything in a wildcard like *.txt".

I added this to my Anki cards :)

#Alternative "english" ways of using the asterisk:
##Can you output all the txt files in this directory?
Yes we will need to copy some files over from the previous chapter_15 so we have some files to work with.
Then I  will use the command 'cat' and the * to wildcard match all .txt files in 'chapter_16' 
and have them output to the command line....

$cp ../chapter_15/*.txt ./
$cat *.txt
bar bar bar bar bar bar bar
bar bar bar bar bar bar bar


##Show me the content of the text files in slash temp.
There isnt any ".txt" files within the /tmp directory. This is the output I get...

Chapter_16(master) $cat /tmp/*.txt
cat: /tmp/*.txt: No such file or directory

Then I ended up doing an 'ls' on the "/tmp" folder just to make sure there isn't any ".txt" files..
This is the output I get when I do just an 'ls' on the "/tmp" directory...

chapter_16(master) $ls /tmp/
KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.7Za92pcJ86
com.apple.launchd.AJ70vjzC82
ct.shutdown
textmate-501.sock
wifi-1CbRhM.log
wifi-5GrxLy.log
wifi-QTE7ET.log
wifi-Y4rUhs.log
wifi-o7DPFY.log
chapter_16(master) $
