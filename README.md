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

I can't identify the ISP from the intermediate server DNS names for 
Amazon.com, Google.com, or Microsoft.com.



### Identify the "class" of IP address for each major step in the trip

#### Amazon.com

1 (10.18.0.2): Class A
2 (198.48.66.5): Class C
3 (10.132.5.75): Class A
4 (10.132.255.21): Class A
5 (10.132.255.22): Class A
6 (209.124.188.134): Class C
7 (198.71.47.5): Class C
8 (163.253.1.167)(163.253.1.165): Class B
9 (162.252.69.123): Class B
10 (23.203.145.201): Class A
11 (23.36.54.14): Class A

#### Google.com

1 (10.18.0.2): Class A
2 (198.48.66.5): Class C
3 (10.132.5.75): Class A
4 (10.132.255.21): Class A
5 (10.132.255.22): Class A 
6 (209.124.190.134): Class C 
7 (74.125.51.244): Class A 
8 * * *
9 (74.125.243.177): Class A 
  (142.251.50.244): Class B 
  (216.239.56.222): Class C 
10 (142.250.217.68): Class B 
   (74.125.243.189): Class A 
   (74.125.243.195): Class A
   
#### Microsoft.com

1 (10.18.0.2): Class A
2 (198.48.66.5): Class C
3 (10.132.5.75): Class A
4 (10.132.255.21): Class A
5 (10.132.255.22): Class A
6 (209.124.188.134): Class C
7 (198.71.47.5): Class C
8 (163.253.1.165): Class B
  (163.253.1.167): Class B
9 (162.252.69.123): Class B
10 (23.203.145.157): Class A
11 (23.200.56.161): Class A


