# showpath

Show various linux'ish system paths

## Usage


### show default set of paths
```
showpath
```


### show python paths
``` python
$ showpath-python
sys.argv: ['/home/adrian/bin/showpath-python']
env vars
PATH: /home/adrian/.rvm/gems/ruby-2.0.0-p353/bin:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global/bin:/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin:/home/adrian/.rvm/bin:/home/adrian/src/ansible/bin:/home/adrian/bin:/home/adrian/.local/bin:/usr/lib64/qt-3.3/bin:/usr/local/bin:/usr/local/sbin:/usr/bin:/usr/sbin:/bin:/sbin:/home/adrian/.cabal/bin:/home/adrian/gopath/bin:/home/adrian/.cabal/bin
HOME: /home/adrian
PYTHONPATH: /home/adrian/src/ansible/lib:
PYTHONHOME: None
PYTHONNOUSERSITE: None
PYTHONUSERBASE: None

python sys paths
sys.path: 
	/home/adrian/src/alikins-bin
	/home/adrian/.local/lib/python2.7/site-packages/github_comments-1.3-py2.7.egg
	/home/adrian/.local/lib/python2.7/site-packages/subscription_manager-1.17.3-py2.7.egg
	/usr/lib/python2.7/site-packages/pip-1.5.6-py2.7.egg
	/usr/lib/python2.7/site-packages/rho-0.0.21-py2.7.egg
	/usr/lib/python2.7/site-packages/tbgrep-0.2.3-py2.7.egg

	/usr/lib/python2.7/site-packages/rainbow_logging_handler-2.2.2-py2.7.egg
	/usr/lib/python2.7/site-packages/github_comments-1.3-py2.7.egg
	/usr/lib/python2.7/site-packages/noselog-0.0.5-py2.7.egg
	/usr/lib/python2.7/site-packages/tito-0.6.2-py2.7.egg
	/home/adrian/src/ansible/lib
	/home/adrian/src/showpath
	/usr/lib64/python27.zip
	/usr/lib64/python2.7
	/usr/lib64/python2.7/plat-linux2
	/usr/lib64/python2.7/lib-tk
	/usr/lib64/python2.7/lib-old
	/usr/lib64/python2.7/lib-dynload
	/home/adrian/.local/lib/python2.7/site-packages
	/usr/lib/python2.7/site-packages
	/usr/lib64/python2.7/site-packages
	/usr/lib64/python2.7/site-packages/gtk-2.0
	/usr/local/lib/python2.7
	/usr/local/lib/python2.7/site-packages
sys.prefix: /usr
sys.exec_prefix: /usr
sys.meta_path: []
sys.path_hooks: [<type 'zipimport.zipimporter'>]

python site.py (+sitcustomize)
site.PREFIXES: ['/usr', '/usr']
site.USER_SITE: /home/adrian/.local/lib/python2.7/site-packages
site.USER_BASE: /home/adrian/.local
site.getsitepackages(): 
	/usr/lib64/python2.7/site-packages
	/usr/lib/python2.7/site-packages
	/usr/lib/site-python

sitecustomize dir: ['__builtins__', '__doc__', '__file__', '__name__', '__package__', 'os', 'path', 'platform', 'site', 'site_path', 'sys']
```

### show paths to python related things
```
$ showpath-python-shell 
python: /usr/bin/python
python-config --prefix: /usr
python-config --includes: -I/usr/include/python2.7 -I/usr/include/python2.7
python2: /usr/bin/python2
python3: /usr/bin/python3
pip exec: /usr/bin/pip
easy_install: /home/adrian/.local/bin/easy_install
```


