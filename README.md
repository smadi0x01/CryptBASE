## Compile
- csc.exe -out:insideheartz.exe insideheartz.cs

## Execute
- coldcryptor run []
<details><title> Will create three directories (one, two, three) and populate each with 50 .txt files. 
- If a file called "data" is detected in the current directory, then its contents will be used to populate the generated files.
- Alternatively, if a directory is supplied, then it (and the files inside) will be used instead of the three directories + generated files.
- The list of files is then randomized and each file is encrypted and saved as the provided extension. 
- Finally, it writes a key and file association to HKCU. The association sets the extension to launch calc. However, no registry changes will happen if:

- the current directory is UNC path
- a directory is supplied and it is a UNC path
</title></details>


