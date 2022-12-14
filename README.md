![image](https://user-images.githubusercontent.com/75253629/198406644-f75ec147-0e46-4326-a999-06a052f0721e.png)

## Compile
<strong><h4>$~ csc.exe -out:insideheartz.exe insideheartz.cs</h4></strong>

## Execute
<strong><h4>$~ coldcryptor run []</h4></strong>

<details> <summary><strong><h3>Details</h3></strong></summary> 
  
- This will create three directories (one, two, three) and populate each with 50 .txt files.
  
- If a file called "data" is detected in the current directory, then its contents will be used to populate the generated files.
  
- Alternatively, if a directory is supplied, then it (and the files inside) will be used instead of the three directories + generated files.
  
- The list of files is then randomized and each file is encrypted and saved as the provided extension. 
  
- Finally, it writes a key and file association to HKCU. The association sets the extension to launch calc. However, no registry changes will happen if:
1. The current directory is UNC path
2. A directory is supplied and it is a UNC path
</details>

## Cleanup
<strong><h4>$~ insideheartz clean []</h4></strong>

<details> <summary><strong><h3>Details</h3></strong></summary>
  
  - This will delete the three directories/provided directory and all registry keys (same UNC restrictions apply).

</details>

## ⚠️ Disclaimer :
- I am not responsible for any misuse of this information, its only for education purposes 

## 📞 Contact :
<p align="center">
<a href="https://instagram.com/smadi0x01" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="smadi" height="25" width="25" /></a>
<a href="https://linkedin.com/in/saud-smadi" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="smadi" height="25" width="25" /></a>
<a href="https://t.me/rootsmadi" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/telegram.svg" alt="smadi" height="25" width="25" /></a>
</p>
