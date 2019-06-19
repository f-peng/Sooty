[![Generic badge](https://img.shields.io/badge/Made%20with-Python-blue.svg?style=flat-square)](https://GitHub.com/theresafewconors/sooty)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg?style=flat-square)](https://GitHub.com/theresafewconors/sooty)
[![GitHub contributors](https://img.shields.io/github/contributors/theresafewconors/sooty.svg?style=flat-square)](https://GitHub.com/theresafewconors/sooty/graphs/contributors/)
[![Generic badge](https://img.shields.io/badge/Built%20For-SOC%20Analyst's-olive.svg?style=flat-square)](https://GitHub.com/theresafewconors/sooty)
[![HitCount](http://hits.dwyl.io/theresafewconors/sooty.svg)](https://GitHub.com/theresafewconors/sooty)




# Sooty

The SOC Analysts all-in-one CLI tool to automate and speed up workflow. 

![](readmeimages/repcheck.gif)

### Sooty can Currently:
  - Sanitise URL's to be safe to send in emails
  - Perform reverse DNS and DNS lookups
  - Perform reputation checks from:
    - [VirusTotal](https://www.virustotal.com)
    - [BadIP's](https://www.badips.com/)
  - Check if an IP address is a TOR exit node
  - Decode Proofpoint URL's and  UTF-8 encoded URLS
  - Get file hashes and compare them against [VirusTotal](https://www.virustotal.com) (see requirements)
  - Perform WhoIs Lookups

 
### Requirements
 - [Python 3.x](https://www.python.org/)
 - To use the Hash comparison with VirusTotal requires an [API key](https://developers.virustotal.com/reference), replace the key in the code with your own key.
 
 
### Development

Want to contribute? Great!

  #### Code Contributions
  - New features / requests should start by opening an issue. This helps track new features and prevent crossover.
  - All code modifications, enhancements or additions must be done through a pull request. 
  - Once reviewed and merged, contibutors will be added to the ReadMe



### Contributors:

 - [Aaron J Copley](https://github.com/aaronjcopley) for his code to decode ProofPoint URL's
 - [James Duarte](https://github.com/GarnetSunset) for adding a hash and auto-check option to the hashing function
 - [mrpnkt](https://github.com/mrpnkt) for adding the missing whois requirement to requirements.txt

 ![](readmeimages/vt_hashchecker.gif)
