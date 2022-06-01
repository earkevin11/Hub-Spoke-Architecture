# Hub-Spoke-Architecture

# What is the purpose of the Hub-Spoke Architecture?
- Companies will use one central network that will act as a Hub. Companies will install the Azure Firewall Service instance.
- Then there will be other virtual networks that will act as a Spoke network. 
- The traffic coming from Spoke networks will flow through the <em> Hub network </em>.
- Routing will be taken care by the route tables.
- Networks will be connected via peering network service.
- On-Prem networks that need to contact azure virtual networks will also go through the Hub networks.
