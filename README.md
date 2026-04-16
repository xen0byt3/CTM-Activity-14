Activity # 14 SOC Log Cleaning & Threat Detection Simulation

[Github Repository]

	https://github.com/xen0byt3/CTM-Activity-14

[Overview]

In this activity, you will take the role of a SOC Analyst assigned to investigate a messy and unstructured log file.

Unlike typical logs, this dataset contains:

Noise and irrelevant entries
Inconsistent formats
Hidden threats
Embedded flags

Your mission is to

	Clean the logs
	Extract meaningful data
	Detect cyber attacks
	Identify attacker behavior
	Generate investigation reports

[Learning Objectives]

	By completing this activity, you will:

		Apply advanced Linux text processing commands
		Clean and normalize messy log data
		Extract IP addresses from unstructured logs
		Detect brute-force attacks
		Perform basic data masking
		Identify phishing and insider threats
		Think like a real SOC analyst

[Installation / Setup]
	Go to the repository
	Download files or clone
		git clone https://github.com/xen0byt3/xen0byt3-CTM-Activity-14.git
	Locate the .exe file
	Run the simulator

[How to Use]

	After launching the program:

	Press ENTER to continue...

	Menu:

	[1] Start Investigation
	[2] Flag
	[3] Exit

[PART 1: Investigation Mode]

	Select

	[1]

	You will perform real SOC tasks such as

	Log Cleaning
		Remove noise and irrelevant entries using sed
	Data Extraction
		Extract failed login attempts
		Extract IP addresses
	Log Normalization
		Standardize logs into consistent format
	Analysis
		Count attacks per IP
		Detect brute-force activity
	Security Controls
		Mask sensitive data (IP addresses)
		Apply multi-pattern replacements
	Live Monitoring
	Simulate real-time attack logs
	Detect
		Phishing attack
		Brute-force success
		Insider threat

You must type the correct commands to proceed.

[PART 2: Flag Mode (CTF Challenge)]

	Select:

	[2]

	Answer all questions using:

		flag{your_answer}
	Example:
		flag{messy.log}
		flag{yes}
		flag{203.0.113.50}

[Final Challenge]

	Identify the new threats detected in real-time

[Output Files]

After completing the simulation:

	log_cleaning_report.txt
		Commands executed
		Outputs generated
	flag_monitoring_report.txt
		Your answers
		Score and rating

[Submission Guidelines]

	Option 1 (Recommended)
	Upload:
		log_monitoring_report.txt
		flag_monitoring_report.txt
	Push to your GitHub repository
	Add xen0byt3 as collaborator

	Option 2 (Most Recommended)
	Create a Pull Request in CTM-Activity-14
	Include:
		log_monitoring_report.txt
		flag_monitoring_report.txt

[Scoring & Rating]

	Score	Rating
	9–10	SOC Analyst
	6–8	Junior Analyst
	0–5	Trainee

[Rules]

	Follow exact command syntax
	Analyze before answering
	Do not skip steps
	Avoid guessing
	Think like a SOC analyst

[Tips]

	Focus on patterns, not just lines
	Identify repeated IP addresses
	Compare failed vs successful logins
	Watch for hidden flags
	Pay attention to live logs

[Real-World Scenario]

	This simulation represents real cybersecurity operations:

		Log cleaning in SIEM systems
		Threat detection from noisy data
		Phishing attack identification
		Brute-force attack analysis
		Insider threat detection

[Credits]

	Developed by xen0byt3

	“Clean the noise. Find the threat.”