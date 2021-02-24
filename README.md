To configuring the master node you have to write the ip in ansible inventory file of the target node and also give role path inside inventory file.
Clone the ansible role in a folder and write a yml code that apply the role on the target node.
For join the slave node you have to create a token using command < kubeadm token create --print-join-command >.
This is what you have to do in the master side.
