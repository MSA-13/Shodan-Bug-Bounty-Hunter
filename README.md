# Shodan-Bug-Bounty-Hunter
Shodan Bounty Scanner: Unleash the Power of Shodan for Bug Bounty Hunting and Discover Vulnerability Gems. Boost your Reconnaissance Efforts and Reveal Lucrative Targets for Rewarding Bug Bounty Engagements.


## Finding XSS in a Million Websites (cPanel CVE-2023-29489)

Discover and exploit a reflected cross-site scripting vulnerability in cPanel, a widely deployed web hosting control panel software. With approximately 1.4 million installations of cPanel exposed on the internet, this tool enables you to efficiently identify vulnerable targets. By leveraging Shodan's search capabilities and using nuclei for scanning, you can automate the process of extracting IPs and ports for targeted XSS testing. Boost your bug bounty efforts and secure valuable rewards.




1.Open a terminal or command prompt.
2.Navigate to the directory where you have saved the script.
3.Make sure you have installed the necessary dependencies. You can install them by running the following command:
pip install shodan
4.Replace /path/to/CVE-2023-29489.yaml in the script with the actual path to the CVE-2023-29489.yaml file on your system.
5.Run the script using the following command:
python3 script.py
6.Enter the target domain or IP address when prompted.
7.The script will perform the Shodan search, extract the IPs and ports to CTRL.txt, and run the httpx and nuclei commands.
8.The results will be stored in the outCVE-2023-29489.txt file.

Make sure you have a valid Shodan API key and the necessary YAML template file (CVE-2023-29489.yaml) in the specified location for the nuclei command to work correctly.
Let me know if you encounter any issues or need further assistance!


Notes: 
It is recommended to use a VPS for optimal results.
