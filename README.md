![Warehouse Efficiency Evaluation](https://github.com/user-attachments/assets/7b636aa1-c360-47e4-a63e-af6453db92f1)
# Warehouse Efficiency Evaluation
## Abstract
Warehouses play a significant role in logistical operations and significantly influence the pace and cost of supply chains. Although order picking and other specific warehouse tasks have generally acknowledged standards, little is known about the technological efficiency of warehouses as a whole. The industry's capacity to pinpoint the greatest chances for enhancing warehouse performance is constrained by a lack of a general grasp of warehouse technical efficiency and the related cause variables.

In this study, we make use of DEA models as a tool to evaluate the efficiencies of twenty-nine (29) homogeneous warehouses of the company. DEA is a linear programming technique used to evaluate the efficiency of decision-making units (DMUs) where multiple inputs and outputs are involved. 

The CCR and BCC models were both utilised to identify efficient and inefficient warehouses, and the efficient warehouses were then graded using the Anderson and Peterson super efficiency model. Peer warehouses and slacks were identified as efficient operations that inefficient DMUs may adapt to attain the efficient frontier.

The model effectively detects the relative efficiencies of efficient and inefficient decision-making units (DMUs), indicating the possibility for saving areas for future improvement action by the warehouse's operations department. The study also provided some intriguing and relevant management insights and ramifications.

## Introduction to Operational Research
Operational Research (OR) is a science which deals with problem, formulation, solutions and finally appropriate decision making. In the decades after the two world wars, the tools of operational research (OR) were more widely applied to problems in business, industry and society. It is often concerned with determining the extreme values of some real-world objective: the maximum (of project, performance, or yield) or minimum (of loss, risk, or cost). Originating in military efforts before World War II, its techniques have grown to concern problems in a variety of industries. Since that time operational research has expanded into a field widely used in industries ranging from airlines, finance, logistics, and government, moving to a focus on the development of mathematical models that can be used to analyse and optimize complex systems, and has become an area of active academic and industrial research.
Operational Research encompasses the development and use of a wide range of problem-solving techniques and methods applied in the pursuit of improved decision making and efficiency. It is often considered as a sub-field of applied mathematics.

## Multicriteria Decision Making (MCDM)
Multi-criteria decision-making or multiple-criteria decision analysis (MCDA) or Multi-criteria decision models (MCDM) is a sub-discipline of operations research that explicitly considers multiple criteria in decision-making environments. Whether in our daily lives or in professional settings, there are typically multiple conflicting criteria that need to be evaluated in making decisions. Cost or price is usually one of the main criteria. Some measure of quality is typically another criterion that is in conflict with the cost. In purchasing a car, cost, comfort, safety, and fuel economy may be some of the main criteria we consider. It is unusual to have the cheapest car to be the most comfortable and the safest. In portfolio management, we are interested in getting high returns but at the same time reducing our risks. Again, the stocks that have the potential of bringing high returns typically also carry high risks of losing money. In a service industry, customer satisfaction and the cost of providing service are two conflicting criteria that would be useful to consider.

In our daily lives, we usually weigh multiple criteria implicitly and we may be comfortable with the consequences of such decisions that are made based on only intuition. On the other hand, when stakes are high, it is important to properly structure the problem and explicitly evaluate multiple criteria. In making the decision of whether to build a nuclear power plant or not, and where to build it, there are not only very complex issues involving multiple criteria, but there are also multiple parties who are deeply affected from the consequences.

Structuring complex problems well and considering multiple criteria explicitly lead to more informed and better decisions. There have been important advances in this field since the start of the modern multiple criteria decision-making discipline in the early 1960s. A variety of approaches and methods, many implemented by specialized decision-making software, have been developed.

## Data Envelopment Analysis (DEA)
Data Envelopment Analysis (DEA) is a methodology based upon an interesting application of linear programming. It is originally developed for performance measurement. It has been successfully employed for assessing the relative performance of a set of firms that use a variety of identical inputs to produce a variety of identical outputs. 
### Decision Making Units (DMU)
Data Envelopment Analysis is a linear programming- based technique for measuring the performance efficiency of organization units which are termed as Decision- Making unis (DMUs). This technique aims to measure how efficiently a DMU uses the resources available to generate a set of outputs, according to Charnes et al. Decision-making units can include manufacturing units, departments of big organizations such as universities, schools, bank branches, hospitals, power plants, police stations, tax offices, prisons, defence bases, a set of firms or even practising individuals such as medical practitioners.

#### Input and Output Oriented DEA Program
Let us study the two envelopment versions, the version that involves to produce the observed outputs with minimum inputs, is often referred to as an input-oriented envelopment DEA program. The other version is referred to as an output-oriented envelopment DEA program as it aims to maximize output production, subject to the given resource level.
Now, this can be deduced that the dual of the output maximizing multiplier program is the input-oriented envelopment program. Similarly, the dual of the input minimizing multiplier program is the output-oriented envelopment program.
The general matrix representations of the four programs are given below.
![image](https://github.com/user-attachments/assets/28ea68e2-c9ee-4bdc-ba0d-88105234175c)

#### Technical and Scale Efficiency
Given the fact that DMUs are assigned different efficiencies in case of CRS and VRS assumptions, i.e., using CCR models and BCC models, we can distinguish two different kinds of efficiencies—Technical and Scale Efficiencies.
The CCR model estimates the gross efficiency of a DMU. This efficiency comprises technical efficiency and scale efficiency. Technical efficiency describes the efficiency in converting inputs to outputs, while scale efficiency recognizes that economy of scale cannot be attained at all scales of production, and that there is one most productive scale size, where the scale efficiency is maximum at 100 per cent.
The BCC model takes into account the variation of efficiency with respect to the scale of operation, and hence measures pure Technical Efficiency. 

## Super Efficiency
Data envelopment analysis was originated in 1978 by Charnes et al. and the first DEA model was called CCR (Charnes, Cooper and Rhodes) model. The objective of DEA models is to evaluate overall efficiencies of decision-making units (DMUs) that are responsible to convert a set of inputs into a set of outputs. Efficient DMUs are identified by an unity of 1.0 and inefficient DMUs have efficiency scores less than 1.0. When being evaluated, the efficiency score of a DMU is measured by the combination of a set of DEA efficient DMU(s), which form a part of the segments on the efficiency frontier. The efficient DMUs are not comparable among themselves in the CCR and other DEA models. In the last decade, some DEA researchers initiated a new area called super-efficiency to rank the DEA efficient DMUs and developed various models. Although the developed models are interesting and useful, in general, they have the drawbacks of lacking either stability or feasibility.
Researchers focused on ranking only DEA efficient DMUs based on the results obtained either from CCR or BCC models. The research in this area was first developed by Andesen and Petersen. In their research, they ranked DEA efficient DMUs in such a way that superior DEA efficient DMUs may have efficiency scores greater than unity.

## Problem Definition
One of the top businesses providing warehousing and logistics services is NCUBATE INDIA SERVICES PVT. LTD. NISPL has a distribution and warehousing network over all of India. And because of the fierce competition on the worldwide market, the corporation strives to implement the idea of Optimality by boosting the effectiveness of every warehouse. Considering last-mile delivery is crucial to the supply chain's overall success. 
All items produced by the Livpure, Livfast, Livgaurd, LivGreen, Lectrix, Mooving, and other brand companies are part of the SAR group. Transporting the goods from the producing facility to the warehouse and from the warehouse to the final customer is the responsibility of NISPL. Therefore, it's crucial to ensure that the entire warehouse is operating smoothly.
According to its size, equipment, the volume of the products and turnover outcomes per year. These twenty nine warehouses represent the decision-making units (DMUs). In all warehouses, the picking process is done manually. With this order, workers are picking goods and set up pallets. After that, goods are wrapped in a special foil, also manually, the full pallet is carried to the front of the warehouse and the next action involves checking by the checkers. Management of the company from year to year closely monitors the picking process. Efficiency in these warehouses is not at the same level. Some warehouses have higher efficiency than others. In the rest of this project, the DEA method will be applied to find the most efficient unit.
This project presents an application of Multi -Criteria Decision making for calculating efficiency of all warehouses, which is concluded through data envelopment analysis (DEA) and implementing the suggestions provided.

## Input and Output Criterias
FIVE INPUT FACTORS
1)	Size of the warehouse: Total Warehouse space used for receiving, storage, order consolidation, shipping, aisles, and offices. Warehouse space is mostly interpreted as the total floor area in total square feet.
2)	Number of full-time employees: The total number of all full-time employees (FTEs) who are directly involved in all the inbound and outbound warehouse activities; these inbound activities include unloading and receiving product into the warehouse storage locations, and outbound activities include all activities involved in picking, packing, and shipping products to specific customers.
3)	Number of pallets: Pallets are very important in the modern logistics. Even though they are cheap in price and requires simple maintenance. But,they need fumigation or heat treatment when one-time export packaging materials, so as to raise additional costs and extend the clearance time.
4)	Number of IT Assets: Technology is making many warehouse processes more efficient by augmenting the work of humans or, in some cases, automating tedious, manual tasks, freeing up associates to focus on more complex tasks. Warehouse may have many IT assets like Bar code printer, scanner and laptops.
5)	Warehouse Operating cost: Generally, the operational cost for a warehouse is a combination of various costs such as inventory cost, labour cost, maintenance cost, electricity cost, management cost. Inventory cost is a total storage cost per unit, which is major cost. Labour cost is salary paid to all personnel involved in warehouse operations. Maintenance cost is sum of costs of all maintenance activities such as building maintenance, equipment maintenance. Electricity cost is the cost of electricity consumption either by feeder or by any alternate source, that is, generator or invertors. The cost for managing warehouse smoothly and professionally by various activities such as pest control, sanitation, documentation, hospitality management cost.
THREE OUTPUT FACTORS
1)	Number of Orders (Sales): Warehouse total number of orders demanded by the end customers is usually measured as units, boxes or other meaningful units of measures.
2)	Level of Value-Added Services: It can be measured by the number of VAL activities offered by the company and performed in warehouses. Level of value-Added logistics is measured on an increasing five-point ordinal scale. It is the kind of service a warehouse perform that is tailored to the wishes and needs of the customer. In most cases, it is an effort to create a more efficient supply chain.
3)	Error-free Order lines: Error-free % is measured on an increasing nine-point ordinal scale. This measures what percentage of shipping order lines was error free on average. The example of errors are: faulty quantities, deliveries not on time (too early or too late), packing mistakes, product errors, incorrect component/modules.

