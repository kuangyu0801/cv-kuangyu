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

## 工作經驗
- 數字化導向：我經手的project跟product!
- design interface between HW, BRP, L1

- change request, performance enhancement, assertion/exception root cause debugging
- release using Jenkins
可以放入產品spec比較專業, https://www.mediatek.com/products/smartphones/mediatek-helio-p25
用xml設計interface, 用yaml去define test case, UT, IT, regression
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


### Location Temperature App with Realtime Database
- Developed Android application for location and temperature data in JSON with NoSQL database, Google Firebase Readtime Database
- Implement- functions for access, update, query, subscribe data in with Firebase-API

### ATP Tennis Player Network Analysis
- Developed Python programs to build tennis player network and derive structural insights such as Page Rank, Connectivity and Clustering.
- Implemented alogorithms with NetworkX package and built an undirectied graph by processing real tennis match statics in csv format.
- Visualized and rendered network topology with open-source software Gephi
of tennis match statics.

Discovered, 
# My Days in MTK
- Modem and AP relationship
- 4G制式
- FW, HW, SW的關係, ECO, 對應不同版好
- 產品如何靠eFuse區別
- release的load各種進code規定, brp interface
- logging system台灣跟大陸的權限
- 3G, 4G時代中國政府對於電信商補貼的關係與策略, 運營商, 手機商的角力