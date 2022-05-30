# Kubernetes Architecture

```mermaid
    flowchart TD;
    basic-linux((<b> Be a linux intermediate </b>))
    basic-linux --> learn-basics
    

    learn-basics(Learn the linux basics - Linux Journey Grasshopper)
    learn-basics --> use-first-linux

    use-first-linux(Use your first linux)
    use-first-linux --> use-your-computer

        use-your-computer(Add linux tools to your current computer)
        use-your-computer --> install-ubuntu-on-windows
        use-your-computer --> use-mac-as-linux

        install-ubuntu-on-windows(<u><b>Windows</u></b><br> Install Ubuntu on Windows)
        click install-ubuntu-on-windows "https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview"
        install-ubuntu-on-windows --> create-virtual-machine

        use-mac-as-linux(<u><b>Mac</u></b><br> Understand the difference between Mac and Linux)
        click use-mas-as-linux "https://www.comptia.org/blog/applying-your-linux-skills-to-macos-terminal-bash-and-common-commands"
        use-mac-as-linux --> create-virtual-machine

    
    create-virtual-machine(Create a linux virtual machine)
    create-virtual-machine --> run-linux-as-vm-on-windows
    create-virtual-machine --> run-linux-as-vm-on-mac

        run-linux-as-vm-on-windows(<u><b>Windows</u></b><br> Run Linux as a virtual machine on Windows)
        click run-linux-as-vm-on-windows "https://www.hawkdive.comhow-to-install-ubuntu-20-04-lts-on-virtualbox-in-windows-11/"
        run-linux-as-vm-on-windows --> learn-bash-tricks

        run-linux-as-vm-on-mac(<u><b>mac</u></b><br> Run Linux as a virtual machine on OS X)
        click run-linux-as-vm-on-windows "https://www.simplehelp.net/2015/06/09/how-to-install-ubuntu-on-your-mac/"
        run-linux-as-vm-on-mac --> learn-bash-tricks

    learn-bash-tricks(Learn Tools)
    learn-bash-tricks --> vi
    learn-bash-tricks --> linux-pipe
    learn-bash-tricks --> linux-awk
    learn-bash-tricks --> linux-sed

        vi(vi - A text editor)
        vi --> do-some-interview-questions

        linux-pipePipe(Linux pipe)
        linux-pipe --> do-some-interview-questions

        linux-awk(awk)
        linux-awk --> do-some-interview-questions

        linux-sed(sed)
        linux-sed --> do-some-interview-questions

    do-some-interview-questions(Do some interview questions)
    click do-some-interview-questions "https://www.interviewbit.com/linux-interview-questions/"

```


## Learn Linux
- [Linux Journey](https://linuxjourney.com/)
- [Introduction to Linux & Terminal Commands by Kunal Kushwaha](https://www.youtube.com/watch?v=iwolPf6kN-k)
- [Pick up one of the crash courses on YouTube](https://www.youtube.com/results?search_query=learn+linux)
