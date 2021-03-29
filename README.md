# cv-kuangyu

# 參考資料：
- 排版可以參考這篇：https://theundercoverrecruiter.com/what-is-the-best-font-for-your-resume-infographic/
- overleaf using color: https://www.overleaf.com/learn/latex/Using_colours_in_LaTeX
- 如何local build latext
	- 安裝macTex, 可以直接用TeXShop產生pdf
	- Editor可以選用texmaker
- linkedIn Page and CV always up to date
- work visa eligibility
- https://resumegenius.com/blog/resume-help/latex-resume-template
- 這個版本很好！https://github.com/posquit0/Awesome-CV

# 改進項目

## 排版
- 專有名詞附上連結？！
- [Done] 挑一個更好讀的字體：無襯線
- 顏色Highlight
- 關鍵字標底線或是斜體或是改顏色？
- [Done] 邊界不夠寬
- [Done] 名字下面直接先放email, linkedlin, github
- [Done] 之後再放住址
- [Done] 版本管理

## Professional Headline/Summary
- 關鍵字：back-end, cloud, java, software
- 目前想到的有
	- Cloud-Focused IT Master Graduate

## Technical Strength
-  怎麼樣分類比較好
	- Tool: 拿掉PyCharm, 加入Eclipse, Kubernette, JUnit
	- 加入protocol: HTTP, TCP/IP,

## 工作經驗
- 需要好的動詞！https://www.monster.com/career-advice/article/sample-resume-software-engineer-midlevel
- 數字化導向：我經手的project跟product!
- design interface between HW, BRP, L1

- change request, performance enhancement, assertion/exception root cause debugging
- release using Jenkins
- 需要更多keyword

可以放入產品spec比較專業, https://www.mediatek.com/products/smartphones/mediatek-helio-p25
用xml設計interface, 用yaml去define test case, UT, IT, regression
- Handled technical change requests with troubleshooting, log examination, issue analysis, solution implementation and patch releasing for global including Samsung, LG and Huawei, etc.
- Supported technical issue with troubleshooting, issue analysis, solution implementation, and patch releasing for global customer including Samsung, LG and Huawei, etc.

## Project
- 應該要怎樣描述一個project比較好？目的，功能，底層實踐？

## Projects
- Github 頁面整理
	+ 要求
		+ README, 一目瞭然
		+ src code folder清楚
		+ report直接放在外面
	+ https://github.com/kuangyu0801/software-defined-networking-ws20/tree/main/sdn-assign-03
	+ https://github.com/kuangyu0801/software-defined-networking-ws20/tree/main/sdn-assign-04
	+ mobile computing project merging
		+ 加入demo 影片
	+ cpx project cleasing
		+ 整理報告（壓縮程式當檔案）
### SDN-4: Publish-Subscribe Service for Software-Defined Network, Java, REST API, HTTP
- Developed a "Subscriber" Java application which can register energy measurement data subscription via REST API and receive UDP datagram from a publishing service by type and value.
- Developed a publishing service, which can receive subscription via HTTP request (GET, POST,  DELETE) and perform content-based routing in OpenFlow network. The services is developed as a Java module in Floodlight controller. The routing algorithm is based on sorting and merging interval of encoded IP-address to minimize network traffic and reduce application filtering effort.
- Follow-up: GitHub reformat
- Jakson parser

### SDN-3: Dynamic Routing for Software-Defined Network, Java, TCP, Dijkstra
- Developed a Java module in Floodlight controller, which provides two dynamic routing modes in OpenFlow network.
- Reactive mode routes with shortest path. Adaptive mode routes TCP flow with load balancing by querying network traffic statistics dynamically and routing in network and transport layer. The implementation is based on Dijkstra's algorithm.
- The Adaptive routing achieves up to 6 times bandwidth increase (582kbs vs 3478kbs) verified with Iperf tool in a MiniNet virtual network on Linux. 

- Developed a Java module, which provides dynamic routing in OpenFlow network. The module is a component in Floodlight controller and contains two modes: Reactive and Adaptive.
- Other keyword: 
Path Selection, maximize bandwidth utilization

### MC-4: Java Application for Wireless Ad-hoc Network Communication, Java, UDP, Raspberry Pi
- Developed 4 Java server and client applications which implement 2 protocols: Flooding and Dynamic Source Routing (DSR). 
- Uses DatagramSocket classes from java.net package for UDP transmission.
- Flooding achieves high robustness with UDP messages broadcast.
- DSR achieves reduced data transfer overhead with route discovery in control messages: Route Request (RREQ) and Route Reply (RREP).
- Deployed and verified applications on Raspberry Pi with real mesh 802.11 WiFi network. 
Java Socket programming


