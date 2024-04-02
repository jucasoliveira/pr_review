# How it happened

- 2021

  - Jia Tan (JiaT75) creates her GitHub account

  - Their early contributions are already suspicious, in particularly a PR on libarchive that introduced a potential vulnerability.
    ![JiaT75's first appointment with XZ](https://cdn-images-1.medium.com/max/800/1*TVm5QDCcXIETfwXdCs1pvA.png)
    ps.: libarchive supports a wide variety of archive formats, including popular ones like tar, gzip, zip and rar, as well as several others. The library is designed to be portable and used across multiple Unix-like operating systems, including FreeBSD, Linux, and macOS, as well as Windows.

- 2022:

  - In April 2022 Jia Tan sends an apparently irrelevant patch. But here marks the entry of another persona, Jigar Kumar, who pushes for the inclusion of this patch and later for the addition of another maintainer to XZ.
    ![Marking JiaT75's first commit with XZ](https://cdn-images-1.medium.com/max/800/1*h8KhYWkCqtFVqeRQZwZE1A.png)

  - JiaT75's first commitment to XZ: Three days after the emails, Lasse Collin ends up adding JiaT75 as a maintainer. This is when they make their first commitment to xz , and from then on he starts making regular contributions to the project, eventually becoming the second most active contributor.
    ![JiaT75's first appointment with XZ](https://cdn-images-1.medium.com/max/800/1*JISkxpQVkCb_HKIqVolD3A.png)

  - At the same time Jigar Kumar and another account, Dennis Ens, involved in the pressure for changes in the XZ, ceased their online activity.
    ![JiaT75's first appointment with XZ](https://cdn-images-1.medium.com/max/800/1*BU4P3-q4A2cHbKcxdEDcpQ.png)

- 2023 :

  - January: Jia Tan makes his biggest contribution to the project, indicating full confidence in him as maintainer of the XZ repository. Apparently the history was deleted or reverted, so I don't have a record of what was changed.
    ![Marking JiaT75's first commit with XZ](https://cdn-images-1.medium.com/max/800/1*f_o9bNiwn-hKdwmVLy8i5A.png)

  - Marco: JiaT75 creates a PR with changes to Google's oss-fuzz contact email and introduces commits into the testing infrastructure, this is a basis for the exploit.
    ![Marking JiaT75's first commit with XZ](https://cdn-images-1.medium.com/max/800/1*DulPIc9j_qfgN3THNbmuhA.png)

  - July: A PR in oss-fuzz aims to hide malicious changes and here we see a focus on creating issues in order to divert attention from these vulnerabilities.
    ![Marking JiaT75's first commit with XZ](https://cdn-images-1.medium.com/max/800/1*UjQCWmIelXdwOcF8_h8qTw.png)

- 2024 Control over project URL

  - Jia Tan creates a PR that changes the project URL, indicating an attempt for greater control over the XZ project. From what I saw in the cybersecurity community, the new url directed users to a different server.
    ![Marking JiaT75's first commit with XZ](https://cdn-images-1.medium.com/max/800/1*GPM9xfsJsYz2P0NqyXEcsg.png)

  - Marco: After these changes, anomalies in the system's performance lead to the discovery of the backdoor, caused by unexpected behavior and performance problems in software that depends on liblzma.

- And then we could see the full picture

  - [x] To attack and create a backdoor, several fake accounts were created over time to create a false view of different actors interested in these open source projects

  - [x] This can be seen when Hans Jansen, another ghost account, pushes for the compromised version of XZ to be included in Debian, along with other suspicious accounts advocating its inclusion in various projects.

  - [x] JiaT75 and Lasse Collin's accounts are suspended from Github, with the XZ repository also banned, complicating auditing efforts.

  - [x] And this actually compromised the only legitimate developer who maintained this Open Source: Lasse Collin, as he apparently was more a victim than an accomplice in this event

  - [x] And we have to verify that, most of the rollbacks of these malicious changes were made by Lasse Collin, as soon as he was informed about what was happening.
