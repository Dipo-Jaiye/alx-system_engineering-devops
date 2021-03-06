<h1> Shell commands </h1>

> Make sure to start scripts with #!/bin/bash and make scripts executable with chmod u+x filename

1. 0-current\_working\_directory - This script uses the pwd shell command to print the current working directory's absolute path.

2. 1-listit - This script uses ls to print all the contents of the current working directory.

3. 2-bring\_me\_home - This script uses cd and a space to redirect user to home directory. Try it with source to see the effect.

4. 3-listfiles - This script uses ls -l to list all contents in working directory in long format.

5. 4-listmorefiles - This script uses ls -al to list all files including hidden ones in long format.

6. 5-listfilesdigitonly - This scripts uses ls -lan to list all files in long format with user id and numeric group IDs.

7. 6-firstdirectory - This script uses mkdir to create a directory in the /tmp/ directory.

8. 7-movethatfile - This script uses the mv command to move betty from somewhere to another.

9. 8-firstdelete - This script uses the rm command to delete a file with path specified.

10. 9-firstdirdeletion - This script deletes a directory with rm -r.

11. 10-back - This script changes a working directory to previous with cd -.

12. 11-lists - This script lists all directories in a specified order.

13. 12-file\_type - This script prints file type with file command.

14. 13-symbolic\_link - This script creates a symbolic link of __ls__ to /bin/ls

15. 14-copy\_html - This script copies stuff using cp and the -u flag.

16. 100-lets\_move - This script moves all files starting with capital to a directory /tmp/u with the -t flag.

17. 101-clean\_emacs - This script uses rm to delete files matching a wildcard.

18. 102-tree - This script creates three directories with mkdir.

19. 103-commas - This script uses various options of the ls command.

20. School.mgc - This magic file was compiled with file -C -m school. It checks for files that start with SCHOOL at offset 0.
