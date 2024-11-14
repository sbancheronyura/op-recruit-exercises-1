# Exercise 3: Working with Azure Storage Account

## Objective

Write a script to interact with an Azure Storage Account, downloading and uploading files.

## Instructions

1. **Accessing Data:** You are provided with a SAS (Shared Access Signature) URL for a container in an Azure Storage Account. This URL gives you access to download files within the container.

2. **Task:**
   - Use the SAS URL to download all files in the container.
   - Process or modify the files as you see fit (e.g., add a simple text line, compress, etc.).
   - Upload the processed files back to the container in a subfolder named `processed`.

3. **Resources Provided:**
   - **SAS URL**: You will be given a link to access the container.
   - **Documentation**: Refer to [Azure Blob Storage Documentation](https://learn.microsoft.com/en-us/azure/storage/blobs/) for information on how to use SAS URLs.
   - **Hint**: In python, you might want to use [this library] (https://pypi.org/project/azure-storage-blob/)

4. **Script Requirements:**
   - Write a Python script that:
     - Connects to the Azure Storage Account container using the provided SAS URL.
     - Downloads all files in the container to a local directory.
     - Processes or modifies the files in some way (you may choose any simple transformation, just rename the files, or upload something different).
     - Uploads the modified files to the same container.

5. **Deliverable:**
   - Submit your script along with any comments.

## Evaluation Criteria

Your submission will be evaluated based on:
- Successful connection to Azure Blob Storage and file management using SAS URL.
- Code readability and error handling.
- Completeness of the file download and upload functionality.

Good luck, and feel free to reach out if you have any questions!