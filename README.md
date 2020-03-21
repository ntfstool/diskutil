diskutil tool for MacOS

For Example

getDiskList().then((diskList) => {
    console.log(diskList, "getDiskList");
});

Debug Mode
getDiskList(true).then((diskList) => {
    console.log(diskList, "getDiskList");
});


getDiskInfo("disk2s1").then((diskInfo) => {
    console.log(diskInfo, "diskInfo");
});
    
getDiskInfo("disk2s1",true).then((diskInfo) => {
    console.log(diskInfo, "diskInfo");
});

keywords:diskutil macos disk