** 7-Eleven Bluetooth Smart Cup Jailbreak ** 

**Warning: Viewer Discretion is Advised** 

#  ![thanks!](https://github.com/actuator/7-Eleven-Bluetooth-Smart-Cup-Jailbreak/assets/78701239/c2a3b84c-0c8b-496e-8dfa-7e29a67b0d5e)

In 2019 7-Eleven distributed a limited promotional item they generically named the 'Custom Message Cup’*.
* https://fccid.io/2AQNV-60961HC

Customers could personalize their cups with their own messages & slogans.

The cup consists of a plastic shell lined with an LED strip that communicates via BlueTooth Low Energy & allows users to send messages from their mobile device & is available for Android & iOs.

There is a word filter restriction on this promotional cup that displays filtered words using asterixis '*'.

![Capture](https://github.com/actuator/7-Eleven-Bluetooth-Smart-Cup-Jailbreak/assets/78701239/55b4e78e-755c-41b1-9e74-f2946e58b128)

Searching the source via JADX-GUI revealed the de-facto list of vulgar words & the regex word filter accomplished via  client-side filtering* so I proceeded to edit that wordlist. 

![pottymouth](https://user-images.githubusercontent.com/78701239/236337322-3666ac1d-a154-47a7-b8c2-e90a95548d2a.PNG)


APK Easy Tool was effective in providing a turn-key solution to decompile, sign & recompile the 'Hello Cup'(v1.3.1) Application.

The first step was to retrieve the Smali resource files that is essentially specialized assembly language code that is used to represent the Dalvik bytecode of Android applications & specific to the Android runtime environment.

![pogobad](https://user-images.githubusercontent.com/78701239/236341352-f93b04d0-090f-4bee-a6af-fb77140e3639.PNG)

Because I quit ‘Pokemon GO’ only the string 'pogo' will be restricted & everything else previously banned such as 'ugly' (really?) will no longer be filtered.

![Ugly](https://github.com/actuator/7-Eleven-Bluetooth-Smart-Cup-Jailbreak/assets/78701239/67d5442f-bda9-476f-b51b-7ab37b399b0e)

As a result the message 'Ugly Censorship' previously rendered as '**** Censorship' will now display 'Ugly Censorship'.

![Ugly2](https://github.com/actuator/7-Eleven-Bluetooth-Smart-Cup-Jailbreak/assets/78701239/b157a88f-52fb-4426-be7e-2bc01153cd1e)

Although modifying the application was trivial, it served as an interesting illustration bypassing client-side filtering.


** CWE-602: Client-Side Enforcement of Server-Side Security 

https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-34761

