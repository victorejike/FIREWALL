# Installation Guide

## Prerequisites

- Linux operating system (Ubuntu/Debian recommended)
- Python 3.6 or higher
- GCC/G++ compiler
- libpcap development libraries

## Step-by-Step Installation

1. Clone the repository:
   `bash
   git clone https://github.com/yourusername/real-time-firewall-monitor.git
   cd real-time-firewall-monitor

   sudo apt-get update
sudo apt-get install -y libpcap-dev python3 python3-pip sqlite3

pip3 install -r middleware/requirements.txt

cd backend
make
cd ..
python3 middleware/data_processor.py

chmod +x scripts/start_system.sh
./scripts/start_system.sh
