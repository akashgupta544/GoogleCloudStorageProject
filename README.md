# GoogleCloudStorageProject
Utility to Drop and Dowload Files to and from Google Cloud Storage

This Project is to provide a utility that runs on your local device that allows
files in your local file system to be dropped into Google cloud storage, for added
safety those files should be encrypted, and after moving the encrypted file to Google
cloud it should be deleted from the local device. Of course, you should be able to
retrieve a file and decrypt it.
You should use a (validated) single key encryption, such as AES, and each file may
have it’s own key (password) so your program should prompt for that key/password.
You should also (in your program) be able to list and remove files from your
cloud storage.