### Android App for City Temperature with Google Firebase
- Developed an Android application, which can update, subscribe, and calculate daily avearge of designated city temperature
- Implemented functions for accessing and querrying shared data in Readtime NoSQL database in JSON format with Google Firebase API

### ATP Tennis Player Network Analysis
- Developed Python programs to build tennis player network and derive structural insights such as Page Rank, Connectivity and Clustering.
- Implemented alogorithms with NetworkX package and built an undirectied graph by processing real tennis match statics in csv format.
- Visualized and rendered network topology with open-source software Gephi
of tennis match statics.

Discovered, 

# My Days in MTK
- 同一個公司不同地域的職位關係
	- 英國負責演算法
	- 大陸負責不敏感的
	- 美國有架構
	- 台灣Design, DSP核心
	- 瑞典架構
- Modem and AP relationship
- 4G制式
- FW, HW, SW的關係, ECO, 對應不同版好
- 產品如何靠eFuse區別
- release的load各種進code規定, brp interface
- logging system台灣跟大陸的權限
- 3G, 4G時代中國政府對於電信商補貼的關係與策略, 運營商, 手機商的角力
- 競爭力的探求：IC設計、高科技產業實戰策略與觀察 https://www.books.com.tw/products/0010396103?sloc=main

# Similar Position
## 4G/5G Protocol Software Engineer and project lead 
+ Job Description
Modem project management
Customer partnership
Customer engineering for 4G/5G modem/protocol/system domains
+ Requirement
1. Experienced with modem protocol and system.
2. Project management skill
3. MS or above with major in EE, CS or Telecommunication Engineering related field
4. Experienced in Wireless communication or embedded system development
5. Related working experience in mobile or wireless software is preferred
6. Familiar with MTK modem solution

## 5G NR communication software development engineer
+ Job Description
1. Develop multi-mode NR/LTE L1/DSP software, including state machine, channel scheduling and modem/RF control SW
2. Implement OFDM communication signal processing and theory in embedded system
3. Realize digital communication in ASIP/DSP architecture
+ Requirement
1. Familiar with C Language and Data Structure
2. Familiar with digital communication
3. Better if have studied 3GPP NR/LTE Spec or have experience in L1 and Protocol(> 3 years)

## 4G/5G Communication System Analysis Engineer
+ Job Description
1. Communication system analysis for 5G NR system
(a) PHY Spec and Procedure Validation
(b) Algorithm design verification and signal analysis
(c) System verification and procedure analysis
2. Communication platform development for 5G NR system analysis
(a) L1 test mode development for physical layer verification.
(b) Full Stack (MLAPI/XLAPI) platform development for system and RRM verification
3. Modem 4/5G system level / physical layer issue analysis
(a) Develop and integrate build and auto testing process
(b) Collect / analyze system requirement & system design
(c) Support urgent system function or performance problem
+ Requirement
1. Related background of wireless communication, digital communication, and digital signal processing, etc.
2. Knowledge of the OFDM related system (NR,LTE, WiFi, DTV, WiMAX...,etc)
3. It's better if you are familiar with 3GPP LTE/NR spec or with the related experience for algorithm design.
4. It's better if you have the experience for MLAPI development or RRM on LTE.
5. Experience with at least one of the following area
5.1. LMMSE
5.2. MIMO mutual information theory
5.3. MIMO channel estimation theory
6.Plus if match the following criteria
6.1. turbo code decode, LDPC decode, polar code decode
6.2. MIMO search algorithm
6.3. SIC (successive interference canceling) algorithm
7. RF receiver structure

## 2021 System Performance Evaluation Intern
FW implementation of performance evaluation of microprocessor used in cellular modem application in 5G.

· Performance evaluations of FW modules for code size and cycles.
· Design of software models for several microprocessor modules.
· Detailed documentation of the designs.

Currently enrolled in MS or PhD program pursuing degree in Electrical Engineering, Computer Engineering, or Computer Science

· BS in Electrical Engineering, Computer Engineering, or Computer Science is required
· Proficient in C, C++, and Python programming
· Excellent FW design concepts/experiences including vector processing design through previous internship or school projects
· Knowledge of computer architecture and/or performance evaluation and analysis
· Experience with operating system and compiler design are big pluses
