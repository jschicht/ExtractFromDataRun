Introduction

In short this is stripped down version of the NTFS File Extractor; https://github.com/jschicht/NtfsFileExtractor


Details

It supports extraction from: 
 -Disk images, both of MBR/GPT style. 
 -Partition images. 
 -Volume Shadow Copies. 
 -Mounted NTFS volumes. 
 -Unmounted NTFS volumes, by scanning physical disk. 


However, as it is extracting from one given datarun list, it is limited to one data chunk at the time (normally a file). But it can be any attribute, not necessarily $DATA. 

This tool works well on the outputted datarun list, as output from the $LogFile parser; https://github.com/jschicht/LogFileParser
