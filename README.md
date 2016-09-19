# exiftool-rpm

# 2016-09-19
# Where there's a need, we tend to make something up.
# So, here's something to help you make Phil Harvey's 
# most excellent Image-ExifTool for Red Hat / CentOS

# Download the latest tarball from:
# http://www.sno.phy.queensu.ca/~phil/exiftool/

# as normal user do:
# $ sudo yum install rpmdevtools
# $ rpmdev-setuptree
# $ cd rpmbuild/SOURCES && wget <source tarball>
# $ cd ..
# $ cp ~/exiftool.spec ./SPECS/
# $ rpmbuild -ba SPECS/exiftool.spec

# package should be ready for you in ~/rpmbuild/RPMS/
# $ sudo yum install ~/rpmbuild/RPMS/Image-ExifTool....rpm
