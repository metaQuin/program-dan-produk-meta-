/[<user>@]<host>[:<port>]/<path-to-git-repo>

git://<host>[:<port>]/<path-to-git-repo>

http[s]://<host>[:<port>]/<path-to-git-repo>

ftp[s]://<host>[:<port>]/<path-to-git-repo>

An alternative scp-like syntax may also be used with the ssh protocol:

[<user>@]<host>:/<path-to-git-repo>

This syntax is only recognized if there are no slashesecho "# program-dan-produk-meta-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/metaQuin/program-dan-produk-meta-.git
git push -u origin main
