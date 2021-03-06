## Test plan Simplified smoke test.

| Test Case                                | Expected Result                          | Result      | Related Comment |
| ---------------------------------------- | ---------------------------------------- | ----------- | --------------- |
| **Web UI**                               |                                          |             |                 |
| Login with admin user.                   | Admin logs in.                           | :construction: |                 |
| Create a text file.                      | Text editor can open, file is saved.     | :construction: |                 |
| Modify a text file.                      | File can be modified, no problems found. | :construction: |                 |
| Rename a file.                           | File is renamed.                         | :construction: |                 |
| Upload a file.                           | File is uploaded, no problems found.     | :construction: |                 |
| Overwrite a file by uploading a new version. | File is uploaded and overwritten, no problems found. | :construction: |                 |
| Remove a file.                           | File is removed correctly, it appears in the trashbin. | :construction: |                 |
| Move a file inside a folder.             | There are not problems on the process.   | :construction: |                 |
| Create a folder.                         | Folder is created, no MKCOL problems appear. | :construction: |                 |
| Delete a folder.                         | Folder is removed.                       | :construction: |                 |
| Move a folder inside another.            | No problems while moving the folder.     | :construction: |                 |
| Share a file by link.                    | Link is created and can be accessed.     | :construction: |                 |
| Share a file with another user.          | It is shared correctly.                  | :construction: |                 |
| Share a file with a group.               | It is shared correctly.                  | :construction: |                 |
| Share a file with another user in another server. | Federated shared happens correctly.      | :construction: |                 |
| Share a folder with userB giving edit permissions, As userB open the recieved folder, download files inside, open them. Upload new files. Modify files and delete them. | userB doesn't find any problem while interacting with files. | :construction: |                 |
| Federate share a folder giving edit permissions with userB in serverB, As userB open the recieved folder, download files inside, open them. Upload new files. Modify files and delete them. | userB doesn't find any problem while interacting with files. | :construction: |                 |
| **Desktop Client**                       |                                          |             |                 |
| Set up two clients with the same user. Change files, add some, delete some, move some, create folders. | Changes sync properly in both clients without errors. | :construction: |                 |
| Share a file using contextual menu with userB. | Option to share appears in the contextual menu and file is correctly shared. | :construction: |                 |
| **Mobile Clients** (iOS \|\| Android)    |                                          |             |                 |
| Connect to server, see files, download one. | No problems while downloading.           | :construction: |                 |
| Upload a file using mobile client.       | No problems while uploading.             | :construction: |                 |
| Share a file with userB using mobile client. | File is correctly shared.                | :construction: |                 |



