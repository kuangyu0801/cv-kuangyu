# cv-kuangyu

# 參考資料：
- 排版可以參考這篇：https://theundercoverrecruiter.com/what-is-the-best-font-for-your-resume-infographic/
- overleaf using color: https://www.overleaf.com/learn/latex/Using_colours_in_LaTeX
- 
# 改進項目

## 排版
- 專有名詞附上連結？！
- 版本管理
- 挑一個更好讀的字體：無襯線
- 顏色Highlight
- [Done] 邊界不夠寬
- [Done] 名字下面直接先放email, linkedlin, github
- [Done] 之後再放住址

## Professional Headline/Summary
- 關鍵字：back-end, cloud, java, software
- 目前想到的有
	- Cloud-Focused IT Master Graduate
	- 
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
- 關鍵字標底線或是斜體或是改顏色？

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

### MC-4: Routing Protocols for Wireless Ad-hoc Network, Java, UDP, Raspberry Pi
- Flooding in application layer uses UDP broadcast messages to achieve high robustness.
- Dynamic Source Routing (DSR) achieves reduced data transfer overhead
- Deployed and verified applications on Raspberry Pi with real mesh 802.11 WIFI network. 
Java Socket programming
## 版本管理
- 如何local build latext
	- 如何直接利用overleaf範本auto build
	- 安裝macTex, 可以直接用TeXShop產生pdf,
	-  TODO: TexMaker的default command沒有辦法產生pdf, 要在挑整