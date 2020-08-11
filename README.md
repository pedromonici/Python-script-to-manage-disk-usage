# Python-script-to-manage-disk-usage

Hi there! This is a simple script to generate a disk usage report on Linux.

First of all, you need to make sure that you have the ***Pandas*** module, if is not installed just type:

`$ pip3 install pandas`

Next, you need to clone this repository in your machine:

`$ git clone https://github.com/pedromonici/Python-script-to-manage-disk-usage.git DiskUsage`

And then just type the following commands:

`$ cd DiskUsage`

`$ python disk_report.py Directory` , i.e: `$ python disk_report /home`
 
 In some cases, you need the root permission to access the directory, then just type with `sudo`

After that, the script will generate a .csv file with the results of the disk report given in the command line!
