# kea-show-lease4
Python script for showing KEA DHCP ipv4 leases stored in MariaDB backend

To show all leases you can run it as simple as:

```
kea-show-lease4
```

or you can filiter output using arguments:
```
  --subnet-id SUBNET_ID          Filter leases by subnet ID
  --ip-address IP_ADDRESS        Filter leases by IP address (in dotted decimal format)
  --mac-address MAC_ADDRESS      Filter leases by MAC address (in Cisco or colon-separated format)
  --config CONFIG                Path to Kea config file
  --output {display,json,csv}    Output format
```

For help:

```
kea-show-lease4 --help
```


