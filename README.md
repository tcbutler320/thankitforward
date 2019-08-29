# Thankitforward
Thankitforward is a repository of tips and tricks I've learned over the years in the infosec and computer science world. Its a means to thank forward all the help I've received in the tech space from an amazing infosec community. I will continuously update this repo with the best resources, tools, and techniques I've learned along the way. If there are any questions feel free to reach out. I do not take credit for any of the resources listed here, they are all online tools and resources i've valued greatly

# Index
- [Thankitforward](#thankitforward)
- [Index](#index)
- [Home Pen Test Lab](#home-pen-test-lab)
    - [Index](#index-1)
    - [Getting Started](#getting-started)
    - [Virtualization](#virtualization)
    - [Attack Machines](#attack-machines)
    - [Target Machines](#target-machines)
    - [CTF](#ctf)
    - [Competitions](#competitions)
    - [More Resources](#more-resources)
  - [Penetration Testing](#penetration-testing)
  - [Programming](#programming)
  - [Raspberry Pi](#raspberry-pi)
  - [Custom PC Build](#custom-pc-build)


# Home Pen Test Lab
If you have ever thought about setting up a lab at home to further develop your penetration testing skills, this repository is for you. Here, I will add relevant resources I've come across in my own home lab development 

### Index
- [Thankitforward](#thankitforward)
- [Index](#index)
- [Home Pen Test Lab](#home-pen-test-lab)
    - [Index](#index-1)
    - [Getting Started](#getting-started)
    - [Virtualization](#virtualization)
    - [Attack Machines](#attack-machines)
    - [Target Machines](#target-machines)
    - [CTF](#ctf)
    - [Competitions](#competitions)
    - [More Resources](#more-resources)
  - [Penetration Testing](#penetration-testing)
  - [Programming](#programming)
  - [Raspberry Pi](#raspberry-pi)
  - [Custom PC Build](#custom-pc-build)

### Getting Started
The only basic requirement to setting up a home lab is access to a computer. If you do not have access to one, you can use one of the many online resources for access to a lab. Check out the [Online Pen Testing Resources](#penetration-testing) for more information on online labs. A home pentest lab can mean differnet things. For me, it's a collection of virtual machines used for practice. Below is an image of the current machines I keep in my lab. 


Home Dashboard: 
![alt text](/images/home-lab-spread.png "Nmap Scans in CTF Documentor")

### Virtualization 
The two most popular virtualization tools for a home lab are VM Ware or Virtual box. Download these to your computer with the following links 

1. [VM Ware Fusion](https://my.vmware.com/web/vmware/info/slug/desktop_end_user_computing/vmware_fusion/11_0)
2. [Virtual Box](https://www.virtualbox.org/wiki/Downloads)

With working virtualization software, you can now add machines to your lab. Keep in mind that most machines will be software specefic, if your downloading a machine built for virtualbox you should only import it there.

### Attack Machines
Now, download an attack machine. The most popular option is Kali Linux, but there are some other options as well. Find the links below

*Virtual Box Attack Machines*
1. [Kali Linux for Virtual Box](https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/)
2. [Parrot Security for Virtual Box](https://parrotlinux.org/download-security.php)
3. [BlackArch Linux](https://blackarch.org/downloads.html)
   
*VM Ware Attack Machines*
1. [Kali Linux for VMware](https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/)

### Target Machines

*Target Machines*
1. [Metasploitable](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/): This is one of the most popular target machines. It is purposfully built full of vulnerabilities. In contrast to most CTF machines, metasploitable has plenty of services up and running to play around with
2. [Metasploitable 2](https://metasploit.help.rapid7.com/docs/metasploitable-2): An updated version of metasploitable 
3. [Vulnhub Machines](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwjaks2D26bkAhWNtlkKHfWvDIMQFjAAegQIBBAC&url=https%3A%2F%2Fwww.vulnhub.com%2F&usg=AOvVaw0gnPjhXK-D1tSwTt15wBnD): Most of these are CTF's, but there is no other better source for getting virtual machines to test on. Visit [this](#ctf) link for a list of good vulnhub machines to try. 

### CTF
CTF's are a great source of vulnerable target machines to practice one. These are great for two reasons. First, sites like [vulnhub](www.vulnhub.com) offer hundreds of CTF machines for you to practice with. Second, if you are stuck or don't know where to start while trying to root a machine, most CTF's have tutorials online where you can get tips to get passed a difficult flag.

*Great Vulnhub Machines* #ctf-list
1. [Rickdiculously Easy CTF](https://www.vulnhub.com/entry/rickdiculouslyeasy-1,207/): A good begginer CTF. If you need tips on where to get started check out this [ tutorial](https://portunreachable.com/ctf-walkthrough-vulnhub-rickdiculouslyeasy-26da0981413a?gi=928bfc352af2)


*CTF Resources* #CTF
1. [A beginners Guide to Vulnhub](https://medium.com/@gavinloughridge/a-beginners-guide-to-vulnhub-part-1-52b06466635d): An overview on using vulnhub to find vulnerable target machines.
2. Introduction to Attack and Defense CTF](https://www.youtube.com/watch?v=oMDBTvehzs8): A brief overview video by the WriteupCTF Team about attack and defense CTF competitions
3. Livestream CTF Tutorial](https://www.youtube.com/watch?v=XJTYramNfEw): A live CTF twitch stream by thejustinsteven 
4. [CTF's useful for OSCP](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=0)
5. [Vulnhub](https://www.vulnhub.com/): An online repository of CTF's and vulnerable machines to use as target vm's



### Competitions



### More Resources
1. [Cover 6 Solutions, Home Lab Tutorial](https://www.cover6solutions.com/home-lab-setup/): A great guide to the ins and outs of setting up a home lab
2. [System Overloard on Building a Home Lab](https://systemoverlord.com/2017/10/24/building-a-home-lab-for-offensive-security-basics.html#hardware-option-a-just-use-the-cloud): A blog post about considerations for pen test labs


## Penetration Testing
1. [Awesome Pentest](https://github.com/enaqx/awesome-pentest): One of the best repo's for pen testing
2. [Over the Wire](https://overthewire.org/wargames/): An online platform for practicing penetration testing
3. [Hack the Box](https://www.hackthebox.eu/): An online platform with access to a virtual pen testing lab with over 20 machines of varying difficulty 

## Programming
1. [Quick Tip: Speed up your Python data processing scripts with Process Pools](https://medium.com/@ageitgey/quick-tip-speed-up-your-python-data-processing-scripts-with-process-pools-cf275350163a).
2. [Make Python Programs Run Faster with Process Library](https://medium.com/@urban_institute/using-multiprocessing-to-make-python-code-faster-23ea5ef996ba)

## Raspberry Pi

## Custom PC Build

1. [How To Build a $500 Gaming PC in 2018](https://www.youtube.com/watch?v=dFyhn6seoow)
2. [Wired : Building a Custom PC](https://www.wired.com/story/how-to-build-a-pc/
