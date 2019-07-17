## Modify Authz file

# Input Value

1.ReadOnlyGroupMember		'tom, jack'
2.ReadWriteGroupMember		'tom'
3.SVNSRCPath			'/SYS/new/branch'
4.SVNRootPath			'/root/svn'




# Add group
******a = a, b, c
******b = e, f, g

# Add group auth
[/SYS/new/branch]
******a = rw
******b = r
