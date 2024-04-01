# How it happened

- 2021 Jia Tan (JiaT75) Creates GitHub Account

  - Their initial contributions are suspicious, particularly a PR in libarchive that introduced a potential vulnerability.
    ![JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*TVm5QDCcXIETfwXdCs1pvA.png)
    ps.: libarchive supports a wide range of archive formats, including popular ones like tar, gzip, bzip2, zip, and rar, as well as several others. The library is designed to be portable and is used in various Unix-like operating systems, including FreeBSD, Linux, and macOS, as well as on Windows.
    2022

- April 2022:

  - Jia Tan submits a seemingly irrelevant patch, marking the entry of another persona, Jigar Kumar, who pressures for this patch's inclusion and later for adding another maintainer to XZ.
    ![Marking JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*h8KhYWkCqtFVqeRQZwZE1A.png)

  - JiaT75's First Commit to XZ: Three days after the emails pressuring Lasse Collin to add JiaT75 as maintainer, as they makes their first commit to xz - Marks their regular contribution to the project, eventually becoming the second most active contributor.
    ![JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*JISkxpQVkCb_HKIqVolD3A.png)

  - Disappearances: Jigar Kumar and another account, Dennis Ens, involved in pressuring for changes in XZ, cease their visible online activity.
    ![JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*BU4P3-q4A2cHbKcxdEDcpQ.png)

- 2023 JiaT75 Gains Trust:

  - Merges their first significant commit on January 7, indicating full trust within the XZ repository. Fortunatelly it was reverted, and I cant actually refer the history here.
    ![Marking JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*f_o9bNiwn-hKdwmVLy8i5A.png)

  - March 2023: JiaT75 push Changes to Google's oss-fuzz contact email and commits introduce testing infrastructure for the exploit.
    ![Marking JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*DulPIc9j_qfgN3THNbmuhA.png)

  - July 2023: A PR in oss-fuzz aims to hide malicious changes, and issues are opened to draw attention away from these vulnerabilities.
    ![Marking JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*UjQCWmIelXdwOcF8_h8qTw.png)

- 2024 Control Over Project URL

  - A PR changes the project URL, indicating an attempt to further control over the XZ project.
    ![Marking JiaT75's first commit to XZ](https://cdn-images-1.medium.com/max/800/1*GPM9xfsJsYz2P0NqyXEcsg.png)

  - The Discovery: Anomalies in system performance lead to the discovery of the backdoor, prompted by unexpected behavior and performance issues in software relying on liblzma.

- Additional Developments

  - Suspicious Activities: Hans Jansen pushes for the compromised version of XZ to be included in Debian, alongside other suspicious accounts advocating for its inclusion in various projects.

  - GitHub Suspensions: The accounts of JiaT75 and Lasse Collin are suspended, with the XZ repository also banned, complicating audit efforts.

  - Lasse Collin's Response: Begins reverting malicious changes and provides a FAQ to address the situation.
