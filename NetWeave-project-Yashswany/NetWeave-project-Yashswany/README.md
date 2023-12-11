NetWeave

In this project, the network is configured with EIGRP as the routing protocol,
 utilizing Layer 3 switches as VTP servers.
 The VLAN structure is organized to allow specific communication between different VLANs.

VLAN 10 is isolated from other networks on the WAN, ensuring restricted communication.
 Meanwhile, VLANs 2, 3, 4, and 5 are configured to communicate freely with each other,
 fostering seamless connectivity within this group.

The Layer 3 switch in France serves as the DHCP server,
 allocating IP addresses to PCs in India, the USA, and France.
 Additionally, dynamic NAT is implemented on devices in Japan, utilizing a pool of addresses (192.168.3.30-40/24).
 Meanwhile, a static NAT configuration is applied to PC 24 in Canada (192.168.4.10), and PAT is implemented on PC 26 in India (pool: 192.168.1.10-10/24).

To enhance security, VLAN 10 PCs are restricted from communicating with other networks on the WAN.
 Furthermore, PC 22 in China is prohibited from communicating with PC 30 in the USA.

Server 1 is configured to communicate with networks on the WAN while maintaining a shield
 against external communication through the implementation of a fake IP address (10.0.10.5-10/27).
 This ensures that only designated traffic can access Server 1 from the wider network.

Finally, access controls are put in place to allow specific PCs to access the web on Server 1,
 creating a controlled and monitored web access environment within the network.

Overall, this project provides a robust and secure network configuration,
 incorporating various features such as VLAN segmentation, routing with EIGRP, NAT, 
and access controls to meet specific communication requirements and enhance network security.

![src](https://github.com/YashswanyPrakash/samavesasthalah/assets/152088752/d5df6741-512f-4ef3-bdad-383cbce8edb5)




## Installation
To install Cisco Packet Tracer on your desktop, follow these steps:

1. *Download Cisco Packet Tracer:*
   Visit the official Cisco Networking Academy website to download Packet Tracer.
 You may need to create a Cisco NetAcad account if you don't have one. The download link can be found on the Cisco Networking Academy website.

2. *Install Packet Tracer:*
   Once the download is complete, run the installer. Follow the on-screen instructions to install Packet Tracer on your desktop.

3. *Accept License Agreement:*
   During the installation process, you will be prompted to accept the license agreement. Read through the terms and conditions,
 and if you agree, proceed with the installation.

4. *Choose Installation Location:*
   Select the destination folder where you want to install Cisco Packet Tracer. You can choose the default location or specify a different one.

5. *Complete the Installation:*
   Allow the installer to complete the installation process. This may take a few minutes.

6. *Launch Packet Tracer:*
   Once the installation is finished, you can launch Cisco Packet Tracer. Look for the shortcut on your desktop or find it in your Start menu.

7. *Log in (if required):*
   Depending on your version and license, you might need to log in with your Cisco Networking Academy credentials. Follow any on-screen prompts for this step.

8. *Start Using Packet Tracer:*
   After successful installation and login, you can start using Cisco Packet Tracer to simulate and experiment with network configurations.

Remember to always download software from official sources to ensure security and reliability. If you encounter any issues during the installation,
 refer to the documentation or support resources provided by Cisco.


you can download the cisco packet tracers from this link "https://drive.google.com/file/d/0B4wyEULZuLd2Mlo4Q2RHUkl0V00/view?usp=sharing&resourcekey=0-wOmFVTvWpGiv5EvzlDN35Q"


## Usage
- 1. download this rapository.
- 2. open file NetWeave-project-yashswany.pkt with cisco packet tracer.

## License
- This project is licensed under the MIT License. 

## Contributing
Thank you for considering contributing to this project! Here are the basic steps:
1. **Fork** the repository.
2. Create a new branch (`git checkout -b feature/issue-name`).
3. Make your changes and **commit** them (`git commit -am 'Add new feature'`).
4. **Push** to the branch (`git push origin feature/issue-name`).
5. Create a new **Pull Request**.

## Contact
- Email: [amar301275@gmail.com](mailto:amar301275@gmail.com) | LinkedIn: [Yashswany Prakash](https://www.linkedin.com/in/yashswany-prakash-9827a42a1/)
