# Unified Host and Network Dataset
#### The Unified Host and Network Dataset is a subset of network and computer (host) events collected from the Los Alamos National Laboratory enterprise network over the course of approximately 90 days. The host event logs originated from most enterprise computers running the Microsoft Windows operating system on Los Alamos National Laboratory's (LANL) enterprise network. The network event data originated from many of the internal enterprise routers within the LANL enterprise network.
#### The data values have been deidentified (anonymized) to protect the security of LANL’s operational IT environment. The identities match across both the host and network data allowing the two data elements to be used together for analysis and research. In some cases, including well-known network ports, system-level users names (not associated to people), and system-level hosts, the values were not deidentified. In addition, in some cases hosts were combined where they represented well-known redundant services including the Active Directory servers, LANL’s email servers, and LANL’s automated vulnerability scanning systems.

Dataset: https://csr.lanl.gov/data/2017/
## Network Event Data


```http
  Time, Duration, SrcDevice, DstDevice, Protocol, SrcPort, DstPort, SrcPackets, DstPackets, SrcBytes, DstBytes
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Time` | `string` | The start time of the event in epoch time format |
| `Duration` | `string` | The duration of the event in seconds. |
| `SrcDevice` | `string` | The device that likely initiated the event.|
| `DstDevice` | `string` | The receiving device. |
| `Protocol` | `string` | The protocol number. |
| `SrcPort` | `string` | The port used by the SrcDevice. |
| `DstPort` | `string` | The port used by the DstDevice. |
| `SrcPackets` | `string` | The number of packets the SrcDevice sent during the event. |
| `DstPackets` | `string` | The number of packets the DstDevice sent during the event. |
| `SrcBytes` | `string` | The number of bytes the SrcDevice sent during the event. |
| `DstBytes` | `string` | The number of bytes the DstDevice sent during the event. |
