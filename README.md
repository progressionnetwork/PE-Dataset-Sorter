# PE-Dataset-Sorter
Tool for removing dublicates, validate, sort and separate PE files (for x86\64, .NET\Native, PE\NOT PE) in specified directories.

---

## Configuration
*Just configure dirs and options*

Classify set legitimate \ malware

* legitimate = True

Copy not pe objects to not_pe \ not_pe_clean dirs

* copy_not_pe = False 
    
Clean dublicate files matched by md5 hash

* clean_dublicates = False
    
    
*Dir to move legitimate files:*
* root_dir = 'Z:/training_set/not_classified_clean/'
* not_pe_dir = 'Z:/training_set/not_pe_clean/'
* net_pe_dir = 'Z:/training_set/net_pe_clean/'
* x32_dll_dir = 'Z:/training_set/x32_dll_clean/'
* x64_dll_dir = 'Z:/training_set/x64_dll_clean/'
* x32_exe_dir = 'Z:/training_set/x32_exe_clean/'
* x64_exe_dir = 'Z:/training_set/x64_exe_clean/'


*Dir to move malware files:*
* root_dir = 'Z:/training_set/VirusSignList_Free_140817/'
* not_pe_dir = 'Z:/training_set/not_pe/'
* net_pe_dir = 'Z:/training_set/net_pe/'
* x32_dll_dir = 'Z:/training_set/x32_dll/'
* x64_dll_dir = 'Z:/training_set/x64_dll/'
* x32_exe_dir = 'Z:/training_set/x32_exe/'
* x64_exe_dir = 'Z:/training_set/x64_exe/'


_Example of sorting:_
![alt text](https://github.com/progressionnetwork/PE-Dataset-Sorter/blob/master/pe_sorter.png)
