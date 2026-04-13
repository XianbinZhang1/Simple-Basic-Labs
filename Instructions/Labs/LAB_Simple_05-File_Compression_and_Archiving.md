---
lab:
  title: 'Simple Lab 05: File Compression and Archiving'
  module: Basic Computer Skills
  description: Learn to compress and archive files using built-in Windows tools
  duration: 15 minutes
  level: 100
  islab: true
  primarytopics:
    - File Compression
    - ZIP Archives
    - File Archiving
---

# Simple Lab 05 - File Compression and Archiving

## Lab introduction

In this lab, you will learn how to compress files and create archives. File compression reduces file sizes, making them easier to store and transmit. Windows provides built-in tools for creating ZIP archives without requiring additional software.

## Estimated timing: 15 minutes

## Lab scenario

You have multiple documents that you need to send via email or store efficiently. In this exercise, you will compress files into a ZIP archive to reduce the overall file size and create a portable archive.

## Job skills

+ Task 1: Create a ZIP archive from files
+ Task 2: Extract files from a ZIP archive

## Task 1: Create a ZIP archive from files

In this task, you will compress multiple files into a single ZIP archive.

1. Open **File Manager** and navigate to **Documents > MyLab_Documents > Projects**.

2. You should see the text files created in **Simple Lab 02** (ProjectPlan_v2.txt, Tasks.txt, Notes.txt).

3. Select the first file by clicking on it.

4. Hold **Ctrl** and click on the other files to select all three files at once.

5. Right-click on one of the selected files and look for the **Send to** option.

6. Hover over **Send to** and select **Compressed (zipped) folder**.

7. A new ZIP file will be created with a default name like **Projects.zip**.

8. Right-click on the new ZIP file and select **Rename**.

9. Type a new name: `MyLab_Archive.zip` and press **Enter**.

10. Observe that the ZIP file shows a **zipper icon** indicating it is a compressed archive.

11. Right-click on **MyLab_Archive.zip** and select **Properties** to view:
    - The compressed file size
    - Compare it with the original files' combined size
    - Note the reduction in storage space

## Task 2: Extract files from a ZIP archive

In this task, you will extract files from the ZIP archive to verify the backup.

1. Right-click on **MyLab_Archive.zip** and select **Extract All**.

2. The **Extract Compressed (Zipped) Folders** dialog will appear.

3. Click **Browse** to choose where to extract the files.

4. Navigate to **Documents > MyLab_Documents > Resources** folder.

5. Click **Select Folder** to confirm the extraction location.

6. Click the **Extract** button.

7. Wait for the extraction to complete. The extracted files will appear in the Resources folder.

8. Navigate to **Documents > MyLab_Documents > Resources** to verify:
   - ProjectPlan_v2.txt
   - Tasks.txt
   - Notes.txt

9. Open one of the extracted files to confirm the content is intact and unchanged.

10. Verify that the extracted files have the same content as the originals by opening **Lab_Notes.txt** (if available) and comparing.

## Summary

In this lab, you have successfully:
- Selected multiple files for compression
- Created a ZIP archive using Windows' built-in compression
- Named the archive with a meaningful filename
- Compared the compressed and original file sizes
- Extracted files from the ZIP archive
- Verified that extracted files are identical to the originals

These file compression skills are essential for managing storage space and sharing files efficiently.