## Summary of CCR Model
Following is the table of efficiency score of all the DMUs (Warehouses). It can be clearly seen that there are 15 efficient DMUs and 14 inefficient DMUs.

![image](https://github.com/user-attachments/assets/b6168309-2c86-469a-9cd9-c7bbca18f9c2)

## Summary of BCC Model
Here we have 19 efficient DMUs and 10 Inefficient DMUs.

![image](https://github.com/user-attachments/assets/20b4b159-788d-4a3f-b975-58073ae56928)

## Summary of Super Efficiency
After applying Anderson-Peterson Model, following is the list of super-efficient score of all the efficient warehouse.

![image](https://github.com/user-attachments/assets/7ce52e45-e269-4408-9eff-24ddb254763d)

## Conclusion
The DEA approach may be said to be one of the most often utilised to determine the effectiveness of Decision-Making Units (DMUs). The 29 DMUs in this study were evaluated for effectiveness using DEA methodologies.
Additionally, it can be said that the CCR model revealed that 15 warehouses, or more than half of them, were efficient, while just 14 of them were inefficient. And in the BCC model, when there are 19 efficient warehouses and 10 inefficient, the number of efficient warehouses rises. The inefficient warehouses in both models run within a range that calls for substantial adjustments to increase efficiency.
The input variables have to be adjusted in order to get the desired results. All of the DMUs will function effectively once the input variables have been fixed as illustrated above. Let's have a look at DMU 1 in the CCR model. At first glance, it is clear that there has to be a 3.111 and an 8.7778 reduction in the number of full-time employees and pallets, respectively. As can be seen, there are 3.111 full-time employees and 8.7778 pallets respectively. Pallets and staff cannot both be 0.111 and 0.8778 in reality. In such a circumstance, it is advised to hire contract employees who will uphold and meet the output parameters in order to temporarily address the problem..
Last but not least, using the notion of super-efficiency, the warehouse in Jammu was placed best while the warehouse in New Delhi was ranked last.





