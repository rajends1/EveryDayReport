## overview

use Eclipse or STS 
require maven ,spring and Junit 

### testData
See file /src/main/java/com/bank/service/beans.xml
The model must be trade1, trade2, ..... tradeN
```
<bean id="trade1" class="com.bank.model.Trade">
		<property name="cur" ref="currencyUSD"></property>
		<property name="ent" ref="entityFoo"></property>
		<property name="tt" ref="buyTradeType"></property>
		<property name="instructionDate" value="01 Jan 2016 "></property>
		<property name="settlementDate" value="02 Jan 2016 "></property>
		<property name="units" value="300"></property>
		<property name="pricePerUnit" value="100.25"></property>		
</bean>
```
