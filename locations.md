---

copyright:
  years: 2019, 2021
lastupdated: "2021-09-13"

keywords: data centers, regions, locations, network, ibm cloud regions, multizone regions, MZRs, latency, HA, high availability, endpoints, cloud regions, cloud data centers, multizone, resources, geography, global, geo, load balance, availability zone, zones, north america, south america, europe, asia, DC, tiers, globally resilient, resilient

subcollection: overview

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:note: .note}
{:term: .term}
{:external: target="_blank" .external}

# Locations for resource deployment
{: #locations}

{{site.data.keyword.cloud}} has a resilient global network of locations to host your highly available cloud workload. You can create resources in different locations but with the same billing and usage view. You can also deploy your apps to the location that is nearest to your customers to achieve low application latency.
{: shortdesc}

{{site.data.keyword.cloud_notm}} provides three tiers of regions: [multizone regions](#x9774820){: term} (MZR), [single-zone regions](#x9774825){: term} (SZR), and [data centers](#x2439906){: term}. For more details, see the following sections.

## Multizone regions
{: #mzr-table}

MZRs are composed of three or more zones that are independent from each other to ensure that single failure events affect only a single zone. MZRs provide low latency (< 2-milliseconds latency) and high bandwidth (> 1000 Gbps) connectivity across zones. Any [GA](#x2117947){: term} service in an MZR is available in all MZRs within 90 days. 

The advantage of an MZR is that it provides consistent cloud services across different zones, better resiliency, availability, higher interconnect speed between data centers for your resources. These features can be critical to your applications. Deploying the application in an MZR rather than an SZR can increase the availability from 99.9% to 99.99% when deployed over three zones. 

The following table lists the {{site.data.keyword.cloud_notm}} MZRs and the region, zone, and data center codes for each one. 

| Location | Region | Zone | Data center |
|-----------|----------|------|----|
| Dallas | us-south | us-south-1<br>us-south-2<br>us-south-3 | DAL10<br>DAL12<br>DAL13 |
| Sao Paulo | br-sao | br-sao-1<br>br-sao-2<br>br-sao-3 | SAO01<br>SAO04<br>SAO05 |
| Toronto | ca-tor | ca-tor-1<br>ca-tor-2<br>ca-tor-3 | TOR01<br>TOR04<br>TOR05 |
| Washington DC | us-east | us-east-1<br>us-east-2<br>us-east-3 | WDC04<br>WDC06<br>WDC07 |
{: caption="Table 1. MZRs in North and South America" caption-side="top"}
{: #americas-mzr}
{: tab-title="Americas"}
{: tab-group="mzr"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Location      | Region   | Zone | Data center |
|-----------|----------|------|----|
| Frankfurt     | eu-de    |eu-de-1<br>eu-de-2<br>eu-de-3 | FRA02<br>FRA04<br>FRA05 |
| London        | eu-gb    |eu-gb-1<br>eu-gb-2<br>eu-gb-3 | LON04<br>LON05<br>LON06|
{: caption="Table 1. MZRs in Europe" caption-side="top"}
{: #europe-mzr}
{: tab-title="Europe"}
{: tab-group="mzr"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Location      | Region   | Zone | Data center |
|-----------|----------|------|----|
| Osaka         | jp-osa   |jp-osa-1<br>jp-osa-2<br>jp-osa-3 | OSA21<br>OSA22<br>OSA23|
| Sydney        | au-syd   |au-syd-1<br>au-syd-2<br>au-syd-3 | SYD01<br>SYD04<br>SYD05|
| Tokyo         | jp-tok   |jp-tok-1<br>jp-tok-2<br>jp-tok-3 | TOK02<br>TOK04<br>TOK05|
{: caption="Table 1. MZRs in Asia Pacific" caption-side="top"}
{: #asiapacific-mzr}
{: tab-title="Asia Pacific"}
{: tab-group="mzr"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

Osaka is a single-site MZR. In a single-site MZR, the three data centers that support the three zones are running in the same building. The underlying infrastructure in the Osaka MZR zone has the same SLA as other individual zones in a multi-site MZR. Osaka MZR resiliency to failures in local city and location infrastructures is reduced because of being located in a single building. 
{: note}

## Single-zone regions
{: #szr-table}

You can also choose to deploy resources to an SZR, but you can't spread them across zones. The following table lists the SZRs that are available in {{site.data.keyword.cloud_notm}} and the region, zone, and data center codes for each one.

| Location      | Region   | Zone | Data center |
|-----------|----------|------|----|
| Seoul     | kr-seo | kr-seo-1 | SEO01 |
| Chennai | in-che  |in-che-1  | CHE01 |
{: caption="Table 2. SZRs for creating resources" caption-side="top"}

## Data centers
{: #data-centers}

In addition to selecting a region for your resource, you can select from a list of the {{site.data.keyword.Bluemix_notm}} data centers, depending on the type of resource you're working with. For example, you get this option with all classic infrastructure services. Data centers host the power, cooling, compute, network, and storage resources used for services and apps. They don't provide isolation from multizones in a location. 

Data centers are based on a POD architecture where each data center can have more than one POD, depending on on-demand buildout. Each POD consists of racks, servers, networks, and storage, along with backup power generators. Placing application servers across PODs further improves the availability.

See [Global locations for your global business](https://www.ibm.com/cloud/data-centers/){: external} for an interactive map that shows the available data centers, MZRs, [points of presence](#x5458832){: term} (PoPs), and federal data centers. 

See the following table for the specific code for each data center.

| Data center      | Code  |
|------------------|-------|
| Dallas 05        | DAL05 |
| Dallas 06        | DAL06 |
| Dallas 08 [^1]    | DAL08 |
| Dallas 09        | DAL09 |
| Dallas 10        | DAL10 |
| Dallas 12        | DAL12 |
| Dallas 13        | DAL13 |
| Mexico 01        | MEX01 |
| Montreal 01      | MON01 |
| San Jose 01      | SJC01 |
| San Jose 03      | SJC03 |
| San Jose 04      | SJC04 |
| Sao Paulo 01     | SAO01 |
| Sao Paulo 04     | SAO04 |
| Sao Paulo 05     | SAO05 |
| Toronto 01       | TOR01 |
| Toronto 04       | TOR04 |
| Toronto 05       | TOR05 |
| Washington DC 01 | WDC01 |
| Washington DC 03 [^2] | WDC03 |
| Washington DC 04 | WDC04 |
| Washington DC 06 | WDC06 |
| Washington DC 07 | WDC07 |
{: caption="Table 3. Data centers in North and South America" caption-side="top"}
{: #americas}
{: tab-title="Americas"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

[^1]: IBM Cloud for Government [Learn more](https://www.ibm.com/cloud/federal)

[^2]: IBM Cloud for Government [Learn more](https://www.ibm.com/cloud/federal)

| Data center  | Code  |
|--------------|-------|
|Amsterdam 01 | AMS01|
|Amsterdam 03 | AMS03|
|Frankfurt 02 | FRA02|
|Frankfurt 04 | FRA04|
|Frankfurt 05 | FRA05|
|London 02 | LON02|
|London 04 | LON04|
|London 05 | LON05|
|London 06 | LON06|
|Milan 01 | MIL01|
|Paris 01 | PAR01|
{: caption="Table 3. Data centers in Europe" caption-side="top"}
{: #europe}
{: tab-title="Europe"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

| Data center  | Code  |
|--------------|-------|
|Chennai 01 | CHE01|
|Hong Kong 02 | HKG02|
|Osaka 21 | OSA21|
|Osaka 22 | OSA22|
|Osaka 23 | OSA23|
|Seoul 01 | SEO01|
|Singapore 01 | SNG01|
|Sydney 01 | SYD01|
|Sydney 04 | SYD04|
|Sydney 05 | SYD05|
|Tokyo 02 | TOK02|
|Tokyo 04 | TOK04|
|Tokyo 05 | TOK05|
{: caption="Table 4. Data centers in Asia Pacific" caption-side="top"}
{: #asiapacific}
{: tab-title="Asia Pacific"}
{: tab-group="dcs"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the data centers located in the specific geographical area."}

The table includes certain data centers that are set to close soon. For the list of data centers that are closing, see [Data center closures in 2021](/docs/get-support?topic=get-support-dc-closure).
{: note}

## Viewing resources by location
{: #filter-location}

You can view all resources and locations from the Resource list page in the console. If you want to view and work with resources in a specific location, expand the **Location** filter, and select a location from the list. By expanding a specific location, you can select to filter by individual data centers, regions, or zones.

Depending on the type of resource, you might be interested in only specific types of location data. For example, if you created a service or VPC infrastructure service, you can filter the Resource list page by the region and zone codes. However, if you're working with classic infrastructure resources, the specific data center codes are the pertinent information for you.

For example, if you have resources that are deployed in the London 2 (eu-gb-2) zone, you can set filters to display only those resources in your resource list. Expand the **London** metro option, and the **London (eu-gb)** region option. Within that region, you can select from the list of available zones, such as **London 2 (eu-gb-2)**. If you have a classic infrastructure resource that is deployed in a specific data center, you can identify the data center by the specific metro location and alphanumeric code. For example, use **Dallas** for the metro location and then **Dallas 05 (dal05)** for the data center.

You might also want to display your resources that are located globally. The **Global** option means that only one logical, globally accessible instance of the service, independent of any region or zone, is published to customer applications. These types of resources are accessible from a global endpoint.

As illustrated in the following graphic, a data center is a physical building that represents an availability zone that is located within a multizone region (MZR). An MZR is organized by its metro location. For example, London can encompass more than one grouping of data centers within an MZR. The graphic shows three availability zones in one MZR that work together in the instance that one of the data centers becomes unavailable. Availability zones are connected directly to each or through low latency links.

![A location hierarchy that shows a geography that contains data center buildings inside of availability zones that are interconnected with points-of-presence within a metro.](images/Location-Illustration.svg){: caption="Figure 1. Location hiearchy" caption-side="bottom"}
