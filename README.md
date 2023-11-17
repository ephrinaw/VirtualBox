
The purpose of this assignment is to get an overview of "VirtualBox Tool" for creating virtual machines, cloning and taking snapshots.
## Materials
Oracle VM VirtualBox,
Ubuntu Server Image and  
[Virtual Box Official Documentation](https://www.virtualbox.org/wiki/Documentation) 
## Step-by-step guide:
Set up Virtual Box in your personal device. You may also do it on top of a virtual machine in Vcommander.
Conduct tasks as mentioned in the attached word document file.
### The answer is attached in this repository as a file check it out

 



 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/eb6ed04f-8592-459c-ba97-fc3ad5adc42b)

TABLE OF CONTENTS <br>
1	Lab 1: Create a Linux Server – VM	2 <br>
2	Lab 2: Taking a snapshot	3<br>
3	Restoring a snapshot	3 <br>
4	Deleting a snapshot	3 <br>
5	Cloning a VM	3 <br>
6	Exporting Appliance in OVF	4 <br>
7	Removing Virtual Machines	4 <br>

 
1	LAB 1: CREATE A LINUX SERVER – VM

1.	Make sure that  VirtualBox installed in your machine. Or install Extension pack for better performance. 
 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/dfb1773f-1bad-40f0-bd6d-031cb96df838)


2.	First need to download the Server Install Image for Ubuntu 20.04.1 LTS (Focal Fossa). The image is available at this link: https://releases.ubuntu.com/20.04/ubuntu-20.04.1-live-server-amd64.iso 
3.	 Set up a virtual machine using the image that have been recently downloaded. The configuration of the virtual machine should be as below:
a.	The name of the virtual machine must be Firstname_lastname_ubuntuSer
b.	Base Memory (RAM) : 1024 MB
c.	Storage: Type: Normal (VDI), Virtual Size: 15 GB, Dynamically allocated differencing storage

 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/c876df75-7029-4492-9b6f-0689ff648123)

 

2	LAB 2: TAKING A SNAPSHOT 

Please take a snapshot of the recently installed Virtual Machine. 
 
![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/7eb93215-30dd-4e4e-b9cf-420e4d62826b)



3	RESTORING A SNAPSHOT
From the list of your snapshots, select the snapshot that you created and restore it. Please remember that when you restore a snapshot it will affect the virtual hard drive that is connected to your VM and the entire state of the virtual hard drive will be reverted as well. All files that were created after the snapshot will be lost. Please write the steps for restoring a snapshot.<br>
Answer:<br>  1.Click on the virtual machine <br>
         2.Select Snapshot <br>
         3.Click the specific snapshot to be restored <br>
         4.Click Restore from the upper menu.<br>
 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/bc8ed53e-a9cb-40c3-99d9-4d855ac9848a)

4	DELETING A SNAPSHOT
Please delete the snapshot that you created earlier and write the steps below for deleting it.<br> 
Answer:<br>  1.klick on the virtual machine <br>
               2.Select Snapshot <br>
               3. Klick the specific snapshot to be deleted <br>
               4.Klick Delete from the upper menu. <br>
N.B. Snapshot with child snapshots can’t be deleted .
 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/042a568e-6321-4341-86b7-0d36d0288e2e)


5	CLONING A VM
Create a clone of your existing VM and name it is Firsname_lastname_clone. Start the newly cloned virtual machine and submit the screenshot. 
 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/876ccbf6-7b40-44ad-b05a-59392d41d0bb)

6	EXPORTING APPLIANCE IN OVF
Export the VM you created earlier in the OVF format. Mention the steps for exporting appliance in OVF. <br>
Answer: <br>1.Click on File <br>
               2.Click Export Appliance <br>
               3.Select the virtual machine. <br>
               4. Click Export<br>

 ![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/f2032ba9-525d-4543-932c-705d8857bbd2)



7	REMOVING VIRTUAL MACHINES
You may now remove (if you don’t need them) all VMs including clones and the OVF file that you created in previous tasks. <br>
Answer:<br> 1.Right Click on the virtual machine <br>
               2.Select Remove <br>
               3.From the subsequent dialogue box Click Delete to remove both files and the VM.

![image](https://github.com/ephrinaw/VirtualBox/assets/39829776/8d569cad-cd73-4307-a7cd-c622fb240183)

 