### show rvm related paths
```
$ showpath-rvm 
rvm info

ruby-2.0.0-p353:

  system:
    uname:       "Linux grimlock.usersys.redhat.com 3.10.0-327.10.1.el7.x86_64 #1 SMP Sat Jan 23 04:54:55 EST 2016 x86_64 x86_64 x86_64 GNU/Linux"
    system:      "redhat/7/x86_64"
    bash:        "/usr/bin/bash => GNU bash, version 4.2.46(1)-release (x86_64-redhat-linux-gnu)"
    zsh:         " => not installed"

  rvm:
    version:      "rvm 1.25.27 (stable) by Wayne E. Seguin <wayneeseguin@gmail.com>, Michal Papis <mpapis@gmail.com> [https://rvm.io/]"
    updated:      "1 year 9 months 8 days 21 hours 1 minute 31 seconds ago"
    path:         "/home/adrian/.rvm"

  ruby:
    interpreter:  "ruby"
    version:      "2.0.0p353"
    date:         "2013-11-22"
    platform:     "x86_64-linux"
    patchlevel:   "2013-11-22 revision 43784"
    full_version: "ruby 2.0.0p353 (2013-11-22 revision 43784) [x86_64-linux]"

  homes:
    gem:          "/home/adrian/.rvm/gems/ruby-2.0.0-p353"
    ruby:         "/home/adrian/.rvm/rubies/ruby-2.0.0-p353"

  binaries:
    ruby:         "/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin/ruby"
    irb:          "/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin/irb"
    gem:          "/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin/gem"
    rake:         "/home/adrian/.rvm/gems/ruby-2.0.0-p353/bin/rake"

  environment:
    PATH:         "/home/adrian/.rvm/gems/ruby-2.0.0-p353/bin:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global/bin:/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin:/home/adrian/.rvm/bin:/home/adrian/src/ansible/bin:/home/adrian/bin:/home/adrian/.local/bin:/usr/lib64/qt-3.3/bin:/usr/local/bin:/usr/local/sbin:/usr/bin:/usr/sbin:/bin:/sbin:/home/adrian/.cabal/bin:/home/adrian/gopath/bin:/home/adrian/.cabal/bin"
    GEM_HOME:     "/home/adrian/.rvm/gems/ruby-2.0.0-p353"
    GEM_PATH:     "/home/adrian/.rvm/gems/ruby-2.0.0-p353:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global"
    MY_RUBY_HOME: "/home/adrian/.rvm/rubies/ruby-2.0.0-p353"
    IRBRC:        "/home/adrian/.rvm/rubies/ruby-2.0.0-p353/.irbrc"
    RUBYOPT:      ""
    gemset:       ""


gemsets info

gemsets for ruby-2.0.0-p353 (found in /home/adrian/.rvm/gems/ruby-2.0.0-p353)
=> (default)
   add-skus-to-stage
   alikins
   candlepin
   candlepin-api
   fresh-thumbslug
   global
   newcandlepin
   NO-JOB-NAME-gemset
   padscraper
   rhc


gemsets for ruby-1.9.3-p547 (found in /home/adrian/.rvm/gems/ruby-1.9.3-p547)
=> (default)
   cp_api
   devtowermisc
   github-markdown
   global
   nagios
   vim-flavor


gemsets for ruby-1.9.3-p545 (found in /home/adrian/.rvm/gems/ruby-1.9.3-p545)
=> (default)
   candlepinproject.org
   global


```

