# Order Entry

### General info

Order entry panel allows to create trading orders with different conditions, such as order quantity, price, side, order type and submit them on the market. From the Order Entry panel, you can supply all of the necessary information for an order and easily submit it by clicking the appropriate action button.

![General view of Order Entry panel](../../.gitbook/assets/order-entry-panel-in-quantower-platfrom.png)

The selection of a trading instrument can be performed manually through Symbol Lookup or via linking the panel to other panels, for example, to the chart. Just select one link color in two panels and they will have a synchronized symbol parameter.

### **Order types and restrictions**

Order Entry automatically lists all exchange-supported order types available for the associated instrument under the selected connection. Within our existed connections we support:

* **Market order** is an order placed without a price with the intention of hitting the best Bid or taking the best Offer currently available in the market. The order fills at the current best price.
* **Limit order** allows to submit an order at a specific limit price or better.
* **Stop order** allows to submit a buy or sell market order if and when the stop trigger price is touched.

![Order types](../../.gitbook/assets/order-types.png)

**Time-in-force** \(TIF\) instructions define the length of time over which an order will continue working before it is canceled. Within our existed connections we support many TIFs:

* **DAY** is an order will be canceled if it is not executed within the current trading day;
* **FOK** \(or Fill or Kill\) -  an order will be canceled if it is not executed in the entire volume as soon as it becomes available;
* **GTC** \(Good till cancelled\) orders will remain working until they are cancelled by trader or the contract expires;
* **IOC** \(Immediate or cancel\) requires that any portion of an order that is not filled as soon as it becomes available in the market is canceled;
* **GTD** \(Good till date\) order will remain working within the system and in the marketplace until it executes or until the close of the market on the date specified.

![The list of TIF conditions](../../.gitbook/assets/tif-types.png)

{% hint style="info" %}
The TIF list can be different depends on connection, order type or instrument type!
{% endhint %}


