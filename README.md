<a href="https://www.buymeacoffee.com/medheeraj"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a beer&emoji=🍺&slug=medheeraj&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"></a>

## Description
**KARMA**
is a simple bash script automation that can talk to [Shodan](https://shodan.io) Premium API and find active IPs, ASN, Common Vulnerabilities, CVEs &amp; Open Ports.

#### Installation

```shell
git clone https://github.com/Dheerajmadhukar/karma.git
pip3 install shodan
apt install jq -y
````

**Usage**
```
# bash karma.sh target.tld

Output will be saved in output/target.tld-YYY-MM-DD directory
```

##### Requirements
- shodan python module [ pip3 install shodan ]
- jq [ apt install jq -y ]
