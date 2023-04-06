# TcpTools

## Using "ping" 
### Ping three popular websites (for 5 or so packets each)

  Ping www.amazon.com three times | Ping www.google.com  three times | Ping www.microsoft.com three times

#### What were the min/avg/max/stddev statistics for each?

##### Amazon

  | Ping     | Min      | Avg      | Max     | StdDev  |
  | :----:   | :----:   |  :----:  | :----:  | :----:  |
  | 1        | 3.781    | 9.135    | 12.537  | 3.512   |
  | 2        | 4.231    | 10.362   | 12.844  | 3.132   |
  | 3        | 4.176    | 6.817    | 10.789  | 3.031   |

##### Google

  | Ping     | Min      | Avg      | Max     | StdDev  |
  | :----:   | :----:   |  :----:  | :----:  | :----:  |
  | 1        | 4.570    | 14.792   | 33.648  | 11.854  |
  | 2        | 9.307    | 11.768   | 13.357  | 1.559   |
  | 3        | 4.675    | 9.989    | 12.594  | 2.854   |

##### Microsoft

  | Ping     | Min      | Avg      | Max     | StdDev  |
  | :----:   | :----:   |  :----:  | :----:  | :----:  |
  | 1        | 4.164    | 96.736   | 167.097 | 61.803  |
  | 2        | 4.054    | 10.254   | 12.597  | 3.280   |
  | 3        | 4.018    | 9.142    | 13.197  | 4.131   |

#### Was there any packet loss on any of the pings?

  There was no packet loss for Amazon.com, Google.com, or Microsoft.com


#### Did the IP address change for a given website between pings?

  The IP address changed from the first to second ping for Amazon but 
  remained the same for the second and third ping.

  The IP address remained the same for all three pings for Google and Microsoft.
  
  
# Using "tracert" 
## Use tracert (or traceroute, depending on your OS) on the following sites:
www.amazon.com | www.google.com | www.microsoft.com


### What was the target server's IP address?

Amazon: 23.36.54.14
Google: 142.250.217.68
Microsoft: 23.200.56.161

### How many hops were needed to reach the target?

Amazon: 11
Google: 10
Microsoft: 11

### Can you identify your ISP from the intermediate server DNS names?



### Identify the "class" of IP address for each major step in the trip

