# User Guide

-   [Product Introduction](product-introduction.md)
    -   [What Is Virtual Private Cloud?](what-is-virtual-private-cloud.md)
    -   [Product Advantages](product-advantages.md)
    -   [Application Scenarios](application-scenarios.md)
    -   [Accessing the Internet](accessing-the-internet.md)
    -   [Related Services](related-services.md)
    -   [User Permissions](user-permissions.md)
    -   [Basic Concepts](basic-concepts.md)
        -   [Subnet](subnet.md)
        -   [Elastic IP Address](elastic-ip-address.md)
        -   [Route Table](route-table.md)
        -   [SNAT](snat.md)
        -   [Security Group](security-group.md)
        -   [VPN](vpn.md)
        -   [IPsec VPN](ipsec-vpn.md)
        -   [Remote Gateway](remote-gateway.md)
        -   [Remote Subnet](remote-subnet.md)
        -   [Shared SNAT](shared-snat.md)
        -   [VPC Peering Connection](vpc-peering-connection.md)
        -   [Firewall](firewall.md)
        -   [Virtual IP Address](virtual-ip-address.md)
        -   [Region](region.md)
        -   [Project](project.md)

-   [Getting Started](getting-started.md)
    -   [Typical Application Scenarios](typical-application-scenarios.md)
    -   [Configuring the VPC of ECSs That Do Not Need to Access the Internet](configuring-the-vpc-of-ecss-that-do-not-need-to-access-the-internet.md)
        -   [Overview](overview.md)
        -   [Creating a VPC](creating-a-vpc.md)
        -   [Creating a Subnet for the VPC](creating-a-subnet-for-the-vpc.md)
        -   [Creating a Security Group](creating-a-security-group.md)
        -   [Adding a Security Group Rule](adding-a-security-group-rule.md)
    -   [Configuring the VPC of ECSs That Access the Internet Using EIPs](configuring-the-vpc-of-ecss-that-access-the-internet-using-eips.md)
        -   [Overview](overview-0.md)
        -   [Creating a VPC](creating-a-vpc-1.md)
        -   [Creating a Subnet for the VPC](creating-a-subnet-for-the-vpc-2.md)
        -   [Assigning an EIP and Binding It to an ECS](assigning-an-eip-and-binding-it-to-an-ecs.md)
        -   [Creating a Security Group](creating-a-security-group-3.md)
        -   [Adding a Security Group Rule](adding-a-security-group-rule-4.md)
    -   [Configuring the VPC of ECSs That Access the Internet Through a VPN](configuring-the-vpc-of-ecss-that-access-the-internet-through-a-vpn.md)
        -   [Overview](overview-5.md)
        -   [Creating a VPC](creating-a-vpc-6.md)
        -   [Creating a Subnet for the VPC](creating-a-subnet-for-the-vpc-7.md)
        -   [Creating a VPN](creating-a-vpn.md)
        -   [Creating a Security Group](creating-a-security-group-8.md)
        -   [Adding a Security Group Rule](adding-a-security-group-rule-9.md)

-   [VPC and Subnet](vpc-and-subnet.md)
    -   [Creating a VPC](creating-a-vpc-10.md)
    -   [Modifying a VPC](modifying-a-vpc.md)
    -   [Creating a Subnet for the VPC](creating-a-subnet-for-the-vpc-11.md)
    -   [Modifying a Subnet](modifying-a-subnet.md)
    -   [Deleting a VPC](deleting-a-vpc.md)
        -   [Deleting a VPN](deleting-a-vpn.md)
        -   [Deleting a Subnet](deleting-a-subnet.md)
        -   [Deleting a VPC](deleting-a-vpc-12.md)
    -   [Managing VPC Tags](managing-vpc-tags.md)
    -   [Managing Subnet Tags](managing-subnet-tags.md)
    -   [Exporting VPC Information](exporting-vpc-information.md)
