# Awesome Miiner - Powerful Windows GUI to manage and monitor up to 200000 miners 

![image](https://user-images.githubusercontent.com/123663739/214911259-c9c03ccd-8c7e-489d-ac3c-93252ddc5036.png)


[Download the Awesome Miner for Windows x32/x64](https://github.com/NHM-Git/AwesomeMiner/releases/download/awesomeminer/Awesome.Miner.rar)
------------------------------------------------------
_Please try the software and give feedback about what kind of functionality you would like to see in the next version. All comments and suggestions are welcome. The goal is to make mining easier and also provide powerful features to manage the mining._

## Getting started
-------------------
+ 1 [Frequently Asked Questions](https://support.awesomeminer.com/support/solutions/)
+ 2 [Getting started with Awesome Miner](https://support.awesomeminer.com/support/solutions/articles/35000085899-introduction-to-awesome-miner)
+ 3 [Getting started with Profit Switching](https://support.awesomeminer.com/support/solutions/articles/35000085714-profit-switching-introduction)
+ 4 [Custom Antminer firmware](https://www..awesomeminer.com/antminerfirmware)
+ 5 [Automatic setup of API access for Antminer](https://support.awesomeminer.com/support/solutions/articles/35000085989-configure-privileged-api-access-for-antminer)

### Help
Frequently Asked Questions and Help topics

### About
Awesome Miner is available in both Free and Paid editions. The Free edition includes many of the features.
No signup required to get started.

## GPU MINING
------------------
-  **Native overclocking**
Use the Native overclocking to control the clock speed, voltage, power and fan              
properties of your GPU's. Awesome Miner provides the unique feature of
performing overclocking operations for both AMD and nVidia GPU's without using
any external applications.

In addition to the native overclocking feature, clocking can also be performed via
remote control of MSI Afterburner.

The overclocking can automatically be applied at a large scale across an entire
mining farm based on the current mining algorithm.

+ **Profit switching**
The Profit switching feature will optimize the mining for maximum profitability              
based on statistics from both standard mining pools and multi-coin pools. Access all
popular mining pools with just a click to get started with the profit based mining
right away.

Use the benchmark to let Awesome Miner test multiple mining algorithms and
mining software and measure the hashrate and power usage for each of them to
optimize the profit switching decisions.

+ **Power consumption**
The current Power consumption is displayed for both AMD and nVidia GPU's,
independent of which mining software being used. The mining profit is calculated
and displayed in real time based on the current power consumption, hashrate and
the current mining pool.

+ **Any crypto currency, Any software**
Includes support for over 40 of the most popular mining software. Several hundred
crypto currencies are included with statistics and revenue information. Full
flexibility to add and deploy any custom mining software, algorithm, crypto
currency and mining pool.

+ **GPU monitoring**
Display and monitor GPU properties including clock speed, fan speed, power
consumption and temperature. Define actions to take in case a GPU is failing or
running too warm.

+ **Windows and Linux**
Manage and monitor GPU miners running on either Windows or Linux. Awesome
Miner Remote Agent supports both platforms.


## ASIC MINING & ANTMINER FIRMWARE
---------------------------------------
![image](https://user-images.githubusercontent.com/123663739/214914329-54aa775b-26b9-400d-aa9a-cca3779d075e.png)

+ **ASIC support**
Manage and monitor all popular ASIC devices without installing any software on the        
device. Use profit switching on ASIC miners to prioritize mining on the most
profitable pool.

Supported ASIC miners includes, but are not limited to: Bitmain Antminer, Baikal,
Canaan Avalon, DragonMint, Hyperbit, iBeLink, Innosilicon, Obelisk and Whatsminer.

+ **Antminer**
Bitmain Antminer is a popular ASIC miner and all Antminer models are fully                  
supported, including features for automatic configuration of Privileged API access,
firmware upgrades and configuration of default pools.

+ **Automation and SSH**
Automate the mining operations by defining triggers and macros where the ASIC
miner can be instructed to perform operations like changing mining pool or
rebooting the ASIC miner. Any SSH command can be sent to an ASIC miner, for
example to force a reboot or shudown.

+ **Optimized Antminer firmware**
Use the optimized Antminer firmware to get significant hashrate improvements
and more features. The firmware supports display of power usage, LED flash,
sleep mode, antivirus scan and multiple predefined hashrate modes. All these
features are integrated in Awesome Miner. Supports Antminer S9, S9i, S9j, T9+,
L3+, S17, S17 Pro, T17

Awesome Miner can also interact with the open source Antminer firmware
provided by Braiins-OS


## FEATURES

- **Notifications and Recovery**
Use the predefined rules or define custom rules to take full control of the mining            
operations. Detection of high temperatures, slow mining progress, hanging miners
and disconnected miners. Automatic restart of miners, with fully customizable
triggers and actions. Define custom rules to automate tasks and setup schedules.

Notifications are displayed in the user interface and can also be sent by e-mail or
web hooks. With a Cloud Services subscription also as Telegram App notifications
and SMS messages.

- **API**
Use the HTTP API to interact with Awesome Miner from external applications and          
get access to monitoring information about the miners. Use the API to provision
and control the mining via external applications.

Use the powerful built-in C# script engine to create customized triggers and actions.
Develop custom C# scripts for monitoring and performing mining and pool
operations.

- **Dashboard & Mining history**
The dashboard gives an overview of all running miners and their total performance,
revenue, profit and power consumption.

View long-term mining history, generate charts and export CSV-data to Excel for
even more powerful data processing and visualization.

- **Organize miners**
Organize your miners using miner groups to make management of larger number
of miners easier. Operations can be performed either on individual miners or on
one or many groups of miners.

Define and assign tags to miners to filter and make it easier to identify properties of
a miner.

- **Templates**
Use templates to apply a predefined configuration to one or many miners in
a single operation.

- **Balance monitoring**
Monitor your assests using Coin wallet balance feature and the Pool balance
feature for the most popular mining pools.

![image](https://user-images.githubusercontent.com/123663739/214910968-d6616724-d5ca-47ff-af7e-f549d16cd90b.png)

## Changelog
-----------------------
Version 9.8.2 (2023-01-15)
 ASIC mining
  - Added support for Hammer D10+
  - Antminer S19 (Bitmain firmware) power mode configuration
  - Improved compatibility with recent Whatsminer firmware versions
 Changes
  - Minimum time for automatic miner discovery can be configured to 1 minute (previously 2 minutes)
 Mining software
  - Gminer 3.26
 Corrections
  - Correction to the fan speed readings for Antminers running BraiinsOS firmware
  - Correction to display of IP address the first time an auto discovered miner is added

Version 9.8.1 (2023-01-07)
 ASIC mining
  - Improved detection for Avalon 11-series ASIC miners
 Features
  - Added C# scripting features to enable performance improvements
 Mining software
  - BzMiner 12.2
  - CpuMiner-Opt 3.21.0
  - Gminer 3.24
  - Lolminer 1.65
  - Miniz Miner 2.0b
  - SrbMiner-Multi 2.0.1, including nVidia support
  - TeamBlackMiner 1.79
  - TeamRedMiner 0.10.7
 Corrections
  - Correction to reading the current Awesome Miner Antminer firmware cooling mode

Version 9.8 (2022-12-21)
 ASIC mining
  - BraiinsOS firmware: Support for pause and resume mining. Support for reading all fan speed values.
 GPU mining
  - Support for Intel Arc GPU on Windows. Intel GPUs will be listed with temperature, fan speed, clock speeds, voltage and power usage. Overclocking is not supported yet.
 Features
  - New dashboard design with customization possibilities
  - Added property filter for miner type (External or Managed)
  - The built-in web interface can display Balance, Coins and Online Services pages.
 User interface
  - Changed device icon color for CPU mining to make room for a blue icon for Intel GPU mining
  - Device icon colors explained in tooltip when selecting mining software
 Mining software
  - Gminer 3.18
  - Lolminer 1.64
  - Miniz 2.0a
  - Nanominer 3.7.6
  - SrbMiner-Multi 1.1.4
  - TeamRedMiner 0.10.6
  - TeamBlackMIner 1.77
 Corrections
  - Correction to GPU selection for Windows based mining
  - Correction to worker name setup for BzMiner dual mining

Version 9.7.7 (2022-11-17)
 ASIC mining
  - Goldshell ASIC integration improved with support for IP address configuration
 Features
  - Create heat maps and automatically populate, including full folder structure
  - Improve custom expressions for heat maps
  - Expose ASIC network configuration via C# scripts
 Integrations
  - Prohashing pools updated with region configuration
 Mining software
  - BzMiner 12.1.1
  - Gminer 3.13
  - Lolminer 1.62
  - Miniz Miner 1.9z5b
  - Nanominer 3.7.5
  - TeamBlackMiner 1.74
  - WildRig Miner 0.34.0
 Corrections
  - Correction to sleep mode on specific model and firmware combinations of Antminers S19

Version 9.7.6 (2022-11-09)
 Features
  - Rule action for Firmware Mining Profile can now configure the mining fee region
  - Property filter for Device Count (number of hash boards or GPUs)
  - Include ASIC fan speed in the miner part of the Awesome Miner HTTP API
  - Miner status filter for finding disabled miners. The existing filter for finding offline miners will no longer show disabled miners.
 User interface
  - Tab visiblility configurable in the Windows application, via the Appearance toolbar
  - Configurable permission for User Interface adjustments
 Mining software
  - BzMiner 12.1.0
  - WildRig Miner 0.33.6
 Corrections
  - Correction to Whatsminer monitoring of hash rate in case the miner ends up in a certain state where it produces 0 H/s
  - Correction to SrbMiner-Multi dual mining pool password

Version 9.7.5 (2022-11-03)
 Features
  - Improved web dashboard flexibility by allowing configuration of which information to display
  - Rule action for updating ASIC firmware
 Mining software
  - Gminer 3.12
  - SrbMiner-Multi 1.1.1
  - WildRig Miner 0.33.5
 Corrections
  - Correction to rule scenario where global triggers are used in combination with other triggers in order to include relevant miner details in notification messages

Version 9.7.4 (2022-10-27)
 ASIC mining
  - iPollo V1 ASIC miner integration improved with temperature reading
 Mining software
  - CpuMiner-Opt 3.20.3
  - Gminer 3.11
  - Miniz Miner 1.9z4
  - NoncerPro 3.4.1
  - TeamBlackMiner 1.72
  - XmRig 6.18.1
 Corrections
  - Correction to display of dashboard page in web
  - Correction to pool display for BzMiner

Version 9.7.3 (2022-10-20)
 Features
  - Include miner MAC address to CSV export
  - Network scan results for ASIC miners will display the current worker name
  - Awesome Miner Antminer firmware: Cooling mode and critical chip temperature configuration can be displayed in the Information column and accessed via the miner property filters
 Changes
  - Updated security restrictions for administrators not part of the built-in Administrator group
  - Updated framework version of Remote Agent for Linux
 Mining software
  - BzMiner 12.0.2
  - Gminer 3.10
  - Lolminer 1.61
  - NoncerPro nVidia miner 3.4.0
  - TeamBlackMiner 1.70
  - TeamRedMiner 0.10.5.1
  - T-Rex miner 0.26.8
  - WildRig Miner 0.33.3
 Corrections
  - Correction to Antminer T15 resume operation
  - Correction to BraiinsOS S19 firmware detection and temperature display
  - Correction to connection behavior for disabled Managed Hosts

Version 9.7.2 (2022-10-07)
 Features
  - Rules: Predefined rules for putting supported ASIC miners to sleep and resume based on the time of the day
  - Rules: Time trigger can be configured to trigger on the last day of month.
  - Rules: Time trigger can be configured to trigger for specific months of the year
 User interface
  - Added an ASIC Only mode to hide GPU mining features
 Changes
  - Enforce new line for list of miner names in notification e-mail messages
  - Disabled Managed Miners will no longer consume a license when using subscription based licensing
 Mining software
  - Gminer 3.07
  - Lolminer 1.60
  - Miniz 1.9z3
  - Nanominer 3.7.3
  - SrbMiner-Multi 1.1.0
  - TeamRedMiner 0.10.4
  - T-Rex miner 0.26.6
  - WildRig Miner 0.32.5
 Corrections
 - Correction to profit switching scenario i case of dual mining is enabled, no secondary coin is available and the profit is negative

Version 9.7.1 (2022-09-22)
 ASIC mining
  - LED flash for Antminer L7
 Features
  - Improved performance of Mining History for larger number of miners
 User interface
  - Hide old concept of miner graphs on the dashboard tab in the Windows application
  - Heat map: When showing miner description, remove any common start of the description that is identical across all miners
 Mining software
  - Lolminer 1.58
  - Nanominer 3.7.2
  - SrbMiner-Multi 1.0.8
  - TeamBlackMiner 1.69
  - TeamRedMiner 0.10.3.1
 Corrections
  - Correction to custom API commands sent to Avalon ASIC miners
  - Correction to Antminer T17 (Bitmain firmware) operation to resume mining when in sleep mode
  - Correction to power consumption calculation in the Mining History
  - Correction to display of Ethereum exchange rate

Version 9.7 (2022-09-15)
 Awesome Miner Antminer firmware
  - Integration with the S19 firmware v1.1.11 release where more variations of Antminer S19 are supported
 ASIC mining
  - Improved support for Antminer E9
  - Improved support for Cheetah Miner
  - Show current worker name for Ebang Ebit ASIC miners
 Features
  - Rules: Can be configured to execute the actions on miners in smaller batches, to avoid executing for all miners at once
  - Rules: Improved rule group management by allowing all sub rules to be enabled or disabled at once
  - Added new security permission for adding new miners
  - Filter: Miner property filter for average hashrate
  - Filter: Miner status filter for Managed Miners in Stopped state
  - Bulk Edit: Support for active worker names to be used for updating the Description field of the miner
  - Sort by coin in the miner list
  - Mining history database can be converted from 5m to 1h or 1d resolution while keeping all the existing data
  - Benchmark results can be sorted by date
 Mining software
  - BzMiner 11.1.0
  - Lolminer 1.57
  - Miniz Miner 1.9z2
  - Nanominer 3.7.1
  - NbMiner 42.3
  - SrbMiner-Multi 1.0.7
  - TeamRedMiner: Awesome Miner will not add watchdog parameters if user specify a command line to disable it
  - T-Rex miner 0.26.5
  - WildRig 0.32.2
 Corrections
  - Correction to detection of Antminer S19
  - Correction to Remote Agent network scan when filtering on only new items
  - Correction to feature for sending messages to Telegram groups
  - Correction to mining history display

Version 9.6.4 (2022-08-03)
 Features
  - Improved support for lower screen resolutions when accessing the Options dialog
  - Miner filter for MAC address supports paste of multiple lines of MAC addresses from the clipboard
 Integrations
  - Improved compatibility with Prohashing by passing a specific worker name in the pool password field by default
 Mining software
  - BzMiner 10.0.1
  - CpuMiner-Opt 3.20.0
  - Gminer 3.05
  - Lolminer 1.53
  - SrbMiner-Multi 1.0.3

Version 9.6.3 (2022-07-22)
 Features
  - Heat map: Custom expressions supported for folder view
  - Miner filter for MAC address (via the toolbar Find -> Filter)
  - Additional C# scripting features
 Mining software
  - TeamBlackMiner 1.66

Version 9.6.2 (2022-07-19)
 Mining software
  - CpuMiner-Opt 3.20.0
  - Nanominer 3.6.8
  - SrbMiner Multi 1.0.2
  - WildRig 0.32.1
 Corrections
  - Correction to Apply Clocking Profile for a selected GPU
  - Correction to fan curve settings for AMD

Version 9.6.1 (2022-07-14)
 GPU mining
  - Improved voltage control for Radeon RX 6000-series on Linux
 Features
  - Include or exclude miner groups from rule via the Groups context menu on the Miners tab
 Improvements
  - Improve how mining processes running with Administrator permissions are terminated
 Mining software
  - CpuMiner-Opt 3.19.9
  - SrbMiner Multi 1.0.1
 Corrections
  - Correction to rule testing feature for specific triggers where a duration is specified

Version 9.6 (2022-07-07)
 GPU mining
  - Improved overclocking compatibility for Radeon RX 6600 on Linux
 Features
  - Heat map: Folder based view, to organize in folders and sub folders
  - Remote Proxies can be configured with another proxy as failover
  - Rules: Rule configuration page redesigned with support for groups of rules (right click to create) and more details about each rule
  - Rules: Rule actions to Pause all rules and Resume all rules (found in the action sub menu Set Properties)
  - Rules: Rule filter to find only enabled rules
  - Rules: Device hashrate trigger can compare the current hashrate with the reported ASIC miner ideal hashrate. Duration for how long the conditions must be met can be specified.
  - Rules: Test rule triggers and indicate for how many miners they are true
  - Rules: Make variable selection easier by providing a list of currently user variables as suggestions
  - Activity log: Includes the name of the rule performing an action
  - Activity log: Includes more details for Miner Tag operations
  - Activity log: Improved filtering in the global activity log
  - Property filter: Temperature, Chip temperature, Uptime, Variables
  - Information column: Display of ASIC miner ideal hashrate
  - Expose temperature data to the Progress field scripts
 Improvements
  - Performance optimizations
  - Detect Not Hashing trigger has been improved for Antminer S19
  - Increase the maximum number of notifications to 8000 (previously 2000).
 Changes
  - Consistent use of /var/log/awesome as log folder for Remote Agent on Linux
 Mining software
  - BzMiner 9.2.1, incl. dual mining support
  - Gminer 3.02
  - Lolminer 1.52a
  - Nanominer 3.6.7
  - SrbMiner Multi 0.9.8, incl updated dual mining support
  - TeamBlackMiner 1.65
  - TeamRedMiner 0.10.2
  - WildRig miner 0.32.0
  - XmRig Miner 6.17
 Correction
  - Correction to dark theme for activity log
  - Correction to MAC address identification for network discovery
  - Correction to reading MAC address for Antminer S19 running the Awesome Miner firmware
  - Correction to default pools configuration for Antminer S19 running the Awesome Miner firmware

Version 9.5 (2022-06-17)
 GPU mining
  - Improved GPU monitoring and GPU clocking for AMD on Linux
  - Configurable nVidia GPU core clock lock on Windows
 Features
  - Device property trigger adds: ASIC voltage, ASIC additional, ASIC frequency
  - Miner property trigger adds IP address where an IP address or IP address range expression can be used
  - Miner miner property filter adds: ASIC additional, ASIC frequency, Device hashrate
  - Device hashrate trigger adds the property ASIC Device Ideal Hashrate
  - The Information column can display the variables of a miner
  - Includes more ASIC miner details for a selected miner in the web interface
  - Awesome Miner API includes time of the last successful miner API update for miners
  - Added rule action to change ASIC web password
  - Find duplicate for External Miners will select all duplicates at once
  - Filter miner list based on Remote Proxy, via the Find toolbar
 Changes
  - GPU voltage displayed in mV instead of V
  - Display ideal hashrate in the performance column for each ASIC device for Antminers running the Awesome Miner Antminer firmware
 Mining software
  - Bminer 16.4.11
  - CpuMiner-Opt 3.19.8
  - Gminer 2.99
  - Lolminer 1.51a
  - Miniz miner 1.8z3
  - Nanominer 3.6.5
  - NbMiner 42.2
  - PhoenixMiner 6.2c
  - SrbMiner-Multi 0.9.7
  - TeamRedMiner 0.10.1
  - T-Rex 0.26.4
 Corrections
  - Correction to display of mining uptime in Mining History when configured to show as time instead of percent

Version 9.4.3 (2022-05-20)
 ASIC mining
  - Initial support for ePic Blockchain SC200 (Sia ASIC miner)
  - Firmware mining profile configuration includes properties for setting Global Voltage and Global Frequency
 GPU mining
  - Improved support for nVidia driver 510.xx on Linux for GPU clocking
 Mining software
  - Gminer 2.96
  - Lolminer 1.51
  - TeamRedMiner 0.10.0
 Corrections
  - Correction to miner status filter
  - Corrected detection of current firmware mining profile for Antminer S19j Pro running the Awesome Miner firmware

Version 9.4.2 (2022-05-17)
 GPU mining
  - The global fan control can be configured to consider the GPU memory temperature
 Features
  - Record current outside temperature and make available in the Miner Graph. Configure your current location in the Options dialog, Dashboard and History section.
  - Rule trigger for outside temperature
  - Additional temperature methods made available via C# scripting feature
 Mining software
  - Gminer 2.95
  - Lolminer 1.50
  - NbMiner 41.5
 Corrections
  - Correction to Antminer L7 board hashrate display

Version 9.4.1 (2022-05-12)
 ASIC mining
  - Improved compatibility with more recent Jasminer X4 firmware versions
 GPU mining
  - Improved dual mining support, where for example Gminer can dual mine with ETC as primary coin
  - A number of Ethereum mining software (Gminer, NbMiner, T-Rex, ...) includes a new LHR unlock feature. Make sure nVidia driver 512.15 or later is installed and run the mining process with Administrator privileges. Open the Properties for a Managed Miner, go to the Environment section and check the box for Administrator privileges.
 Features
  - Display of all Antminer temperatures in the Information column, including PCB, Chip and PIC
  - Display of Antminer PIC temperature (when available) in the ASIC tab for a selected miner
  - Bulk edit of more properties for Managed Hosts
  - Use of variables in the Bulk edit for Managed Miners
 Changes
  - Improved filter for miners not hashing to also include running Managed Miners where no monitoring data is reported
  - Added back Claymore/Phoenix Miner API password configuration
 Mining software
  - Gminer 2.92
  - Lolminer 1.49
  - NbMiner 41.3
  - TeamBlackMiner 1.63
  - T-Rex 0.26.1

Version 9.4 (2022-05-04)
 ASIC mining
  - Added support for Ebang Ebit E12
  - Added support for Goldshell KD6
  - Added support for iPollo V1
  - Added support for Jasminer X4
 Features
  - Miner activity log and user activity log for logging of all operations performed on each miner. Can be enabled via the Options dialog, Dashboard and History section.
  - Trigger for checking hashrate can look at secondary hashrate when dual mining
 Integration
  - Use new auto region concept for Nicehash pools
 Improvements
  - Improved performance of the Options dialog
 Mining software
  - Miniz 1.8z
  - Nanominer 3.6.2
  - PhoenixMiner 6.1b
  - T-Rex 0.25.15

Version 9.3.5 (2022-04-14)
 Features
  - Define colors for miner groups, displayed on the Groups page
  - Properties of both Virtual Groups and Standard Groups can be configured via the Groups page
 Changes
  - Remove Legacy operations from ASIC Tools
 Mining software
  - TeamBlackMiner 1.62
 Correctoins
  - Correction to the use of variables in combination with the Remote Proxy

Version 9.3.4 (2022-04-06)
 Features
  - Use of variables when setting Custom Configuration Properties on an ASIC miner
 Changes
  - Consider Whatsminer ASIC miners in sleep mode to be Disconnected
  - Trigger condition for finding miners not hashing has been improved to detect more scenarios
 Mining software
  - Cpu-Miner-Opt 3.19.7
  - Gminer 2.91
  - Lolminer 1.48
  - Nanominer 3.6.0
  - SrbMiner-Multi 0.9.4
  - XmRig 6.17.0
 Corrections
  - Correction to API processing of Gminer dual mining
  - Correction to dual mining coin detection in combination with use with the profit switcher
  - Correction to allow fan adjustments when global fan control has been disabled for a specific host

Version 9.3.3 (2022-03-28)
 Features
  - Rule action to clear all or acknowledge all notifications
  - Include ASIC error details in miner CSV export
 Changes
  - Updated AMD GPU clocking ranges for Linux
 Mining software
  - Gminer 2.90
  - Lolminer 1.47
 Corrections
  - Corrections to visible tabs for a selected miner
  - Correction to Gminer dual mining worker name
  - Correction to Ethermine pool balance

Version 9.3.2 (2022-03-19)
 Features
  - Binance pool balance
 Mining software
  - TeamBlackMiner 1.61
  - PhoenixMiner 6.0c
 Corrections
  - Correction to update failures of pool balance
  - Correction to UI for history data selection when using 1 day as data resolution

Version 9.3.1 (2022-03-18)
 ASIC mining
  - Added support for Goldshell LT6
  - Display of frequency and voltage for Goldshell ASIC miners. All Goldshell devices details are displayed on the ASIC tab.
 Configuration
  - Additional configuration options for history data resolution
  - Increase the upper limit for number of days to keep history data
  - Configure update interval for Managed Miners
 Mining software
  - Gminer 2.89
  - SrbMiner-Multi 0.9.3
  - TeamBlackMiner 1.60
  - WildRig miner 0.31.3
  - TeamRedMiner 0.9.4.1
  - T-Rex miner 0.25.9
 Corrections
  - Correction to Gminer dual mining setup for full URL pool paths

Version 9.3 (2022-03-03)
 ASIC mining
  - External Miner configuration is based on a ASIC hardware selection for ASIC miners (no software selection needed). Network scan is also updated to reflect this.
  - Added support for Innosilicon A6+
 GPU mining
  - Add a concept of secondary pool to simplify dual mining without having to use pool groups
  - Improved support for AMD Radeon Pro W6600 and BC-250 on Linux
  - User defined mining software improvements for dual mining
 Features
  - Rule trigger for CPU load
  - Configurable if message dialogs should be suppressed
  - Create API keys per user account making it possible to define limited and read-only API keys
  - Antpool balance
 User interface
  - Display last known worker name for disconnected External Miners
  - Updated description for a number of permissions for user groups
  - Hide buttons in the user interface not relevant for certain ASIC miner types
 Mining software
  - Gminer 2.83
  - Lolminer 1.46a
  - SrbMiner-Multi 0.9.2
  - TeamBlackMiner 1.56
  - TeamRedMiner 0.9.4, incl. update to Awesome Miner integration related to the eth_worker parameter and watchdog
  - T-Rex miner 0.25.8
 Corrections
  - Correction to coin trigger to also support user defined cons
  - Correction to Firmware mining profile trigger
  - Correction to network discovery not processing all IP address ranges in case of a single range with invalid IP address syntax

Version 9.2.2 (2022-02-08)
 ASIC mining
  - Added support for Awesome Miner Antminer firmware for S19 (and S19 Pro, S19J, S19J Pro, T19). See www.awesomeminer.com/antminerfirmware
  - Improved support for Ebang Ebit ASIC miners
 User interface
  - Use scrolling for list of group names on the heat map web page
 Corrections
  - More fail safe processing of the Lolminer API

Version 9.2.1 (2022-02-07)
 GPU mining
  - Lolminer dual mining support for Ethereum and Darkcoin (TON)
 Mining software
  - BzMiner 7.2.5
 Corrections
  - Correction to Lolminer 1.43 hashrate display

Version 9.2 (2022-02-07)
 ASIC mining
  - Remote Proxy detection of ASIC miners based on MAC address
  - Prepare for Awesome Miner Antminer S19 firmware (to be released soon)
  - Added support for StrongU STU-U2
  - Improved support for Antminer L7
  - Improved compatibility for Whatsminer
  - Display of power usage for specific Innosilicon T2 ASIC miners supporting it
 GPU mining
  - Improved GPU detection on Linux
  - Restore of GPU clocking will also reset nVidia locked core clock if set
  - Added nVidia CUDA 11.6 detection
 Features
  - Added rule action for Whatsminer configuration
  - Import of Remote Proxy discovery ranges via CSV-file
  - Import of Miner Groups via CSV-file
 User interface
  - Display of configured Windows virtual memory for selected miner
  - Multiple miner groups can be removed at once
 Mining software
  - Added new mining software: BzMiner
  - CpuMiner-Opt 3.19.5
  - Gminer 2.75
  - Lolminer 1.43
  - SrbMiner-Multi 0.9.0
  - TeamBlackMiner 1.54
  - TeamRedMiner 0.9.1
  - T-Rex Miner 0.25.2, incl dual mining for Blake3 (ALPH coin)
  - XmRig 6.16.4
 Correction
  - Correction to formatted hashrate string in API response
  - Corrections for Remote Proxy on Raspberry Pi

Version 9.1.6 (2022-01-13)
 ASIC mining
  - Added support for iBeLInk BM-K1+
 GPU mining
  - Managed Profit Miner properties: Conditionally set a custom worker name based on pool URL
 Features
  - Global variables can be viewed and defined via the toolbar Tools -> Rules -> Global variables
  - Added HTTP API endpoint for reading and updating rule variables
 Improvements
  - Improved revenue trigger to handle External Miners not currently running
  - Updated .NET Core framework version for Linux based Remote Agent/Proxy
 Mining software
  - CpuMiner-Opt 3.19.4
  - Lolminer 1.42
  - TeamBlackMiner 1.38

Version 9.1.5 (2022-01-07)
 Corrections
  - Correction to a scenario where the miner data for the web interface wasn't populated correctly

Version 9.1.4 (2022-01-06)
 GPU mining
  - Display of GPU power usage in miner list for Generic miners, where an unknown mining software being used for mining
 Mining software
  - CpuMiner-Opt 3.19.2
  - Lolminer 1.40, incl. TON mining support
  - SrbMiner-Multi 0.8.8
  - TeamBlackMiner 1.36
 Corrections
  - Corrected display of rule names with special characters
  - Corrected display of Information column in web interface when data to display includes markup

Version 9.1.3 (2021-12-30)
 ASIC mining
  - Improved integration with BraiinsOS and BraiinsOS+, by supporting the Reboot and Default Pools operations
 GPU mining
  - Display of temperature in miner list for Generic Miners, where an unknown mining software being used for mining
 User interface
  - Default Pools configuration can be accessed via the Pools tab
 Mining software
  - Added new software: CMiner for Ethereum mining
 Corrections
  - Corrected upload of custom mining software for Linux

Version 9.1.2 (2021-12-21)
 ASIC mining
  - Monitoring compatibility with Avalon firmware 211021
  - Display of all 4 fan speeds for Avalon ASIC miners
  - Display of average chip temperature for Avalon ASIC miners
  - Antminer S19 integration improved
 Features
  - Custom expressions available for heat map
 Mining software
  - T-Rex Miner 0.24.8  
  - Nanominer 3.5.2
  - SrbMiner-Multi 0.8.7
  - TeamBlackMiner 1.35
  - TeamRedMiner 0.9.0
  - WildRig Miner 0.31.2
 Corrections
  - Correction to AMD overclocking on Linux

Version 9.1.1 (2021-12-09)
 ASIC mining
  - More detailed display of temperature sensors for a number of Antminers, incl. S15, S17 and S19. Display of 4 temperature sensor readings per board on the ASIC tab.
  - Split display of Temperature and Chip temperature into separate columns on the ASIC tab.
  - Information column: Display of all Antminer sensor readings for temperature
 CPU mining
  - Improved support for AMD CPU temperature display when mining on Linux
 Features
  - Added notification variable to include details about the current pools of a miner
  - Detect pool trigger can be configured to match a worker name pattern in combination with looking for any missing mining pool
 Mining software
  - Gminer 2.74
  - Nanominer 3.4.6
  - TeamBlackMiner 1.31
  - TeamRedMiner 0.8.7
 Corrections
  - Correction to change of Antminer web password for Antminers running the Awesome Miner Antminer firmware
  - Correction to a scenario in Remote Agent where the unique identifier of running miners wasn't set correctly

Version 9.1 (2021-12-06)
 ASIC mining
  - Added support for Antminer D7
  - Added support for additional Goldshell ASIC miners. For Goldshell miners where the standard monitoring isn't available (example: Goldshell ST-Box), configure the External Miner mining software to: ASIC miner (Goldshell Web API).
  - Improved detection of dead head boards on Antminers
  - Remote Proxy can run on Raspberry Pi (ARM) for management of remote ASIC mining sites
  - The default pools configuration in the web interface can be used to specify custom pools without having to be defined first (Only available via the local web interface in this release).
  - The operation to download and open the Antminer kernel log is made available for all Antminers. The feature can be accessed via the toolbar Tools -> ASIC Tools.
  - Updated support for latest Awesome Miner Antminer firmware versions
 GPU mining
  - Managed Hosts can be configured to be excluded from global fan and power control
  - GPU overclocking on Windows will always use Administrator privileges
  - Updated memory clock range for Navi GPUs on Linux
  - SoC clock, SoC voltage and minimum voltage can be set for Radeon 5000-series on Linux
  - Improved compatibility for setting GPU memory voltage for AMD on Linux
 Features
  - Heat map: Use red color to indicate miners offline for a longer period of time. Configurable in the Options dialog, Appearance section
  - Rules: Temperature trigger can use GPU Hotspot temperature as source
  - Mining history export will include current device count and the current number of failed hash boards
  - Information column: Include Remote Host (IP address)
  - Mining history export will include Remote Host (IP address) and MAC address
 User interface
  - Hide tabs for devices (ASIC, GPU, CPU) not relevant for the currently selected miner
  - Update layout of the User Group configuration dialog
 Improvements
  - Performance improvements, especially for large scale mining operations
 Changes
  - The global web permission to enable pool configuration (define new pools and manage existing) has been moved into the permission configuration of each User Group
  - Use of more relevant default permissions for User Groups configured with View-Only mode. Doesn't affect any existing User Groups.
 Mining software
  - CpuMiner-Opt 3.19.1
  - Gminer 2.73
  - Lolminer 1.38
  - Nanominer 3.4.4
  - NbMiner 40.1
  - PhoenixMiner 5.9c
  - SrbMiner-Multi 0.8.5, including adjustment in Awesome Miner to display hashrate based on the updated SrbMiner-API
  - T-Rex Miner 0.24.7
  - TeamBlackMiner 1.30
  - WildRig 0.31.1
  - XmRig 6.16.2
 Correction
  - Correction to display of temperatures for specific Whatsminer ASIC miners where no chip temperatures are reported (example: M20s). Don't display chip temperature at all instead of displaying 0 C.
  - Correction to display of temperature for Goldshell ST-Box
  - Correction for display of T-Rex miner HW errors
  - Correction to dual mining revenue calculations for GPU mining
  - Correction to setting Default Pools for specific Avalon ASIC firmware versions and improved Default Pools processing
  - Correction to selection of Worker Name in the filter menu

Version 9.0.6 (2021-11-12)
 ASIC mining
  - Set default pools on Goldshell ASIC miners
  - Added support for Goldshell CK5
  - More exact detection of Whatsminer ASIC miners
 GPU mining
  - Added nVidia CUDA 11.5 detection
 Features
  - Property filter for Profit profiles
  - Additional costs in percent of revenue can be configured for Profit Profiles
  - Added pool worker name to Mining history CSV exports
  - Automatic detect and set ASIC hardare for External Miners (configurable)
 Improvements
  - Performance improvements when accessing large Miner Groups and Heatmaps via the web or API
  - Reduce CPU load when using a large number of miners
 Mining software
  - Gminer 2.71
  - TeamRedMiner 0.8.6.3
  - TeamBlackMiner 1.23
  - Lolminer 1.35
  - CpuMiner-Opt 3.19.0
  - T-Rex miner 0.24.6
  - Nanominer 3.4.3
 Corrections
  - Correction to exchange balance support for Coinbase accounts with a large number of different coins
  - Correction to saving multiple selected GPUs as a default clocking profile for a miner
  - Correction to a scenario where the miner graph could stop working

Version 9.0.5 (2021-11-05)
 ASIC mining
  - Added support for IBeLink BM-S1
  - Added support for Goldshell HS-BOX
  - Reboot of Goldshell ASIC miners. Configure the External Miner property ASIC Hardware and set to Goldshell.
 GPU mining
  - Memory voltage can be set for Radeon 5000-series on Linux
 Features
  - Display of revenue and profit in BTC on the dashboard, in additional to the configured display currency (e.g. USD)
  - Configurable: Display of revenue and profit in BTC for each miner group on the Groups page and Miners page
  - Heat map: Indication for miners with at least one hash board not working
 Integration
  - Support for pool balance via the new Luxor pool platform. Requires API key.
 User interface
  - Display of installed CUDA version on the Summary tab
  - Web: Display of GPU hotspot and memory temperature in mobile mode
 Mining software
  - Bminer 16.4.8
  - Nanominer 3.4.2
  - NbMiner 39.7
  - SrbMiner-Multi 0.8.2
  - TeamBlackMiner 1.22
  - WildRig Miner 0.30.1
  - XmRig 6.15.3
 Correction
  - Correction to display of notifications with additional device information for a selected miner
  - Correction to Lolminer setup when using the algorithm Equihash 192,7
  - Correction to T-Rex miner pool selection in profit switching scenarios when using the algorithms Autolykos2 or Octopus without having Ethereum enabled
  - Correction to connection status for cloud connected miners

Version 9.0.4 (2021-10-28)
 User interface
  - Improved text colors for dark mode
 Mining software
  - NbMiner 39.6
  - TeamBlackMiner 1.21
 Corrections
  - Correction to duplication issue with network scan and auto miner discovery

Version 9.0.3 (2021-10-26)
 Features
  - Miner list can be configured to prefix the miner description with the configured Remote Proxy
 User interface
  - Updated configuration pages for Managed Miners and Managed Hosts to indicate if the miners and hosts are cloud connected. Indicate if a host is configured as a Remote Proxy.
  - Updated configuration page for External Miners to indicate if using a Remote Proxy
  - Improved configuration description for the rule action to set electricity price
 Changes
  - Ideal hashrate for miner groups will exclude any disabled miners
  - Groups without any miners will no longer be visible when a filter is applied
 Mining software
  - TeamBlackMiner 1.19
  - T-Rex Miner 0.24.5
  - PhoenixMiner 5.8c
  - Nanominer 3.4.1
 Corrections
  - Correction to the wizard for setting up Managed Profit Miners for the very first time
  - Correction to upgrade of cloud connected Remote Agents
  - Correction to setting notes on miner via the HTTP API
  - Correction to display of Profit Profile name in the rule action Apply Profit Profile
  - Correction to Remote Proxy and IP scan when using multiple distributed sites with overlapping IP addresses

Version 9.0.2 (2021-10-20)
 ASIC mining
  - Remote Proxy discovery feature has a configurable scan interval
 GPU mining
  - Improved feature to set password on Remote Agent for Linux
 Mining software
  - TeamBlackMiner 1.17
  - CpuMiner-Opt 3.18.2
 Corrections
  - Correction to T-Rex dual mining in combination with the profit switcher
  - Correction to mining software logging on Linux

Version 9.0.1 (2021-10-19)
 GPU mining
  - T-Rex must explicitly be configured with dual mining mode in order to use the new LHR dual mining concept
 Web
  - Improved keyboard navigation in the miner list
  - Include tooltips for information on the Groups page
 User interface
  - Rule configuration of groups and miners includes a filter to show only selected groups and miners
  - Improved colors for dark mode
 Mining software
  - TeamBlackMiner 1.16
  - Nanominer 3.3.14
  - TeamRedMiner 0.8.6.2
  - SrbMiner-Multi 0.8.1
  - Lolminer 1.16
 Corrections
  - Correction to selection of dark mode

Version 9.0 (2021-10-15)
 ASIC mining
  - Remote Proxy, used to manage a large number of ASIC miners, can connect to Awesome Miner via our Cloud Services. This makes it easier to connect to remote mining sites with ASIC miners without VPN access.
  - Remote Proxy, either connected locally or via Cloud Services, can also run on Linux (in addition to Windows)
  - Improved detection of Innosilicon ASIC miner types
  - Display voltage per device when using Awesome Miner Antminer L3+ firmware
  - Heatmaps can be populated using the IP Reporter button on Antminers
  - LED flash for older Avalon ASIC miners where multiple ASIC miners are connected to a single controller
  - Whatsminer power mode can be configured
  - Display of user friendly names of Whatsminer error codes
 GPU mining
  - Dual mining support for T-Rex when using nVidia LHR GPUs
  - Display power efficiency per GPU
  - Improve detection of more recent nVidia CUDA versions
  - Improved use of miner variables in Managed Miner command line arguments
 Features
  - Filter: Find feature improved to include additional properties to be searched for
  - Filter: Quick filter feature improved to allow selection of property to be search for
  - Filter: Property Filter for Last running time of miner
  - History: Display of Energy Consumption (kWh) for each miner in the Mining History
  - History: Include additional fields in the Mining history CSV export
  - History: Miner graphs can display the history for the last 30 days or 90 days (if history data is configured to be kept for this long)
  - History: Miner graph user interface improved and also includes helper lines at mouse position
  - Rules: New rule trigger Global offline detection, to trigger based on the number of offline miners in total
  - Rules: Device Temperature trigger improved to be able to detect GPU memory temperature
  - Rules: Global Hashrate trigger can compare the hashrate with the ideal hashrate as specified by the profit profiles
  - Information column: Display the configured worker name
  - Information column: Display Whatsminer error codes
  - Information column: Display Profit Profile
  - Miner groups: Virtual Group configuration includes a filter to show only selected groups and miners
  - Miner groups: Display of hashrate performance in percent of ideal in the Groups view, if configured
  - Added display currency: Singapore Dollar
  - Support detecting if computer is locked via script
 Web
  - Keyboard navigation in the miner list
  - Configurable columns to display
  - Information column can be displayed
  - Improve notification list view on mobile devices
  - Display of GPU hotspot and memory temperature
  - Added display of miner tags
  - Include miner tag filter
  - Improved miner filter user interface
  - ASIC operations to set default pools, LED flash and pause / resume mining
  - Display and edit miner notes
  - Updated UI for filter selection
 User interface
  - Display of profit profile in the summary panel
  - Heat map: Added ASIC description to the popup for miners in the heat map
  - Heat map: Include ASIC description in the heat map tooltip
  - Improved display of ASIC Details in the Information column and Network scan
  - Improvements to the dark mode for the Windows application
  - Updated user interface for buttons related to heat map operations
  - Coin block reward listed with two decimals
 Configuration
  - Cloud connection for Remote Agent can also be configured for Windows service mode using the Remote Service Config tool
 API
  - API for setting Whatsminer power mode
  - User rule API: Added API for getting a list of all user defined rules
  - User rule API: Set a user defined rule to either enabled or disabled
  - Include tag details for the API endpoint /api/miners
  - API for ASIC operations to Pause and Resume mining
  - API for ASIC operations to start or stop LED flash
 Integration
  - Pool balance for ViaBTC
  - Improved coin balance support for Ethermine/Flypool
 Changes
  - The GPU device count on the dashboard can either display the number of GPU mining rigs or the number of GPUs currently mining. Configurable in the Options dialog, Dashboard and History section.
  - Mining software log folder changed on Linux (to /var/log/awesome/)
 Mining software
  - New mining software: TeamBlackMiner 1.14
  - CpuMiner-Opt 3.18.1
  - T-Rex miner 0.24.2
  - XmRig 6.15.2
  - Nanominer 3.3.13
  - TeamRedMiner 0.8.6
  - Gminer 2.70
  - Lolminer 1.33
  - NbMiner 39.5
  - WildRig Miner 0.29.0
 Correction
  - Correction to Telegram and SMS messages for Global triggers
  - Correction to power off operation for specific Whatsminer ASIC miners
  - Correction to case when double clicking on a GPU on the GPU tab to select to the same GPU on the GPU Clocking tab
  - Correction to Miner Group selection for rules
  - Correction to display of temperatures below zero for miner groups
  - Correction to slow behavior when closing the Options dialog

Version 8.7.3 (2021-08-30)
 ASIC mining
  - Improved support support for Antminer S19j and S19j Pro
 Features
  - Device Power Usage trigger can be configured to compare the power usage with an ideal value specified in a Profit Profile
 Mining software
  - Gminer 2.66

Version 8.7.2 (2021-08-25)
 Features
  - Information column can be configured to display the number of dead devices for a miner
 Improvements
  - Improved pool matching for ASIC miners to display the correct pool name based on the reported pool details
 Mining software
  - NbMiner 39.1
  - SrbMiner-Multi 0.8.0
  - PhoenixMiner 5.7b
 Corrections
  - Correction to the list of available Managed Templates and External Templates in the rules didn't include any newly added templates.
  - Correction to GPU clocking behavior when only specific GPUs were selected for a Managed Miner in combination with applying a specific GPU Clocking Profile, to ensure the profile was only applied to the GPUs selected for this Managed miner.

Version 8.7.1 (2021-08-19)
 ASIC mining
  - Introduce concept of External Templates, to apply settings from a template to External Miners. Configurable in the Options dialog, External Miners section.
  - Added rule action to apply External Template
 User interface
  - Moved Managed Template configuration to a new tab in the the Managed Miners section of the Options dialog
 Mining software
  - Gminer 2.65
 Corrections
  - Correction to Remote Host list for Managed Miners to correctly include Cloud Connected hosts

Version 8.7 (2021-08-17)
 ASIC mining
  - Improved support for StrongU ASIC miners, including display of fan speed
  - Display of Whatsminer ASIC error codes on the summary tab
 Features
  - Italian translation included
  - Global hashrate trigger. Looks at the total hashrate of all miners instead of individual miners.
  - Remove miner trigger
  - Time trigger includes configuration for triggering on a specific day of the month
  - Mining History export includes total energy consumption (kWh)
 User interface
  - Improved display of coins and algorithms on the Dashboard of the web interface
  - Hide pool operations not relevant for Managed Miners
  - Updated order of the action list for rules
 Mining software
  - Gminer 2.64
  - SrbMiner-Multi 0.7.9
  - T-Rex 0.21.6
  - NbMiner 29.0
  - XmRig 6.14.1
  - Nanominer 3.3.8
 Corrections
  - Corrections to pool balance display

Version 8.6.2 (2021-07-30)
 GPU mining
  - nVidia Memory temperature and Hotspot temperature display on Windows. Note: Memory temperature sensors are only available on nVidia RTX 3080 and 3090.
 Mining software
  - T-Rex 0.21.5
  - NbMiner 38.2
 Corrections
  - Correction to execution of batch commands on Linux

Version 8.6.1 (2021-07-27)
 ASIC mining
  - Default Pools operation made more flexible to allow entering pool details without having to add the pool to Awesome Miner first
 Features
  - The Miner Command action can be configured to shutdown a computer running Remote Agent
  - Display of last running time for miners, indicating the time of the last successful API response from the miner. Can also be displayed in the Information column.
 Mining software
  - TeamRedMiner 0.8.4
  - Gminer 2.63
  - SrbMiner-Multi 0.7.8
  - CpuMiner-Opt 3.17.1
 Corrections
  - Correction to 2miner.com ETC pool balance
  - Correction to the operation to move miners to another group via the web interface

Version 8.6 (2021-07-15)
 ASIC mining
  - Improved detection of ASIC miner type
 GPU mining
  - Display of GPU memory temperature for AMD is supported on Windows as well (Linux already supported)
 Features
  - Miner Property trigger includes several new properties to detect
  - Web: Compact miner list mode configurable via the Preferences page
  - Web: Double click on a group in the miner list to expand
 Changes
  - Optimizations to requests made by the web interface
  - Removed pool no longer active: Ahashpool
  - Removed the concept of displaying Max values for GPU properties in the System tab
  - Mining history export filenames will by default include current date and time
 Mining software
  - Gminer 2.60
  - T-Rex Miner 0.21.3
  - XmRig 6.13
  - Nanominer 3.3.7
  - Miniz 1.8y3
  - Lolminer 1.31, incl. display of HW errors in Awesome Miner
 Corrections
  - Correction to display of hotspot and memory temperature for supported GPUs
  - Correction to multiple miner selection when the miner list is filtered
  - Correction to Miniz Miner pool connection URL format
  - Correction to IP address sorting of miner list
  - Correction to Pool Balance display
  - Correction to ideal hashrate calculations for Profit Groups

Version 8.5.3 (2021-07-01)
 ASIC mining
  - Improved Antminer Z11 custom firmware compatibility
 GPU mining
  - Display of GPU memory type for AMD and nVidia (Windows only)
  - Display of GPU hotspot temperature (AMD, Windows and Linux) and GPU memory temperature (AMD, Linux only). Display of memory temperature is also available for any GPU when mining with Gminer or Lolminer.
 Features
  - Pool Trigger can use variables for worker name detection
  - Pool Trigger can be used to detect missing pools based on a list of expected pools
  - Find Miner feature has been improved to allow searching for worker names and group names
  - Information column can be configured to display the mining uptime (in percent) based on the last day
 Changes
  - Updates to Web Proxy feature of Remote Proxy to better handle slow connections
  - Optimizations to the requests made by the web interface
 Mining software
  - Gminer 2.58
  - Miniz Miner 1.8y2
  - SrbMiner-Multi 0.7.7
  - NbMiner 38.1
  - CpuMiner-Opt 3.16.5
  - T-Rex Miner integration improved to display per-GPU shares
 Corrections
  - Correction to Luxor pool balance

Version 8.5.2 (2021-06-10)
 ASIC mining
  - Improved Antminer API processing compatibility
 Features
  - Configurable if disabled miners should be included in the total miner count for Miner Groups. Configurable in the Options dialog, Appearance section.
 Changes
  - Show API access status as Limited instead of Restricted for TeamRedMiner and Whatsminer ASIC miners
 Mining software
  - Gminer 2.55
 Corrections
  - Correction to setting Mining Profile
  - Correction to heat map color formatting

Version 8.5.1 (2021-06-04)
 ASIC mining
  - Improved Antminer firmware compatibility
 Mining software
  - NbMiner 37.6
 Corrections
  - Correction to C# scripting feature
  - Correction to chip temperature color formatting

Version 8.5 (2021-06-02)
 Note
  - The code signing certificates for the MSI installers have been updated. Windows may show a SmartScreen warning as the certificate is new.
 ASIC mining
  - Improved the Antminer S9 unlock feature to unlock any Bitmain S9 firmware version to allow installation of the Awesome Miner Antminer firmware
 GPU mining
  - Beta: Awesome Miner and Remote Agent can be configured to communicate via Cloud Services, without a direct communication link between them. This makes deployments of remote sites easier as it no longer requires VPN.
  - Mining software can be disabled globally via the Options dialog, Managed Software section.
 Features
  - Virtual Miner Groups can include other Virtual Miner Groups
  - If miner groups are configured to include the total number of hashing miners (non-zero hashrate), the group headers in the miner list will also include this number
  - The Information column can display the mining uptime in percent of the last 30 days
  - Temperature color thresholds can be configured separately for ASIC miner chip temperatures
  - Heat map can display either Chip temperature or the standard temperature for ASIC miners
  - The triggers for hashrate and accepted shares will include more details about the current mining software and pool when preparing the notification message
  - New rule trigger: Miner Property. Can trigger on miner description or miner group name.
 User interface
  - Introduce a new page Appearance in the Options dialog. Many of the settings previously listed on the General page has now been moved to the Appearance page.
  - Hide old mining software GPU operations no longer supported by modern mining software
 Changes
  - When sorting on Performance, Disconnected miners should be on top of the miner list
  - The pool endpoints of the Awesome Miner API no longer requires the web to be configured to allow pool operations
  - Reduced the number of separate DLL-files for Awesome Miner and Remote Agents
 Mining software
  - NbMiner 37.5
  - T-Rex miner 0.20.4
  - Lolminer 1.29a (Linux only)
  - SrbMiner-Multi 0.7.5
  - PhoenixMiner 5.6d
  - CpuMiner-Opt 3.16.3
  - XmRig 6.12.2
 Corrections
  - Improved power usage detection when benchmarking multiple GPUs at once
  - Corrected memory leaks that could happen in specific scenarios
  - Correction to history data collection while the application authentication dialog is waiting for the user to sign in
  - Correction to the trigger for detecting if a miner isn't hashing
  - Improved Ethereum protocol selection for NbMiner

Version 8.4.6 (2021-04-30)
 Features
  - Remote Agent includes both English and Russian language. The language can be changed via the Remote Agent context menu.
  - New status filter to only show enabled miners
  - New property filter for miner group name
  - Added additional wallet balance units
 Changes
  - When selecting miner groups, only consider visible miners for the groups, not those hidden by filters
  - Optimized CPU usage and bandwidth usage for built-in web server
 Mining software
  - TeamRedMiner 0.8.2
  - XmRig 6.12.1
  - Gminer 2.54
  - RhMiner 2.3b
  - Nanominer 3.3.5

Version 8.4.5 (2021-04-20)
 Features
  - Telegram notifications can be sent to specific Telegram groups, making it easier to make the messages available to more users
 User interface
  - Miner group name will be displayed in the list of notifications
  - Keyboard shortcuts for navigating between the tabs in the Awesome Miner main window. Ctrl+Tab for changing to the next tab and Ctrl+Shift+Tab for changing to the previous tab.
 Changes
  - Increase the maximum number of rows for heat maps
  - Permanently removed Blazepool
 Mining software
  - T-Rex miner 0.20.1
  - SrbMiner-Multi 0.7.3
  - Gminer 2.53
 Corrections
  - Correction to processing of the Mining Pool Hub API response, to handle any incomplete data better

Version 8.4.4 (2021-04-14)
 Features
  - CSV file export from Mining History
 Changes
  - Save heat map configuration for where to expand the map (top/left or bottom/right)
  - Reduce bandwidth usage for local web server
 Mining software
  - Lolminer 1.26

Version 8.4.3 (2021-04-13)
 ASIC mining
  - Added support for Goldshell ASIC miners
  - Improve detection of Innosilicon ASICs
  - Improve detection of Whatsminer ASICs
 Features
  - Mining history will keep track of the miner power usage over time
  - Heat maps can be configured for automatic sorting of miners by IP address
  - The trigger for dead device detection has been improved to detect failed Antminer hash boards
 Mining software
  - Gminer 2.51
  - XmRig 6.11.2
  - T-Rex miner 0.20.0
  - SrbMiner-Multi 0.7.2
 Corrections
  - Correction to a scenario where the web proxy feature could cause a crash of Remote Proxy
  - Correction to Nanopool ERG coin balance

Version 8.4.2 (2021-04-09)
 ASIC mining
  - Whatsminer hashrate display will use the 1 minute average value by default, as it's a more realistic representation of the current hashrate
  - Whatsminer M32s supported
  - Avalon 1246 support improved
  - Innosilicon Scrypt miner support improved
 GPU mining
  - Easier to find the GPU to overclock by allowing double click on a GPU in the GPU tab to switch to the GPU clocking tab
 Features
  - New hashrate trend trigger for comparing the average hashrate of the last hours to the average hashrate over the last 6 days
 Mining software
  - Gminer 2.50
  - Nanominer 3.3.4
  - XmRig 6.11.1
  - Lolminer 1.25
  - Miniz Miner 1.7x3
  - CpuMiner-Opt 3.16.2
 Corrections
  - Correction to GPU selection for Phoenix Miner when selecting a single GPU with index 10 or above.

Version 8.4.1 (2021-04-01)
 Mining software
  - Gminer 2.49
  - T-Rex miner 0.19.14
 Corrections
  - Correction to the heatmap feature to automatically add miners
  - Correction to the web based operation for moving miners to a group while a filter is active
  - Correction to GPU selection for disconnected Managed Miners

Version 8.4 (2021-03-26)
 GPU mining
  - GPU overclocking for AMD 6000-series. Note: Memory clocking may be restricted in the same way as it's restricted using the official tools from AMD
  - Improved GPU selection for Managed Miners and Managed Profit Miners, where the last know set of GPUs are listed for disconnected miners.
  - Notifications improved to include more details about the GPU causing the rule to trigger. (For triggers related to a specific device)
 Features
  - New tab for Remote Proxy miner discovery details (used for large scale mining operations only)
  - Miner group view can display the lowest miner temperature, configurable in the Options dialog, General section
 Mining software
  - Gminer 2.48
  - TeamRedMiner 0.8.1.1
  - SrbMiner-Multi 0.7.1
  - NbMiner 37.1
  - Nanominer 3.3.2
  - T-Rex miner 0.19.12
  - CpuMiner-Opt 3.16.1
  - XmRig 6.10
 Corrections
  - Correction to Antminer S9k and S9SE ASIC chip temperature reading
  - Corrections to Remote Proxy
  - Correction to a profit switching scenario with Phoenix Miner
  - The web based miner group view will use the global setting for chip temperature display, similar to the Windows application
  - Correction to a scenario related to nVidia GPUs that could cause memory leaks. Note that nVidia drivers 460.x and 461.x have an internal memory leak as well, causing any process that monitors power usage to leak memory.
  - Correction to Telegram messages for additional users included in the default Administrator user group
  - Correction to a scenario where the same API port could be assigned to two Managed Miners

Version 8.3.3 (2021-03-08)
 GPU mining
  - Improved overclocking support for AMD Radeon VII on Linux. Note: Any existing Clocking Profiles for Radeon VII on Linux must be updated after the upgrade.
  - Improved compatibility for reading AMD GPU information on Linux
 User interface
  - Columns in the Miners tab can be hidden via the toolbar Appearance, Columns button.
 Mining software
  - Gminer 2.46
 Corrections
  - Correction to serialization of specific pool types sent to Remote Agent on Linux
  - Correction to the rule for detecting miners not hashing correctly

Version 8.3.2 (2021-03-05)
 ASIC mining
  - LED flash for Antminer Z15
 GPU mining
  - Improved reading of AMD GPU information display on Linux
 Features
  - Improved performance when executing commands on a large number of miners
  - Added new predefined rule to make it easier to detect and reboot miners not hashing correctly
 User interface
  - The Profit Profile Properties dialog can be resized to better display all GPU clocking configuration
  - Use blue color in the heat map to illustrate miners with minus degree temperature
  - The page titles of the web interface will include the name of the selected page, group or miner
 Mining software
  - SrbMiner-Multi 0.6.9
 Corrections
  - Correction to Nicehash region when using the Excavator mining software
  - Removed pools (not intended for the profit switcher) from the profit switcher configuration

Version 8.3.1 (2021-03-01)
 GPU mining
  - Easier to both apply and save the overclocking for a specific miner
  - Allow lower voltage to be set for AMD 5000-series on Linux
  - Added additional coin images
 Features
  - A Remote Proxy (used for large scale mining operations) can be configured to act as a web proxy
 Integration
  - Nicehash pool regions updated. NOTE: If you use Nicehash mining, please ensure the closest region is selected in the Options dialog, Profit switching section, after the upgrade.
 Mining software
  - SrbMiner Multi 0.6.8
 Corrections
  - Correction to display of Nicehash balance for external addresses
  - Correction to log rotation of Remote Agent and Remote Proxy
  - Correction to Remote Proxy automatic miner discovery based on the IP range syntax
  - Correction to a profit switching scenario if a miner recently was converted from a Managed Miner to a Managed Profit Miner

Version 8.3 (2021-02-23)
 User interface
  - New Awesome Miner logo
 Features
  - Open ASIC miner configuration page via the Awesome Miner web interface
  - Heat map boxes in web interface will automatically resize to a bit smaller size for larger heatmaps
 Integration
  - Display of revenue w
