ios-error-summary
====

1.fatal error:file'xxx' has been modified since the precompiled header ‘’was built
note: after modifying system headers, please delete the module cache at '/Users/xxx/Library/Developer/Xcode/DerivedData/ModuleCache/2NL4JXNO4XWW8'

改变了系统头文件，直接删除提示的文件，然后clean工程，重新编译即可

2.ERROR ITMS-9000: “Redundant Binary Upload. There already exists a binary upload with build version '1.7' for train '1.7'”

see:http://stackoverflow.com/questions/25680604/error-itms-9000-redundant-binary-upload-there-already-exists-a-binary-upload
