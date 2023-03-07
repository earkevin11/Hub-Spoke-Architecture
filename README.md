# Hub-Spoke-Architecture

# What is the purpose of the Hub-Spoke Architecture?
- Companies will use one central network that will act as a Hub. Companies will install the Azure Firewall Service instance within the Hub network
- Then there will be other virtual networks that will act as a Spoke network. 
- The traffic coming from Spoke networks will flow through the <em> Hub network </em>.
- Routing will be taken care by the route tables.
- Hub metworks will be connected to Spoke network via peering network service.
- On-Prem networks that need to contact azure virtual networks will also go through the Hub networks.


<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/171688005-e3f65c28-cc93-4a40-b71b-a1116e028151.png" height="180%" width="180%" alt="hubspoke"/>

<p/>

# Use Case: Set up a Hub-Spoke model where there is an on-prem network commmunicating with the spoke network via the central hub network.
- The central hub network must have a Azure Firewall Service.
