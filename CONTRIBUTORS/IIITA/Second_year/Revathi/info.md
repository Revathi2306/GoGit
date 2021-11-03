SSH keys:
SSH is a secure shell network protocol that is used for network management, remote file transfer, and remote system access.
When SSH is created a public and a private key is generated. public key(lock) is shared with a platform and private key(key) is kept to oneself in a secure place.
SSH is a total solution to allow trusted, encrypted connections to other platforms.
Ques - What is a GitHub gpg key? Why it is used? Also, tell that why we need to sign the commits? Ans: A gpg key encodes our name and email into an encrypted form and this is attached to our github account. We sign commits with our gpg key so they can be verified and other collaborators can trust the source of the commit
How to edit the last commit message in git?
Ans:The most recent commit message can be edited using the git commit --amend command 
git commit --amend -m "title" -m "description"
use force push to change a commit which has been pushed.