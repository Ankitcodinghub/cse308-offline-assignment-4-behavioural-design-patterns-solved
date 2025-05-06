# cse308-offline-assignment-4-behavioural-design-patterns-solved
**TO GET THIS SOLUTION VISIT:** [CSE308 Offline Assignment # 4-Behavioural Design Patterns Solved](https://www.ankitcodinghub.com/product/cse308-offline-assignment-4-behavioural-design-patterns-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97075&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE308 Offline Assignment # 4-Behavioural Design Patterns Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Behavioural Design Patterns

Q1: You have to use the Observer Design Pattern to build a stock trading platform where each user can subscribe to the different kinds of stocks in the market.

Consider an input file containing the stock names followed by their counts and price (Table 1).

P1 3 40.00 P2 4 30.00 P3 5 80.00 P4 6 25.00 P5 7 15.00 P6 9 50.00

Table 1: Contents of the input file

After a user logs into the system, he will be shown the number of stocks and their respective prices. A user can subscribe to a particular stock by using the S command (e.g., S P3). Analogously, he can also unsubscribe to a subscribed stock using the U command.

Use the following trigger commands (fed into the system) to change the state of the stocks: 1. I: Increase a stock price. Example: I P1 10.00

2. D: Decrease a stock price. Example: D P4 5.00

3. C: Change in stock count (always positive). Example: C P2 2

Subscribers will be notified if the state of their subscribed stocks has changed.

Q2: The city of Johannesburg has the following four major public service organizations.

<ul>
<li>Johannesburg Water Supply Authority (JWSA) provides WATER related services.</li>
<li>Johannesburg Power Development Board (JPDC) provides ENERGY related services.</li>
<li>Johannesburg Road and Transport Authority (JRTA) provides TRANSPORT services.</li>
<li>Johannesburg Telecommunication Regulatory Commission (JTRC) provides TELECOM ser- vices.
1
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The organizations depend on each other for cross services (e.g. JRTA depends on JPDC for ENERGY related services). Due to the recent allegations of poor service and lack of cooperation among the organizations, Johannesburg City Corporation (JCC) has decided to act as the mediator among these four entities. Any cross service will have to be performed through JCC.

Each organization can either provide service or request for service that others provide. The requests for services are sent to JCC who puts the requests on the specific organization’s service queue. The organizations have no idea whom they are serving. Implement the above scenario using Mediator design pattern.

</div>
</div>
<div class="layoutArea">
<div class="column">
Sample Input

Init

JWSA POWER JRTA POWER JPDC TELECOM JPDC SERVE JPDC SERVE

</div>
<div class="column">
Expected Outcome

All four services are initiated through mediator JWSA requests for POWER service JRTA requests for POWER service JPDC requests for TELECOM service JPDC serves the request of JWSA JPDC serves the request of JRTA

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 2: Sample Input and Expected Outcome You can use built-in Queue data structure of Java for this problem.

</div>
</div>
</div>
