# VSB Power Line Fault Detection


### **Description:**

Medium voltage overhead power lines run for hundreds of miles to supply power to cities. These great distances make it expensive to manually inspect the lines for damage that doesn't immediately lead to a power outage, such as a tree branch hitting the line or a flaw in the insulator. These modes of damage lead to a phenomenon known as partial discharge — an electrical discharge which does not bridge the electrodes between an insulation system completely. Partial discharges slowly damage the power line, so left unrepaired they will eventually lead to a power outage or start a fire.

**The aim of the project is to detect partial discharge patterns in signals acquired from these power lines with a new meter designed at the ENET Centre at VSB. Effective classifiers using this data will make it possible to continuously monitor power lines for faults.**

ENET Centre researches and develops renewable energy resources with the goal of reducing or eliminating harmful environmental impacts. Their efforts focus on developing technology solutions around transportation and processing of energy raw materials.

By developing a solution to detect partial discharge you’ll help reduce maintenance costs, and prevent power outages.

The metric used in this notebook was **Matthews correlation coefficient (MCC)** between the predicted and the observed response and then used **LSTM Model creation and Stratified K-fold cross validation** method to a find better score. 


![vsb](https://user-images.githubusercontent.com/109660074/228856062-b9647793-95c7-4c09-b4fc-6c85cf3264b7.jpg)
