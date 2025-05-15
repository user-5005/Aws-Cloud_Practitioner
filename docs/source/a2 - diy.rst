DIY
=========

.. info::

   After completing the lab, the player does **DIY**.


1. Select DIY to make


2. In the **Plan** interface

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Select **Open AWS Console**


3. In **AWS Console**, find and select **EC2**


4. Select **Launch instance**


5. In Choose an **Amazon Machine Image (AMI)**

- Select **Amazon Linux 2 AMI (HVM) - Kernel 5.10, SSD Volume Type**
- Select **Select**


6. In **Choose an Instance Type**

- Select **t2.micro**
- Then select **Next: Configure Instance Details**


7. In **Configure Instance Details**

- Select **VPC**
- Choose **Subnet** different from the subnet of **Practice**


8. In **Advanced Details**

- Select **As file**
- Select **Select file** and download the file **user-data**
- Select **Next: Add Storage**


9. In **Add Storage**, select **Next: Add Tags**


10. In **Add Tags**, select **Next: Configure Security Group**

11. In **Configure Security Group**, create a security group

- Security group name, enter 
.. raw:: html

   <span style="background-color:#fff4c2; font-family:monospace;">
     <span id="copy-text" style="user-select: all;">Security-Group-Lab-2</span>
     <button onclick="navigator.clipboard.writeText(document.getElementById('copy-text').innerText)" style="border:none; background:none; cursor:pointer;">📋</button>
   </span>
Description, enter HTTP Group Lab 2
Rule, select HTTP
Select Review and Launch
DIY

In Review Instance Launch, double check and select Launch
DIY

In Select an existing key pair or create a new key pair
Select Proceed without a key pair
Select I acknowledge…
Select Launch Instances
DIY

Select View Instances
DIY

Result of creating 2 Amazon EC2 Instance
DIY

After creating 2 Amazon EC2 Instance, copy both Instance ID
Paste in Instance ID in AZ1
Paste in Instance ID in AZ2
Select VALIDATE
DIY

After selecting VALIDATE, if VALIDATION MESSAGE contains Success! … is complete
DIY

Select EXIT
DIY

In ASSIGNMENT select COLLECT
DIY

Select NEXT
DIY

Select COLLECT
DIY

Get rewarded
