## Third-Party Downloads

This is a list of 3rd party binary packages based on Apache Apex. The Apache Apex project does not endorse or maintain any 3rd party binary packages.

- Apache Apex Bigtop packages [Docker image](https://hub.docker.com/r/apacheapex/sandbox/) (a ready to use sandbox environment in which bigtop-hadoop and bigtop-apex are pre-installed)

- [Apache Apex binary build](https://github.com/atrato/apex-cli-package/releases/) for users with existing clusters

- [Bigtop](http://bigtop.apache.org/) CI based distribution binaries:
  - Setup Bigtop Environment:
    1. Grab the repo/list file for your favourite linux distribution from [here](http://www.apache.org/dist/bigtop/bigtop-1.1.0/repos/)
    2. Install bigtop hadoop:
      - For RPM based systems: ** yum install hadoop\* **
      - For DEB baed systems: ** apt-get install hadoop\* **
    3. Follow steps [here](https://cwiki.apache.org/confluence/display/BIGTOP/How+to+install+Hadoop+distribution+from+Bigtop+0.5.0#HowtoinstallHadoopdistributionfromBigtop0.5.0-RunningHadoop) to start hadoop services.

  - Apex packages available are:
    - RPM: [CentOS 6](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=centos-6/lastSuccessfulBuild/artifact/output/apex/apex-3.5.0-1.el6.src.rpm), [CentOS 7](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=centos-7/lastSuccessfulBuild/artifact/output/apex/apex-3.5.0-1.el7.centos.src.rpm), [Fedora 25](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=fedora-25/lastSuccessfulBuild/artifact/output/apex/apex-3.5.0-1.fc25.src.rpm), [OpenSUSE 42.1](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=opensuse-42.1/lastSuccessfulBuild/artifact/output/apex/apex-3.5.0-1.src.rpm) 
    - DEB: [Ubuntu 16.04](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=ubuntu-16.04/lastSuccessfulBuild/artifact/output/apex/apex_3.5.0-1_all.deb), [Debian 8](https://ci.bigtop.apache.org/job/Bigtop-trunk-packages/COMPONENTS=apex,OS=debian-8/lastSuccessfulBuild/artifact/output/apex/apex_3.5.0-1_all.deb)


- <a href="https://www.datatorrent.com/download/" rel="nofollow">DataTorrent RTS</a>, which contains a binary build of Apache Apex.

If you would like to provide your own edition of Apache Apex here, please send email to [dev@apex.apache.org](mailto:dev@apex.apache.org).