### show gem related paths
```
$ showpath-gem 
ruby environment
RubyGems Environment:
  - RUBYGEMS VERSION: 2.2.2
  - RUBY VERSION: 2.0.0 (2013-11-22 patchlevel 353) [x86_64-linux]
  - INSTALLATION DIRECTORY: /home/adrian/.rvm/gems/ruby-2.0.0-p353
  - RUBY EXECUTABLE: /home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin/ruby
  - EXECUTABLE DIRECTORY: /home/adrian/.rvm/gems/ruby-2.0.0-p353/bin
  - SPEC CACHE DIRECTORY: /home/adrian/.gem/specs
  - RUBYGEMS PLATFORMS:
    - ruby
    - x86_64-linux
  - GEM PATHS:
     - /home/adrian/.rvm/gems/ruby-2.0.0-p353
     - /home/adrian/.rvm/gems/ruby-2.0.0-p353@global
  - GEM CONFIGURATION:
     - :update_sources => true
     - :verbose => true
     - :backtrace => false
     - :bulk_threshold => 1000
  - REMOTE SOURCES:
     - https://rubygems.org/
  - SHELL PATH:
     - /home/adrian/.rvm/gems/ruby-2.0.0-p353/bin
     - /home/adrian/.rvm/gems/ruby-2.0.0-p353@global/bin
     - /home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin
     - /home/adrian/.rvm/bin
     - /home/adrian/src/ansible/bin
     - /home/adrian/bin
     - /home/adrian/.local/bin
     - /usr/lib64/qt-3.3/bin
     - /usr/local/bin
     - /usr/local/sbin
     - /usr/bin
     - /usr/sbin
     - /bin
     - /sbin
     - /home/adrian/.cabal/bin
     - /home/adrian/gopath/bin
     - /home/adrian/.cabal/bin

```

### show go related paths
``` shell
$ showpath-go 
/home/adrian/gopath
GOARCH="amd64"
GOBIN=""
GOCHAR="6"
GOEXE=""
GOHOSTARCH="amd64"
GOHOSTOS="linux"
GOOS="linux"
GOPATH="/home/adrian/gopath"
GORACE=""
GOROOT="/usr/lib/golang"
GOTOOLDIR="/usr/lib/golang/pkg/tool/linux_amd64"
CC="gcc"
GOGCCFLAGS="-fPIC -m64 -pthread -fmessage-length=0"
CXX="g++"
CGO_ENABLED="1"
```

### show java related paths
```
$ showpath-java 
JAVA_HOME=/usr/lib/jvm/java
java - status is auto.
 link currently points to /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/java
/usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/java - priority 1700099
 slave jjs: (null)
 slave keytool: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/keytool
 slave orbd: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/orbd
 slave pack200: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/pack200
 slave policytool: (null)
 slave rmid: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/rmid
 slave rmiregistry: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/rmiregistry
 slave servertool: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/servertool
 slave tnameserv: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/tnameserv
 slave unpack200: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre/bin/unpack200
 slave jre_exports: /usr/lib/jvm-exports/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64
 slave jre: /usr/lib/jvm/java-1.7.0-openjdk-1.7.0.99-2.6.5.0.el7_2.x86_64/jre
/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/java - priority 1800077
 slave jjs: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/jjs
 slave keytool: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/keytool
 slave orbd: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/orbd
 slave pack200: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/pack200
 slave policytool: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/policytool
 slave rmid: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/rmid
 slave rmiregistry: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/rmiregistry
 slave servertool: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/servertool
 slave tnameserv: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/tnameserv
 slave unpack200: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/unpack200
 slave jre_exports: /usr/lib/jvm-exports/jre-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64
 slave jre: /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre
Current `best' version is /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/bin/java.
    java.class.path = .
    java.endorsed.dirs = /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/lib/endorsed
    java.ext.dirs = /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/lib/ext
    java.home = /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre
    java.library.path = /usr/java/packages/lib/amd64
    sun.boot.class.path = /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/lib/resources.jar
    sun.boot.library.path = /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.77-0.b03.el7_2.x86_64/jre/lib/amd64
    user.dir = /home/adrian/src/showpath
    user.home = /home/adrian

```

### show paths set via shell env variables
``` shell
showpath-bash
PATH=/home/adrian/.rvm/gems/ruby-2.0.0-p353/bin:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global/bin:/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin:/home/adrian/.rvm/bin:/home/adrian/src/ansible/bin:/home/adrian/bin:/home/adrian/.local/bin:/usr/lib64/qt-3.3/bin:/usr/local/bin:/usr/local/sbin:/usr/bin:/usr/sbin:/bin:/sbin:/home/adrian/.cabal/bin:/home/adrian/gopath/bin:/home/adrian/.cabal/bin