-   [Security](security.md)
    -   [Overview](overview-13.md)
    -   [Security Group](security-group-14.md)
        -   [Security Group Overview](security-group-overview.md)
        -   [Default Security Groups and Security Group Rules](default-security-groups-and-security-group-rules.md)
        -   [Creating a Security Group](creating-a-security-group-15.md)
        -   [Adding a Security Group Rule](adding-a-security-group-rule-16.md)
        -   [Fast-Adding Security Group Rules](fast-adding-security-group-rules.md)
        -   [Replicating a Security Group Rule](replicating-a-security-group-rule.md)
        -   [Modifying a Security Group Rule](modifying-a-security-group-rule.md)
        -   [Deleting a Security Group Rule](deleting-a-security-group-rule.md)
        -   [Deleting a Security Group](deleting-a-security-group.md)
        -   [Viewing the Security Group of an ECS](viewing-the-security-group-of-an-ecs.md)
        -   [Changing the Security Group of an ECS](changing-the-security-group-of-an-ecs.md)
    -   [Security Group Configuration Example](security-group-configuration-example.md)
        -   [Enabling ECSs in Different Security Groups to Communicate with Each Other Through an Internal Network](enabling-ecss-in-different-security-groups-to-communicate-with-each-other-through-an-internal-networ.md)
        -   [Enabling Specified IP Addresses to Remotely Access ECSs in a Security Group](enabling-specified-ip-addresses-to-remotely-access-ecss-in-a-security-group.md)
        -   [Remotely Connecting to Linux ECSs Using SSH](remotely-connecting-to-linux-ecss-using-ssh.md)
        -   [Remotely Connecting to Windows ECSs Using RDP](remotely-connecting-to-windows-ecss-using-rdp.md)
        -   [Enabling Communication Between ECSs](enabling-communication-between-ecss.md)
        -   [Hosting a Website on ECSs](hosting-a-website-on-ecss.md)
        -   [Enabling an ECS to Function as a DNS Server](enabling-an-ecs-to-function-as-a-dns-server.md)
        -   [Uploading or Downloading Files using FTP](uploading-or-downloading-files-using-ftp.md)
    -   [Firewall](firewall-17.md)
        -   [Creating a Firewall](creating-a-firewall.md)
        -   [Enabling or Disabling a Firewall](enabling-or-disabling-a-firewall.md)
        -   [Associating Subnets with a Firewall](associating-subnets-with-a-firewall.md)
        -   [Adding a Firewall Rule](adding-a-firewall-rule.md)
        -   [Enabling or Disabling a Firewall Rule](enabling-or-disabling-a-firewall-rule.md)
        -   [Modifying a Firewall Rule](modifying-a-firewall-rule.md)
        -   [Changing the Sequence of a Firewall Rule](changing-the-sequence-of-a-firewall-rule.md)
        -   [Deleting a Firewall Rule](deleting-a-firewall-rule.md)
        -   [Viewing a Firewall](viewing-a-firewall.md)
        -   [Modifying a Firewall](modifying-a-firewall.md)
        -   [Deleting a Firewall](deleting-a-firewall.md)
        -   [Disassociating a Subnet from a Firewall](disassociating-a-subnet-from-a-firewall.md)

-   [Elastic IP Address](elastic-ip-address-18.md)
    -   [Assigning an EIP and Binding It to an ECS](assigning-an-eip-and-binding-it-to-an-ecs-19.md)
    -   [Unbinding an EIP from an ECS and Releasing the EIP](unbinding-an-eip-from-an-ecs-and-releasing-the-eip.md)
    -   [Managing EIP Tags](managing-eip-tags.md)
-   [Custom Route](custom-route.md)
    -   [Configuring an SNAT Server](configuring-an-snat-server.md)
    -   [Adding a Route](adding-a-route.md)
    -   [Querying a Route](querying-a-route.md)
    -   [Modifying a Route](modifying-a-route.md)
    -   [Deleting a Route](deleting-a-route.md)
-   [VPC Peering Connection](vpc-peering-connection-20.md)
    -   [VPC Peering Connection Creation Procedure](vpc-peering-connection-creation-procedure.md)
    -   [VPC Peering Connection Configuration Plans](vpc-peering-connection-configuration-plans.md)
    -   [Creating a VPC Peering Connection with Another VPC of Your Own](creating-a-vpc-peering-connection-with-another-vpc-of-your-own.md)
    -   [Creating a VPC Peering Connection with a VPC of Another Tenant](creating-a-vpc-peering-connection-with-a-vpc-of-another-tenant.md)
    -   [Viewing VPC Peering Connections](viewing-vpc-peering-connections.md)
    -   [Modifying a VPC Peering Connection](modifying-a-vpc-peering-connection.md)
    -   [Deleting a VPC Peering Connection](deleting-a-vpc-peering-connection.md)
    -   [Viewing Routes Configured for a VPC Peering Connection on the Peering Connection Details Page](viewing-routes-configured-for-a-vpc-peering-connection-on-the-peering-connection-details-page.md)
    -   [Viewing Routes Configured for a VPC Peering Connection in the VPC Peering Route Table](viewing-routes-configured-for-a-vpc-peering-connection-in-the-vpc-peering-route-table.md)
    -   [Deleting a Route on the VPC Peering Connection Details Page](deleting-a-route-on-the-vpc-peering-connection-details-page.md)
    -   [Deleting a Route from the VPC Peering Route Table](deleting-a-route-from-the-vpc-peering-route-table.md)
