# Important Packages for a software engineer based on their project.
---

> **MARKDOWN REFERENCE SHEET**
>> Here is a resource for a markdown reference sheet by [Mark Down Guide](https://www.markdownguide.org/basic-syntax/)

> ## Core Modules
> ---
>> - FS
>> - Path

---
---

> ## **FS**
> ---
>
>> #### Reference Link
>> ---
>>> - **[NodeJs.org]**(https://nodejs.org/api/fs.html)
>>>   
>> ##### **__SYNTAX__**
>> 
>>>     const fs = require('fs'); //import statement in JS
>>
>> ##### Use Case
>> ---   
>>>  - The built-in Node.js file system module helps us store, 
>>>    access, and manage data on our operating system. Commonly used 
>>>    features of the fs module include fs.readFile to read data from a 
>>>    file, fs.writeFile to write data to a file and replace the file if 
>>>    it already exists, fs.watchFile to get notified of changes, and 
>>>    fs.appendFile to append data to a file. The fs core module is available 
>>>    in every Node.js project without having to install it.
>>>    The node:fs module enables interacting with the file system in a way
>>>    modeled on standard POSIX functions.
>   
>> #### **__ESM Script EXAMPLES__**
>>   ---
>> 
>>>  ###### Promise example
>>>   ---
>>> 
>>>>      import { unlink } from 'node:fs/promises';
>>>>      try {
>>>>        await unlink('/tmp/hello');
>>>>        console.log('successfully deleted /tmp/hello');
>>>>        }
>>>>      catch (error) {
>>>>        console.error('there was an error:', error.message);
>>>>        } 

---
---

> ### **Path**
> ---
>
>>   #### Reference Link
>> ---
>>> - **[Scaler.com]**(https://www.scaler.com/topics/nodejs/path-module-in-node-js/)
>>
>>>   #### **__SYNTAX__**
>>>   ---
>>>>      const path = require('path'); //importing path in JS
>>>>      path.basename(path[, ext]) //using path
>
>> #### Use Case
>> ---      
>>>   - Many people forget about one of Node.js' most simple and important 
>>>    core modules, the path module. The path module in node js is used for 
>>>    managing and altering file paths. It's a part of the core modules with 
>>>   methods that help you deal with directory and file path names on the local 
>>>    machine's file system. Every system has a different environment and a specific 
>>>    operating system to manage it. Different operating systems manage file 
>>>    and directory-related operations differently.
>   
>>   - **__EXAMPLES__**
>>   ---
>>>     
>>>      // Importing the path module in node js
>>>        const path = require('path');
>>>     
>>
>>>     
>>>        // basename method gives the file name from path name
>>>        const filename = path.basename('/Users/scaler/demo_path.js');
>>>        console.log(filename);
>>>     
>>
>
     
