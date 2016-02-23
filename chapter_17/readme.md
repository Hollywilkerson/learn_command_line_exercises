#Alternative "english" ways of asking for your working directory:
##Can you show me all the files in slash temp slash foo?
Yes, use the command structure find . -name 'FILE' -print to list all files in '/tmp/foo/'.
I started in the path of..
/Users/hollywilkerson/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_17/log

I typed:
          find . -name "*.log"
 
 This is the output I got back...
 
 
         ./practice_2.log
         ./practice_3.log
         ./practice_4.log



##What log files are in your log directory?
I will use the find command again, but this time I will check for ".log" files within the 'log' directory.
I typed...

'find . -name "*.log" -print'

This is the output I got back...


        ./tmp/foo/house.log
        ./tmp/foo/practice.log
        ./tmp/foo/test.log


#Run find in the class directory, pipe the output to pbcopy and create a gist with the content.Paste the Gist URL as a comment on this story.

Ok i am going to 'cd' over to the class directory.. So I am starting in the path of..
/Users/hollywilkerson/workspace/davinci_coders_t1_2016

Now I am going to type:

find . -name '*' -print > homework/learn_command_line_exercises/chapter_17/pbcopy.txt

This is going to copy the output from the find into a pbcopy.txt within my chapter_17
directory. I will copy the URL as a comment to this story.




