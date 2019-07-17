# Modify Authz file

## Input Value

|Vars|Example|
|:-:|:-:|
|ReadOnlyGroupMember|'tom, jack'|
|ReadWriteGroupMember|'tom'|
|SVNSRCPath|'/SYS/new/branch'|
|SVNRootPath|'/root/svn'|




## Add group

******a = a, b, c

******b = e, f, g

## Add group auth

[/SYS/new/branch]

******a = rw

******b = r
