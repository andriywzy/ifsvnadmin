#ifsvnadmin with php+httpd
Default user&password: admin

Run command:
docker run -d -p 80:80 --name YourAPP andriywzy/ifsvnadmin

SvnRepo Path is /svndata ,if you want to use local path:
docker run -d -p 80:80 -v YourRepoPath:/svndata andriywzy/ifsvnadmin

