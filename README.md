ios-error-summary
====

1.fatal error:file'xxx' has been modified since the precompiled header ‘’was built
note: after modifying system headers, please delete the module cache at '/Users/xxx/Library/Developer/Xcode/DerivedData/ModuleCache/2NL4JXNO4XWW8'

改变了系统头文件，直接删除提示的文件，然后clean工程，重新编译即可
