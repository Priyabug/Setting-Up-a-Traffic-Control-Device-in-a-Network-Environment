<h1>Implementation and setting up a single firewall on a network</h1>



<h2>Description</h2>
The learning objective of this lab is two-fold: learning how firewalls work, and setting up a simple firewall
for a network. Students will first implement a simple stateless packet-filtering firewall, which inspects packets, and decides whether to drop or forward a packet based on firewall rules. Through this implementation
task, students can get the basic ideas on how firewall works.
Actually, Linux already has a built-in firewall, also based on netfilter. This firewall is called
iptables. Students will be given a simple network topology, and are asked to use iptables to set up
firewall rules to protect the network. In this project we will also see the interesting applications
of iptables. This project covers the following topics:
 <ul>
        <li>Firewall</li>
        <li>Netfilter</li>
        <li>Loadable Kernel Module</li>
        <li>Using Iptables to set up firewall rules</li>
        <li>Various applications of IPtables</li>
  
  </ul>


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ununtu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

- <b>Task 1: Implementing a Simple Firewall</b>
- <b>Task 1.A: Implement a Simple Kernel Module</b>
- <b>Task 1.B: Implement a Simple Firewall Using Netfilter</b>
- <b>Task 2: Experimenting with Stateless Firewall Rules</b>
- <b>Task 2.A: Protecting the Router</b>
- <b>Task 2.B: Protecting the Internal Network</b>
- <b>Task 2.C: Protecting Internal Servers</b>
- <b>Task 3.A: Experiment with the Connection Tracking</b>


