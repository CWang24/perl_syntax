
#Directly modify the originally file
$^I='.bak';                                   #this means generate a backup named .bak"
$file1='cmd.txt';                             #the value of $^I, if set as "undef", the edit-on-original function is closed
push @ARGV,$file1; 
while(<>)
{
	s/\s((.)..)\s..../ $1 $2/;
	print ;
}
close(INFO);