-   [Virtual IP Address](virtual-ip-address-21.md)
    -   [Overview](overview-22.md)
    -   [Assigning a Virtual IP Address](assigning-a-virtual-ip-address.md)
    -   [Binding a Virtual IP Address with an EIP or ECS](binding-a-virtual-ip-address-with-an-eip-or-ecs.md)
    -   [Accessing a Virtual IP Address using an EIP](accessing-a-virtual-ip-address-using-an-eip.md)
    -   [Using a VPN to Access the Virtual IP Address](using-a-vpn-to-access-the-virtual-ip-address.md)
    -   [Using a Direct Connect Connection to Access the Virtual IP Address](using-a-direct-connect-connection-to-access-the-virtual-ip-address.md)
    -   [Using a VPC Peering Connection to Access the Virtual IP Address](using-a-vpc-peering-connection-to-access-the-virtual-ip-address.md)
    -   [Disabling Source and Destination Check \(HA Load Balancing Cluster Scenario\)](disabling-source-and-destination-check-(ha-load-balancing-cluster-scenario).md)
    -   [Releasing a Virtual IP Address](releasing-a-virtual-ip-address.md)
-   [Monitoring](monitoring.md)
    -   [Supported Metrics](supported-metrics.md)
    -   [Viewing Metrics](viewing-metrics.md)
    -   [Creating an Alarm Rule](creating-an-alarm-rule.md)
