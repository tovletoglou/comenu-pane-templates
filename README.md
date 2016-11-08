# ConEmu & Cmder: Panes templates and examples

## Templates

Here is a list of templates that I use to split tabs and create tab grids in ConEmu.

A handy way to use the pane functionality in ConEmu is to store them as predefined tasks (Settings->Startup->Tasks) and assigne them various tasks not just open a `cmd`, go to *Example configuration* section for more.

### Vertical
#### 1:1 Split screen
![1:1](images/1-1.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H

#### 1:2
![1:2](images/1-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H

    cmd -cur_console:s2T50V

#### 1:3
![1:3](images/1-3.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H

    cmd -cur_console:s2T68V
    cmd -cur_console:s3T50V

#### 2:2
![2:2](images/2-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H

    cmd -cur_console:s1T50V
    cmd -cur_console:s2T50V

#### 1:1:1
![1:1:1](images/1-1-1.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T68H
    cmd -cur_console:s2T50H

#### 1:2:2
![1:2:2](images/1-2-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T68H
    cmd -cur_console:s2T50H

    cmd -cur_console:s2T50V
    cmd -cur_console:s3T50V

#### 1:(2:2)
![1:2:2](images/1--2-2-.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H
    cmd -cur_console:s2T50H

    cmd -cur_console:s2T50V
    cmd -cur_console:s3T50V

#### 2:2:2
![2:2:2](images/2-2-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T68H
    cmd -cur_console:s2T50H

    cmd -cur_console:s1T50V
    cmd -cur_console:s2T50V
    cmd -cur_console:s3T50V

#### 3:3:3
![3:3:3](images/3-3-3.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T68H
    cmd -cur_console:s2T50H

    cmd -cur_console:s1T68V
    cmd -cur_console:s2T68V
    cmd -cur_console:s3T68V

    cmd -cur_console:s4T50V
    cmd -cur_console:s5T50V
    cmd -cur_console:s6T50V

#### 1:1:1:1
![1:1:1:1](images/1-1-1-1.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T75H
    cmd -cur_console:s2T67H
    cmd -cur_console:s3T50H

#### 2:2:2:2
![2:2:2:2](images/2-2-2-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T75H
    cmd -cur_console:s2T67H
    cmd -cur_console:s3T50H

    cmd -cur_console:s1T50V
    cmd -cur_console:s2T50V
    cmd -cur_console:s3T50V
    cmd -cur_console:s4T50V

#### 1:1:1:1:1
![1:1:1:1:!](images/1-1-1-1-1.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T80H
    cmd -cur_console:s2T75H
    cmd -cur_console:s3T65H
    cmd -cur_console:s4T50H

#### 2:2:2:2:2
![2:2:2:2:2](images/2-2-2-2-2.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T80H
    cmd -cur_console:s2T75H
    cmd -cur_console:s3T65H
    cmd -cur_console:s4T50H

    cmd -cur_console:s1T50V
    cmd -cur_console:s2T50V
    cmd -cur_console:s3T50V
    cmd -cur_console:s4T50V
    cmd -cur_console:s5T50V

#### 3:3:3:3:3
![3:3:3:3:3](images/3-3-3-3-3.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T80H
    cmd -cur_console:s2T75H
    cmd -cur_console:s3T65H
    cmd -cur_console:s4T50H

    cmd -cur_console:s1T66V
    cmd -cur_console:s2T66V
    cmd -cur_console:s3T66V
    cmd -cur_console:s4T66V
    cmd -cur_console:s5T66V

    cmd -cur_console:s6T50V
    cmd -cur_console:s7T50V
    cmd -cur_console:s8T50V
    cmd -cur_console:s9T50V
    cmd -cur_console:s10T50V

### Horizontal

#### (1:1)
![-1-1-](images/-1-1-.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50V

#### (1:1:1)
![-1-1-1-](images/-1-1-1-.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T66V
    cmd -cur_console:s2T50V

#### (1:2)
![-1-2-](images/-1-2-.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50V

    cmd -cur_console:s2T50H

#### (1:3)
![-1-3-](images/-1-3-.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50V

    cmd -cur_console:s2T68H
    cmd -cur_console:s3T50H

### Going Crazy

#### alpha
![alpha](images/alpha.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T33H

    cmd -cur_console:s2T68V
    cmd -cur_console:s3T50V

    cmd -cur_console:s1T33V

#### beta
![beta](images/beta.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T33H

    cmd -cur_console:s2T68V
    cmd -cur_console:s3T50V

    cmd -cur_console:s1T33V
    cmd -cur_console:s5T50H

#### gamma
![gamma](images/gamma.png?raw=true)

    cmd -cur_console
    cmd -cur_console:s1T50H
    cmd -cur_console:s2T50H

    cmd -cur_console:s2T33V
    cmd -cur_console:s2T50V

    cmd -cur_console:s3T33V
    cmd -cur_console:s3T50V

    cmd -cur_console:s1T33V
    cmd -cur_console:s8T50H

## Example configuration

Actual predefined tasks (command groups) that I use on daily basis.

### Task examples

Default task assigned to right-click `ConEmu Here`.

    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe --login -i

Run bash as admin.

    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe --login -i -cur_console:a

Login to remote server (Open bash from Windows -> SSH connection to remote server -> login to remote bash).

    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t username@server '/bin/bash -login'" -cur_console:n:t:"Tab name"

Open bash from Windows -> SSH connection to remote server -> Execute commands -> login to remote bash.

    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t username@server 'cd /home/user/directory && git fetch && /bin/bash -login'" -cur_console:n:t:"Tab 1"

Multi-server login. This is a single task with name "Vagrant" that logins to 5 Vagrant VMs (part of the same testing environment).

    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t vagrant@ansible.dev '/bin/bash -login'" -cur_console:n:t:Ansible
    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t vagrant@galera1.dev '/bin/bash -login'" -cur_console:s66H:n:t:Galera1
    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t vagrant@galera2.dev '/bin/bash -login'" -cur_console:s50H:n:t:Galera2
    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t vagrant@galera3.dev '/bin/bash -login'" -cur_console:s2T50V:n:t:Galera3
    set CHERE_INVOKING=1 & %ConEmuDir%\..\git-for-windows\bin\bash.exe -c "ssh -t vagrant@haproxy.dev '/bin/bash -login'" -cur_console:s3T50V:n:t:HAProxy

### Integrate bash with ConEmu on a portable manner

In order to run the above examples I use [ConEmu](https://github.com/Maximus5/ConEmu) with `bash` form [git-for-windows](https://github.com/git-for-windows/git).

1. Create a directory `software` in your CloudSyncService (Dropbox, Google Drive, OneDrive, etc) **without spaces** (some Linux tools that you will use later needs extra caution with spaces on paths, so we avoid them in the first place)
2. Download and extract the portable version of [git-for-windows-latest](https://github.com/git-for-windows/git/releases/latest)
3. Download and extract the portable version of [conemu-latest](https://github.com/Maximus5/ConEmu/releases/latest)

Directory structure:

    C:\CloudSyncService\
    C:\CloudSyncService\software\
    C:\CloudSyncService\software\git-for-windows\
    C:\CloudSyncService\software\git-for-windows\bin\bash.exe
    C:\CloudSyncService\software\conemu\
    C:\CloudSyncService\software\conemu\ConEmu.exe
