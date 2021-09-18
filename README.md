# Simple PHP Web Backdoor

<img src="https://user-images.githubusercontent.com/22043590/133885536-edd18c74-2eae-4a0a-b6a4-0d3603b532ab.png" width="450" />

A simple PHP web backdoor allows you to retrieve directory/file contents and upload file(s) from the local machine or remote URL.

It is handy if standard PHP web shells are restricted (e.g. system function disabled and such). I used this when performing penetration testing on security labs and Hack The Box, and it works great!

## Features

### Retrieve File/Scan Directory

<img src="https://user-images.githubusercontent.com/22043590/133885503-476cad23-978d-4b19-827d-3545c198993b.png" width="400" />

Enter the path you want to explore.

If it's a directory, it will list all the items in the directory. Otherwise, it will show the content of the file.

### Upload File From Your Local

Upload any file from your local computer. You can upload one or more files.

The backdoor will save the file in the same working directory.

### Upload File From URL

Upload any file from a remote URL. You need to specify the output file name and the URL of the remote file.

Make sure the host can access the remote file.

## Disclaimer

This script is only for permitted penetration testing and security research, and I will not be responsible if you use it for illegal activities.
