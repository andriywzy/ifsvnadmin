# ifsvnadmin
ifsvnadmin with php+httpd

Default user&password: admin

How to visit your svnrepo?
http://YourIP/svn/repo 
(you mast creat zhe repo)

# Run command:
docker run -d -p 80:80 --name YourAPP andriywzy/ifsvnadmin

# SvnRepo Path is /svndata ,if you want to use local path ,UID is 33:
docker run -d -p 80:80 -v YourRepoPath:/svndata andriywzy/ifsvnadmin


