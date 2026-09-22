# WC-2026-F11507001-YeeCher
# Yee Cher's Wireless Communications Notes
###### tags: `Wireless Communications`

## :notebook_with_decorative_cover: Personal Information
:::info
- Name: Teh Yee Cher
- Research: None
- Briefly summarize your background and why you want to take this course:
Hi, I'm a year 3 electrical engineering undergraduate exchange student from Singapore. I'm mainly interested in power supply and how power is distributed, the grid and sustainability. I thought would be interesting to understand how communications has evolved over the years and how we get signals and information passed around in split seconds amidst all the other signals in the environment around us.
:::

## :notebook_with_decorative_cover: Study Notes
### A1: Basic Wireshark
:::warning
- **A1: Basic Wireshark (12pt)**
    - **Deadline : 12:00, Oct. 7**
    - **Goal:** 
        - Students will be able to use Wireshark to perform basic packet capture and analysis, and understand the structure of network packets.
    - **Requirment and Rule:**
        - Rule: 
              1. Please provide proof for each answer using a screenshot or log.
              2. Please include the link to your PCAP file (you can upload it to your Google Drive).
              3. You will receive full points if you provide the correct answer for each question.
              4. Paste your study note link and video link on your personal hackmd home page's `Deliverable`.
        - Requirment:
            - Make a wireshark and [KS wireshark](https://drive.google.com/drive/folders/1FiEmKeXc4M7qfkHbAzDjbaQ0Yn-SRcCO?usp=sharing) installation guide
                - ==Note: KS wireshark only can install in the **Windows** OS==
            - (1 pt) Capture packets: access the NTUST homepage (https://www.ntust.edu.tw/home.php) and answer the following questions:
              - What is the IP address and port of the NTUST homepage (https://www.ntust.edu.tw/home.php)?
              - What is the IP address and port of your PC when initially accessing the page?
              - What is the process of the TCP three-way handshake?
            - (1 pt) Use the filter `dns` to find a DNS packet and answer the following questions:
              - What is the IP address and port of the DNS server?
              - What is the domain name in this query?
              - Which protocol(s) does this DNS packet use? (List the protocols from Layer 2 — Link Layer — up to Layer 5 — Application Layer in the TCP/IP five-layer model.)
            - (1 pt) Access an HTTP page (e.g., http://www.gzxyzn.com/Article/bjrk2/1644.html) and answer the following questions:
              - Which HTTP page did you access?
              - What is the IP address and port of the server hosting this page?
              - What is the request method?
              - What is the response status code, and what does it mean?
    - **Deliverable:**
      - [ ] (4 pts) [Study Note](https://hackmd.io/@2xIzdkQiS9K3Pfrv6tVEtA/ryfyPD3oge):
        - [ ] (1 pt) Make a wireshark installation guide
        - [ ] (1 pt) Capture packets: access the [NTUST homepage](https://www.ntust.edu.tw/home.php) and answer the following questions:
        - [ ] (1 pt) Use the filter `dns` to find a DNS packet and answer the following questions:
        - [ ] (1 pt) Access an HTTP page (e.g., http://www.gzxyzn.com/Article/bjrk2/1644.html) and answer the following questions:
      - [ ] (4 pts) Presentation Video (5 mins)
      - [ ] (1 pt) [Vote the Top3](https://docs.google.com/forms/d/e/1FAIpQLSehUNvidISkA4JD97emaqW53Lze0zSrHqtWIIeSEYrNP1S96A/viewform?usp=header)
      - Top3:
        * Top1(3pts):
        * Top2(2pts):
        * Top3(1pt):
    - **Reference:**
        - [Wireshark-Basics.pdf](https://drive.google.com/file/d/15hqyIT_i-IEboLMnthlA8ZcC5HRLAgtp/view?usp=sharing)
        - [How to install two different Wireshark versions in same PC](https://drive.google.com/file/d/1xA_2otvBCCxwzFfWDvkX0h_W4tpcdOrB/view?usp=drive_link)
        - [KS-wireshark for 5G RRC_NAS callflow analysis](https://drive.google.com/drive/folders/1FiEmKeXc4M7qfkHbAzDjbaQ0Yn-SRcCO?usp=drive_link)
:::
### A2: 5G End-To-End Log Analysis (14pt)
:::warning
- **A2: 5G End-To-End Log Analysis (14pt) -> Provided by Prof. MA**
    - **Deadline : 12:00, Dec. 9**
    - **Goal:** 
        - Students will be able to analyze sample pcap traces to understand the 5G End-to-End (E2E) Call Flow, gaining familiarity with the complete procedure from UE through RAN, core network, and user data transmission.
    - **Requirment and Rule:**
        - Rule: 
              1. Please provide proof for each answer using a screenshot or log.
              2. You will receive full points if you provide the correct answer for each question.
              3. Paste your study note link on your personal hackmd home page's `Deliverable`.
              4. Please download the [PCAP file: 5G E2E CallFlows for HW in NTUST](https://drive.google.com/file/d/1C610NTzzaABf3sbSMwe1fln1Gx0JCwn8/view?usp=sharing) and use KS-wireshark for answering 5G E2E Call Flows Analysis
        - Requirment:
            - Mult-choice question for 5G E2E SCAS lessons (2 pts)
            - 5G E2E Call Flows Analysis (8 pts)
                1. Answer the following question from UElog
                2. Answer the following question from 5GClog
    - **Deliverable:**
      - [ ] (2 pts) [Mult-choice question for 5G E2E SCAS lessons](https://docs.google.com/forms/d/e/1FAIpQLSeLIHPZQeS_cBTS9nax9Ld_CgVwuAX98K_IaW05p2CCTR11MQ/viewform)
      - [ ] (8 pts) [5G E2E Call Flows Analysis](https://hackmd.io/@2xIzdkQiS9K3Pfrv6tVEtA/SJjBTLKlbl)
          - [ ] (6 pts) Answer the following question from UElog
          - [ ] (2 pts) Answer the following question from 5GClog
      - [ ] (1 pt) [Vote the Top3](https://docs.google.com/forms/d/e/1FAIpQLScI3ZA223rjn1YO3NcL3WWniKKI6-fPhERh4aw2GbfOUZVMDg/viewform?usp=publish-editor) (DL: 23:59, Dec. 12)
      - Top3:
        * Top1(3pts):
        * Top2(2pts):
        * Top3(1pt):
    - **Reference:**
        - [PCAP file: 5G E2E CallFlows for HW in NTUST](https://drive.google.com/file/d/1C610NTzzaABf3sbSMwe1fln1Gx0JCwn8/view?usp=sharing)
        - [SSC Modes – Session and Service Continuity in 5G](https://www.techplayon.com/ssc-modes-session-and-service-continuity-in-5g/)
:::
