# vendor_nurkeinneid
Repo for adding my personal apps to my device(s)

Feel free to fork and use/edit/modify as you will =)

Just clone the project or add the following to your roomservice.xml:
```bash
<project name="NurKeinNeid/vendor_nurkeinneid" path="vendor/nurkeinneid" remote="github" revision="master" />
```
Then, add the following call in your rom makefile (ie: lineage.mk)
```bash
$(call inherit-product, vendor/nurkeinneid/apps.mk)
```
