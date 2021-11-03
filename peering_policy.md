---

copyright:
  years: 2020, 2021
lastupdated: "2021-01-21"

keywords: public peering

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Public peering 
{: #public-peering}

Public peering is conducted across a shared network. Peering requests can be accepted when a mutually agreeable decision to peer based on operational needs exists. 
{: shortdesc}


## Guidelines and general information
{: #guide-gen-info}

The following are guidelines and some general information for public peering with {{site.data.keyword.Bluemix}}. 

- Potential and current peers must have and maintain a valid [PeeringDB.com](https://www.peeringdb.com/){: external} record.
- Use of the [Internet Routing Registry (IRR)](http://www.irr.net/){: external} is required for prefix filtering.
- Peers must supply a contact with 24x7 availability, such as a Network Operations Center.
- Peers must not use any form of gateway of last resort or default route that is directed at {{site.data.keyword.Bluemix_notm}}.
- Peers must provide access to a looking glass or traceroute server to facilitate troubleshooting.
- Peer announcements must be consistent across all Interconnect locations.
- {{site.data.keyword.Bluemix_notm}} sends and accepts MED attributes by request only.

{{site.data.keyword.Bluemix_notm}} reserves the right to suspend peering for an indefinite period if any form of network abuse is detected and verified to be taking place via the peering interconnect. This suspension includes setting a default route to {{site.data.keyword.Bluemix_notm}}. {{site.data.keyword.Bluemix_notm}} doesn't accept any IPv4 announcements smaller than /24 or IPv6 announcements smaller than /48. An MD5 password is preferred but not required.

For more information, see the [PeeringDB record](https://www.peeringdb.com/asn/36351){: external}.

If {{site.data.keyword.Bluemix_notm}}'s operational needs cause a peering arrangement to conflict with the best interest of {{site.data.keyword.Bluemix_notm}}, {{site.data.keyword.Bluemix_notm}} reserves the right to end the peering agreement with reasonable advance notice.
{: note}

## Public peer exchanges
{: #peer-exchanges}

The following table shows the current public peer exchanges.

| Country                       | City            | State or Province  | Exchange          |
|-------------------------------|-----------------|--------------------|-------------------|
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong          | Equinix Hong Kong |
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong          | HKIX              |
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong          | BBIX Hong Kong    |
| Japan                        | Osaka           | Japan             | BBIX Osaka       |
| Japan                         | Osaka           | Japan             | JPIX Osaka       |
| Japan                         | Osaka           | Japan             | JPNAP Osaka       |
| Japan                         | Tokyo           | Japan              | BBIX Tokyo        |
| Japan                         | Tokyo           | Japan              | Equinix Tokyo     |
| Japan                         | Tokyo           | Japan             | JPNAP Tokyo       |
| South Korea                   | Seoul           | Gyeonggi-do        | KINX              |
| Singapore                     | Singapore       | Singapore          | BBIX Singapore    |
| Singapore                     | Singapore       | Singapore          | Equinix Singapore |
{: class="simple-tab-table"}
{: caption="Table 1. Public peer exchanges for Asia Pacific" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #AP}
{: tab-title="Asian Pacific"}

| Country     | City      | State or Province  | Exchange         |
|-------------|-----------|--------------------|------------------|
| Germany    | Frankfurt | Hesse             | DE-CIX           |
| Germany    | Frankfurt | Hesse              | NIX.CZ           |
| England    | London   | England            | LINX Juniper LAN |
| England    | London   | England            | LINX Extreme LAN |
| France    | Paris    | Île-de-France     | Equinix Paris    |
| Italy      | Milan    | Italy             | MIX-IT           |
| Netherlands | Amsterdam | North Holland      | AMS-IX           |
| Netherlands | Amsterdam | North Holland      | NL-IX            |
| Sweden    | Stockholm | Uppland           | Netnod STH-A     |
| Sweden    | Stockholm | Uppland           | Netnod STH-B     |
{: class="simple-tab-table"}
{: caption="Table 1. Public peer exchanges for Europe" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #EU}
{: tab-title="Europe"}

| Country       | City        | State or Province | Exchange            |
|---------------|-------------|-------------------|---------------------|
| Canada       | Toronto     | Ontario          | TorIX               |
| United States | Denver     | Colorado        | ANY2 Denver         |
| United States | Denver     | Colorado        | IX Denver           |
| United States | Miami      | Florida          | FL-IX               |
| United States | Miami      | Florida          | Equinix Miami       |
| United States | Boston    | Massachusetts     | MASS-IX             |
| United States | New York  | New York        | DE-CIX NYC          | 
| United States | New York  | New York        | TIE NYC             |
| United States | New York  | New York        | NYIIX               |
| United States | Seattle    | Washington      | SIX                 |
| United States | Los Angeles | California      | ANY2 Los Angeles    | 
| United States | Los Angeles | California      | Equinix Los Angeles |
| United States | Palo Alto  | California       | Equinix Palo Alto   |
| United States | San Jose  | California      | Equinix San Jose    |
| United States | Atlanta    | Georgia          | TIE-ATL             |
| United States | Chicago    | Illinois        | Equinix Chicago     |
| United States | Dallas    | Texas            | Equinix Dallas      |
| United States | Dallas    | Texas            | DE-CIX DAL          |
| United States | Ashburn    | Virginia        | Equinix Ashburn     |
| United States | Ashburn    | Virginia        | LINX NoVa           |
{: class="simple-tab-table"}
{: caption="Table 1. Public peer exchanges for North America" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #NA}
{: tab-title="North America"}

| Country   | City      | State or Province      | Exchange                     |
|-----------|-----------|------------------------|------------------------------|
| Australia | Melbourne | Victoria               | Equinix Melbourne            |
| Australia | Melbourne | Victori               | IX Australia Victoria        |
| Australia | Melbourne | Victoria              | MegaIX Melbourne             |
| Australia | Melbourne | Victoria              | PIPE MEL                     |
| Australia | Sydney  | New South Wales        | Equinix Sydney               |
| Australia | Sydney  | New South Wales        | IX Australia New South Wales |
| Australia | Sydney  | New South Wales        | MegaIX Sydney                |
| Australia | Sydney  | New South Wales        | PIPE SYD                     |
{: class="simple-tab-table"}
{: caption="Table 1. Public peer exchanges for Oceania" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #OC}
{: tab-title="Oceania"}

| Country | City      | State or Province | Exchange |
|---------|-----------|-------------------|----------|
| Brazil | São Paulo | São Paulo         | PTT-SP   |
{: class="simple-tab-table"}
{: caption="Table 1. Public peer exchanges for South America" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #SA}
{: tab-title="South America"}
