# Transform-data-google-drive

Want to move a large number of files from a shared folder to your own drive without downloading them? Here's the solution for you. Select "open in colab" and enter the following inputs:

1. **Path to the folder on your Google Drive.**
2. **Path to the shared folder on Google Drive.**
3. **Optional settings:**
    - **From page, To page:** 0-0 to download all files, 0-1 to download files 1 to 100, 1-2 to download files 101 to 200, sorted by name.
    - **Maximum size (GB):** Total size of downloaded files. If this limit is exceeded, the program will stop. This value should be less than 750GB.
    - **Ignore files, folders containing:** Do not download files or folders containing the specified phrase. For example, if you want to avoid downloading .mp4 and .srt files, enter ".mp4,.srt" (separated by commas)."
