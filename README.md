# FileReaderPython
Financial Document Reader
import os
os.chdir('/Users/580636/Documents')
print(os.getcwd())
# cwd = os.getcwd()  # Get the current working directory (cwd)
# files = os.listdir(cwd)  # Get all the files in that directory
# print("Files in %r: %s" % (cwd, files))
#
with open('/Users/580636/Documents/Finances/Discover/Discover-Statement.csv') as discover_file:
     for line in discover_file.readlines():
        print(line)
