## ICMP Pinger - Python

Welcome to ICMP Pinger! This simple Python script helps you ping any website or IP address to check if it's reachable and measure the round-trip time (RTT). Whether you're testing the connectivity of your own services or troubleshooting network issues, ICMP Pinger is the tool for you.


---

## Features

🚀 Ping any website or IP address with ease.

⏱️ Measure round-trip time (RTT) in milliseconds.

💡 Display results clearly with accurate timings.

🛠️ Handle errors gracefully, including unreachable websites.



---

## Requirements

Before using the script, ensure you have Python 3.x installed. The script uses built-in libraries such as os and subprocess, so no additional dependencies are required!

If you're on a Linux or macOS system, make sure you have the ping command available. For Windows, it’s usually pre-installed.


---

## Installation

1. Clone the repository or download the script:

git clone https://github.com/01nstagram/pinger.git

cd pinger

2. Install dependencies (if necessary):

No external dependencies are required for this script, but make sure the ping utility is installed on your system.

---

## Usage

1. Run the script:

Open your terminal and run the Python script by entering the following command:

python pinger.py

2. Input your target:

The script will prompt you to input a website or IP address you'd like to ping. You can enter:

A website URL (e.g., example.com)

An IP address (e.g., 8.8.8.8)


The script will start pinging your target and display the round-trip times!


---

## Example Output

Here’s what you might see after running the script:

Ping test started for: example.com
Pinging example.com...
Round-trip time: 32.5ms
Round-trip time: 28.3ms
Round-trip time: 31.1ms
Average round-trip time: 30.3ms

This shows the times for each ping and the average round-trip time.


---

## Code Explanation

The script uses the ping utility to send ICMP Echo Request messages to the target and measures the round-trip time (RTT).

Main Steps:

1. Get the target (host or IP) from the user.


2. Execute the ping command using Python's subprocess module.


3. Parse the output to extract the round-trip times.


4. Display the results, including the average round-trip time.




---

## License

This project is licensed under the MIT License. See the LICENSE file for full details.


---

## Contributions

Feel free to fork this repository, open an issue, or submit a pull request! We welcome suggestions for improvements, bug fixes, or new features.


---

## About the Creator

This project is created by 01nstagram, a passionate developer working on useful tools to help streamline network diagnostics and more. If you have any feedback or just want to say hello, feel free to reach out!