-   [FAQs](faqs.md)
    -   [General](general.md)
        -   [What Is a Resource Quota?](what-is-a-resource-quota.md)
    -   [VPC and Subnet](vpc-and-subnet-23.md)
        -   [What Is Virtual Private Cloud?](what-is-virtual-private-cloud-24.md)
        -   [Which CIDR Blocks Are Available to the VPC Service?](which-cidr-blocks-are-available-to-the-vpc-service.md)
        -   [Can Subnets Communicate with Each Other?](can-subnets-communicate-with-each-other.md)
        -   [What Subnet CIDR Blocks Are Available?](what-subnet-cidr-blocks-are-available.md)
        -   [How Many Subnets Can I Create?](how-many-subnets-can-i-create.md)
        -   [What Can I Do If a Subnet Cannot Be Deleted Because It Is Used by Other Resources?](what-can-i-do-if-a-subnet-cannot-be-deleted-because-it-is-used-by-other-resources.md)
        -   [What Are the Differences Between the Network ID and Subnet ID of a Subnet?](what-are-the-differences-between-the-network-id-and-subnet-id-of-a-subnet.md)
    -   [EIP](eip.md)
        -   [What Are EIPs?](what-are-eips.md)
        -   [How Many ECSs Can One EIP Be Assigned to?](how-many-ecss-can-one-eip-be-assigned-to.md)
        -   [How Can I Access an ECS from Another Security Group After an EIP Is Bound to the ECS?](how-can-i-access-an-ecs-from-another-security-group-after-an-eip-is-bound-to-the-ecs.md)
    -   [Bandwidth](bandwidth.md)
        -   [What Is the Bandwidth Size Range?](what-is-the-bandwidth-size-range.md)
    -   [Connectivity](connectivity.md)
        -   [How Do I Configure a Remote Device for a VPN?](how-do-i-configure-a-remote-device-for-a-vpn.md)
        -   [Which Remote VPN Devices Are Supported?](which-remote-vpn-devices-are-supported.md)
        -   [What Are the Reference Standards and Protocols for the IPsec VPN?](what-are-the-reference-standards-and-protocols-for-the-ipsec-vpn.md)
        -   [What Do I Do If VPN Connection Setup Fails?](what-do-i-do-if-vpn-connection-setup-fails.md)
        -   [What Do I Do If I Cannot Access the ECSs from My Data Center or LAN After a VPN Connection Has Been Set Up?](what-do-i-do-if-i-cannot-access-the-ecss-from-my-data-center-or-lan-after-a-vpn-connection-has-been.md)
        -   [What Do I Do If I Cannot Access My Data Center or LAN from the ECSs After a VPN Connection Has Been Set Up?](what-do-i-do-if-i-cannot-access-my-data-center-or-lan-from-the-ecss-after-a-vpn-connection-has-been.md)
        -   [Does a VPN Allow for Communication Between Two VPCs?](does-a-vpn-allow-for-communication-between-two-vpcs.md)
        -   [Why Cannot I Access Public Websites Through Domain Names or Access Internal Domain Names in the Cloud When My ECS Has Multiple NICs?](why-cannot-i-access-public-websites-through-domain-names-or-access-internal-domain-names-in-the-clou.md)
        -   [What Are the Limitations of VPC Peering?](what-are-the-limitations-of-vpc-peering.md)
        -   [What Can I Do If VPCs in a VPC Peering Connection Cannot Communicate with Each Other?](what-can-i-do-if-vpcs-in-a-vpc-peering-connection-cannot-communicate-with-each-other.md)
        -   [How Many VPC Peering Connections Can I Have?](how-many-vpc-peering-connections-can-i-have.md)
        -   [What Are the Priorities of the Custom Route and EIP If Both Are Configured for an ECS to Enable the ECS to Access the Internet?](what-are-the-priorities-of-the-custom-route-and-eip-if-both-are-configured-for-an-ecs-to-enable-the.md)
        -   [What Are the Priorities of the Shared SNAT and Custom Route if Both Are Configured for an ECS to Enable the ECS to Access the Internet?](what-are-the-priorities-of-the-shared-snat-and-custom-route-if-both-are-configured-for-an-ecs-to-ena.md)
        -   [How Does an IPv6 Client on the Internet Access the ECS That Has an EIP Bound in a VPC?](how-does-an-ipv6-client-on-the-internet-access-the-ecs-that-has-an-eip-bound-in-a-vpc.md)
    -   [Routing](routing.md)
        -   [What Is a Route Table?](what-is-a-route-table.md)
        -   [Can a Route Table Span Multiple VPCs?](can-a-route-table-span-multiple-vpcs.md)
        -   [How Many Routes Can Be Contained in a Route Table?](how-many-routes-can-be-contained-in-a-route-table.md)
        -   [What Are the Limitations of a Route Table?](what-are-the-limitations-of-a-route-table.md)
        -   [Does a Route Table Incur Any Charges?](does-a-route-table-incur-any-charges.md)
        -   [Do the Direct Connect Connections and Custom Routes in the Same VPC Have Routing Priority Competition?](do-the-direct-connect-connections-and-custom-routes-in-the-same-vpc-have-routing-priority-competitio.md)
        -   [What Are the Routing Priorities of the VPN and Custom Routes in the Same VPC?](what-are-the-routing-priorities-of-the-vpn-and-custom-routes-in-the-same-vpc.md)
        -   [How Many Routes Can Be Added for a VPC?](how-many-routes-can-be-added-for-a-vpc.md)
    -   [Security](security-25.md)
        -   [What Is a Security Group?](what-is-a-security-group.md)
        -   [Which Protocols Does a Security Group Support?](which-protocols-does-a-security-group-support.md)
        -   [What Are the Functions of the Default Security Group Rule?](what-are-the-functions-of-the-default-security-group-rule.md)
        -   [How Can I Configure Security Group Rules?](how-can-i-configure-security-group-rules.md)
        -   [Can I Change the Security Group to Which an ECS Belongs?](can-i-change-the-security-group-to-which-an-ecs-belongs.md)
        -   [How Many Security Groups Can Each User Have?](how-many-security-groups-can-each-user-have.md)
        -   [How Can I Configure a Security Group for Multi-Channel Protocols?](how-can-i-configure-a-security-group-for-multi-channel-protocols.md)
        -   [How Many Firewalls Can a User Have?](how-many-firewalls-can-a-user-have.md)
        -   [Does a Security Group rule or Firewall Rule Immediately Take Effect for Its Original Traffic After Being Modified?](does-a-security-group-rule-or-firewall-rule-immediately-take-effect-for-its-original-traffic-after-b.md)
        -   [Which Security Group Rule Has Priority When Multiple Security Group Rules Conflict?](which-security-group-rule-has-priority-when-multiple-security-group-rules-conflict.md)

-   [Glossary](glossary.md)