PYTHONPATH=/home/adrian/src/ansible/lib:

GEM_PATH=/home/adrian/.rvm/gems/ruby-2.0.0-p353:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global

rvm_bin_path=/home/adrian/.rvm/bin

rvm_path=/home/adrian/.rvm

rvm_prefix=/home/adrian

JAVA_HOME=/usr/lib/jvm/java

M2_REPO=/home/adrian/.m2/repository
```

### show misc system paths
``` shell
$ bin/showpath-misc 
ldconfig/ld
/usr/lib64/atlas:
/opt/rh/devtoolset-3/root/usr/lib64/dyninst:
/usr/lib64/dyninst:
/usr/lib64/iscsi:
/usr/lib64/cmpi:
/usr/lib64/llvm:
/usr/lib64/mysql:
/usr/lib64/opencryptoki:
/usr/lib64/opencryptoki/stdll:
/usr/lib64/qt-3.3/lib:
/usr/lib64/tcl8.5:
/usr/lib64/xulrunner:
/lib:
/lib64:
/lib/sse2: (hwcap: 0x0000000004000000)
/lib64/sse2: (hwcap: 0x0000000004000000)
/lib64/tls: (hwcap: 0x8000000000000000)
MANPATH=/home/adrian/src/ansible/docs/man:
rvm_bin_path=/home/adrian/.rvm/bin
VIRTUALENVWRAPPER_SCRIPT=/home/adrian/bin/virtualenvwrapper.sh
GEM_HOME=/home/adrian/.rvm/gems/ruby-2.0.0-p353
IRBRC=/home/adrian/.rvm/rubies/ruby-2.0.0-p353/.irbrc
QTDIR=/usr/lib64/qt-3.3
MY_RUBY_HOME=/home/adrian/.rvm/rubies/ruby-2.0.0-p353
rvm_path=/home/adrian/.rvm
WORKON_HOME=/home/adrian/.virtualenvs
rvm_prefix=/home/adrian
PATH=/home/adrian/.rvm/gems/ruby-2.0.0-p353/bin:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global/bin:/home/adrian/.rvm/rubies/ruby-2.0.0-p353/bin:/home/adrian/.rvm/bin:/home/adrian/src/ansible/bin:/home/adrian/bin:/home/adrian/.local/bin:/usr/lib64/qt-3.3/bin:/usr/local/bin:/usr/local/sbin:/usr/bin:/usr/sbin:/bin:/sbin:/home/adrian/.cabal/bin:/home/adrian/gopath/bin:/home/adrian/.cabal/bin
ANSIBLE_HOME=/home/adrian/ansible
VIRTUALENVWRAPPER_HOOK_DIR=/home/adrian/.virtualenvs
PWD=/home/adrian/src/showpath
JAVA_HOME=/usr/lib/jvm/java
PYTHONSTARTUP=/home/adrian/.pystartup
KDEDIRS=/usr
HOME=/home/adrian
PYTHONPATH=/home/adrian/src/ansible/lib:
M2_REPO=/home/adrian/.m2/repository
GEM_PATH=/home/adrian/.rvm/gems/ruby-2.0.0-p353:/home/adrian/.rvm/gems/ruby-2.0.0-p353@global
GOPATH=/home/adrian/gopath
PKG_CONFIG_PATH=/usr/local/lib/pkgconfig/
ANSIBLE_CONFIG=/home/adrian/ansible/ansible.cfg
WINDOWPATH=1
XDG_RUNTIME_DIR=/run/user/1000
QT_PLUGIN_PATH=/usr/lib64/kde4/plugins:/usr/lib/kde4/plugins
```

## Install

Copy "bin/\*" to your path.

If you don't know what is on the path, run 'showpath'

## License

GPLv2
